# Project Description
A website for managing events. Users could make and book events through it.

# Website 
https://eventoos.herokuapp.com

# Development Technologies
* HTML5
* CSS3
* Javascript ES6
* NodeJs v12.18.1
* ExpressJs v1.0.1
* MongoDB v2.6.10
* JQuery
* Bootstrap v4
* React v16.13.1
* npm v6.14.4

# Development Environment
* Visual studio code
* Live server vscode extension
* React devtools extension for mozilla firefox browser
* Mozilla firefox browser

# User Manual
### Note: 
Make sure to install all tools in Development Technologies before start.

## 1. Setup a Database
1. Open https://www.mongodb.com/cloud/atlas
2. Make an account and signin.
3. Make a free cluster, follow all the default settings.
4. You should be able to see this page
![AtlasMain](https://i.imgur.com/Paqktd2.png)
5. On the right. Open *Database Access* in *SECURITY* section.
6. Press on *ADD NEW DATABASE USER*.
7. Enter your user data, and make sure to save them anywhere.
8. Press on *ADD USER*.
9. On the right. Open Network Access in *SECURITY* section.
10. Press on *ADD IP ADDRESS*.
11. Press on *ADD CURRENT IP ADDRESS*, and confirm.
12. On the right. Open *Clusters* in *DATA STORAGE* section.
13. On your cluster, press *connect*.
14. Press on *Connect your application*.
15. Copy URL under *Add your connection string into your application code*.
16. In the project source code, open *nodemon.json* file.
17. Change *MONGO_USER* and *MONGO_PASSWORD* to the user you make in step 7.

*Now, your database is setup completlely, you can run the app*.
## 2. Install all dependencies
```sh
npm install
```
## 3. Run the backend
```sh
npm start
```
## 4. Run the frontend
```sh
cd frontend
npm install
npm start
```

# Screenshots
![Main page](https://i.imgur.com/Uft2Rfr.png)
![Signup page](https://i.imgur.com/4wwm1cZ.png)
![Sign in](https://i.imgur.com/L8ZS8nc.png)
![Events1](https://i.imgur.com/IehGaJq.png)
![Book event](https://i.imgur.com/SxKv0HX.png)
![Add event](https://i.imgur.com/Xy5em3g.png)
![Events2](https://i.imgur.com/vSrQKLr.png)
![Bookings](https://i.imgur.com/rzwkmMt.png)
