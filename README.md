# hardhat
https://hardhat.org/getting-started/#overview

## Compile Contracts
```zsh
  yarn compile
```

## Testing your contracts
```zsh
  yarn test
```

## Deploying your contracts
```zsh
  yarn deploy --network ropsten --network <network> # ropsten, rinkeby, kovan, gorli
```

## Etherscan
```zsh
npx hardhat verify --network ropsten CONTRACT_ADDRESS "ARGS"
```

## Starts a JSON-RPC server on top of Hardhat Network
```zsh
  yarn node
```

## Sample Accounts
```zsh
  npx hardhat accounts
```
