Pravljenje ove aplikacije je počelo od linka *https://www.webrtc-experiment.com/Pluginfree-Screen-Sharing/*.

Sva WebRTC komunikacija mora se odbezbediti korišćenjem HTTPS protokola.

Aplikacij se nalazi na linku: [Heroku](https://webrtc-screen-sharing.herokuapp.com/)

[README.md](https://webrtc-screen-sharing.herokuapp.com/README.md)

---

1. index.html - Poziva direktno funkcije (id i klase) iz webrtc.js
2. webrtc.js - Povezuje se na sokete preko https://socketio-over-nodejs2.herokuapp.com:443 i importuje socket.io.js
3. conference.js - Koristi adapter.js i config iz webrtc.js
