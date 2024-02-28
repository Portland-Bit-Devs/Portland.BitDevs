---
date: '2024-02-27'
type: Doc/
title: "27 February 2024 PDX BitDevs"
---

## Announcements

Please join us for our next Socratic Seminar. A special thank you to our host <a href="https://dicksprimalburger.com/" data-no-summary>Primal Burger</a>, for the event space. Please support them by buying their delicious food or a beverage.

If you can't make it to the main event please join us at Lutz Tavern around 9PM **<a href="https://www.lutztavern.com/" data-no-summary>here</a>.**

### Special Thanks | Mentions
- [Rearden](https://twitter.com/reardencode) Speaking on LNHANCE - Feb 27 2024
- Thank you to everyone who shows up each month!

### Rules
- Respect people's privacy
- [Chatham House Rules](https://www.chathamhouse.org/about-us/chatham-house-rule)
- Interaction and asking questions are encouraged!

### Requests
- A guest speaker for March 25 2024
- Artist / Graphic designed to help with branding and web applications.
- A Portland BitDevs project to rally around.

### Giveaway
- [Use Guess the Nonce](https://nonce.portlandbitdevs.com/)
    - [Freedom Foods - Premium Freeze Dried Food](https://freedomfoods.store/)
        - Beef broccoli teriyaki
        - Spaghetti

### Schedule
- **6:30 - 7:00pm:** Arrive, socialize, and grab some food.
- 7:00 - 8:00pm: [@reardencode](https://twitter.com/reardencode) presenting about LNHANCE a covenants proposal for Bitcoin Core.
- **8:00 - 8:30pm:** Join @PortlandHODL for a Socratic Seminar as they delve into the latest updates to Bitcoin & Lightning (so many current events to talk about!)
- **8:30 - 9:00pm:** Overtime discussions about tonights topics or additional user submissions.

## Bitcoin Dev News
- [Coldcard Q1 Production Samples Go Out](https://twitter.com/COLDCARDwallet/status/1755639690357510485)
    - [Firmware released](https://github.com/Coldcard/firmware/pull/332)
    - Beta firmware 0.3 still has bugs that can brick, upgrade to 0.6 if you have one.
- [LNHANCE](https://github.com/bitcoin/bitcoin/pull/29198)
    - OP_CHECKTEMPLATE_VERIFY
    - OP_CHECKSIGFROMSTACK
    - OP_INTERNALKEY
- [27877](https://github.com/bitcoin/bitcoin/pull/27877)
    - Coin grinder selection algorithm will
        - Optimizes to reduce fees in the current TX
        - Assumes fees network fees will go down so the next TX could/will be larger
        - Does this by minimizing inputs.
- [Marathon Slipstream](https://mugglehead.com/marathon-digital-holdings-bypasses-bitcoin-high-transaction-scaling-issues-with-slipstream/)
    - This article sucks but still shows the general sentiment
    - Direct Submissions of TXs
    - Private mempool
- [Bitcoin-dev Mailing List Migration](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-February/022327.html)
    - [New location](https://groups.google.com/g/bitcoindev)
- [Rijndael OP_CAT Covenants](https://twitter.com/rot13maxi/status/1748452535017296069)
    - Uses Liquid
    - [Andrew Poelstra Thesis](https://medium.com/blockstream/cat-and-schnorr-tricks-i-faf1b59bd298)
    - No need for OP_CHECKSIGFROMSTACK

## Tech news
- [Zeus 0.8 Released](https://github.com/ZeusLN/zeus/releases/tag/v0.8.0)
    - OLYMPUS by ZEUS 0-conf channel service
    - Zaplocker self-custodial lightning addresses
    - Taproot Channel Support
- OP_CHECKTEMPLATEVERIFY regains community support
    - [Twitter Post Supporting Covenants](https://twitter.com/reardencode/status/1739059702485709212)
    - [Mailing List - Scaling Lightning with Simple Covenants](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-September/021941.html)i

## Education
- [Programming Bitcoin Part 1. Finite Fields](https://twitter.com/PortlandHODL/status/1746731228122976617)
- [Programming Bitcoin Part 2. Elliptic Curves](https://twitter.com/PortlandHODL/status/1746731228122976617)
