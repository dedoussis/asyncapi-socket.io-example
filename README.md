# Socket.IO Chat API documented with AsyncAPI

The simple chat demo of Socket.IO documented using [AsyncAPI](https://www.asyncapi.com/).  
Application has been forked from: <https://github.com/socketio/socket.io/tree/master/examples/chat>

## How to use

```bash
$ npm ci
$ npm start
```

And point your browser to `http://localhost:3000`. Optionally, specify
a port by supplying the `PORT` env variable.

## Features

- Multiple users can join a chat room by each entering a unique username on website load.
- Users can type chat messages to the chat room.
- A notification is sent to all users when a user joins or leaves the chatroom.
