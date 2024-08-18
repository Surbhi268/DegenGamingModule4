# ETH+AVAX MODULE_4 DEGENGAMING_TOKEN

![Avalanche](https://img.shields.io/badge/Avalanche-Fuji_Network-red.svg)
![Status](https://img.shields.io/badge/Website-Running-088395.svg)

In this we have create an ERC20 token and deploy it on the Avalanche network for Degen Gaming.

## Description
I created and deployed the Degen Token (DGN) on the Avalanche Fuji testnet using the ERC20 standard. This project includes a fully integrated React.js frontend that allows users to interact with the smart contract seamlessly. Key features of the platform include the ability for users, excluding the owner, to purchase DGN tokens using Wei. The owner has the exclusive ability to mint new tokens. Users can also burn their tokens, transfer them to friends, and view NFTs they have redeemed in the game.

The platform includes a store where various NFTs are listed with their respective DGN token prices. Users can redeem these NFTs using the DGN tokens in their accounts, with the token balance automatically decreasing upon successful redemption. Additionally, the interface integrates with Metamask, allowing users to connect their wallets, see their testnet address, and view their token balance directly from the page. The project offers a comprehensive in-game economy experience powered by blockchain technology.

Code walkthrough vedio-
https://www.loom.com/share/428665803a9247be9bae4b0f88394094?sid=a0f38487-c08d-4ca4-9faf-e4419e80b54b

- After successful connection
  
![WhatsApp Image 2024-08-18 at 15 45 59_f5b53f46](https://github.com/user-attachments/assets/638bb9b8-23c9-4edc-bbf4-67b50c162dfa)


- SNOWTRACE TESTNET(ADDRESS RECORDS), show what are the transactions being performed
  
![WhatsApp Image 2024-08-18 at 15 44 38_69a5aa72](https://github.com/user-attachments/assets/deb49e5f-7bb9-47e7-a5bf-50dfe1cfcee8)
![WhatsApp Image 2024-08-18 at 15 45 01_5baa0769](https://github.com/user-attachments/assets/1adc48c9-c049-4380-8173-acfc41736926)

- Inside the transactions
  
 ![WhatsApp Image 2024-08-18 at 15 45 34_9672a85a](https://github.com/user-attachments/assets/635d3a02-1e60-415f-ae2d-f0f2e617c989)

## Getting Started

- Detailed explanation of the project you will find in above code walkthrough vedio

 - Firstly the contract has been deployed using the remix
![WhatsApp Image 2024-08-18 at 15 48 54_638a7984](https://github.com/user-attachments/assets/08559b89-f791-453d-8102-fceb7a4bc454)

![WhatsApp Image 2024-08-18 at 15 49 21_787ad4a6](https://github.com/user-attachments/assets/804dec86-6280-49bb-9f39-af8753411c0d)

![WhatsApp Image 2024-08-18 at 15 48 18_f1d8a8d1](https://github.com/user-attachments/assets/98155fc4-7c36-4213-99ab-2d2a4c510d45)

- I have intergrated it to frontend also for seamless experience using next.js
- Now I can buy tokens, mint tokens, burn tokens, transfer token to another address, redeem our tokens, see the token balance in the webpage(localhost:3000)
- Minting using the avalanche fuji testnet
  
![WhatsApp Image 2024-08-18 at 15 47 05_d24fe273](https://github.com/user-attachments/assets/522e2183-c7e1-4ecd-afd4-9c919fee0115)

- Transferring

 ![WhatsApp Image 2024-08-18 at 15 47 18_f312593e](https://github.com/user-attachments/assets/829ed1a3-2c2a-4090-a060-d957411e09b3)

- Burning
  
  ![WhatsApp Image 2024-08-18 at 15 47 32_9d97b729](https://github.com/user-attachments/assets/e5a3af4b-8013-454d-87b3-8ba7858437e1)


- View redeemed nfts from the store
  
![WhatsApp Image 2024-08-18 at 15 46 48_85502b07](https://github.com/user-attachments/assets/ac31c95e-8b16-41f6-a253-96725d4656e1)
 

- Degen Gaming Nfts
  
![WhatsApp Image 2024-08-18 at 15 46 25_00373f41](https://github.com/user-attachments/assets/a4e1a3bf-cab5-457d-9414-40d7df051262)

  
### Executing program
  - Firstly compile the solidity contract then copy the address of deployed contract and paste it on the page.js>contractAddress then
  - For executing I have to simply go on bash and write the command {npm run dev}. It will start the local server at available port
    
## Authors
Surbhi Priya

email - psurbhi237@gmail.com

## License

This project is licensed under the MIT.
