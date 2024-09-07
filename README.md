# Snappy - Chat Application 
Snappy is chat application build with the power of MERN Stack. 


## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)


```shell
git clone https://github.com/sajal-123/MERN-Project-1
cd chat-app-react-nodejs
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
