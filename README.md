### Setup
First, put your API key in `sora-config.json` where it says `<api_key_here>`. Also, install dependencies:
```bash
yarn install
```

### Running the example
To start the example site
```
node serve.js
```
Then visit `localhost:3000/login` or `localhost:3000/verification`.

You can also specify a port (the default is 3000):
```
PORT=5000 node serve.js
```
Then visit `localhost:5000/login` or `localhost:5000/verification`.
