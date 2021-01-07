---
title: "10 Rules to Avoid Losing Bitcoin"
date: 2020-12-04T15:34:30-04:00
classes: wide
excerpt: "Self-custody can make your Bitcoin the safest asset in the world, so long as you follow these rules."
image: "/assets/images/custody.jpg"
---
![custody](/assets/images/custody.jpg)
{: .image-title}

If you use a custodian to store you Bitcoin you have the following risks:

* Your Bitcoin might not be [allocated to you][reserves] if the custodian becomes insolvent.
* Custodial Bitcoin can be [be hacked][hack] or confiscated.
* Insurance might not cover your loss.

Self-custody is the solution, but before you attempt to hold your own Bitcoin you must understand these rules:

**1. Buy a [reputable hardware wallet](/hardware-wallets/).**  Software wallets and paper wallet generators are easier to hack.  If you can't afford a hardware wallet, you can use BlueWallet vault (2-of-3 multsig) and split your key across 3 devices.

**2. Verify your wallet is authentic.**  Buy directly from the manufacturer and check for tampering.  [Roll dice][dice] to generate the seed yourself.

**3. Backup all recovery information in a secure location.**  If your wallet dies or you forget a passphrase make sure you can recover your Bitcoin. Many people use [steel backups][steel].

**4. Provide recovery instructions to your inheritors.**  Write down instructions in a will or [dead-man’s switch][switch] including the location of your seed and passphrase backups.

**5. Practice receiving, sending, and recovery with your wallet.**  Receive and send a small amount of Bitcoin to the wallet.  Wipe your wallet's seed and see if you can restore it.

**6. Always check the address on your hardware wallet when sending or receiving.**  Hackers can [replace addresses][addresses] on your computer with their own, so double-check on your device.

**7. Never enter your seed on a computer or phone.**  An app or website might transmit your seed to a scammer who [steals all your Bitcoin][phish]. Only enter your seed into a hardware wallet.

**8. Only send Bitcoin to people you know are authentic.**  Any deal that seems too good to be true is probably a [scam][scam].  There is no way to undo a transaction.

**9. Double-check you own Bitcoin.**  Don’t trust a website to tell you that you’ve received Bitcoin, double-check on a [block explorer][explorer] using [Tor][tor] or your [own node][node].

**10. Determine the level of privacy you need.**  Owning Bitcoin makes you a target for extortion or theft.  Keep your Bitcoin as private as you can.

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

At first it may seem like a lot to remember, especially if you are new to Bitcoin, but it only takes a few hours to set up a wallet.  After you move Bitcoin into your wallet there is nothing left for you to worry about until you need to move it again.  Your Bitcoin will be safe from bad custodians, hackers, fraudsters, and accidents.

Once you have mastered using your hardware wallet, you can decide whether you want to add multisig to your security.  Multisig adds more complexity,  but protects you against rare events which I recommend if you store a significant amount of your savings.

Over time as hardware and software improves, self-custody will become easier and these practices will change.  One day, Bitcoin self-custody will be as natural as storing money in a bank is for most people today.

[dice]: https://medium.com/cobo-vault/how-to-verify-the-recovery-phrase-created-by-dice-rolling-be86b30810c1
[steel]: https://jlopp.github.io/metal-bitcoin-storage-reviews
[switch]: https://blog.dashlane.com/what-the-hack-dead-mans-switch
[addresses]: https://techcrunch.com/2018/07/03/new-malware-highjacks-your-windows-clipboard-to-change-crypto-addresses
[phish]: https://cointelegraph.com/news/community-donates-07-btc-to-phishing-victim-who-lost-entire-bitcoin-holdings
[scam]: https://news.bitcoin.com/crypto-luminary-impersonation-scammers-on-social-media-raked-in-millions-in-2018
[explorer]: https://www.lopp.net/bitcoin-information/block-explorers.html
[node]: https://bitcoinmagazine.com/articles/buy-or-diy-an-overview-of-7-bitcoin-full-node-products
[tor]: https://www.torproject.org/download/
[hack]: https://selfkey.org/list-of-cryptocurrency-exchange-hacks
[reserves]: https://niccarter.info/proof-of-reserves