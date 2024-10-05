## Scoot-Scoot

## Overview
Scoot Scoot an e-scooter rental app built on Solana. Scoot Scoot breaks down the barriers of traditional urban transportation, offering a simple, rewarding, and efficient way to navigate cities while contributing to a greener planet. With every ride, users can earn our Carbon Tokens that can be used for future rides or within our growing ecosystem of Solana products in Sierra Leone and beyond.

## Repositories

### Core API
This repository contains all the necessary functions for integrating Solana blockchain into our e-scooter rental platform. It uitilizes web3.js and has the logic to handle payments by first checking balance of the user and then initaiting the payment process. This API was built to function as a Solana action.

**Technologies used:** Express JS, Web3 JS, Solana Actions SDk
**Features**
-Checks the sender's USDC balance
-Prepares a transaction to transfer 1 USDC if the balance is sufficient
-Returns a serialized transaction ready for signing by a Solana wallet
-**Repository Link:** [https://github.com/stElmitchay/skoot-core]

### Mobile Application
This repository contains the core functionality of the mobile application 
**Technologies used:** React Native, Supabase, Mapbox API
**Features**
-Performas the core fuctionaliuty of the mobile application
- Includes logic to start and end rides
- Includes logic that logs users and ride data to Supabase
- Includes logic for wallet creation upon sign up 
-**Repository Link:** [https://github.com/giantfoe/scoot-scoot-mobile]

##Support
For any questions or support regarding these repositories, please open an issue in the respective repository or contact our development team at `mitchel@christex.foundation`.

Join us in reshaping urban mobility and building a more sustainable future, one ride at a time!
