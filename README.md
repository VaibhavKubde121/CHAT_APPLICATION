# PluseTalk - Chat Application 
PulseTalk is chat application build with the power of MERN Stack.

## Overview

This chat application allows users to engage in real-time conversations. It is built with Node.js on the server-side, using Socket.io for real-time communication, React.js for the frontend, and MongoDB for storing chat data.

## Features

- Real-time chat functionality
- User authentication
- Message history retrieval
- Responsive UI design


# Project Images

![Screenshot 2024-02-06 102151](https://github.com/VaibhavKubde121/CHAT_APPLICATION/assets/113769045/9bebe91a-a3a6-48d6-85e2-80c9d5f5c1f6)

![Screenshot 2024-02-06 102218](https://github.com/VaibhavKubde121/CHAT_APPLICATION/assets/113769045/eff378fe-31ea-4ec0-8fd4-c42bd5612f33)

![Screenshot 2024-02-06 102351](https://github.com/VaibhavKubde121/CHAT_APPLICATION/assets/113769045/d4d3d46f-ab39-45e8-88eb-67d087506f23)

![Screenshot 2024-02-06 102603](https://github.com/VaibhavKubde121/CHAT_APPLICATION/assets/113769045/ed584cd2-ec78-4594-adf7-8c1357fae172)



Both should be installed and make sure mongodb is running.

```shell
git clone https://github.com/VaibhavKubde121/CHAT_APPLICATION
cd CHAT_APPLICATION
```
Now rename env files from .env.example to .env
```shell
cd client
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
npm
cd ..
cd client
npm
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd client
npm start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
npm start
```

Done! Now open localhost:3000 in your browser.
