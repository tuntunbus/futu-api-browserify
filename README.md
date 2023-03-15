## Description
Use futu-api in browser
## installation
```
npm install futu-api-browserify
```
## Usage
```
import FutuWebSocket from "futu-api-browserify"
const futuWebSocket = new FutuWebSocket();
futuWebSocket.onLogin = (ret, msg) => {};
futuWebSocket.start(addr, port, enableSSL, key);
```
## Notice
Please use `onLogin` instead of `onlogin`.