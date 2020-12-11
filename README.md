<div class="mobile-fixed">

# Ethereum Wallet 101
# Preface

Looking back on the decades of development of cryptocurrencies, Bitcoin (BTC) is the pioneer that has overcome difficulties, promotes fairness and justice represented by decentralization, and created the precedent for decentralized cryptocurrencies. The spirit of Satoshi Nakamoto and the design of Bitcoin are great, but unfortunately, due to the lack of scalability of Bitcoin, it is difficult for the Bitcoin network to support more advanced and complex applications. The problems mentioned here are also confirmed by the functions of the early Bitcoin wallets, which were only two: asset management and mining.

Ethereum (ETH) is an open-source public blockchain platform that supports smart contracts and also one of the most prosperous public chains. The main objectives of Ethereum were to:

 - Solve the scalability problem of the blockchain network,
 
 - The automatic execution and editable features of smart contracts,
 
 - Fits the idea of decentralization,

 - Greatly improve the efficiency and features of the blockchain network,
 
 Since then, DApps with various functions have been developed based on Ethereum, and the Ethereum ecosystem has flourished. It is fair to say that Ethereum has set the path for the future development of public chains, and the public chain ecosystem has begun to rise.
 
 In this context, as a core component of the Ethereum ecosystem, the functions of the wallet will naturally not be limited to single fund management and mining. As the scale of functional DApps on Ethereum grows, users can interact with the chain through the wallet at any time to perform operations such as mining, gaming, staking, voting, and investing in DeFi. As a convenient entrance to on-chain applications, it has brought vitality and prosperity to the public chain ecosystem. The prosperity and competition also encourage wallets to maintain extremely high update efficiency and comfortable user experience, thus forming a virtuous circle. The majority of users who want to take part in the Ethereum public chain ecosystem must first understand the basics of Ethereum and learn how to use the Ethereum wallet.
 
 # Ethereum Account and Wallet
 ## What is an Ethereum Account?
 
<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111454.png)
</center>
In Ethereum, an account is called an address. In the figure above, the ETH address would be 0xd6755E6Ac74dB436370e8a70f04195F8d6Dd6852. The standard Ethereum account format is as follows.

 - The address starts with 0x. The prefix indicates that this is a hexadecimal number.

 - 0x is followed by 40 characters, the value range of each character is one of the 16 characters between 0-9 and a-f.

There are 2 types of accounts, namely externally owned accounts, and contract accounts. 

 - Regular users use external accounts, which are controlled by private keys. As long as the user holds the account’s private key, basic operations such as transfer, deposit, and authorization can be performed.

 - Contract accounts are controlled by the code of the smart contract.
 
 While external accounts can trigger transactions, contract accounts cannot actively initiate transactions, and can only execute transactions according to pre-written smart contract code after being triggered.
 
 During the daily usage, in addition to ordinary transfers, we often perform authorization operations on contract accounts. For example, when using Uniswap, we authorize a token to interact with a contract account. To avoid the loss of assets, we need to understand the specific scope of authorization. For example, TokenPocket, in order to avoid smart contracts from performing malicious transactions, we added a function to set the number of token authorizations for approval.
 
## How to Create an Ethereum Wallet?

Ethereum is the pioneer of smart contracts. It has a broader consensus and community. The current mainstream digital wallets basically all support the Ethereum chain. Users can easily complete the creation of an Ethereum account using the wallet apps.

1. Select [Ethereum]

2.	[Create Wallet]

3.	Set a wallet name, set the password, and click [Create wallet]

4.	After clicking [Create wallet], a mnemonic phrase will be generated, make sure to back it up, and then enter the mnemonic phrase in the same order to confirm.


<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111548.png)
</center>

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111549.png)
</center>

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111550.png)
</center>

<center>(TokenPocket Ethereum wallet creation page)</center>

When creating an Ethereum wallet in TokenPocket (hereinafter referred to as TP wallet):

 - First, you need to enter a wallet name, which is mainly used to identify your wallets in TP, as multiple Ethereum wallets can be created, the name can be customized.
 
 - For transfers and exportation of the private key, you must enter the wallet password. This is for the protection of your assets and the private key.
 
During the process of creating a wallet, you must copy and keep the private key safely. In order to lower the threshold for users, most digital wallets generally provide mnemonic phrases. Mnemonic phrases are generally composed of 12 ordered English words, which can also be imported into the wallet through [mnemonic phrase].

Backing up mnemonic words is the same as backing up a private key. You may copy them, preferably offline, on two pieces of paper and keep them safely in separate places. If you prefer to make an online backup anyway, try to save it after editing it, i.e. inserting a few random words in between. In short, try not to save a complete mnemonic phrase online. We do not recommend that users back up their private keys and mnemonic phrases online.

## Import an Ethereum wallet

If you already have an ETH account, you can import it directly. You can import the Ethereum wallet in three ways: The private key, mnemonic phrase, and Keystore.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111642.png)
</center>

*1. Import an Ethereum wallet through a private key*

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111645.png)
</center>

1.	Enter the private key or scan the QR if you have it.

2.	Name the wallet

3.	Set a password and double confirm

4.	Set a hint if you wish

5.	Click [Import Wallet] 

*2. Import an Ethereum wallet through the mnemonic phrase*

In addition to using the private key to import the wallet, importing the wallet through the mnemonic phrase is also a common import method. When importing mnemonic words, input them in order, and pay attention to separating words with spaces.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111652.png)
</center>

1.	Enter the private key or scan the QR if you have it.

2.	Name the wallet

3.	Set a password and double confirm

4.	Set a hint if you wish

5.	Click [Import Wallet] 

*3. Import an Ethereum wallet through Keystore*

1.	Paste the Keystore content

2.	Check “Read and agree with the term and conditions”

3.	Name the wallet

4.	Click [Import Wallet]

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111654.png)
</center>

*About Keystore*

A Keystore File (sometimes called a UTC file) is an encrypted version of your private key. They are generated using your private key and a password that you use to encrypt it. If you open up your Keystore file in a text editor it contains data pertaining to the encryption of the private key.

Keystore, private key, and mnemonic phrases are common to all wallets. The wallet service provider may choose to only provide its users with one or more of these methods, but if the same method cannot be restored normally in a wallet, the wallet may have certain problems.

*About the password*

