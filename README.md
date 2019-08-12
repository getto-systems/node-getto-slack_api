# node-getto-slack_api

slack_api : getto-psycher vendor plugin

```javascript
const slack_api = require("getto-slack_api");

slack_api.chat.postMessage({
  token: "TOKEN",
  channel: "CHANNEL",
  text: "TEXT",
});

slack_api.reactions.add({
  token: "TOKEN",
  channel: "CHANNEL",
  timestamp: "TIMESTAMP",
  name: "thumbsup",
});
```


###### Table of Contents

- [Requirements](#Requirements)
- [Usage](#Usage)
- [License](#License)

## Requirements

- Node.js: 10.16.0


## Usage

```javascript
const slack_api = require("getto-slack_api");

slack_api.chat.postMessage({
  token: "TOKEN",
  channel: "CHANNEL",
  text: "TEXT",
});

slack_api.reactions.add({
  token: "TOKEN",
  channel: "CHANNEL",
  timestamp: "TIMESTAMP",
  name: "thumbsup",
});
```

### Install

```bash
npm install --save getto-slack_api
```


## License

node-getto-slack_api is licensed under the [MIT](LICENSE) license.

Copyright &copy; since 2019 shun@getto.systems

