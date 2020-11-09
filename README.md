# Realtime Chat
This is a realtime chat using the websocket protocal. 

## Dependencies
I used `node.js` as my backend language. 
Installing `Express` as backend framework and `Socket.io` as websocket implementation. It also requires `moment` to get the current time.

```
npm install express socket.io moment
``` 

Lastly, we need to install `nodemon` to easily access chages on the server.

```
npm install -D nodemon
```

## Run
The server will be running on `PORT:3000`. This is hard coded and you may change it if you like

```
npm run dev
```