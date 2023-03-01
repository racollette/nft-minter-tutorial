# ✅ [Completed] NFT Minter Tutorial

This project contains the COMPLETED files for the [NFT Minter tutorial](https://wiki.elastos.net/tutorials/ui/frontend), which demonstrates how to connect a smart contract to a React dApp project by building an NFT Minter using Metamask and Web3. It is best used as a reference.

# 🪜 Installation

To use this minter, you'll need to do the following:

1. Run `npm install` to download the `node_modules` folder.
2. Download the [dotenv package](https://www.npmjs.com/package/dotenv) in your project directory by running `npm install dotenv --save` in your terminal
3. Create a `.env` file in the root directory this `nft-minter` by entering the following on your command line: `vim .env` and then add your [Pinata Key and Secret](https://pinata.cloud/keys). Altogether, your `.env` file should look like so:

```
REACT_APP_PINATA_KEY = <pinata-key>
REACT_APP_PINATA_SECRET = <pinata-secret>
```

4. Run `npm start`in your terminal to open the minter in your browser at http://localhost:3000/.
