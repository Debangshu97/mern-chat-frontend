# Butterfly-The funky chat app

[Visit The Website!](https://mern-chat-1.netlify.app/)

# Note
- This is the frontend code for the project .
  Check the backend code in the repo link below

[See backend code here..](https://github.com/Debangshu97/mern-chat-backend)

## Overview

Butterfly is chat application build with the power of MERN Stack. It is a realtime chat app with react, node.js and socket.io with mongodb and express. 
The chat app is also responsive and it is styled with the styled components.


## Tech Stack

The following technologies:

- React
- Nodejs
- MongoDb
- Express.js
- Socket.io
- Avatar Api
- Axios
- Netlify

## Objectives

The idea is described in the following points:

- This is a webapp with 3 pages. We see the Login Page at first , the Register page and the Chat page.
- The users profile details and chat history are stored in a Mongodb Atlas Cluster
- I used React styled components to style the webapp
- I use React for the frontend and Nodejs , Expressjs for the backend and use Socket.io to relay information using websockets
- I access the cool profile avatar from a free api.The api call is made through Axios post request because it converts the response directly to json.
- Implement best practices and standards when structuring the files using nested elements, indentation, comments, and line breaks
- I used netlify to deploy and host the app as it is very convenient and free.
- I used Render to host the backend as a web service for free.

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/Debangshu97/mern-chat-frontend
cd mern-chat-frontend
```
Now create .env files 
For Frontend and Backend

Now install the dependencies
For Frontend
```shell
cd server
yarn
```
For Backend
```shell
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

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
