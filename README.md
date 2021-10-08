# Crypto2048 Announcement

[Crypto2048](https://opensea.io/collection/crypto-2048) is the on-chain version of 2048.
All tiles and images are store on the blockchain of Ethereum.

Crypto2048 consists of two important parts, an ERC1155-compliant NFT and an ERC20-compliant Token.

Crypto2048 is just an experimental on-chain game.

## Crypto2048 NFT

Crypto2048 NFT is a number of columns of NFT in compliance with ERC1155 standard, it contains 11 tiles, i.e. 2, 4, 8, 16, 32, 64, 128, 256, 512, 1024 and 2048.

All tile images are stored in SVG format on the chain.

The colors of all tile images, including the number colors and the background colors, are used from [Game 2048](https://play2048.co/). Thanks to [Gabriele Cirulli](https://twitter.com/gabrielecirulli), the creator of 2048.

The total supply of Crypto2048 NFT is 8888, but it's not just 8888.

Anyone can pay 0.02 ETH to mint a tile, and the tiles will be randomly mint according to a certain probability. The probabilities are as follows:

|Tile|Probability|
|:-|:-|
|2048|4 / 8888|
|1024|8 / 8888|
|512|16 / 8888|
|256|32 / 8888|
|128|64 / 8888|
|64|128 / 8888|
|32|256 / 8888|
|16|512 / 8888|
|8|1024 / 8888|
|4|2048 / 8888|
|2|(4096 + 700) / 8888|

`Tip: 4096 + 2048 + 1024 + 512 + 256 + 128 + 64 + 32 + 16 + 8 + 4 = 8188, but I like 8888.`

If you have two identical tiles, you can choose to merge them.

If you have the tile of 2048, you can choose to burn it to claim some ERC20 token.

Happy merging!

## Basic Info

* Contract Address: 0x383af52af00ede7f5a2c55bbd254c55f079856e5
* Etherscan: [https://etherscan.io/address/0x383af52af00ede7f5a2c55bbd254c55f079856e5#code](https://etherscan.io/address/0x383af52af00ede7f5a2c55bbd254c55f079856e5#code)
* OpenSea: [https://opensea.io/collection/crypto-2048](https://opensea.io/collection/crypto-2048)

## How to mint tiles?

No web, but you can choose to mint tiles on Etherscan.

1. Go to [https://etherscan.io/address/0x383af52af00ede7f5a2c55bbd254c55f079856e5#writeContract](https://etherscan.io/address/0x383af52af00ede7f5a2c55bbd254c55f079856e5#writeContract)
2. Click "Connect to Web3" to connect to your Ethereum wallet
3. At `5. mint`, enter `0.02` in `payableAmount(ether)` and `1` in `amount(uint256)`. Of course, you can fill in the quantity and the corresponding ETH according to your preferences.
4. Click `Write` and it'll confirm in your Ethereum wallet.

## Crypto2048 Token

Crypto2048 Token is a governance token in the Crypto2048 ecosystem and can only be mint by burn Tile-2048.

There is no cap, but there is a release rate.

Only one Tile-2048 is allowed to be burned per 8 block heights.

## Roadmap

* Crypto2048 Token and NFT relase
* 10 ETH airdrop to the top 10 address to burn Tile-2048
* 10 ETH add to the Liquidity pool
* 5 ETH to [Gabriele Cirulli](https://twitter.com/gabrielecirulli), the creator of 2048
* The 2048 DAO
* The 2048 series games base one NFT 2048 , for burn the 2048 token
* The web development
* More exchanges for Token 2048
