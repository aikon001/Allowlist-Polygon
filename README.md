# Polygon-Allowlist 

This is a dApp built for Polygon to add the user to an allowlist ,
it shows how Fauna and React can work together to help safeguard your dApp data.

## Setup
Create an .env file in the root folder like this :
MNEMONIC=your mnemonic
Then create another .env file in the client folder like this :
REACT_APP_FAUNADB_SECRET= your fauna db secret
Finally on truffle-config.js put the rpc-endpoint.

## Run
From the client folder:
```bash
npm run start
```

## Screenshot
![Page](https://github.com/aikon001/Allowlist-Polygon/blob/master/screen.png)
