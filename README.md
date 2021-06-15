# Vector Application

## Introduction
This is an application developed primarily to utilize Firebase Authentication using <ChatEngine /> to offer Realtime Chat functionality. After signing in using Google, the user is prompted to create a chat with other users.

### Setup
- Create .env file in the root directory
```
REACT_APP_CHAT_ENGINE_KEY=YOUR_CHAT_ENGINE_KEY
REACT_APP_CHAT_ENGINE_ID=YOUR_CHAT_ENGINE_ID
```
- Navigate to `/src/firebase.js` file and replace the boilerplate with real values
```js
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGE_SENDER_ID",
  appId: "YOUR_APP_ID"
}).auth()
```
- run ```npm install && npm start```