In order to further enhance security, most wallets will use a password to encrypt the private key twice. The encryption method and storage method of each wallet is different.

This is why when you use a wallet to conduct transactions, you always need to perform authorization. This actually involves the wallet using the password to decrypt the private key, and then use the private key to sign the transaction and other complex processes.

## Export an Ethereum Wallet

Corresponding to the three import methods, we can export the mnemonic phrase, private key, and Keystore of the account in [Settings]. When exporting, we need to enter the password of the wallet.

Many new users often forget the wallet password they had set before. In this case, the only way is to re-import the private key, mnemonic phrase, or Keystore and set a new wallet password. You may also reset the password through the mnemonic phrase and/or private key.

Note: As a decentralized wallet, TP does not store the user's private key, mnemonic phrase, Keystore, or password. This guarantees the security of the user's assets to the greatest extent, and your assets are controlled only by you. Therefore, when the user loses this information, TP cannot give any help, so please be sure to save it properly!

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111659.png)
</center>

Among them, the private key is a string of letters, and the Keystore is a file composed of characters. When backing up the Keystore, you can also use the QR code to back up.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111700.png)
</center>

## Ethereum GAS

Transactions on the Ethereum network are not free. When sending transactions, a small fee, the Gas Fee, is required. The existence of fees is to give nodes and miners sufficient compensation and incentives and, at the same time, to prevent small and junk transactions. Users must pay fees when trading on Ethereum, otherwise, they will not be able to complete the transaction.

## How is the Gas Fee calculated?

The fee on Ethereum is also called Gas. In the transaction records displayed on the Ethereum browser Etherscan (https://etherscan.com/), you will see Gas Limit, Gas Used by Transaction, and Gas Price, which are special terms related to gas fees. 

 - Gas Limit: the maximum amount of resources that can be consumed in this transaction.
 
 - Gas Used by Transaction: the actual amount of resources consumed.
 
 - Gas Price: the unit price of resources.

*Gas Limit* represents the upper limit of the resources that can be used by the transaction. It prevents contract vulnerabilities or malicious programs from causing users to consume an excessive amount of Gas. Once the amount of Gas consumed exceeds the Gas Limit, the miner will stop executing the program and stop the loss in time, so it can be regarded as insurance.

 - If the actual gas consumption exceeds the set upper limit, the transaction will be terminated. 
 
 - If the actual consumption of gas is lower than the upper limit, the excess gas will be returned. 
 
 - The actual consumption of resources in the transaction, this is, Gas Used by Transaction is generally related to the settings in the transaction contract.

The common unit of *Gas Price* is Gwei, and the conversion for Gwei and ETH is 1ETH=10^9Gwei, that is, 1ETH=1 billion Gwei. Generally speaking, the value of Gas Price is very small, and the setting of Gwei is for the convenience of expressing a small amount of ETH. For example, when we make a transaction, we set the Gas Price to 0.000000012 ETH and use Gwei as the unit to express it as 12Gwei. Obviously, the latter is more simple and intuitive.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111703.png)
</center>

From the image above, we can see that the transaction fee depends on the Gas Used by the Transaction and Gas Price. The formula is as follows: 

Transaction Fee = Gas Used by Transaction * Gas unit Price.

To help you understand, let’s use a simple example: Suppose you need to send a package, the courier company charges a fee based on the weight of the package, and the shipping cost = package weight * postage per kilogram, that is, the heavier the package, the higher the postage. Here, you can easily find out that: 

 - Postage = handling fee

 - The weight of the package = amount of resources used 
 
 - The postage per kilogram = the unit price of resources.

Then, we can extend this example a bit to get more conclusions. Suppose this company offers 2 services, land transport, and air transport. Air transportation is more expensive, but also much faster. Similarly, when making a transaction on Ethereum, if you set the Gas Price relatively high, then the miners tend to prioritize your transaction, and the transaction confirmation speed will naturally be faster.

## How to set the handling fee (GAS) 

Generally speaking, there are only two parameters that users need to set when making a transfer: Gas Limit and Gas Price. Gas Limit can be calculated by code, and the value of Gas Price and transaction speed is determined by the current network conditions. However, don’t worry about the calculations! Nowadays all the mainstream wallet apps on the market will help you calculate and give recommended values.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111706.png)
</center>

When making transactions on the TP Wallet, it will give the user 3 options - slow, recommended, and fast - according to the current network conditions. The corresponding fees and estimated transaction confirmation time are also displayed intuitively so users can choose the appropriate option according to their demand for transaction speed. This system is user-friendly, with reasonable allocation for the 3 options, which generally covers all users’ transfer speed requirements, and enhances the user experience while effectively reducing the risks related to manual input.

Of course, if the user needs to modify the Gas Limit or is willing to set a higher Gas Price, just click [Customize] to manually set the Gas Limit and Gas Price. The corresponding handling fee and estimated time will also be displayed in real-time to provide users with reference, so it is also convenient for you!

## Ethereum Transactions

Every transaction on Ethereum consumes GAS, which will be deducted from the ETH balance. When the balance is not enough to pay the GAS fee, the transfer will fail.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111708.png)
</center>

To make a transaction: 

1.	Enter the receiver’s ETH address

2.	Enter the amount of ETH to transfer

3.	Select the gas fee option

4.	Click [Confirm]

## TokenPocket Ethereum Gas Station

When the Gas is insufficient during a transaction, you can use the Gas Station on TokenPocket to quickly recharge some.

1.	Click on [Gas Station]

2.	Select the address to recharge (If you have multiple)

3.	Pay and [Confirm]. You can either choose Alipay or Paypal

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111709.png)
</center>

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111710.png)
</center>

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111711.png)
</center>

## Ethereum Transaction Speedup 

Due to the limitations of the Ethereum public chain, when there are too many transactions happening at the same time, the Ethereum network will be congested, and the transaction confirmation time will be longer than usual, so the transaction status will usually be displayed as "pending" during some time.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111712.png)
</center>

For transactions that are "pending", in addition to canceling the transaction or continuing to wait, you can also use the speed-up function in TokenPocket to accelerate the completion of the transaction. The principle is actually to pay more miners' fees so that miners process our tx first. On the speed up page, TokenPocket will automatically select the best miner fee for the user. There is no need to adjust the miner fee, you can accelerate with one click; at the same time, the user can also customize the miner fee.  

