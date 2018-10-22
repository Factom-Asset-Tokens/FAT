# Frequently Asked Questions



### What Is a Data-Only Protocol/Standard?

The FAT protocol is what we are calling a data-only protocol. FAT exists and functions as pure
data! In contrast, Ethereum runs smart contract code in parallel across the
network to function and reach consensus. Ethereum is a computational blockchain
and it distributes computation and data across the network.

Our data-only protocols only share the data at the blockchain layer, and defer the
computation to the users of the protocol to filter and validate the data
according to the FAT protocols.

Sharding data storage is a problem that has been successfully solved and
implemented in many production database systems, but sharding computation
remains a very difficult challenge that plagues the scalability of many
blockchains to this day and will for years to come. Building FAT as a data-only protocol allows it to leverage the fact that data storage is easy to shard to create very efficient tokenization.


### Is FAT comparable with Ethereum?

Let's compare an ERC-20 token (Ethereum) and a FAT-0 token functionality:

| Criteria                                 | ERC-20 | FAT-0 |
| ---------------------------------------- | ------ | ----- |
| Decentralized Blockchain                 | Y      | Y     |
| Anyone Can Issue & Trade                 | Y      | Y     |
| Decentralized Trade                      | Y      | Y     |
| Tokens Tradable in Fractions             | Y      | Y     |
| Decentralized Issuance                   | Y      | Y     |
| Decentralized & Trustless Code Execution | Y      | N     |

Now, before we start complaining about the N on that last category,
let's list some killer pros for FAT:

| Criteria                                                     | ERC-20 | FAT-0 |
| ------------------------------------------------------------ | ------ | ----- |
| Fixed Cost of Operation ($0.001 USD per transaction/KB, Forever) | N      | Y     |
| Tokens/contracts can be written in any programming language  | N      | Y     |
| Functions without potential securities issues of the "gas" tokens | N      | Y     |
| Purchase "gas" in Fiat, no exchange/regulation               | N      | Y     |
| Anchors into the oldest and most secure Blockchain: Bitcoin* | N      | Y     |

\* =  It should be noted that while Factom currently anchors into Bitcoin, it is blockchain agnostic and can be made to anchor into virtually any blockchain.



### So, Why _can't_ it do everything Ethereum does?

FAT is a data only protocol, it achieves consensus on the order, timing, and
content of data using the Factom blockchain.

In Ethereum, a tokens behavior is defined by a smart contract's
code which is run across the network and held to its well defined rules by the miners via consensus. No signing with private keys is needed because the behavior can be trusted by everyone in
the network. For example, I can send ether to a contract and get back an ICO token,
guaranteed.

FAT cannot _force_ an issuer to perform an action like the smart contract in
the example. The issuer (or their software) needs to use their private keys to sign coinbase
transactions to issue new tokens in response to events. Since private keys
cannot be published, the issuer must coordinate a token sale with a degree of
trust from participants:

- Set Exchange Rate **=>** Accept Payments/Verify **=>** Send Tokens Back
  - Manually
  - Automatically by running a piece of software

This means to have smart contract like functionality without a computational
consensus layer on FAT, trusted issuing parties must run, frequently or 24/7,
pieces of software to honor client requests for exchanging tokens.  This is
perhaps the biggest caveat of FAT.

At the same time this meshes with how our legal and social systems regulate
behavior in the real world. The publicly viewable, immutable evidence of lack
of action on behalf of a trusted well known issuer is likely admissible in
court. It is most certainly admissible in the court of public opinion and social enforcement.


### So, Why should I use FAT over Ethereum or BTC Colored Coins?

1. They are crazy affordable. ($0.001/KB for FAT vs \$2.86/KB & \$3.83/KB for Ethereum and Bitcoin respectively at the moment). We're
   talking less than 1/1000th the cost of the competition.
2. They are crazy easy to learn. FAT tokens are written in simple JSON and
   you can build on FAT in your choice of programming language. Libraries are available to
facilitate easy contract module development.
3. They are crazy flexible. Add whatever metadata you want to define custom
   programmatic behavior as an issuer. Contracts and custom token behavior can be written in any programming language. FAT standards can be layered and extended to achieve unique tokenization and smart contract functionality.


### How many transactions per second (TPS) can FAT do?

FAT TPS is equal to Factom's TPS. Currently Factom can do around 10 TPS stably,
which is comparable to Ethereum. Factom can be easily sharded to accommodate increasing volume in the future.


### Can I try FAT out without spending real money?

Absolutely. Factom has a thriving and responsive [Testnet](http://www.factom-testnet.com/Introduction) that allows you
to try FAT out at no cost. Additionally, the FAT wallet currently comes hardcoded with the private key to a pre-loaded Entry Credit address to fund issuance and transactions of FAT on the Factom mainnet.


### Who Owns FAT?

You do. FAT is completely open source under Creative Commons 0. FAT's
development and administration is spearheaded by DBGrow Inc., one of the 27
proud Factom Authority Members.



### Meaning of the FAT Protocol

The FAT protocol stands for Factom Asset Token protocol, and is also a play on the concept of blockchains being “fat” protocols compared to other networks which act as “thin” protocols. The idea is that while the internet generated immense value, it was the application layer on top of the internet that captured that value rather than the network layer itself. Blockchain allows the network layer a better mechanism to capture value, and Factom’s two token system is the strongest mechanism in the blockchain space for capturing that value. We thought it fitting to name our tokenization protocol that exists as pure data within the Factom blockchain the FAT protocol, as value of activity in the Factom Asset Token protocol is captured directly as entry credit burn within the Factom blockchain, the best designed fat protocol in existence .

Read more on the concept of FAT protocols: <http://www.usv.com/blog/fat-protocols>   



