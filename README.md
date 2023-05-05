# Anti Social

## Tech Stack

iOS App
Cosmos Blockchain

## Flow chart

1. User Account Creation/Sign In
2. Select Social Media Platform
3. Lock Platform for a Certain Time Period
4. User Cannot Use Platform During Locked Time Period
5. If User Completes Locked Time Period, Earn xxx Amount of Coins
6. If User Breaks Locked Time Period, Penalized with xx Amount of Coins
7. Add Friends
8. Trade Coins with Friends
9. Highest Earner Featured on App
10. Share Achievements on Social Media

## Algorithm

### User Account Creation/Sign In

- User enters email and password
- App checks if the user already has an account
- If not, the app creates a new account and gives the user 1000 coins
- If yes, the app logs the user in

### Select Social Media Platform

- User selects a social media platform from a list of available platforms

### Lock Platform for a Certain Time Period

- User selects the social media platform he wants to lock
- User selects the time period for which he wants to lock the platform
- App records the start time of the lock and the end time of the lock

### User Cannot Use Platform During Locked Time Period

- App checks if the current time is between the start time and the end time of the lock
- If yes, the user cannot use the locked social media platform
- If no, the user can use the locked social media platform

### If User Completes Locked Time Period, Earn xxx Amount of Coins

- App checks if the current time is after the end time of the lock
- If yes, the app rewards the user with xxx amount of coins

### If User Breaks Locked Time Period, Penalized with xx Amount of Coins

- App checks if the user has used the locked social media platform before the end time of the lock
- If yes, the app penalizes the user with xx amount of coins

### Add Friends

- User selects the option to add friends
- App prompts the user to connect their social media account
- App fetches the user's friend list from the connected social media account
- User selects the friends they want to add on the Anti Social App

### Trade Coins with Friends

- User selects the option to trade coins with friends
- App prompts the user to select a friend to trade with
- App prompts the user to enter the amount of coins they want to trade
- App deducts the traded coins from the user's account and adds it to the friend's account

### Highest Earner Featured on App

- App checks the account balance of all users
- App displays the highest earner on the Anti Social App's leaderboard

### Share Achievements on Social Media

- User selects the option to share an achievement on social media
- App prompts the user to connect their social media account
- App posts a congratulatory message on the user's social media account

## Setting up a Cosmos Blockchain

-[ ] Install the Cosmos SDK
-[ ] Initialize a new Cosmos Blockchain

Run the following command to create a new Cosmos Blockchain

```bash
gaia init <chain-id> --home=<path-to-your-gaia-folder>
```

- Replace `<chain-id>` with the name of your new chain, and `<path-to-your-gaia-folder>` with the path to your new blockchain folder.

- [ ] Configure the Genesis File

Edit the `~/.gaia/config/genesis.json` file to configure the initial state of the blockchain.

- [ ] Start the Blockchain

Run the following command to start your new Cosmos Blockchain

```bash
gaiad start --home=<path-to-your-gaia-folder>
```

## Connecting your App to the Cosmos Blockchain

- [ ] Install the Cosmos SDK in your App
- [ ] Add the Cosmos SDK as a dependency in your app's package manager.
- [ ] Create a new Wallet
- [ ] Use the Cosmos SDK to create a new wallet for your app.
- [ ] Store the wallet's address and private key securely.
- [ ] Connect to the Blockchain
- [ ] Use the Cosmos SDK to connect your app to the running Cosmos Blockchain.
- [ ] Use the blockchain's IP address and port number to establish the connection.
- [ ] Create Transactions
- [ ] Use the Cosmos SDK to create transactions that interact with the Cosmos Blockchain.
- [ ] Sign the transactions with your app's wallet private key.
- [ ] Broadcast Transactions
- [ ] Use the Cosmos SDK to broadcast the signed transactions to the Cosmos Blockchain.
- [ ] Query the Blockchain
- [ ] Use the Cosmos SDK to query the Cosmos Blockchain for information about the current state of the blockchain.

## Files Needed

**Cosmos SDK:** The Cosmos SDK files are needed to create and interact with the Cosmos Blockchain.

**Genesis File:** The genesis.json file is needed to configure the initial state of the Cosmos Blockchain.

**Wallet:** A wallet is needed to sign and broadcast transactions to the Cosmos Blockchain.

**App Files:** The files needed to create and run your iOS app. These files will depend on the programming language and framework you are using.

**Swift SDK for Tendermint:** The Swift SDK for Tendermint is needed to connect your iOS app to the Cosmos blockchain.

**Configuration files:** The configuration files are needed to connect your iOS app to the running Cosmos blockchain.

**Transaction files:** The files needed to create and interact with transactions on the Cosmos blockchain.

**Query files:** The files needed to query the Cosmos blockchain for information.
Smart contract files: The files needed to create and deploy smart contracts on the Cosmos - blockchain.

## Detailed steps to help you connect your iOS app to the Cosmos blockchain

- [ ] Install the Cosmos SDK in your iOS app
- [ ] Add the Cosmos SDK as a dependency in your app's package manager, such as CocoaPods or Carthage.
- [ ] Create a new wallet
- [ ] Use the Cosmos SDK to create a new wallet for your app.
- [ ] Store the wallet's address and private key securely.
- [ ] Connect to the blockchain
- [ ] Use the Swift SDK for Tendermint, which is a popular blockchain protocol that supports the Cosmos SDK, to connect your iOS app to the running Cosmos blockchain.
- [ ] Use the blockchain's IP address and port number to establish the connection.
- [ ] Create transactions
- [ ] Use the Swift SDK for Tendermint to create transactions that interact with the Cosmos blockchain.
- [ ] Sign the transactions with your app's wallet private key.
- [ ] Broadcast transactions
- [ ] Use the Swift SDK for Tendermint to broadcast the signed transactions to the Cosmos blockchain.
- [ ] Query the blockchain
- [ ] Use the Swift SDK for Tendermint to query the Cosmos blockchain for information about the current state of the blockchain.
- [ ] Create smart contracts
- [ ] Use the Cosmos SDK to create smart contracts that run on the Cosmos blockchain.
- [ ] Use the Swift SDK for Tendermint to interact with the smart contracts from your iOS app.
- [ ] Deploy smart contracts
- [ ] Use the Cosmos SDK to deploy the smart contracts to the Cosmos blockchain.