## Authorization

Most DApps on ETH involve contract operations, so when you authorize them, you authorize a certain contract address to manipulate a certain amount of tokens in the address; during the operation, if you authorize token transfers to a malicious contract, this contract will be able to use your tokens as collateral or other malicious operations.

E.g:

Alice has 10,000 tokens, Bob does not have tokens, and Charlie does not have tokens either

Then: Alice delegates Bob to transfer 100 tokens to Charlie. How do we achieve this? 

First, we have to establish a delegation association between Alice and Bob, log in to Alice’s account and execute the approve(b,100). Result: _allowed[A][B] = 100token

Then: execute transferFrom(A,C,100) in Bob’s account. Here, Bob’s is the delegate account sender, gas is deducted from here, and the number of tokens must be less than _allowed[A][B]

In summary, Alice wants to transfer some tokens to Charlie, but the transaction must be sent through Bob's account!

Users are quite familiar now with the DeFi on Ethereum, with such well-known tools as Uniswap, Curve, Balancer, etc. All these tools are easy to use, powerful, and convenient for listing tokens, but also attract malicious users to the platform, so there may be risks every time we trade ERC20 tokens (especially with new tokens). On the TokenPocket wallet, we can now directly see the [Operation Type] and [Authorization Quantity] within the wallet app, to remind users of potential risks.

# Ethereum Token and Wallet
## Ether (ETH), the token
### ETH issuance

Ethereum is the blockchain and ETH is the primary asset/digital asset of Ethereum. Ethereum ecosystem developers need to pay ETH to fuel the operation of the DApps, and users also need to pay a certain amount of ETH as a transfer fee, Gas, when transferring funds.

Unlike Bitcoin, Ethereum's token issuance plan was not set before its creation. Bitcoin protects value by limiting the supply and reducing the number of new tokens, while Ethereum provides a base for decentralized applications (DApps) through tokens. It has not yet been determined what type of token issuance plan is suitable for this purpose.

ETH's valuable in different ways to different people.

 - For users of Ethereum, ETH is valuable because it lets you pay transaction fees.
 
 - Others see it as a digital store of value because the creation of new ETH slows down over time.
 
 - More recently, ETH has become valuable to users of financial apps on Ethereum. That's because you can use ETH as collateral for crypto loans, or as a payment system.
 
 - Of course many also see it as an investment, similar to Bitcoin or other cryptocurrencies.

### How to get ETH Token

Users can obtain ETH Token through three methods: instant token swap, purchase with fiat currency, and through exchange trading.

### Buy it from Exchanges

ETH and the tokens issued on the ETH public chain can be purchased on centralized exchanges, such as Binance, Huobi, and OKEx, etc. However, the types of ETH assets that can be traded in centralized exchanges are often very limited. Generally, only well-developed & high-quality assets can be listed on major centralized exchanges, and other assets on ETH that don’t match those characteristics issued are often traded on decentralized exchanges. 

At present, the best ETH DEX is Uniswap, on which almost all ETH assets can be traded.

Find Uniswap in the [Recommended DApps] area of TokenPocket to trade ETH assets. You can also use the token swap function on the TP wallet to trade ETH assets.

You can consult a list of exchanges here: https://coinmarketcap.com/es/rankings/exchanges/ 

### Token Swap

The Token Swap function allows users to exchange tokens on the ETH chain, such as ETH for DAi, or ETH for BTC/TRON/EOS, and other assets. Such a cross-chain exchange can facilitate the circulation of assets on different chains.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111718.png)
</center>

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111719.png)
</center>

1.	Click on [Swap]

2.	Choose the tokens to swap and enter the amount, receive address

3.	Click [Instant Swap] to perform the swap.

### OTC deals

In addition to exchanges and token swaps, ETH can also be purchased through over-the-counter trading platforms.

After buying ETH, you can use ETH to buy other assets issued on ETH.

### Introduction to other tokens on Ethereum

### Ethereum-USDT

Among the high-quality digital assets issued on Ethereum, USDT is one of them. Every tether is always 100% backed by our reserves, which include traditional currency and cash equivalents and, from time to time, may include other assets and receivables from loans made by Tether to third parties, which may include affiliated entities (collectively, “reserves”). Every tether is also 1-to-1 pegged to the dollar, so 1 USD₮ is always valued by Tether at 1 USD.

Source: https://tether.to/ 

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111722.png)
</center>

Users can use SWIFT to wire USD to the bank account provided by Tether or buy USDT from the exchanges. Users can also exchange bitcoins for USDT on numerous platforms. Ethereum-USDT is Tether issuing ERC20 tokens on the Ethereum network. At present, Tether has issued corresponding versions of USDT tokens on public chains such as Bitcoin (Omni), EOS, and TRON. Among them, the number of ETH-USDT is the largest, which has also boosted the development of the ETH public chain ecosystem.

### Ethereum NFT Token

NFT stands for Non-Fungible Tokens. The common tokens, such as ETH, are all homogenized. There is no difference between each ETH on the network and ERC20 tokens can be considered as fungible tokens. The important feature of NFT is that each NFT is special and different, is not interchangeable between pairs, the minimum unit is 1, and is indivisible.

In many scenarios, the value of the tokens should not be equivalent. For example, the value of items in games is different from each other. Another example, if we tokenize the tickets for a football match, each ticket should have a unique value as every seat has a different value.

In order to distinguish between different tokens and their values, the Ethereum network sets a different token ID for each token to distinguish it when issuing tokens. Such tokens are called NFTs. There are two standards dedicated to the issuance of NFTs in Ethereum, the ERC721 standard, and the ERC1155 standard.

The ERC721 standard defines the interface and characteristics of the NFT in detail. 

The ERC1155 standard was proposed by Enjin, which can 

 - Simultaneously issue Fungible token and Non-Fungible token in one contract. 
 
 - Issue multiple tokens in one contract 
 
These features make it more powerful. For example, the well-known CryptoKitties game uses NFT tokens. Different cats have different values because they are all unique.

### Ethereum Token trading platforms
### Uniswap

ETH and other tokens issued on Ethereum are not exclusively on CEX such as Binance, Huobi, and OKEx, but also on DEX such as Uniswap.

