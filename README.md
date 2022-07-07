The creation of this started from the link: *https://www.webrtc-experiment.com/Pluginfree-Screen-Sharing/*.

All WebRTC communication must be secured using the HTTPS protocol.

The application is available at the link: [Heroku](https://webrtc-screen-sharing.herokuapp.com/)

[README.md](https://webrtc-screen-sharing.herokuapp.com/README.md)

---

1. index.html - It calls directly functions (id and class) from webrtc.js
2. webrtc.js - Connects to sockets via https://socketio-over-nodejs2.herokuapp.com:443 and imports socket.io.js
3. conference.js - It uses adapter.js and config from webrtc.js
