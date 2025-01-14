---
description: >-
  Follow this two step guide to integrate your MetaMask wallet with Alchemy's
  endpoint!
---

# How to Speed Up MetaMask Transactions

MetaMask uses a default node provider to display and send transactions for your account. Because the node provider does not allocate dedicated resources to each user, it may be slow sometimes, i.e. for transaction broadcasting.

Alchemy provides a much better experience when it is used as your MetaMask RPC provider. If you'd like to switch this over to Alchemy to be able to see your transactions in your Alchemy dashboard and use Alchemy specific features and tools, this doc will show you how to integrate your MetaMask account in _two easy steps_.

**NOTE: **This does not mean that Alchemy will have access to your private keys or wallet!&#x20;

For a video version of this doc, check this out:

{% embed url="https://www.youtube.com/watch?v=VUkhkSgMtdk" %}

#### 1. Navigate to your MetaMask wallet and click the network dropdown at the top, selecting "Custom RPC" at the bottom

![Click on "Custom RPC" at the very bottom of the network dropdown.](<../.gitbook/assets/Screen Shot 2021-11-15 at 9.47.25 AM.png>)

#### 2. Fill in the required information

* Make sure you use the correct Alchemy API URL for your desired network
* Alchemy supported chains:

| Network                 | RPC Base URL                                                                                     | Chain ID | Block Explorer URL                                            | Symbol (optional) |
| ----------------------- | ------------------------------------------------------------------------------------------------ | -------- | ------------------------------------------------------------- | ----------------- |
| Ethereum Mainnet        | [https://eth-mainnet.alchemyapi.io/v2/](https://eth-mainnet.alchemyapi.io/v2/)\<api key>         | 1        | [https://etherscan.io/](https://etherscan.io)                 | ETH               |
| Ropsten Test Network    | [https://eth-ropsten.alchemyapi.io/v2/](https://eth-ropsten.alchemyapi.io/v2/)\<api key>         | 3        | [https://ropsten.etherscan.io/](https://ropsten.etherscan.io) | ETH               |
| Rinkeby Test Network    | [https://eth-rinkeby.alchemyapi.io/v2/](https://eth-rinkeby.alchemyapi.io/v2/)\<api key>         | 4        | [https://rinkeby.etherscan.io/](https://rinkeby.etherscan.io) | ETH               |
| Goerli Test Network     | [https://eth-goerli.alchemyapi.io/v2/](https://eth-goerli.alchemyapi.io/v2/)\<api key>           | 5        | [https://goerli.etherscan.io/](https://goerli.etherscan.io)   | ETH               |
| Kovan Test Network      | [https://eth-kovan.alchemyapi.io/v2/](https://eth-kovan.alchemyapi.io/v2/)\<api key>             | 42       | [https://kovan.etherscan.io/](https://kovan.etherscan.io)     | ETH               |
| Polygon (Matic) Mainnet | [https://polygon-mainnet.g.alchemy.com/v2/](https://polygon-mainnet.g.alchemy.com/v2/)\<api key> | 137      | [https://polygonscan.com/](https://polygonscan.com)           | MATIC             |

![Example Polygon Configuration](<../.gitbook/assets/Screen Shot 2021-11-15 at 10.07.44 AM.png>) ![Example Ethereum Mainnet Configuration](<../.gitbook/assets/Screen Shot 2021-11-15 at 10.11.10 AM.png>)

And thats it! Your MetaMask is now hooked up to Alchemy 🎉 You've now unlocked game changing tools like the [Mempool Visualizer](../introduction/core-products/alchemy-build.md#mempool-visualizer) (where you can view all your transactions as they are being mined), [Alchemy Notify](../introduction/core-products/alchemy-notify.md) (receive notifications about address activity, dropped/mined transactions, etc.), and more!