In November 2018, Uniswap was officially launched, positioning itself as a decentralized exchange (DEX) based on Ethereum. Although DEX improves the security of user assets, due to the size of its orders, the liquidity of most DEX assets is not good, and the (slow) transaction speed has become a flaw. In order to solve this problem, Uniswap did not adopt the mainstream order book trading system but chose an automated market maker mechanism. Uniswap's innovative trading mechanism has also started an upsurge in the DEX field, and a large number of AMM projects have emerged since then.

<center>

![ETH address](https://tp-statics.tokenpocket.pro/banner/tokenpocket-202012111723.png)
</center>

At present, in most mainstream decentralized wallet apps such as Token Pocket, you can log in to Uniswap directly to trade. To trade on Uniswap, you just have to select the token and quantity to be exchanged on the interface. The exchange ratio and transaction slippage (price error) will be automatically displayed at the bottom of the page. If all the details are reasonable, click [Swap] to perform the operation immediately. Even if the token that the user chose does not have a direct transaction pair, Uniswap will automatically help the user find the best price path. On the interactive interface, the user only needs to send a transaction to complete the exchange, a one-click Swap.

对Uniwap感兴趣的用户还可以通过以下文章获得更多了解

《人人都玩的Uniswap到底是什么？》点击阅读

《最好用的Uniswap钱包和教程来啦！》点击阅读

### Balancer

Balancer is an automated market maker (AMM) program. On this platform, users do not need to pay fees but actually collect fees from traders who rebalance their portfolios by following arbitrage opportunities. Users can exchange between ETH and ERC20 tokens, or ERC20 tokens in Balancer.

对Balancer感兴趣的用户可以点击阅读使用教程

### Curve

Curve is the main exchange for stable currencies and BTC-ERC20. The advantages of curve are low transaction slippage, low handling fee, high yield, and single token deposit and withdrawal. With these, Curve has attracted a large number of users in a relatively short period.

对Curve感兴趣的用户可以点击阅读使用教程

### AAVE

Aave is a decentralized non-custodial money market protocol where users can participate as depositors or borrowers. Depositors provide liquidity to the market to earn a passive income, while borrowers can borrow in an overcollateralized (perpetually) or undercollateralized (one-block liquidity) fashion. To use the service, you simply deposit your preferred asset and amount. After depositing, you will earn passive income based on the market borrowing demand. Additionally, depositing assets allows you to borrow by using your deposited assets as collateral. Any interest you earn by depositing funds helps offset the interest rate you accumulate by borrowing.

Compared with traditional banks, the Aave protocol can make your incomes more efficient. For example, the borrower can switch between stable and flexible interest rates to maintain the market advantage and obtain the best interest rate.

对AAVE感兴趣的用户可以点击阅读使用教程

### Synthetix

Synthetix is a decentralized synthetic asset issuance protocol built on Ethereum. These synthetic assets are collateralized by the Synthetix Network Token (SNX) which when locked in the contract enables the issuance of synthetic assets (Synths). Synthetic assets include sBTC (BTC synthetic asset), sETH (ETH synthetic asset), iBTC (BTC reverse asset, that is, iBTC rises when BTC falls), iETH, sXAU (gold synthetic asset), and so on.

Synthetix provides a channel for DeFi to use traditional financial assets and more diverse and complex trading strategies. The process of issuing synthetic assets is: 

1.	Stake SNX to generate sUSD

2.	Use sUSD to purchase synthetic assets.

对Synthetix感兴趣的用户可以点击阅读使用教程

### Compound

Compound is an algorithmic, autonomous interest rate protocol based on the Ethereum blockchain. It is a smart contract that allows users to borrow and lend tokens similar to how the banks operate, Compound lends your money to borrowers and earns interest over time.

In February 2020, Compound announced that in order to realize the complete decentralization of the Compound protocol governance process, the team decided to issue a governance token, COMP, to create a community organized by token holders. Community members can make changes to the protocol through proposals and voting, replacing the current centralized governance.

对Compound感兴趣的用户可以点击阅读使用教程

### dForce

dForce advocates for building an integrated and interoperable and scalable open finance protocol network, cultivating intra-protocol liquidity and network effects, while remaining in full openness to interact and integrate with other protocols. Its main products include the dForce interest-earning market, synthetic stable currency USDx minting, stable asset flash swaps, and GOLGx digital gold tokens.

Liquidity mining was officially launched on August 3rd and users could stake dToken and provide liquidity of the corresponding token on Uniswap to farm. 

## Ethereum Wallet Usage 

### Ethereum Token transfer

#### 1. Three different transfer operations

*1) Ordinary transfer (transfer between Ethereum accounts)*

Ordinary transfer refers to transfers between independent Ethereum accounts. You only need to enter the recipient's ETH account number and the transfer amount.

*2) Transfer from an exchange account to an Ethereum account (wallet account)*

Transferring ETH from an exchange to your account (wallet account) means that the Ethereum is withdrawn from the exchange. To withdraw to your wallet, you only need to enter the withdrawal address (Ethereum wallet account) and the amount of ETH to withdraw.

*3) Transfer from Ethereum account (wallet account) to exchange account*

Also known as deposit, the user transfers ETH from the personal Ethereum account (wallet account) to the exchange. You just have to enter the address that the exchange provides to you and the amount of ETH to deposit.

#### 2. Rich and convenient transfer methods

At present, there are several ways to make a transfer: direct transfer, address book transfer, transfer by scanning, and transfer with watch wallet and cold wallet. 

*1) Direct Transfer*

Direct transfer refers to transfers between Ethereum addresses. Users just need to know the recipient's Ethereum account or the address of the exchange where they want to deposit, then copy it to the receipt space, enter the transfer amount, and click [Confirm].

*2) Address Book*

If the user has a commonly used Ethereum transfer address, he can add it to the wallet's address book. The address book works like our mobile’s address book so that users can directly select an account from the address book when transferring assets, saving time, effort, and avoiding errors.

*3) QR Code*

This method is similar to WeChat and Alipay QR code payment. By scanning the user's payment QR code, you can transfer assets to the designated account. It is very convenient for Face-to-face transfers.

4) Use watch mode and a cold wallet for transfers

If a user has a large number of assets stored for a long time but needs to make frequent transfers, it is recommended to use the watch mode + cold wallet to transfer funds and ensure security.

