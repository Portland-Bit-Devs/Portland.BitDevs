---
date: '2025-07-22'
type: Doc/
title: "22nd July 2025 BitDevs"
---

## Announcements

Please join us for our next Socratic Seminar. A special thank you to our host <a href="https://dicksprimalburger.com/" data-no-summary>Primal Burger</a>, for the event space. Please support them by buying their delicious food or a beverage.

If you can't make it to the main event please join us at Lutz Tavern around 9PM **<a href="https://www.lutztavern.com/" data-no-summary>here</a>.**

### Special Thanks | Mentions
- Thank you to everyone who shows up each month!

### Guess the Nonce is Back
After some OPs engineering we can now host a raffle without getting rugged! Prizes this week ... 🎉 🎁 😊

### Rules
- Respect people's privacy
- [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule)
- Interaction and asking questions are encouraged!

### Requests
- A guest speaker for Aug 26 2025
- Artist / Graphic designed to help with branding and web applications
- Revitalize the effort to create our own Portland.BitDevs website

### Schedule
- **6:30pm - 7:00pm:** Arrive, socialize, and grab some food.
- **7:00pm - 8:30pm:** Primary topics discussion.
- **8:00pm - 9:00pm:** Overtime discussions about tonights topics or additional user submissions.

## Bitcoin Dev News
- [Frostsnap Hardware Wallet](https://frostsnap.com/)
  - Sharmir Share Backup
  - Restor Wallet With M/N
  - Based on BDK
  - Early Access (Frostsnap Frontier)
- [Gemini Exchange Adds Taproot Support](https://whentaproot.org/#support)
- [Bitcoin Core Diskfilling Logs Attack Mitigation](https://github.com/bitcoin/bitcoin/pull/32604)
  - 1MB per source maximum
  - After that truncates with ...
- [Cluster Mempool Reorg Support](https://github.com/bitcoin/bitcoin/pull/31553)
  - A bunch of Transctions could be reorged back into the mempool cuasing too large of a cluster
  - Now accounts for this
  - Removes as a DoS vector
- [Descriptor Encoding Compression](https://delvingbitcoin.org/t/a-rust-library-to-encode-descriptors-with-a-30-40-size-reduction/1804)
  - Uses bech32 to reduce the number of Bits needed to represent a descritpor when transmitting thorough a QR Code
- [Taproot Control Block Data Store?](https://x.com/stutxo/status/1947774746030182553)
  - Using the merkle pairs it's possible to encode a payload into the taproot control block
- [Sub 1 sat/vBtye Summer is here](https://x.com/mononautical/status/1947530080475091159)
  - Over 50% of hashrate is now mining sub 1 sat/vByte transactions
- [Mempool.space displays sub 1 sat/vByte Txns](https://x.com/mononautical/status/1946410602177380358)
  - Baha Blast Green Color 

  
