# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```

## MJH

1. Run a local test network in-memory `npx hardhat node`
2. Deploy the contract `npx hardhat --network localhost run scripts/deploy.js`
3. Put the address in `frontend/contracts/contract-address.js` and move `artifacts/contracts/EMJAYToken.json` to `frontend/contracts/`
3. Check front-end `cd frontend; npm run dev`
