# BerandNFTForm

---  

## Overview

**BerandNFTForm** is a user-friendly tool designed for business owners who want to launch a campaign using NFT tokens. It simplifies the process of creating and deploying an NFT contract for promotional campaigns, where customers can claim campaign-specific NFTs by discovering and submitting a secret message.


### Features

- **Simple Form Interface**: Business owners only need to fill out a form with the campaign details, and the BerandNFTForm server handles the rest.
- **Automated NFT Deployment**: The server automatically deploys an NFT contract once the form is submitted.
- **Customer Redemption**: Customers can claim the NFTs by finding and submitting a secret message shared by the business owner.

--- 

## How It Works

1. **Business Owner**: 
   - Fills out a form with the necessary details for their NFT campaign.
   - The parameters include:
     - `name`: The name of the NFT.
     - `symbol`: The symbol for the NFT (e.g., BERA).
     - `maxSupply`: The maximum number of NFTs that can be minted.
     - `benefit`: A description of the benefit associated with the NFT (e.g., "free coffee").
     - `redemptionProcess`: Instructions for customers on how to redeem the benefit.
     - `expirationDate`: The expiry date for the campaign and NFTs.
     - `terms`: Specific terms and conditions for the campaign.
     - `secretMessage`: A message that customers must find to claim the NFT.
     - `defaultTokenURI`: A default image or metadata associated with the NFTs.
  
2. **BerandNFTForm Server**: 
   - Once the form is submitted, the BerandNFTForm server automatically deploys the NFT contract with the parameters provided.
   - The business owner is responsible for sharing the `secretMessage` through their preferred channels.

3. **Customer**: 
   - To receive the NFT, customers must discover the secret message and use it to claim the token through the contract.

---  
## Example Use Case

A coffee shop launches a campaign where customers can receive an NFT by discovering a secret code hidden on their campaign website domain. Once they have the NFT, they can redeem it for a free coffee at any participating location before the campaign's expiration date.

--- 

## Demo Form 

Below is the demo form website that showcases the simplicity of deploying a NFT contract using our form. 

[DemoServer](https://campaign.berand.org) 


