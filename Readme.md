Source: https://ethereum.org/en/developers/tutorials/how-to-write-and-deploy-an-nft/

Setup Steps:
```sh
npm i
cp .env.sample .env # replace vars
cd contracts
```
Test Steps:
```sh
npx hardhat compile
npx hardhat --network ropsten run scripts/deploy.js
# https://ropsten.etherscan.io/address/0x3D30Fc59202a2Ed5303a5a114d550D891e9daB0c

```
