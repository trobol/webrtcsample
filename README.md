# webrtcsample
```
npm install

npm run start
```
Example of the basics of using WebRTC.
This uses a host and a client but WebRTC doesn't require this type of configuration.

There are two pages host and client. Host will connect to the server using websocket as soon as the page loads. Client will connect to the server and exchange information with the host using the server once you click connect. The input box on the client page is basicly useless for now.
THE SERVER WILL CRASH IF YOU CONENCT THE CLIENT BEFORE THE HOST.


I recommend using this with nodemon if you are planning on changing/testing the code.
```
npm i nodemon --save-dev

nodemon server.js
```
