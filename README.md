# Call

## A free group video call app with screen sharing.

It is built using WebRTC, so all your video chat is peer-to-peer. Group video call is achieved using WebRTC mesh. So the quality of the call is inversely proportional to the number of people on the call. The sweet number is somewhere around 6 to 8 people in an average high-speed connection.

### Make a Call

```
npx call
```

### Fork of Talk

This project is a fork of Talk(https://github.com/vasanthv/talk).

- Google Analytics have been removed for privacy.
- Ngrok has been added for a convenient way of exposing the local server to the public internet.
- Published to NPM so the project can be run with one command. `npx call`

### Prerequisites:

- Node.js 8.x or above
- NPM

### How to Build this app locally

```
npm install
```

Run the app

```
npm start
```

### LICENSE

MIT
