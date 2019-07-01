# PalmHR Test Project
## Sowary

To run the api server first install the dependencies with
```
yarn install
```
or
```
npm install
```
If you are using windows OS, you need to manualy go to the server dir and install the dependencies
```
cd server
npm install
```

Than to start the server run
```
yarn start-server
```
or
```
npm run start-server
```
or
```
node server/index.js
```

The server will be runing on port 5000. There are two routes:
* GET [http://localhost:5000/pictures](http://localhost:5000/pictures) which will return json response with the list of images.
* GET [http://localhost:5000/picture/image-name](http://localhost:5000/picture/image-name) which will return img response with the selected image (this uri is in the json response of the first route)

The server runs independently of client code, but the routes in your code need to target uri listed above.



***CLIENT SIDE***

go to CLIENT folder and type yarn-start / npm-start



In order to successfully run application you need to start server as well as client side app.
