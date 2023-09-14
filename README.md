## webRTC videochat demo

* webRTC
* react w/ next.js 13
* firebase

Important: It only works on my home wifi network. Cross-network compatibility requires TURN servers I believe.

### How to use
```
git clone https://github.com/calvinusesyourcode/webrtc-firebase-react-demo
```
```
// update lib/firebase.ts with your firebase config
```
```
npm install
```
```
firebase init firestore
```
```
firebase deploy --only firestore:rules
```
```
// project uses next.js so host with vercel.com or just npm run dev
```

### Resources

* [WebRTC docs](https://webrtc.org/)
* [WebRTC samples](https://webrtc.github.io/samples/)
* [chrome://webrtc-internals](chrome://webrtc-internals)
* [fireship.io's video](https://www.youtube.com/watch?v=WmR9IMUD_CY)
