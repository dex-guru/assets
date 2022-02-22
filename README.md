# Overview

Welcome to DexGuru's Asset Repo! 

Currently, DexGuru uses Token logos from 3 off-chain data sources, with this Repo being the primary source. If token logo's are unavailable here, we will use our supplementary sources. 
Our Token Asset sources are listed and ranked below in terms of priority:
- [DexGuru Asset Repo](https://github.com/dex-guru/assets)
- [Trust Wallet's Asset Repo](https://github.com/trustwallet/assets)
- [Coingecko's API](https://www.coingecko.com/en/api/documentation)

If you're a developer of a Token that's looking to have your Token Logo added onto DexGuru, you may add it our Repo. Please do so by following the instructions below and create a PR according to our guidelines and requirements. 

Please note, although adding Token Logos is currently free, all requests are subject to approval.

Additionally, we only accept Logos for Tokens that are on our currently supported Networks:
- Ethereum
- Binance Smart Chain
- Polygon
- Avalanche
- Arbitrum
- Fantom
- CELO
- Optimism

For the most updated list of Supported Networks, please visit our [Docs](https://docs.dex.guru/data/supported-chains). 

# Requirements & Instructions for Token Logos 

When submitting Token Logos, please ensure that the following requirements are followed to prevent your request from being rejected or delayed:
- Filename should be the Token Address in Checksum Format (For reference, you can double check the correct Checksum Format on Block Explorer's). 
  For example, USDT Checksum Format:  
	> - ✅ **Correct Format**: 0xdAC17F958D2ee523a2206206994597C13D831ec7.svg
  >
	> - ❌ **Incorrect Format**:  0xdac17f958d2ee523a2206206994597c13d831ec7.svg
- File format of **`svg` is strongly preferred and encouraged**, although `png` will be accepted as well
	- Please ensure that either `svg` and `png` in the filename are completely in lower case. For example: 
		- 0xdAC17F958D2ee523a2206206994597C13D831ec7.`svg` 
		- 0xdAC17F958D2ee523a2206206994597C13D831ec7.`png`
	- If you are using png format, please ensure that file size has been optimized. You can use tools such as [Kraken.IO Image Optimizer](https://kraken.io/web-interface) to compress and optimize your file size
- Resolution should be between `50px by 50px` and `400px by 400px`
- Transparent Background 

After preparing your Token's logo to the above requirements, please create a PR request with your Token Logo into the [token folder](https://github.com/dex-guru/assets/tree/main/tokens) in this repo. 
