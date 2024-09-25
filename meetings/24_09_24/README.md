---
date: '2024-08-24'
type: Doc/
title: "23 September 2024 PDX BitDevs"
---

## Announcements

Please join us for our next Socratic Seminar. A special thank you to our host <a href="https://dicksprimalburger.com/" data-no-summary>Primal Burger</a>, for the event space. Please support them by buying their delicious food or a beverage.

If you can't make it to the main event please join us at Lutz Tavern around 9PM **<a href="https://www.lutztavern.com/" data-no-summary>here</a>.**

### Special Thanks | Mentions

- Thank you to everyone who shows up each month!

### Rules

- Respect people's privacy
- [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule)
- Interaction and asking questions are encouraged!

### Requests

- A guest speaker for October 22 2024
- Artist / Graphic designer to help with branding and web applications.
- Continue to improve the Portland BitDevs web experience.

### Schedule

- **6:30pm - 7:00pm:** Arrive, socialize, and grab some food.
- **7:00pm - 7:30pm:** Guest Speaker: Jestopher - BancoLibre Demo
- **7:30pm - 8:30pm:** Primary topics discussion.
- **8:00pm - 9:00pm:** Overtime discussions about tonight's topics or additional user submissions.

## Bitcoin Dev News
- 
- [Bolt12 Added to Bolts Repo](https://github.com/lightning/bolts/blob/master/12-offer-encoding.md)
- [Testnet 4 Consensus Failure](https://github.com/bitcoin/bitcoin/issues/30786)
  - Timewarp mitigation strategy to reduce block forward time from 3200s to 600s.
  - Forked Testnet4.
  - Alerted by NickH from Luxor something was wrong.
  - Added MARA hash an resolved the fork.
- [Mining Pool Similarities](https://b10c.me/observations/12-template-similarity/)
- Floresta [v0.6.0](https://github.com/vinteumorg/Floresta/releases/tag/0.6.0)
	- Expose some unexposed values for jsonrpc: Lets the user select between getting a serialized block or a json
	- Bring our functional tests to life: attempts to build some basis for the Python-based tests
	- Async add new address to electrum: Now, if you subscribe to an address that we don't follow yet, we'll start following it
	- Implement tagged hashes for the leafhashes: This futures-proof the leaf commitment scheme from future modifications of the committed data, and it's now part of the utreexo protocol
	- Connect cli option: This option lets you connect exclusively to one specific node, given its IP address
	- Rework internal node structure: Use our actors model to build optmized nodes for each phase of the startup process
	- Add AssumeValidArg enum and correct verify_script: This adds a new AssumeValidArg to make communicating the desired assume-valid more ergonomic
	- Add batch request for electrum: Now electrum lets users perform multiple requests at once, rather than sending one at the time
	- Add PoW fraud proof: Implement pow fraud proofs for our node and enable it on signet for testing
	- Log to file: Now you can write the logs to a file
	- Add lib.rs: florestad is also a lib now, it can be used on other applications and
	- Download and store filters from the network: Now we can download BIP-158 Compact Block Filters and use them to recover historical transactions without downloading the whole blockchain.
	- Cache headers on ibd: Hold headers in memory and save all-at-once, because the database can optimize some writing operations
	- electrum: new experimental electrum endpoints: This adds some experimental (and not used by any wallet) endpoints to the electrum server blockchain.scriptpubkey
	- Nixify: Add a nix-based build system and some developer tools to floresta
 - [ARC Transaction Performed on Bitcoin Mainnet](https://blog.second.tech/demoing-the-first-ark-transactions-on-bitcoin-mainnet/)
   -[Spec](https://ark-protocol.org/)
 - [Bitcoin Core < 24.0.1 DoS](https://bitcoincore.org/en/2024/09/18/disclose-headers-oom/)

## Bitcoin News

- [Strike adds BOLT12 support](https://strike.me/blog/bolt12-offers/)
  - Bolt12 is overall a 'Better' solution to static payment addresses in lightning
  - No need to setup and maintain a webserver   
- [Fractal Bitcoin - 13EX/s from Bitcoin Mainnet](https://explorer.unisat.io/fractal-mainnet/mining)
  - Shitcoin disguised as L2 uses SHA256D
  - Not merged mined has absorbed 15EX/s
  - [Downward Difficulty](https://mempool.space/)
- [Transactions Lower than 2 sats/vByte were clearing](https://x.com/mononautical/status/1837463728381424097)
- [Merge Mining becoming less popular | STATS](https://x.com/mempoolresearch/status/1837147992287056315)
- [Calculating your Solo Mining Odds](https://solochance.com/)
- [0xB10C Mining Pool Game Theory During Forks](https://x.com/0xB10C/status/1811390920744468502)
- [Blue Wallet v7.0 [1,2] Released](https://github.com/BlueWallet/BlueWallet/releases/tag/v7.0.2)
  - Added total balance to the overview screen
  - Ability to disable phone privacy blur
  - iOS lock screen widgets
  - [BIP47 Address Support](https://medium.com/@ottosch/how-bip47-works-ee641cc14bf3) - Still needs an onchain TXN for payment code.
- [Bitcoin Core 28.0 Release Notes](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/28.0-Release-Notes-Draft)
- [Eric | SuperScalar Proposal](https://delvingbitcoin.org/t/superscalar-laddered-timeout-tree-structured-decker-wattenhofer-factories/1143)
- [Sparrow 2.0 Released](https://github.com/sparrowwallet/sparrow/releases/tag/2.0.0)
  
## Tech News
- [Rust Bitcoin Course Now Free](https://btcdemy.thinkific.com/)
- [Hackers Leak 2.7 Billion Data Records (SSNs, Addresses)](https://www.bleepingcomputer.com/news/security/hackers-leak-27-billion-data-records-with-social-security-numbers/)
- [Caroline Ellison of FTX gets 24 Months](https://x.com/unusual_whales/status/1838670005795459205)
- [Bitcoin Miner Shutting Down Results in 20% Higher Electricity Costs](https://www.nobsbitcoin.com/norway-bitcoin-mining-facility-shutdown-leads-to-20-higher-energy-bills-for-town-residents/)
