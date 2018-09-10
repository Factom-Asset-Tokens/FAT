![image alt ](assets/octahedron.png) 	-

# Factom Asset Tokens

[![](https://img.shields.io/badge/Token%20Standards-3-brightgreen.svg?style=for-the-badge)](FATIPS.md)

[![Discord](https://img.shields.io/discord/479606362507313152.svg?style=for-the-badge)](https://discord.gg/RpYD47t)

[![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg?style=for-the-badge)](#Copyright & Legal)



Factom Asset Tokens (**FAT**) are a collection of open source, data-only blockchain tokenization standards. FAT Tokens open up affordable, secure crypto tokens to the world.



[TOC]



# What Is FAT?

FAT Tokens are decentralized, [tokenized assets](https://medium.com/coinmonks/asset-tokenization-what-why-and-how-73650c49afe0); Pure and simple.

Anyone can send, receive, and create their own tokens for a low fixed cost. FAT offers the security of Bitcoin and the flexibility of Ethereum, all for 1/100th the price.







# Features





![](https://png.icons8.com/cotton/128/000000/refund-2.png)

## Low, Fixed Cost

Fixed at \$0.002 USD per transaction and $0.03 USD per new token issuance, **FAT has 99% lower transaction and issuance costs than Ethereum Tokens** with [similar features](FAQ#Is FAT comparable with Ethereum?) and speed.







![](https://png.icons8.com/cotton/128/000000/domain.png)

## Universal

FAT standards are data only, and are written in universal formats that most programmers already know, and anyone can learn (JSON). There is no need to learn contract languages or other specialized tools.







![](https://png.icons8.com/cotton/128/000000/puzzle.png)

## Extensible

FAT standards and tokens are composable and extensible by design, and are made to be extended to the limit of creativity. Metadata is embeddable in issuances and transactions for unlimited flexibility. 





![](https://png.icons8.com/cotton/128/000000/filled-flag.png)

## Safe

Sending and issuing FAT tokens does not require buying crypto from exchanges. The tokens used to pay for FAT transactions & issuances, [Entry Credits](https://www.factom.com/devs/tokens/entry-credits), are not securities and are [purchasable online instantly](https://shop.factom.com/).





![](https://png.icons8.com/cotton/128/000000/grand-master-key.png)

## Secure

FAT is built on [Factom](/), a decentralized Blockchain run by 100s of community members and over 40 verified enterprise companies worldwide. Every 10 Minutes Factom's data is recorded into the Bitcoin Blockchain to prove it's existence and secure it forever. 







![](https://png.icons8.com/cotton/128/000000/conference-background-selected.png)

## Thriving Community

Harness one of the most active and qualified blockchain communities in the world since 2014: [The Factom Community](https://discord.gg/hSWrJAf). Factom has been awarded multiple [Department of Homeland Security](https://www.dhs.gov/science-and-technology/news/2018/06/15/news-release-dhs-awards-austin-based-factom-inc-192k) and [Gates Foundation](https://www.gatesfoundation.org/How-We-Work/Quick-Links/Grants-Database/Grants/2016/11/OPP1159449) grants for it's work securing data in law enforcement applications and the developing world.



------







# Token Types

FAT features several types and is always adding more. You can create your own too!:



### **[FAT-0](fatips/0.md)**

A fungible asset token standard.

- Most alike an ERC-20 token (TRON, Golem, Ziliqa):

  - Tradable in fractions of a token


### [**FAT-1**](fatips/1.md)

A non-fungible asset token standard.

- Most alike an ERC-721 token (CryptoKitties)
  - Tradable in whole number token increments
  - Every token is unique, and can have unique properties
  - Tokens have a history of the addresses they've resided at



### **[FAT-13](fatips/13.md) (Work In Progress)**

A fungible, mineable asset token standard.

- Most alike Bitcoin:
  - Parties do proof of work to mine tokens
  - Tradable in fractions of a token







# Getting Started

The easiest way to get started exploring, issuing, accepting, and trading FAT tokens is by using the latest official [FAT Wallet Release](/). The wallet is available as an executable for Windows, Mac, or Linux.

You can also use a [Library or API](#Libraries) to programmatically issue, interact with, and send FAT tokens from your code.



## What Is The FAT Wallet?

The FAT Wallet is a piece of software that keeps track of transactions of your selected FAT tokens and allows you to check token balances and send tokens. It's just like the the Bitcoin and Ethereum wallets you're used to. It features a user friendly interface to allow anyone to receive FAT tokens securely on their personal computer.



## What Types of Tokens Work With The Wallet?

Both FAT-0 and FAT-1 are supported. Future token standards will be implemented as deemed appropriate and beneficial for the community.



## What Do I Need To Receive Tokens?

No more than 1 minute of your time. Simply follow the instructions when the wallet starts up for the first time to create an address you can then share with others. This address generated is a Factom address that can also accept Factoids. You can also import a Factoid address if you have one already.



## What Do I Need to Send tokens?

You'll need to purchase some Entry Credits so you can enter data into the Factom blockchain. The wallet will take care of generating an Entry Credit address you can use to receive Entry Credits.

You can acquire Entry Credits from 3rd party purchasers ([Defacto](https://ec.de-facto.pro/) & [Factom Inc.](https://shop.factom.com/)).

Alternatively, you can acquire Factoids from an exchange and burn them into Entry Credits and avoid the markups of 3rd party services. You'll always get a good deal, since the burn ratio between Factoids to Entry Credits is stabilized to give Entry Credits a constant value of $0.001 USD.

Once your Entry Credit address is funded you can send FAT tokens by burning entry credits. It costs approximately 2 Entry Credits to send a transactions ($0.002 USD).

Pending transactions should show up in the wallet within 30 seconds after successful entry into Factom.

 

## What Do I Need to Issue a New FAT Token?

To issue a new FAT token you'll need a [Factom Digital Identity](https://ec.de-facto.pro/). If you already have one it can be imported into the wallet. Otherwise, you can generate a new identity through the wallet. 

Registering a new identity costs around 30 Entry Credits ($0.03). You'll need to wait up to 10 minutes for the block to complete to view and use your new identity.

Once you're identity is ready, simply fill out the instructions in the token issuance dialog.



## Issuing A FAT Token

Using the wallet you can issue a new tokens for your application or organization's needs. Parameters are flexible to allow FAT tokens to fit your use case. You can define basic properties like Display Name & Symbol, Token Type, and rules like Maximum Token Supply. 

Once you've set your parameters you can add an initial set of recipients to receive the newly created tokens. After issuance, you can sell your tokens using traditional business processes or integrate them into your application's functionality to implement token economies.

<u>*It is important to note that FAT tokens are not smart contracts*</u>. FAT tokens cannot automatically, trustlessly execute code or issue tokens* like Ethereum contracts. However, very similar, if not more flexible functionality can be achieved on behalf the issuer using Contract Modules: Reliable pieces of enterprise code controlled by FAT-0 events and data. Contract Modules can be written in any programming language, unlike Ethereum contracts, and react to events outside the blockchain (Stripe Payments, Webhooks, User events).







# Resources

## Guides

TODO



## Software

- #### [FATWallet](/) - Official FAT wallet currently supporting FAT-0 & FAT-1



## Documentation

- #### [Factom Asset Token Improvement Proposals (FATIPs)](FATIPS.md)

  - Detailed technical definitions of the FAT standards & protocols



## Papers

- #### [DBGrow Factom Tokenization Whitepaper](https://docs.google.com/document/d/1YqLhAWEvhWUf4osLYKcN_1sjIYNxAJ4VtHBZlxwYAq8/edit?usp=sharing) 



## Community & Discussion

- #### [Factom Asset Token Discord](https://discord.gg/RpYD47t)

- #### [Factom Community Discord](https://discord.gg/9msfEM) (#third-party-development), mention FAT :blue_heart:

- #### [Factomize Forum - Tokenization Thread](https://docs.google.com/document/d/1YqLhAWEvhWUf4osLYKcN_1sjIYNxAJ4VtHBZlxwYAq8/edit?usp=sharing)



## Development

- #### [Factom Asset Token Improvement Proposals (FATIPs)](FATIPS.md)

  - Main location for community review and development of FAT standards
  - Token API definitions

  #### 


## API Documentation

TODO



## Libraries

- #### [fat-js](https://png.icons8.com/cotton/64/000000/conference-background-selected.png) - Official NodeJS implementations of FAT-X clients & medium nodes







# Copyright & Legal

This project has no affiliation with Factom Incorporated, the original developer of the Factom blockchain. 

The term "Factom" refers solely to the MIT licensed, open source blockchain technology [Factom](https://github.com/FactomProject/factomd).



Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
