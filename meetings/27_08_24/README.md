---
date: '2024-08-24'
type: Doc/
title: "27 August 2024 PDX BitDevs"
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

- A guest speaker for September 28 2024
- Artist / Graphic designer to help with branding and web applications.
- Continue to improve the Portland BitDevs web experience.

### Schedule

- **6:30pm - 7:00pm:** Arrive, socialize, and grab some food.
- **7:00pm - 8:30pm:** Primary topics discussion.
- **8:00pm - 9:00pm:** Overtime discussions about tonight's topics or additional user submissions.

## Bitcoin Dev News

- [Intel SGX Compromised](https://x.com/_markel___/status/1828112469010596347)
  - Not completely comprimised but master private key and sealing key both comprimised
  - Path forward to completely comprimising the SGX
  - SGX is no longer offered in desktop class processors, only Xeons
  - Used in cloud environments to hide information
  - Currently arm Secure Enclave ramins superior
- [Testnet 4 PR Merged](https://bitcoincore.reviews/29775)
  - Attempt was made to fix the 20 minute blockstoms / timewarp - [here](https://github.com/bitcoin/bitcoin/blob/3714692644f45808a6480525abc36870aeee1de4/src/pow.cpp#L32)
  - Most fixes were to fix the issues with blockstroms / timewarp - [here](https://blog.lopp.net/griefing-bitcoin-testnet/)
- [5G Base Station Exploit](https://techcrunch.com/2024/08/07/hackers-could-spy-on-cellphone-users-by-abusing-5g-baseband-flaws-researchers-say/)
  - Defcon Deauth attacks to force a 4g connection, then your phone upgrages back to the comprimised basestation.
- [AMD Sinkclose Flaw](https://www.wired.com/story/amd-chip-sinkclose-flaw/)
- Mempool [v3.0.0](https://github.com/mempool/mempool/releases/tag/v3.0.0)
  - Add Mempool Accelerator™ to accelerate TX from your own instance
  - Add Mempool Googles™ new mempool and blockchain analytics tool
  - Add RBF Timeline visualizations including support for FullRBF
  - Add CPFP and Effective Fee calculations in block visualizations
  - Add Liquid Network audit tool to verify holdings vs liabilities
  - Add new Wallet Balance widget for embedding into external sites
  - Add customizable CSS themes including a new high-contrast mode
  - Add optional support for FreecurrencyAPI fiat currencies
  - Add optional Redis support for faster in-memory database
  - Add support for legacy P2PK addresses and outputs
  - Add new block fees graph at /graphs/mining/block-fees
  - Add new fiat calculator at /tools/calculator
  - Re-design transaction page with new mobile "pizza tracker" UI
  - Re-design address page with new balance history over time
  - Improve Block Audit for accelerated transaction out-of-band fees
  - Improve Websocket API to support tracking multiple addresses
  - Improve search box now supports searching multiple networks
  - Improve TV View to add new circular clock face view
- ['Dark Skippy' Attack](https://cointelegraph.com/learn/dark-skippy-attack-how-to-protect-against-it)
  - [Demo](https://darkskippy.com/)
  - [Pollards Rho (kangaroo)](https://en.wikipedia.org/wiki/Pollard%27s_rho_algorithm)
  - [Visual of the power of Pollards Rho for breaking DLP](https://privatekeys.pw/puzzles/bitcoin-puzzle-tx)
- [Slipstream OP_CAT](https://mempool.space/tx/51bae58fa9d413b86d74da60d5366987dcdeb0586d39b93b2ca22f9e40dc83de?mode=details)
  - Not actually valid
  - OP_SUCCESSx [BIP342](https://github.com/bitcoin/bips/blob/master/bip-0342.mediawiki)
  - Makes scipts unconditionally valid as such anyone can spend.
  - Could cause forks?
  - Retroactive enforcements of rules burden devs.
  - Roles of "Dev Hooks"
  - IRC discussion with GMAXWELL [IRC weblogs](https://bitcoin-irc.chaincode.com/bitcoin-core-dev/2024-08-11)
## Bitcoin News
- [0xB10C Mining Pool Game Theory During Forks](https://x.com/0xB10C/status/1811390920744468502)
- [Blue Wallet v7.0 [1,2] Released](https://github.com/BlueWallet/BlueWallet/releases/tag/v7.0.2)
  - Added total balance to the overview screen
  - Ability to disable phone privacy blur
  - iOS lock screen widgets
  - [BIP47 Address Support](https://medium.com/@ottosch/how-bip47-works-ee641cc14bf3) - Still needs an onchain TXN for payment code.
- [Bisq 2.1.0 Released](https://github.com/bisq-network/bisq2/releases/tag/v2.1.0)
  - Support Lightning Network as a settlement method.
  - Better visualizations
- [Bitcoin Core 28.0 Release Notes](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/28.0-Release-Notes-Draft)
- [A better timewarp attack](https://delvingbitcoin.org/t/zawy-s-alternating-timestamp-attack/1062/12)

## Tech News
- [Hackers Leak 2.7 Billion Data Records (SSNs, Addresses)](https://www.bleepingcomputer.com/news/security/hackers-leak-27-billion-data-records-with-social-security-numbers/)
- [Telegram Founder Arrested - France](https://x.com/Zlatti_71/status/1828529272539304278)
- [Jullian Assange Ends Legal Fight](https://apnews.com/article/assange-justice-department-plea-wikileaks-saipan-australia-00eb380879ff636cc9b916f82f82ed40)

## Figures
### Timestamp vs MTP - Mainnet
![image](https://github.com/user-attachments/assets/075a55c8-af89-4430-bbbf-d20db07d8d63)
### Timestamp Vs MTP - Tesntnet
![image](https://github.com/user-attachments/assets/b699d8fe-425f-43fd-87da-facd70c512fb)



