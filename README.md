# node-nexmo-sms

This is a simple web app written in Node.js with Express to send a sms from web.


## Run Local

### 1. Install dependencies

```bash
$ npm install
```

### 2. Set up a config.js with Your Nexmo API Credentials

Sign up at [Nexmo](https://nexmo.com) to get your own API keys and a virtual number.

Create `config.js` in `/server`. The file should include the credentials.

```javascript
module.exports = {
  api_key: '000000...',
  api_secret: '000000...',
  number: '000000...'
};
```

### 3. Run the Node App
```bash
$ node server/index.js
```

### 4. Launch it on Browser
Go to [http://localhost:4000](http://localhost:4000) and send text messages.