A so-called cold wallet is to physically isolate the wallet from the Internet (for example, a completely disconnected mobile phone) to keep the user's private key and mnemonic phrase from the Internet and ensure that the user's digital assets are close to 100% safe.

With the watch mode, we can observe the balance changes in other addresses without importing the private key and just with the account or public key. By observing the wallet, you can view the transaction records of the account.

When making a transfer, the user should first observe the wallet. Unlike usual transfers, when authorization is required, a QR code will pop up. At this time, use the cold wallet to scan the code. After scanning the code, another QR code will be generated. At this time, you need to use the watch wallet to scan the cold wallet in the reverse direction again to complete the entire transfer operation process.

### Reception of ETH Token 

In the Ethereum wallet, users can also receive ETH or withdraw from exchanges.

#### 1. Using the address

In the wallet interface, users can copy their own address and withdraw ETH from the exchange or transfer ETH from another platform or wallet, which is convenient and safe.

#### 2. Using the QR code

In this case, the user just has to scan the QR code to perform a transaction.

### Ethereum Wallet Whitelisting

The whitelist function provides great convenience for users who use DApps. When using DApps, the smart contract is repeatedly interacting with the user and asking for the user’s password with every interaction, which is inconvenient. The whitelist function grants authorization for specific smart contract operations in the DApp, so only need to enter the password once when setting up the whitelist.

The TokenPocket wallet supports whitelisting to facilitate users' operations.

### Ethereum Blockchain Explorer

A Blockchain Explorer is a web application to view and query blocks working as a web browser that is not connected to the internet, like Google Chrome, but the Blockchain. Their primary function is to allow everyone with an internet connection to track in real-time all the transactions or interactions made by each cryptocurrencies holders, regardless of his or her level of knowledge and expertise. Source

Commonly used Ethereum browsers are etherscan browser http://etherscan.io/ and etherchain browser https://www.etherchain.org/

With the Ethereum browser, you can query the basic data of the entire Ethereum network:

 - The latest block,
 
 - Number of transactions,
 
 - Number of accounts,
 
 - The number of tokens, etc.;
 
Query account information: transaction information, Ethereum balance and staking information, etc.;

You can also directly check transfers, balances, and voting rights.

### Ethereum Wallet Sorting Adjustment

Many users have multiple Ethereum accounts, and their frequently used wallets are located in the back, which is very inconvenient. The wallet sorting function can easily solve this problem. Users can adjust the order of their wallets by dragging it and move it to the top positions, which is more convenient for wallet switching and asset management.

### Ethereum related information acquisition

It is important for Ethereum users to always pay attention to the news from Ethereum to understand its latest development. Users can browse through all this information directly via the wallet. For example, in the TokenPocket wallet, all the latest news, newsletters, and important articles about Ethereum are included in the wallet's newsletter and channels, which optimizes the user's reading experience.

### Ethereum ENS

ENS is the abbreviation of the Ethereum Name Service. It is a scalable, distributed, and open naming system based on the Ethereum blockchain for serving human-readable mapping names. ENS maps human-readable names to machine-readable identifiers and has the function of reading Ethereum addresses, content hashes, and metadata.

When using Ethereum to transfer assets, you can enter the corresponding Ethereum domain name, and the wallet will automatically query the corresponding Ethereum address to realize convenient transfers.

## Ethereum DApps Experience

### DeFi and Wallets

Decentralized Finance, or DeFi, is opposite to traditional centralized finance and refers to applications in various financial fields built on an open decentralized network. The goal is to establish a multi-level financial system based on blockchain technology and cryptocurrencies, to rebuild and improve the existing financial system. Relying on blockchain technology, DeFi can solve many pain points of current centralized finance, such as opacity, low efficiency, and a single point of failure. At the same time, DeFi is highly compatible. Whether it is decentralized exchanges, decentralized lending, payment platforms, derivatives, etc., all can be included in the category of DeFi. Therefore, DeFi is a financial market with great potential and can also form a relatively complete closed-loop ecosystem.

The ETH ecosystem is one of the most well-known. With a large number of diversified ERC (ERC-20 and ERC-721) tokens on its mainnet, the wide application coverage, and the strong interoperability, Ethereum is far beyond the reach of other public chains. In addition, it also laid the foundation for the explosion of DeFi applications.

Most of the DeFi DApps are based on web-side development, so the compatibility with web wallet plugins like Metamask is greater. To easily interact with the contract, the user just needs to create or import a wallet and log-in on the DApp site. However, due to the high immediacy requirements of financial activities such as trading, the drawbacks of the plug-in wallets were revealed and mobile wallets began to become popular among users. After solving the compatibility problem, the mobile wallets are continuously optimizing and updating the DeFi Dapp experience. Users just have to install a mainstream digital wallet like TokenPocket on their mobile phones to enter DeFi DApp with one click and no restrictions on location and time. In addition, the mobile terminal digital wallet has begun to support the Wallet Connect function, and the scan code function in the mobile wallet app can interact with the desktop web wallets, which is convenient and safe!

### DAO and DeFi

The core of DeFi is decentralization, which also empowers DeFi with the advantages of openness, transparency, and no fear of single points of failure. However, a project can’t be described as disrupting if it still has a decentralized way of managing and operating, despite its decentralized on-chain trading. Only by the decentralization of managing power and making a radical change to the governance mechanism, can a revolutionary result been seen. That’s the reason why many DeFi projects are embracing DAO. 

What is DAO? A decentralized autonomous organization (DAO) is an organization represented by rules encoded as a computer program that is transparent, controlled by the organization members and not influenced by a central government. A DAO's financial transaction record and program rules are maintained on a blockchain. At the same time, as a token holder, everyone in the DAO can issue proposals and vote to make decisions so the existence of DAO can essentially solve the problem of DeFi project governance. In fact, DeFi and DAO are not new concepts that were born recently, and the earliest cooperation between the two can be traced back to Maker DAO, which was established in 2014. As early as 2014, MakerDAO, an automated platform on Ethereum, has made an attempt to move towards DAO, and it is also one of the representatives of DeFi projects.

### Popular DeFi applications

The type of applications that have been most developed in the DeFi field mainly include:

 - Credit & Lending
 
 - StableCoins
 
 - DEX
 
 - Payment
 
 - Derivative Protocols/Prediction Markets
 
 - Others
 
