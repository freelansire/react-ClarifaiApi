# SmartBrain - v1
#-REACT -REDIS -POSTGRESQL -NODEjs -EXPRESS----/

-A load balancer using HAProxy to distribute requests across three processing nodes.

-Redis-based job queue system for managing concurrent image processing tasks.

-Worker nodes built with Python's multiprocessing library for parallel image processing.

-Kubernetes for container orchestration and automatic scaling based on queue length.

##FRONT END.
1. Clone or download this repo..
2. Open Frontend folder in Editor..
3. Run `npm install`.
4. Run `npm start` APP start at: http://localhost:3000/

###BACK END.
1. Clone or download this repo.
2. Open BACKend folder in editor..
3. To avoid conflicts in port, you can change port number at bottom of 'server.js' file from 3000 to 3001.
3. Run `npm install`
4. Run `npm start` API local endpoint: http://localhost:3001/
5. You must add your own API key in the `controllers/image.js` found in the backend folder file to connect to Clarifai..

You can get Clarifai API key [here](https://www.clarifai.com/)

###DATABASE
1. Include your PostgreSQL username, password, database and port number in server.js

![get in image](../master/img1.JPG)

![get in image](../master/img2.JPG)

![get in image](../master/img3.JPG)

![get in image](../master/img3.JPG)
