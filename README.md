*Disclaimer: This website compares Bitcoin to a ficticious generic centralised 'cryptocurrency' called "CorporateCash".* 

### Intro

CorporateCash is a centralised database operated by the CorporateCash Group (a collection of companies). As such, those using CorporateCash are fully dependent on these companies to allow them to make payments. It's supply is unpredictable and uncapped and users sacrifice their privacy by using CorporateCash. It is not a 'cryptocurrency', it is a voucher scheme run by a group of corporations. 

Bitcoin is a peer to peer value transfer system operated by anyone who wishes to partake. Individuals using Bitcoin are fully independent, and do not need permission from anyone to make payments. Bitcoin's supply is predictable and limited, and it will soon become the hardest money the world has ever had. It is digital gold, run by the people.

Don't be misled by buzzwords (i.e. 'blockchain' & 'distributed'), CorporateCash is no competitor to Bitcoin.

### Comparison Overview

There are significant fundamental differences between CorporateCash and Bitcoin. Click the feature to read more.

| Feature                                           | CorporateCash                       | Bitcoin                                   |
| -------------------------                         | -------------------         | ------------------                        |
| [Supply](#supply)                                 | Uncapped                    | Capped at 21,000,000                      |
| [New Tokens](#new-tokens)                         | Issued by Companies         | Issued by anyone running mining hardware  | 
| [Transaction Security](#transaction-security)     | Weak (Can be reversed)      | Strong (With 6+ confirmations)            |
| [Rule Enforcement](#rule-enforcement)             | Companies                   | Anyone running their own node             |
| [Privacy](#privacy)                               | Not Private                 | Can be private (like Cash)                |
| [Censorship Resistance](#censorship-resistance)   | Weak (Censored)             | Strong (Uncensorable)                     | 

# Detailed Comparison

### Supply
The supply of bitcoins is set in code and enforced by the bitcoiners using full nodes (see [Rule Enforcement](#rule-enforcement)). 
For these bitcoiners, checking the current bitcoin supply can be done with the command `> bitcoin-cli gettxoutsetinfo`.
Bitcoins are issued at a predictable, decreasing rate, and the last bitcoin will be issued in the year 2140. 

![Bitcoin Supply](Images/Bitcoin_Monetary_Inflation.png)
*[Image Source](http://bashco.github.io/Bitcoin_Monetary_Inflation/)*

Read more about the supply of bitcoins [here](https://en.bitcoin.it/wiki/Controlled_supply). 

### New Tokens
New bitcoins are added to the supply by miners. Anyone can become a bitcoin miner by running free mining software on their computer. Because normal computers are not optimised for mining bitcoin the electricity cost will be far greater than the value of the bitcoin mined. To be more profitable you can buy hardware from one of a growing number of companies who make special computers designed just to mine bitcoin.

### Transaction Security
The more confirmations a bitcoin transaction has, the less likely the transaction could be reversed. Once a transaction has 6 confirmations (~1 hour after the first confirmation) it is very secure. 

### Rule Enforcement
Anyone can run a bitcoin full node which verifies the validity of the current state of the bitcoin network (the UTXO set) and rejects attempts to make invalid transactions (for example a transaction that generates 1000 bitcoin out of nowhere). By using their full node to manage their bitcoin they can use bitcoin without having to trust anyone. For example, to know their bitcoin balance they can check the balance of their addresses using their full node (they don't have to ask some other 3rd party to tell them their balance). 
To run a full node see [this guide](https://bitcoin.org/en/full-node) or the [bitcoin node launcher](https://medium.com/lightning-power-users/windows-macos-lightning-network-284bd5034340).

### Privacy

You don't need to provide any personal information to use Bitcoin. To receive bitcoin you just need to generate a bitcoin address and give it to the person sending you bitcoin. This address isn't linked to your identity, but care needs to be taken to keep it this way. There are tools available to help you keep your bitcoin privacy including [wasabi](https://wasabiwallet.io/), [joinmarket](https://github.com/Joinmarket-Org/joinmarket-clientserver) and [whirlpool](https://github.com/Samourai-Wallet/whirlpool-client). 
The tools to stay private while using bitcoin are becoming increasingly easy to use, and the tools used to break users privacy are becoming increasingly useless by breaking the common [heuristics](https://en.bitcoin.it/wiki/Privacy#Blockchain_attacks_on_privacy). 

### Censorship Resistance

Because you don't need to provide personal information to use Bitcoin, it is not possible to censor individuals using bitcoin (provided they maintain their privacy) because you can't link a user with their coins.  

# FAQ's

### Is CorporateCash an easy way to get Bitcoin?

It is widely believed that CorporateCash Node Operators (the CorporateCash Group) will be able to link transactions with user accounts and that there will be no way to use CorporateCash anonymously. 
If these predictions are correct using CorporateCash to buy bitcoin will have significant privacy implications because the transaction will link the bitcoin you buy to your identity. Bitcoin privacy tools (such as CoinJoin) will help limit this issue somewhat, but it is better to acquire bitcoin without providing your personal information.

### Its it free to send CorporateCash?
It has been reported that CorporateCash can be sent with zero fees. It is not free to send CorporateCash; as with many modern services the cost is likley to be your personal data. It is expected that the reason companies are willing to spend Millions of Dollars to be a part of the CorporateCash Group is to access consumer spending data.