At present, lending and DEXs have received more attention because of their early start and development. In addition, the recent rise of asset data integration and liquidity mining has gained extremely high popularity and attracted a large number of users. The following are the current most popular ETH DeFi DApps

 - Credit & Lending: Aave, Makerdao, Compound, etc.
 
 - DEX: Uniswap, Curve Finance, Balancer, Bancor, etc.

 - Payment
 
 - Derivative Protocols: Synthetix, Nexus Mutual, etc.
 
 - Prediction Markets: Yearn.finance, RenVm, DForce, etc.
 
 - Crossed categories: WBTC, renBTC, etc.

TokenPocket wallet supports almost all popular ETH DeFi DApps at the moment, and is optimized for Uniswap, Balancer, and other popular ETH DApps and optimized DeFi, such as the launch of the Chinese version of Uniswap, adding Uniswap K-line function, trading market information, etc.

Note: high popularity does not mean risk-free. This does not constitute investment advice. Please beware of the risks that are related to investing.

## Ethereum 2.0 and Wallet 

### What is Ethereum 2.0

Ethereum 2.0 is a long-planned upgrade to the Ethereum network and can also be regarded as a substitute for Ethereum 1.0. It will make Ethereum more scalable, more secure, and more sustainable. These upgrades are being built by multiple teams from across the Ethereum ecosystem. In order to solve the “blockchain trilemma”, that is, the coexistence of decentralization, scalability, and security in a protocol, Ethereum 2.0 will introduce a series of innovative solutions such as:

 - The Beacon Chain
 
 - Shard Chains
 
 - The Casper protocol 
 
 - State rent, a mechanism for charging users to store data
 
 - Ethereum's new generation virtual machine project eWASM

In the future, Ethereum 2.0 will gradually become the main chain through continuous updates and iterations, and the current Ethereum main chain will become the shard chain under its management.

In all stages of Ethereum 2.0, users can participate in it through the wallet, whether for the pre-stake or various functions of the new chain after the official launch.

#### Follow the progress of Ethereum 2.0

According to the Ethereum 2.0 plan, there are at least three stages: stage 0, 1, and 2. The stage 0 plan, the beacon chain plan, will be launched on December 1st this year, and phase 1 and phase 2 will be released in the next few years. If 16,384 (2^14) validators participate before December 1st, the 2.0 beacon chain will officially launch. If this amount cannot be met before December 1st, the mainnet will not be launched until 7 days after reaching this number of participants.

To follow the potential launch of the Eth 2.0 beacon, you can use the watch mode of the Ethereum wallet to check the balance of the Eth 2.0 deposit contract on an Ethereum blockchain explorer (0x00000000219ab540356cBB839Cbe05303d7705Fa) in real-time.

## Ethereum Developers and Wallets

As the earliest public chain to support smart contracts, Ethereum has the most mature developer ecosystem with

 - Powerful IDE Remix
 
 - Easy-to-use smart contract development language, Solidity and development framework Truffle
 
 - Widely used NFT protocols ERC721, ERC1155
 
 - It is also the main public chain of various popular DeFi protocols.
 
The wallet is a bridge between developers and users. Taking TokenPocket as an example, we will provide developers with login and signature methods compatible with multiple protocols. The built-in web3 and ethereum objects in the Webview of the wallet are compatible with Metamask's web3 login protocol and support WalletConnect scan code and mobile browser operations. At the same time, TokenPocket also provides Mobile SDK for iOS and Android native apps, which can activate the wallet for login authorization, token transfer, and contract operations.



<main class="tp-main">
<!-- TokenPocket -->
<a class="tp-custom" href="https://www.tokenpocket.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TokenPocket.png"/>
    <div class="tp-content">
        <h5>TokenPocket</h5>
        <p>https://www.tokenpocket.pro</p>
    </div>
</a>


<!-- Trust Wallet -->
<a class="tp-custom" href="https://www.trustwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/TrustWallet.png"/>
    <div class="tp-content">
        <h5>Trust Wallet</h5>
        <p>https://www.trustwallet.com</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- Bitpie -->
<a class="tp-custom" href="https://bitpie.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitpie.png"/>
    <div class="tp-content">
        <h5>Bitpie</h5>
        <p>https://bitpie.com</p>
    </div>
</a>


<!-- imToken -->
<a class="tp-custom" href="https://token.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ImToken.png"/>
    <div class="tp-content">
        <h5>imToken</h5>
        <p>https://token.im</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- Huobi -->
<a class="tp-custom" href="https://www.huobiwallet.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/HuobiWallet.png"/>
    <div class="tp-content">
        <h5>Huobi Wallet</h5>
        <p>https://www.huobiwallet.com</p>
    </div>
</a>


<!-- AToken -->
<a class="tp-custom" href="https://www.atoken.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/AToken.png"/>
    <div class="tp-content">
        <h5>AToken</h5>
        <p>https://www.atoken.com</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- BPEAL Wallet -->
<a class="tp-custom" href="https://www.bepal.pro" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BPEALWallet.png"/>
    <div class="tp-content">
        <h5>BPEAL Wallet</h5>
        <p>https://www.bepal.pro</p>
    </div>
</a>


<!-- Starteos -->
<a class="tp-custom" href="https://www.starteos.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Starteos.png"/>
    <div class="tp-content">
        <h5>Starteos</h5>
        <p>https://www.starteos.io</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- BitKeep -->
<a class="tp-custom" href="https://www.bitkeep.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Bitkeep.png"/>
    <div class="tp-content">
        <h5>BitKeep</h5>
        <p>https://www.bitkeep.com</p>
    </div>
</a>


<!-- MEET.ONE -->
<a class="tp-custom" href="https://www.meet.one" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Meetone.png"/>
    <div class="tp-content">
        <h5>MEET.ONE</h5>
        <p>https://www.meet.one</p>
    </div>
</a>
</main>

<!-- 6 -->

<main class="tp-main">
<!-- Tronlink -->
<a class="tp-custom" href="https://www.tronlink.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Tronlink.png"/>
    <div class="tp-content">
        <h5>Tronlink</h5>
        <p>https://www.tronlink.org</p>
    </div>
</a>


