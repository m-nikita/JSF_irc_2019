# JSF_irc_2019

Project of an IRC server in NodeJS and ExpressJS with Socket.io. Our project accept several simultaneous connections and implement the notion of channels:

- it is possible to join several channels
- we can create channels
- a message is displayed when a user joins or leaves a channel.
- users can chat in the channels they have joined.

To use the project :

- `npm install`
- `npm i socket.io`
- `npm i --save-dev nodemon`
- `npm i express ejs`
- `npm run devStart`
- Go on this url : `http://127.0.0.1:3000/`

If it's not working, try to delete in `node_modules` the `nodemon` folder and in the `.bin` folder the `nodemon` file.
