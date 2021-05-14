# AlgorandFAQ

Welcome to the FAQ page for the /r/AlgorandOfficial subreddit.

Note that Algorand has an [official FAQ on their website](https://algorand.foundation/faq) and you are encouraged to check it out.

# Topics

## Algorand - Overview

### What is Algorand?

Algorand is a blockchain-based cryptocurrency platform that aims to be secure, scalable, and decentralized. The Algorand platform supports smart contract functionality and its consensus algorithm is based on a proof-of-stake and Byzantine Agreement protocol.[5][2][6][7][8] Algorand’s native cryptocurrency is called Algo.

From the Wikipedia page [(currently in draft)](https://en.wikipedia.org/wiki/Draft:Algorand).

### What are the benefits and Unique Selling Points of Algorand?

The heart of Algorand, and what makes it stick out, is its deceptively simple consensus mechanism that results in Pure Proof of Stake. This allows it to solve the Blockchain Trilemma of Scaleable, Secure and Decentralized.

- Transactions per Second: ~1k (by end of 2021 -> 46k) 
- Transaction Finality: ~4.5s (by end of 2021 -> ~2.5s)
- Transaction Cost: 1000 microAlgos/0.001 Algos, approximately $0.0015 or 0.15 cents (2021-05-14).
- Guaranteed to never fork!
- Layer 1 Smart Contracts, part of the consensus protocol
- Algorand Standard Assets being first-class citizens (Fungible & Non-Fungible Tokens)
- Carbon Neutrality
- Automatic Staking
 
Algorand is not the absolute fastest blockchain out there, or the cheapest. There are other blockchains that claim to be able to handle higher TPS. But the combination of all of these properties  makes Algorand uniquely suited for a number of applications.

On a more subjective note, the following have also been praised:
- The quality of the developer docs.
- The UI of the official mobile Algorand app.

### Sorry, what? Algorand solves the Trilemma? How?

[Refer to this talk](https://www.youtube.com/watch?v=Lbje18-zxc8) by Silvio Micali at the Algorand Boston Meetup.

### How is Algorand guaranteed to never fork?

The probability of a network fork occurring is a function of a parameter that the team behind Algorand set at its creation. It was decided to set it to have a 1 in 1 000 000 000 000 000 000 (1/10^-18) risk of a fork. Note that the the age of the Universe is estimated at around 4.3 x 10^17 seconds. Thus, the probability of a fork taking place is pretty much non-existent. 

Refer to the [paper](https://www.algorand.com/Algorand_%20A%20secure%20and%20efficient%20distributed%20ledger.pdf) for more information.

### What are the drawbacks of Algorand?

### Where can I view the metrics for the Algorand Mainnet?

View them [here](https://metrics.algorand.org/).

### Who are some noteworthy people associated with Algorand?

- Founder: Silvio Micali. Turing Award Winner (2012), RSA Award Winner (2004) Gödel Prize Winner (1993), ACM Fellow (2017). He is also known for his foundational work in Cryptography, including (but not limtied to) the fields of public-key cryposystems, pseudorandom functions, digital signatures, zero-knowledge proofs (co-inventor), oblivious transfers, and secure multiparty computaton. Currently a professor at MIT.
- Advisor: Shafrira Goldwasser. Turing Award Winner (2012), Gödel Prize Winner (1993), Gödel Prize Winner (2001), RSA Award Winner (1998), ACM Grace Murray Hopper Award Winner (1996), Suffrage Science Award (2016)...
- Advisor: Paul Milgrom. Nobel Prize (2020).

These are just a few examples of the many prominent people associated with Algorand. The explore the list of people more, refer to the following pages: 
- [Algorand Foundation](https://algorand.foundation/about-us/who-we-are) 
- [Algorand Inc.](https://www.algorand.com/about/our-team) 


### Who is Silvio Micali?

Silvio Micali is the founder of Algorand.

He has been on the faculty at MIT, Electrical Engineering and Computer Science Department, since 1983. Silvio’s research interests are cryptography, zero knowledge, pseudorandom generation, secure protocols, and mechanism design and blockchain. In particular, Silvio is the co-inventor of probabilistic encryption, Zero-Knowledge Proofs, Verifiable Random Functions and many of the protocols that are the foundations of modern cryptography. 

[Silvio Micali | The Path to Algorand](https://www.youtube.com/watch?v=QOMpPZZeguQ)
[Silvio Micali's Lecture on Algorand](https://www.youtube.com/watch?v=NykZ-ZSKkxM)
[Silvio Micali: Cryptocurrency, Blockchain, Algorand, Bitcoin & Ethereum | Lex Fridman Podcast #168](https://www.youtube.com/watch?v=zNdhgOk4-fE)



### What is the difference between Algorand (inc) and Algorand the Foundation? 

### What is the tokenomics?

### What is accelerated vesting?

### What is the strategy regarding marketing?

### What is Algorand's environmental impact?

### Where can I talk to other Algonauts?

## Tokens

### What is a token?

### What is an ASA?

### What is a Fungible Token?

### What is a Non-Fungible Token?

### Why should I create tokens on Algorand specifically?

Algorand has a number of advantages:

- Scalability: It can handle thousands of transactions per second.
- Cheap: Transaction fees are low, at 1000 microALGOs (0.001 ALGOs).
- Fast: Transaction finality at around ~4.5 seconds.
- Uniqueness: Guaranteed to not fork.

The last benefit is very important, as tokens - especially Non-Fungible Tokens - should only exist in one place, and with Algorand you can be confident whatever tokens you create will be the only ones in existence.

The first three benefits mean that an organization that wishes to mint thousands, tens of thousands, or even millions of tokens can do so _reliabily_. In fact, the Italian[ SIAE launched over 4 million NFTs](https://www.algorand.com/ecosystem/use-cases/siae) on Algorand representing the creative rights of 100000+ creators it represents. Algorand was able to 

Refer to [this blog post](https://www.algorand.com/resources/blog/role-of-transaction-finality-speed-in-nft-minting/) for more information.

### Why should I care about tokens (FTs and NFTs)?

The first Internet can be described as the Internet of Information - it allows us to reliably share data representing text, audio, video and more in a decentralized web of computers that stretches all over the world. One of the innovations that blockchain technologies give us is that it allows the digital sharing, storing and transacting of value.

Algo, the native currency of Algorand, is the digital equivalent of "money". The fact that we could represent it digitally is a big achievement. But in this world, there are other things of value that you might own: property, vehicles, securities (e.g. stocks), commodities, membership reward points, intellectual property, etc - to name a few. Anything of value can be represented on the blockchain by minting a token of it.

One might ask themselves why you'd want to do that, why not use traditional web and database technologies? There are three main advantages of representing these things on a blockchain like Algorand:

1) Atomic Swaps

An atomic swap is a transaction where a set of coins or tokens are swaped for another set of coins or tokens in one single transaction such that one cannot be transferred without the other also being transferred.

Consider buying a car second hand. There are two transfers that take place: money and ownership. The buy transfers money to the seller, and in return the seller transfers the ownership. The fomrer might involve the use of a bank, and the latter might involve a governmental agency in charge of vehicle registration.

Instead of having to perform two transfers, with as sophisticated blockchain technology like Algorand, this can be done in a _single transaction_, involving only the relevant parties. The buraucracy that comes with relying on a governmental agency can be offloaded almost entirely to the blockchain, and the economic rents extracted by the bank disappears as well.

You might also consider the risk that the seller might take the money and disappear with it, without giving you the rights of the car, or even the car at all. The former happening would not be possible due to the nature of atomic swaps. The risk of the later remains, but at least, in the eyes of the post-Blockchain law the person would be committing grand theft auto.

2) Control

With tokens, there is a distinction between who owns it at any given point in time, and who created it. The person who created it can sell it while at the same time raiting certain rights. Algorand notably has a clawback function, meaning that if specified, any token could be brought back to the owner of the clawback address. E.g., if a user of am membership rewards program broke some kind of code of conduct.

Algorand also offers the freeze function. An asset being frozen means that it cannot be transferred anywhere, so the owner can own it but not send it to anyone else. Consider a music artist minting an NFT of a song they made, representing the rights to it. They sell it off to Record Label A, which starts to collect revenue on it, but the artist could choose to freeze it in the label's account. One day, Record Label A decides to sell it off to Record Label B. With smart contracts, a chain of logic could be set that measn the artist will unfreeze the asset for transfer, but only if they receive some kind of reward for it.

 This way, the artist is able to moneitze the song again and again everytime the rights are sold. For government, if they had minted the NFT representing the registration and ownership of car mentioned in the previous part, they could do the same and thus force citizens to pay a form of "tax" to allow this to happen.



## Developer

### How do I develop on Algorand?

### What are Algorand Smart Contracts?

### How do I run a node?

### Where can I view transactions?

## Wallet

### What is a wallet?

### How do I keep my coins safe?

## Staking

### What does it mean to "stake"?

### Where should I stake my ALGOs?

### What is Governance staking?

## Ecosystem

### Where can I see a list of companies using Algorand?

### Where can I buy Algorand?

### Where do I buy NFTs?

### Is there a tool I can use to create my own token?

### How do I buy USDC?

## Miscelleanous

### Is Algorand in talks with Central Banks?

### What is the connection between Silvio and the SEC?

The current head of the SEC, Gary Gensler, was previously a professor at MIT teaching the course [MIT 15.S12 Blockchain and Money](https://ocw.mit.edu/courses/sloan-school-of-management/15-s12-blockchain-and-money-fall-2018/). Silvio Micali was also at MIT at the same time and Gensler mentions him and Algorand on at least two occassions in the lecture series. Thus, it can be concluded that Gensler is aware of Algorand and its unique selling points.
