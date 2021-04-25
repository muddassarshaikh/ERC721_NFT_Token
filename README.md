# ERC721_NFT_Token

Creating a unique color collection NFT token using ERC721

## Step for running this project

1. Download and run [Ganache](https://www.trufflesuite.com/ganache)

2. Install truffle globally

```sh
      npm install -g truffle
```

3. Install all dependencies

```sh
      npm install
```

4. Then compile the sample token file

```sh
      truffle compile
```

5. i) Deploy the project on ganache network

```sh
      truffle migrate --reset
```

5. ii) Deploy the project on rinkeby test network
   Uncomment rinkeby network setting in truffle-config.js file and comment the developement network

```sh
      truffle migrate --network rinkeby
```

6. Then do unit testing

```sh
      truffle test
```

7. Extra Notes -- To fork any network use

```sh
      ganache-cli -f https://[network].infura.io/v3/infurakey --account="private key, ETH Amount in wei"
```

WHERE,
network = network which we want to fork like mainnet, rinkeby, kovan, etc.
infurakey = infura key will be provided by [Infura site](https://infura.io/)
privatekey = privatekey of any accounts you want to use
ETH Amount in wei = Amount of eth allocated to the given account