<!-- Lynx -->
<a class="tp-custom" href="https://lynxwallet.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Lynx.png"/>
    <div class="tp-content">
        <h5>Lynx</h5>
        <p>https://lynxwallet.io</p>
    </div>
</a>
</main>

<!-- 7 -->

<main class="tp-main">
<!-- Scatter -->
<a class="tp-custom" href="https://get-scatter.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/scatter.png"/>
    <div class="tp-content">
        <h5>Scatter</h5>
        <p>https://get-scatter.com</p>
    </div>
</a>


<!-- MetaMask -->
<a class="tp-custom" href="https://metamask.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MetaMask.png"/>
    <div class="tp-content">
        <h5>MetaMask</h5>
        <p>https://metamask.io</p>
    </div>
</a>
</main>

<!-- 8 -->

<main class="tp-main">
<!-- ENJIN Wallet -->
<a class="tp-custom" href="https://enjin.io/products/wallet" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ENJINWallet.png"/>
    <div class="tp-content">
        <h5>ENJIN Wallet</h5>
        <p>https://enjin.io/products/wallet</p>
    </div>
</a>


<!-- jaxx wallet -->
<a class="tp-custom" href="https://jaxx.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/JaxxWallet.png"/>
    <div class="tp-content">
        <h5>jaxx wallet</h5>
        <p>https://jaxx.io</p>
    </div>
</a>
</main>

<!-- 9 -->
<main class="tp-main">
<!-- 块信 -->
<a class="tp-custom" href="https://chattle.vip/#/" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/dapp/tokenpocket-1576249499924.png" width=50 />
    <div class="tp-content">
        <h5>块信</h5>
        <p>https://chattle.vip</p>
    </div>
</a>


<!-- KCASH -->
<a class="tp-custom" href="https://www.kcash.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/KCASH.png"/>
    <div class="tp-content">
        <h5>KCASH</h5>
        <p>https://www.kcash.com</p>
    </div>
</a>
</main>


<!-- 10 -->
<main class="tp-main">
<!-- Conibase Wallet -->
<a class="tp-custom" href="https://www.coinbase.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ConibaseWallet.png"/>
    <div class="tp-content">
        <h5>Coinbase Wallet</h5>
        <p>https://www.coinbase.com</p>
    </div>
</a>

<!-- KCASH -->
<a class="tp-custom" style="border:none" target="_blank">
    <!-- <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/KCASH.png"/>
    <div class="tp-content">
        <h5>KCASH</h5>
        <p>https://www.kcash.com</p>
    </div> -->
</a>
</main>

## 中心化钱包

<!-- 1 -->

<main class="tp-main">
<!-- 币信 -->
<a class="tp-custom" href="https://bixin.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/bixin.png"/>
    <div class="tp-content">
        <h5>币信</h5>
        <p>https://bixin.com</p>
    </div>
</a>


<!-- Edge -->
<a class="tp-custom" href="https://edge.app" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Edge.png"/>
    <div class="tp-content">
        <h5>Edge</h5>
        <p>https://edge.app</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">


<!-- Uphold -->
<a class="tp-custom" href="https://uphold.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Uphold.png"/>
    <div class="tp-content">
        <h5>Uphold</h5>
        <p>https://uphold.com</p>
    </div>
</a>

<!-- Conibase Wallet -->
<a class="tp-custom" style="border:none">
    <!-- <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ConibaseWallet.png"/>
    <div class="tp-content">
        <h5>Conibase Wallet</h5>
        <p>https://www.coinbase.com</p> -->
    <!-- </div> -->
</a>

</main>

## 硬件钱包

<!-- 1 -->

<main class="tp-main">
<!-- Ledger -->
<a class="tp-custom" href="https://www.ledger.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Ledger.png"/>
    <div class="tp-content">
        <h5>Ledger</h5>
        <p>https://www.ledger.com</p>
    </div>
</a>


<!-- Trezor -->
<a class="tp-custom" href="https://www.trezor.io" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Trezor.png"/>
    <div class="tp-content">
        <h5>Trezor</h5>
        <p>https://www.trezor.io</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- keep key -->
<a class="tp-custom" href="https://shapeshift.io/keepkey" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/keepkey.png"/>
    <div class="tp-content">
        <h5>keep key</h5>
        <p>https://shapeshift.io/keepkey</p>
    </div>
</a>


<!-- 库神(ColdLar） -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神(ColdLar）</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- 比特护盾（BITHD) -->
<a class="tp-custom" href="https://bithd.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BITHD.png"/>
    <div class="tp-content">
        <h5>比特护盾（BITHD)</h5>
        <p>https://bithd.com</p>
    </div>
</a>


<!-- imKey -->
<a class="tp-custom" href="https://imkey.im" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/imKey.png"/>
    <div class="tp-content">
        <h5>imKey</h5>
        <p>https://imkey.im</p>
    </div>
</a>
</main>

<!-- 4 -->

<main class="tp-main">
<!-- Cobo金库 -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo金库</h5>
        <p>https://cobo.com</p>
    </div>
</a>


<!-- BEPAL Pro S -->
<a class="tp-custom" href="https://www.bepal.pro/bepal-q" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/BEPALProS.png"/>
    <div class="tp-content">
        <h5>BEPAL Pro S</h5>
        <p>https://www.bepal.pro/bepal-q</p>
    </div>
</a>
</main>

<!-- 5 -->

<main class="tp-main">
<!-- 华特钱包 -->
<a class="tp-custom" href="https://www.orientwalt.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/orientwalt.png"/>
    <div class="tp-content">
        <h5>华特钱包</h5>
        <p>https://www.orientwalt.com</p>
    </div>
</a>


<!-- SafePal-->
<a class="tp-custom" href="https://safepal.io/" target="_blank">
    <img class="tp-logo" width=50 src="https://tp-statics.tokenpocket.pro/dapp/tokenpocket-1576591843263.png"/>
    <div class="tp-content">
        <h5>SafePal</h5>
        <p>https://safepal.io/</p>
    </div>
</a>
</main>



## 中心化&去中心化

<!-- 1 -->

<main class="tp-main">
<!-- Cobo -->
<a class="tp-custom" href="https://cobo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Cobo.png"/>
    <div class="tp-content">
        <h5>Cobo</h5>
        <p>https://cobo.com</p>
    </div>
</a>


