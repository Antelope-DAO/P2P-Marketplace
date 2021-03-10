# Antilop DAO

## Install

```
yarn install
```

## Build

We use hardhat.org

```
yarn hardhat compile
```

## Debug

To get details about the transactions being executed, run the buidlerevm
separately in another terminal.

```
yarn hardhat node
```

Then run your tests with the localhost network

```
yarn hardhat --network localhost test
```

## Test

```
yarn hardhat test
```

## Deploy

```
PRODUCTION=1 yarn hardhat run scripts/deploy.kovan.ts --network kovan
```
