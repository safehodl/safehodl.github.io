---
title: "10 Rules for Safe Self-Custody"
date: 2020-12-04T15:34:30-04:00
classes: wide
excerpt: "If you are willing to put in some effort, self-custody can make your Bitcoin the safest asset in the world, so long as you follow these rules."
image: "/assets/images/custody.jpg"
---
![custody](/assets/images/custody.jpg)
{: .image-title}

Bitcoin is the first digital asset that can be stored entirely by yourself.  Self-custody avoids the risk of storing assets with a custodian like an exchange or bank.  When using a custodian you have to ask:

* Can the custodian prove your Bitcoin is [allocated only to you][reserves]?
* How good is the custodian’s [security model][hack]?  Jurisdictional risk?
* Is the custodian insured and what risks does the [insurance policy][insurance] cover?

If you are willing to put in some effort, self-custody can make your Bitcoin the safest asset in the world, so long as you follow these rules:

#### 1. Buy a [reputable hardware wallet](/hardware-wallets/) and learn how to use it.
Hardware wallets are more secure than your phone or computer which can be easily infected with malware.  A wallet generator you get off the internet might be generating seeds that an attacker already knows.  An attacker that knows your seed can take your Bitcoin.

#### 2. Verify your hardware wallet is authentic.
Buy directly from the manufacturer and check for any signs of tampering.  Try to get a wallet that allows you to generate your own seed by [rolling dice][dice] so you don’t have to trust the device’s seed generator.

#### 3. Backup all information to recover your wallet in a separate secure location.
If your hardware wallet dies, you forget your passphrase, or you have a fire in your house make sure you won’t lose access to your Bitcoin.  Store your backup in a location safe from theft or natural disaster.  Many people use [steel backups][steel].

#### 4. Provide recovery instructions to your inheritors.
Write down recovery instructions in a will or [dead-man’s switch][switch] that your inheritors will receive if you suddenly die.  For example, you could include the combination to a safe that contains your seed and passphrase backups.

#### 5. Practice sending, receiving, and backup recovery with your wallet.
Once you have backed up your seed, wipe it from your wallet and see if you can restore it.  Practice receiving and sending a small amount of Bitcoin before moving large amounts into your wallet.

After you setup your wallet, there are a few rules to remember when using it:
{: style="color:gray; text-align: center;"}

#### 6. Always check the address on your hardware wallet when sending or receiving.
Some hackers [replace addresses][addresses] you see on a website with their own.  You must always double-check addresses on your hardware wallet before moving your Bitcoin.

#### 7. Never enter your seed on a computer or phone.
Only ever enter your seed into a hardware wallet.  An app or website that asks for your seed might be transmitting your seed to someone who will [steal all your Bitcoin][phish].

#### 8. Only send Bitcoin to people you trust.
There is no way to undo a transaction and any deal that seems too good to be true is probably a [scam or impersonator][scam].  Treat sending Bitcoin like handing someone cash.

#### 9. Use a source you trust to double-check you’ve received Bitcoin.
Don’t trust a website to tell you that you’ve received Bitcoin, double-check using a [block explorer][explorer] or your [own node][node].  Use the [Tor browser][tor] to visit block explorers if you don’t want your IP address associated with your Bitcoin address.

#### 10. Determine the level of privacy you need.
People who know how much Bitcoin you have may target you for extortion or theft.  Try to keep your Bitcoin as private as you can.

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

I consider these rules to be necessary for safe self-custody.

At first it may seem like a lot to remember, especially if you are new to Bitcoin, but it only takes a few hours to set up a wallet.  After you move Bitcoin into your wallet there is nothing left for you to worry about until you need to move it again.  Your Bitcoin will be safe from bad custodians, hackers, fraudsters, and accidents.

Once you have mastered using your hardware wallet, you can decide whether you want to add multisig to your security.  Multisig adds more complexity, but protects you against rare events--a good idea if you store a significant amount of your savings.

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
[insurance]: https://www.finivi.com/can-you-insure-your-bitcoin
[reserves]: https://niccarter.info/proof-of-reserves