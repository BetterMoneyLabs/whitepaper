Call for Action: Building Peer-to-Peer Economies and Free Banking on Ergo

Since Satoshi's and Hal Finney's early posts and through years of discussions stimulated by Bitcoin experiment and thousands
other attempts to get better money for reworking economies for the better outcomes, some things are now clear. In particular,
the "best" and still realistic monetary system to replace fiat would emerge through competition, not design. There will be some obvious building
blocks though:

* Ergo as a neutral base layer for store-of-value transactions, trustless derivatives and smart reserves.
* Bitcoin as a neutral base digital commodity (would be relevant for some decades to come)
* Private tokens and/or reputation-based systems for niche communities and tight-knit networks
* Tokenized real world assets

Theories aside, in recent months a plan for nice toolset for peer-to-peer networks based economies and free banking has been crystallized:

* merged-mined sidechains, such as Braid, double-merged mined sidechain of both Bitcoin and Ergo, tailored for stablecoins and RWAs issuers and users:

We need for a couple of Rust developers for Ergo merged-mined sidechains, then Bitcoin merged-mined sidechains framework, for starters.

* Git Circles, framework for community currencies for developing communities

Call for contributors has been started for Git Circles! Git Circles is a framework for making community currencies for 
developing communities, based on measurable contributions to git repositories. More info can be found at 
https://github.com/GitCircles/GitCircles-Roadmap/ .

GitCircles would allow for hundreds of thousands of open-source developers along with 

There is need for 1-2 Rust developers to work on git oracle and other offchain code towards the roadmap.


* P2P networks incentivization

There were a lot of attempts to incentivize activities which were mostly done voluntarily before the blockchain in peer-to-peer networks via tokens, mostly failed
due to "bad" tokenomics, but it is impossible to make good tokenomics for uncertain future anyway. We think that money for rewarding activities in peer-to-peer networks,
potentially unbacked where trust or limits for new untrusted peers allow,  should be created along with demand. We have efficient offchain cash constructions based on on-chain reserves for that, such as Basis.

The current plan is to implement Basis-based reward mechanism for Celaut, and then spread it to other p2p networks, making Ergo basis for peer-to-peer economies.

Total market cap of DePIN cryptocurrencies is about $23B (according to Messari's DePIN tracker), and this is just a tip
of an iceberg when we talk about rewarding activities in digital peer-to-peer networks. 

There is need for 1-2 Rust developers to work on offchain part behind Basis, add support for trackers and notes exchange 
(forking current ChainCash Server would work)

* ChainCash based payment network

ChainCash is unique way to create money with elastic supply via trust and blockchain assets in global digital peer-to-peer 
environment, kinda revival of free banking, now with 