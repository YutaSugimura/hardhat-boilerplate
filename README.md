# hardhat
https://hardhat.org/getting-started/#overview

## Compile Contracts
```zsh
  npx hardhat compile
```

## Testing your contracts
```zsh
  npx hardhat test
```

## Deploying your contracts
```zsh
  npx hardhat run scripts/sample-script.ts #hardhat

  # or test network
  npx hardhat run scripts/deploy.ts --network <network> # ropsten, rinkeby, kovan, gorli
```

## Etherscan
```zsh
npx hardhat verify --network ropsten CONTRACT_ADDRESS "ARGS"
```

## Starts a JSON-RPC server on top of Hardhat Network
```zsh
  npx hardhat node
```

## Sample Accounts
```zsh
  npx hardhat accounts
```
