<div align="center">
  <img src="https://github.com/Prathmesh-Dhatrak/cinemagram-frontend/blob/main/src/images/logo-cg.svg" width="500" alt="logo"/>

  # [Community platforms for cinema buffs](https://cinemagram.prathmeshdhatrak.com/)
    
  It's a social media for cinema lover where people can connect with other movie fans discussing films, movies, and TV series
</div>

## **How to install the backend and run locally ?**
```
$ git clone https://github.com/Prathmesh-Dhatrak/cinemagram-server.git
$ cd cinemagram-server
$ npm install
```

Then set the ENV file with your credentials
```
CLIENT_URL= "frontend website url"
SESSION_SECRET= "Secret key you will choose"
SESSION_NAME= "Choose any name"
FIREBASE_ID= "Your firebase config settings have a firebase project id"
FIREBASE_STORAGE_BUCKET= "Your firebase config options showed the firebase bucket URL"
GOOGLE_CREDENTIALS= "Credentials from google OAuth"
MONGODB_URI= "mongodb uri"
DB_NAME= "your database name"
PORT= "port number"
```
Then try running
```
$ npm start
```
