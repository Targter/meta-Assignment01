# NFT Collection Management

This project is a simple JavaScript application that allows for the creation, storage, and management of NFT (Non-Fungible Token) metadata. The project includes functions to mint new NFTs, list all minted NFTs, and get the total supply of NFTs created.

## Description

The application provides a basic structure to manage NFT metadata, including details such as name, category, brand, specifications, price, and release year. It includes three main functions: `mintNFT` for creating new NFTs, `listNFTs` for displaying all stored NFT metadata, and `getTotalSupply` for returning the total number of NFTs minted.

## Getting Started

### Installing

1. Clone the repository or download the JavaScript file.

   ```bash
   git clone https://github.com/yourusername/nft-collection.git
   ```

2. Open the project in your preferred code editor (e.g., VSCode, Sublime Text).

### Executing program

1. Ensure you have Node.js installed on your machine.

2. Open a terminal in the project directory and run the JavaScript file using Node.js.

   ```bash
   node nftCollection.js
   ```

3. The program will automatically execute the minting of NFTs, listing all NFTs, and displaying the total supply of NFTs.

   Example output:
   
   ```plaintext
   NFT Minted:btcbitcoin
   NFT Minted: ETHEthereum
   NFT Minted: BNBBNB

   NFT #1
   Name: btcbitcoin
   symbol: BTC
   amount: 5686872
   day: TUES

   NFT #2
      Name: ETHEthereum
   symbol: ETH
   amount: 31657
   day: MON

   NFT #3
      Name: BNBBNB
   symbol: BNB
   amount: 50084
   day: WED


   Total NFTs Minted: 3
   ```

## Help

For common issues or troubleshooting, please refer to the following:

- Ensure you have the latest version of Node.js installed.
- Make sure the JavaScript file is correctly saved and there are no syntax errors.

```bash
// If you encounter issues with execution
node nftCollection.js
```

## Authors

Contributors names and contact info

-Abhay Bansal

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.
