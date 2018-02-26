CS365-Checkers
==============

A simple, web-based two player checker game made for a Northern Michigan University web programming class. 


#### Running on OSX
* Download and unzip [MongoDB](https://www.mongodb.org/downloads#production)
* Open a Terminal and create the `data` folder

  ```
  sudo mkdir -p /data/db
  ```
* Run `mongod`

  ```
  sudo <path to where you unzipped MongoDB>/bin/mongod
  ```
* Run the server

  ```
  node <path to server>server.js
  ```
* Open in browser

  ```
  http://127.0.0.1:8026/
  ```
