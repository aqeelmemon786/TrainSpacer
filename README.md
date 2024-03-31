# TrainSpacer
Excited to share a dummy solution I've developed using Flutter app dev framework– an app that provides real-time occupancy status for each coach of upcoming Mumbai local trains. 🚆

Using CCTV footage, the system calculates headcount inside coaches, compares it to a threshold (e.g., 300 people per coach), and displays the data. This empowers commuters to make informed decisions on which coach to board, enhancing the overall travel experience.

## The system
### The website
The website is designed on Flask web dev framework for the authorities that have access to the CCTV footages. 
### The app
The app is developed on Flutter app dev framework. This app will be available to the users in which they'll be able to see the occupancy status of upcoming 5 trains on their chosen station.

## The solution
The proposed system aims to solve the problem with the help of installed CCTV cameras insidethe local trains. From our research, we came to know that out of the 259 local trains currently running on the central and the western line combined, 85 of them already have the cameras installed inside them and the IRCTC plans to install cameras in all the trains in the coming future.The first task will extracting the images from CCTV footage and then processing,analyzing, and retrieving data from those images, we’ve built a web application that will be controlled by the respected authorities that have access to the footage. This occupancy data of each train will also be shown on the web application. The data extracted then is uploaded to a database which is hosted on online servers. The data on the database is stored in a tabular format where the whole occupancy data of the coaches can be extracted just by the Train_id which is a unique ID that is given to all the trains to track them by the IRCTC. To display this information to the public, we’ve built an Android application, in which users can see the real- time occupancy data of the upcoming trains on their chosen station. The users will be able to browse through the list of stations and select where they are and then where they want to go, then all the upcoming trains will be shown and user can select their desired train and get

### A more detailed review of how it works can be found here https://drive.google.com/file/d/1iA79iCuXaRcYdUkoXWcjW-pG2iDZByCz/view