<!-- 库神 -->
<a class="tp-custom" href="https://www.coldlar.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/ColdLar.png"/>
    <div class="tp-content">
        <h5>库神</h5>
        <p>https://www.coldlar.com</p>
    </div>
</a>
</main>

<!-- 2 -->

<main class="tp-main">
<!-- 虎符 -->
<a class="tp-custom" href="https://hoo.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Hoo.png"/>
    <div class="tp-content">
        <h5>虎符</h5>
        <p>https://hoo.com</p>
    </div>
</a>


<!-- RenrenBit -->
<a class="tp-custom" href="https://www.renrenbit.com" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Renrenbit.png"/>
    <div class="tp-content">
        <h5>RenrenBit</h5>
        <p>https://www.renrenbit.com</p>
    </div>
</a>
</main>

<!-- 3 -->

<main class="tp-main">
<!-- HyperPay -->
<a class="tp-custom" href="http://www.hyperpay.tech" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/Hyperpay.png"/>
    <div class="tp-content">
        <h5>HyperPay</h5>
        <p>http://www.hyperpay.tech</p>
    </div>
</a>


<!-- Math Wallet -->
<a class="tp-custom" href="http://www.mathwallet.org" target="_blank">
    <img class="tp-logo" src="https://tp-statics.tokenpocket.pro/logo/MathWallet.png"/>
    <div class="tp-content">
        <h5>Math Wallet</h5>
        <p>http://www.mathwallet.org</p>
    </div>
</a>
</main>

<br /><br />

# 以太坊 钱包知识自测

<br /><br />

# 以太坊钱包常见问题
https://www.yuque.com/tokenpocket/gz8u7f

![QRCode](https://tp-statics.tokenpocket.pro/banner/tokenpocket-20201112161352.png)

<br /><br />

# 以太坊联系方式

Website：https://ethereum.org

Twitter：https://twitter.com/ethereum

Youtube：https://www.youtube.com/channel/UCNOfzGXD_C9YMYmnefmPH0g

GitHub：https://github.com/ethereum

<br /><br />

# 版权申明
《区块链入门必读之以太坊钱包知多少》，又称为以太坊钱包小白书。由 TokenPocket 联合TokenPocket 社区志愿者（TP 侠：阿华、明观、币范儿）共同撰写，详细介绍了当前以太坊钱包与以太坊生态密切结合的实例，是目前市面上最为详细的以太坊数字钱包科普资料。

1.本文版权归TokenPocket所有。

2.在征得作者同意的情况下，作品允许非盈利性引用，需要注明并请注明出处和作者，以尊重作者的劳动成果。

3.出处：https://tp-lab.github.io/BlockchainGuide-ETH/

&nbsp;&nbsp;&nbsp;作者：TokenPocket。

4.未经允许，严禁转载。对非法转载者，TokenPocket和作/译者保留采用法律手段追究的权利。

5.对于本文和本声明以及其修改权、更新权及最终解释权均属TokenPocket。

6.以上声明的解释权归“TokenPocket”所有。




  [1]: https://github.tokenpocket.pro/BlockchainGuideSeries/#/
  [2]: https://cn.etherscan.com/
  [3]: https://tether.to/
  [4]: https://mp.weixin.qq.com/s?__biz=MzUyNDkzNTgwMw==&mid=2247486203&idx=1&sn=434ea663224f794f44d791fd676f0508&chksm=fa24fdefcd5374f92b28177577a505fa17c378521b3e81f70118741dab46e969d938a95a57a8&mpshare=1&scene=1&srcid=1027VMDBQhSTAdWrMgjrSnrv&sharer_sharetime=1603801690561&sharer_shareid=ece12c95b3a68df0132982297a5cb7d4&key=de438a290b06e75a68b510a7efb4db495b80145869833edda461689c73315e8d2336d096c602fb4c99ca24d19fdba85e6c879ba1b16b60d7651fcd12fd5682cc45e70eabe318591819a25252112a659618d69ff8113b8195d8722ea023025e1b46933c85525e1377957a7d2f295821f706bb0971a40379f4e991feab118ba2b4&ascene=1&uin=MTM4MTQxMjQ0MA==&devicetype=Windows%2010%20x64&version=6300002f&lang=zh_CN&exportkey=AaS4By4hmGTQY6NUQDhEqwg=&pass_ticket=Bmm69g%2bCOPf5yJELBplaiObqpwYIgmX2/BwQ2Xi8OCasskAuFSbdnrWhn5TScTGG&wx_header=0
  [5]: https://mp.weixin.qq.com/s?__biz=MzUyNDkzNTgwMw==&mid=2247486278&idx=1&sn=718170149ae5737b58e06822a4ee2ad0&chksm=fa24fc52cd537544924de9d1bfd08565eda23d248190ed501c45a30969b7631fda63585e977a&mpshare=1&scene=1&srcid=1027cIHIcIL7wbCXkq0EoCAt&sharer_sharetime=1603802686041&sharer_shareid=ece12c95b3a68df0132982297a5cb7d4&key=de438a290b06e75a4baddb7d916f0dff24cc41300cf8081dd840ce7cf2d1c76d47ae259740fde95f4541269eb84e1ed75c40cbc3c3295abaf2492ca398f6446ac33b0531d7967ffdf6f3ecd6ffc2332003d74431444d942e6b17b37d462aeeb142ea4de897364a458346451a77f18e3e8388b92f49f60cede18b9e2efb32bc55&ascene=1&uin=MTM4MTQxMjQ0MA==&devicetype=Windows%2010%20x64&version=6300002f&lang=zh_CN&exportkey=AR5WoDo64n5g/0zrejbEGuM=&pass_ticket=Bmm69g%2bCOPf5yJELBplaiObqpwYIgmX2/BwQ2Xi8OCasskAuFSbdnrWhn5TScTGG&wx_header=0
  [6]: https://www.yuque.com/tokenpocket/guzgqx/bii4g3
  [7]: https://www.yuque.com/tokenpocket/guzgqx/kxh3ky
  [8]: https://www.yuque.com/tokenpocket/guzgqx/sldy8d
  [9]: https://www.yuque.com/tokenpocket/guzgqx/pr0ucv
  [10]: https://www.yuque.com/tokenpocket/guzgqx/vedyn2
  [11]: https://www.yuque.com/tokenpocket/guzgqx/na8gxr

</div>
