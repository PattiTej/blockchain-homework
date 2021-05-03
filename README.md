

# Case Study Proposal: Ripple (payment system and protocol)

## What Is It
Ripple is a cryptocurrency platform that functions as a remittance network, currency exchange and a real-time gross settlement system. It is created by a US-based technology company called Ripple Labs Inc. It allows quick currency conversion in its platform and instant transfer of any currency to anywhere in the world with negligible fees. It boasts that it can process a transaction in 4 seconds. The system is also scalable and able to process more than 1500 transactions per second. The ledger employs a native cryptocurrency known as “XRP”.

 

Ripple uses RippleNet, its own blockchain network, to execute transactions. There are currently around 200 banks and financial institutions that have already joined the network. 

## Why This Matters
The main reason for the creation of RippleNet is to construct a payment network for use between financial institutions. It’s purpose is to provide, if not replace, an alternative to the Society for Worldwide Interbank Financial Telecommunication (“SWIFT”), which can be described as a slow system, because of the number of intermediaries that are involved, costly, and do not provide transparency in real-time.
RippleNet is regarded as “The world’s only enterprise blockchain solution for global payments.” This exhibits one of the major differences between Ripple and conventional cryptocurrencies such as Bitcoin and Ether – that is, most of the  cryptocurrencies are developed either by an informal society of voluntary developers, such as Bitcoin, or by individual hobbyists such as in the case of Dogecoin, or by a nonprofit foundation such as Ethereum and Litecoin. Their blockchains are permissionless blockchains. On the other hand, blockchains in industry applications are usually permissioned such as Hyperledger, where only members of the consortium that is running the blockchain are allowed to read, write, and validate. The Ripple network is something in between a public and private blockchain; a permissioned-on-permissionless blockchain. The Ripple developers claim that: 
“The Ripple network is an open network. No one, including Ripple Labs, can prevent others from using or building on the Ripple protocol as they desire. However, when Ripple Labs provides software, such as the Ripple Trade client, Ripples Labs may impose additional requirements for the use of the software. As such, Ripple Labs will require identification of Ripple Trade account holders.”



Ripple provides an automated blockchain - the Ripple Ledger -  that tracks all accounts, balances and IOUs thereby strengthening trust relationships. Each account defines its so-called trust-lines. These trust-lines exist between institutional accounts and individual accounts. 


## “Currency agnostic” system
Ripple is called a “currency agnostic” system, because it works independent of currency and of its own cryptocurrency XRP as well. Although, XRP itself can still be used for converting between currencies (if account holders can’t do it themselves because they don’t have the required currency), and to prevent spam. 


## Consensus algorithm
Ripple was able to find a more efficient consensus algorithm which enables it to do transaction confirmations in as short as 4 seconds. 
Every client that participates in the network is able to formulate a transaction. These transactions are similar to Bitcoin transactions but the difference is that the Ripple transaction specifies a path for the changing balances. By means of an illustration, if a person’s bank wants to send a money transfer of that person to the bank of another person, , the bank making the money transfer needs to specify by which gateway (other banks, institutions, or individuals) it is connected in the Ripple network to the receiver’s bank. This is what we have called a trust line in the section above.
Once a client formulates a transaction, it will send it to a validator. Validators are a subset of all participating servers in the Ripple network. Those other servers that do not take part in the validation of transactions are known as tracking nodes and they merely track the current status of the ledger. The validator nodes collect the transactions and turn sets of transactions into proposals. Thereafter, the validators send the proposals to fellow validators in the unique node list (UNL). When proposals from other validators are received, they undergo a voting process as follows: those getting more than 50% consensus are sent further along to other validators while in the next round, it is 60%, then 70%, and finally 80%. This process weeds out doubtful or apparently wrong transactions such as instances of double spending. 
## Validator nodes
There is no formal validator onboarding process as this not compatible with Ripple as it is a system with no central authority. Anyone, can run a server in the Ripple network and any server can become a validator. 

## KYC
Ripple Labs is required by law to follow Know-Your-Client (KYC) laws and regulationa since it is a provider of financial services. As such, they require their clients or account holders to provide personal information. These accounts are processed centrally, and Ripple Labs can change and cancel any account at any time. Although at first you are free to join the network, it is not the same as in the case of Bitcoin and Ethereum, to name a few, which are permissionless. 


## What problem is Ripple trying to solve?
What Ripple is trying to address is making bank transactions more efficient and transparent – especially cross-border, inter-currency payments which bring about the following advantages:
•	On the Ripple Ledger, which is the blockchain, intermediaries are only involved electronically, and no actual work is performed. Intermediaries such as correspondent banks have no need to deduct fees from the funds that they are processing. This makes payments much cheaper.
•	Any administrative overhead cost is greatly reduced because of automation and transparence such that there is no need to look up correspondent banks to correctly fill out the form or phone the transaction addressee to find out if the funds had arrived.
•	Cheaper liquidity is available for banks (see xRapid), thereby allowing them to lower their fees for their customers.

It should be noted thought that what is being employed is probabilistic voting protocol which means that 100% certainty about the validity of a transaction is neither realized nor is  the intention of the protocol. However, the probability that validated transactions are actually valid is high enough for practical purposes, at about 98.889%



 Resources
•	https://en.wikipedia.org/wiki/Ripple_(payment_protocol)
•	https://digiforest.io/en/blog/top-7-fintech-blockchain-companies#rec145721059
•	https://www.howtotoken.com/explained/ripple-different-cryptocurrencies-ultimate-guide/#:~:text=The%20important%20difference%20between%20the,is%20defined%20as%20an%20account.




