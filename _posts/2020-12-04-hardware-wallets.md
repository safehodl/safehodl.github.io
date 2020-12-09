---
title: "Bitcoin Hardware Wallets 2020 Review"
date: 2020-12-04T15:34:30-04:00
classes: wide
excerpt: "When it comes choosing a hardware wallet you should focus on security first."
image: "/assets/images/wallet.jfif"
---
![wallet](/assets/images/wallet.jfif)
{: .image-title}

Most wallet reviews focus on popularity or number of alt coins supported.  However when it comes to self-custodying significant savings, you should focus on security first.

As of December 2020, I recommend the [Coldcard](#cc) for the best security and reputation if you are an experienced Bitcoiner or can spend time learning.

I recommend the [Cobo Vault with Bitcoin-only firmware](#cobo) if you want a much easier-to-use touchscreen at nearly the same level of security.

These are the only two wallets to feature [air-gaps][air] so they don’t need to be plugged into a malware-infected computer.  They also let you generate your seed using [dice rolls][dice] (which I recommend) so you don’t have to trust their seed generation.  Finally they both have great multisig support if you decide to go down that route.

Continue reading for a detailed review of well-known Bitcoin wallets.  Let’s start with the features each wallet has to offer:

|                                     | [Cobo Vault](#cobo) | [Coldcard](#cc) | [BitBox](#bb) | [Trezor](#trezor) | [Ledger](#ledger) | [Specter](#specter) | [Passport](#passport)
| ----------------------------------- |                     |                 |               |                   |                   |                     |
| **Overall Rating**                  | 4/5                 | 4/5             | 3/5           | 2/5               | 2/5               | Unreleased          | Unreleased
| Verifiable Seed Generation          | X                   | X               |               |                   |                   | X                   | X
| Air-gap (USB not required)          | X                   | X               |               |                   |                   | X                   | X
| Device validation (evil MAID-proof) |                     | X               |               |                   |                   |                     |
| Tamper detection                    | X                   | X               |               |                   |                   |                     |
| Secure element                      | X                   | X               | X             |                   | X                 | X                   | X
| Self-destruct PIN                   |                     | X               |               |                   |                   |                     |
| Multisig co-signer storage          | X                   | X               | X             |                   |                   | X                   | X
| Multisig receive address display    | X                   |                 | X             |                   |                   | X                   |
| Touch-screen UI                     | X                   |                 |               | X                 |                   | X                   |
| Open-source firmware                | X                   | X               | X             | X                 |                   | X                   | X
| Open-source design                  |                     | X               | X             | X                 |                   | X                   | X
| Encrypted seed backup               |                     | X               | X             |                   |                   |                     |
| Electrum integration                |                     | X               | X             | X                 | X                 |                     |
| Specter integration                 | X                   | X               | X             | X                 | X                 | X                   |
{: .table-style}

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### Coldcard - Best For Experienced Bitcoiners
{: #cc }
![coldcard](/assets/images/coldcard.png)
{: .image-inline}
[Website](https://coldcardwallet.com/)  [Interview](https://www.youtube.com/watch?v=nhg8_UK0H4k)

If you want the most security features and you are tech-savvy then Coldcard is for you.  The Coldcard has the best reputation among the Bitcoin community thanks to the Coinkite team pioneering advancements in hardware wallet security.  Just be prepared for a steep learning curve and for a user interface that can be frustrating, at least until you master the numeric pad navigation.

**Pros:**
- Extra security features such as a clear case, device validation, and a self-destruct PIN
- Smallest attack surface thanks to the SD card air-gap and simple design
- Reputable team that has pioneered Bitcoin hardware wallet security standards
- Supports dice rolls for verifiable seed generation
- Good multisig support

**Cons:**
- Takes a long time to learn how to use and navigate the menu system
- Needs a computer with a SD card reader and third-party wallet software
- Numeric pad and small screen makes user input frustratingly slow sometimes
- Multisig doesn’t support viewing receive addresses (checks change addresses though)

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### Cobo Vault - Best For Beginners
{: #cobo }
![cobo](/assets/images/cobo.png)
{: .image-inline}
[Website](https://cobo.com/hardware-wallet/downloads?toBtc=true)  [Interview](https://www.youtube.com/watch?v=ecrI6Gx6FA4)

CoboVault shares most of the important security features with Coldcard, but is more user-friendly.  The large Android-based touch screen feels similar to a mobile phone while providing a secure QR-code air-gap.  Despite being lesser-known, the team has taken a lot of user-feedback to make an excellent device I’d recommend to anyone new to Bitcoin self-custody.

**Pros:**
- Best UX for entering seed words and passphrases thanks to the large touchscreen
- QR codes and battery pack make a great air-gapped device
- QR codes work with mobile wallets like BlueWallet which may be easier for novices
- Excellent multisig support, displays multisig receive addresses
- Has a self-destruct mechanism if it detects disassembly
- Supports dice rolls for verifiable seed generation with the Bitcoin-only firmware

**Cons:**
- Relatively newer wallet released April 2020 has less in-the-wild testing
- QR codes can get too big to scan especially for multisig using a computer webcam
- The Android-based OS is an attack surface, though the air-gap makes it unlikely

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### BitBox02 - Best USB Connected Wallet
{: #bb }
![bitbox](/assets/images/bitbox.png)
{: .image-inline}
[Website](https://shiftcrypto.ch/bitbox02/)  [Interview](https://www.youtube.com/watch?v=Z-iXq9R3DYw)

If you want to connect your hardware wallet directly to a computer via USB then BitBox02 is a good option, although possibly less secure than an air-gap.  The multisig support makes it a nice addition to a multisig setup.

**Pros:**
- Multisig stores and verifies co-signers, can check multisig receive addresses
- Deterministic firmware builds in case you want to verify the firmware image

**Cons:**
- Small screen doesn’t display the entire address at once
- Requires BitBox App to set up
- No air-gap, no verifiable seed generation

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### Trezor Model T - Some Security Flaws
{: #trezor }
![trezor](/assets/images/trezor.jpeg)
{: .image-inline}
[Website](https://shop.trezor.io/product/trezor-model-t)  [Interview](https://www.youtube.com/watch?v=tThPxvXY6a8)

The Trezor Model T was a touchscreen upgrade to one of the oldest and most popular hardware wallets.  However, the Trezor has some security flaws that make it hard to recommend, especially the lack of a secure element.  Although the Trezor was one of the first wallets to introduce a touch screen, the Cobo Vault provides a bigger touch screen.

**Pros:**
- Oldest, completely open-source wallet helped pioneer the hardware wallet industry
- Small touch screen provides good UX

**Cons:**
- Lack of secure element means someone with physical access to your device can extract your seed (so you’ll need a strong passphrase)
- No air-gap, no verifiable seed generation, multisig doesn’t store co-signers pubkeys
- Have to connect to Trezor’s less secure web wallet software or use a command-line tool

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### Ledger Nano X - A Useability Challenge
{: #ledger }
![ledger](/assets/images/ledger.jpg)
{: .image-inline}
[Website](https://shop.ledger.com/products/ledger-nano-x)

The Ledger takes a USB form factor with a tiny screen and only a couple buttons.  Inputting anything on the Ledger’s two buttons is painfully slow.  For a much steeper price you could get a touchscreen with the Ledger Blue.

**Pros:**
- Has been an industry leader for a long time
- Has a secure element like most other wallets
- Fits in your pocket easily?

**Cons:**
- Tedious to enter any seed words, passphrase, or PIN on the device
- Closed source firmware
- No air-gap, no verifiable seed generation, poor multisig support

### Upcoming 2021: Specter-DIY - A Promising Do-It-Yourself Wallet
{: #specter }
![specter](/assets/images/specter.jpg)
{: .image-inline}
[Website](https://specter.solutions/shop/specter-shield/)  [Interview](https://www.youtube.com/watch?v=pIpMxhlzsno)

The Specter team released one of the best multisig software wallets this year.  They are now prototyping a do-it-yourself hardware wallet.  It’s a QR-based touch-screen device like the Cobo Vault and will of course have multisig integration with Specter.  It was just released at the end of this year, so consider it experimental as bugs get worked out next year.

**Pros:**
- Large touch screen
- Can built by users with off-the-shelf parts to customize or avoid supply chain risk
- Has a QR-code air-gap with a dedicated QR reader (hopefully easier to scan with)
- Allows entropy generation with dice, picking seed words, and coin flipping

**Cons:**
- Still very early, creators recommend only using with small amounts or in a multisig

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### Upcoming 2021: Foundation Passport - A ColdCard Competitor?
{: #passport }
![passport](/assets/images/passport.jpg)
{: .image-inline}
[Website](https://foundationdevices.com/)  [Interview](https://www.youtube.com/watch?v=DFLte6GbCys)

The Passport will be released in March 2021 and takes the design of the ColdCard and throws on more buttons and a bigger screen with a QR-code air-gap like the Cobo Vault.  The ColdCard team has hinted they are working on a newer model in response.

**Pros:**
- QR-code air-gap
- Will support many of the Coldcard features such as entropy generation

**Cons:**
- Derivative of the Coldcard so might not add much code diversity in a multisig
- Has yet to be released, will take time to be tested in the wild

.   .   .
{: style="color:gray; font-size: 150%; text-align: center;"}

### Future of Hardware Wallets (2021 and beyond)
Over the last couple years while most of us have been watching advancements in Bitcoin protocols such as Taproot and Lightning, hardware wallets have also been advancing at a fast pace.

The future of hardware wallets seems to be towards QR-code air-gaps.  Standards are being developed for animated QR codes to make them viable for multisig.  The upcoming Foundation Passport, Specter DIY, and new Coldcards are supporting QR-codes.  As hardware wallets move to bigger screens I suspect many of them will add touchscreen controls as well.

New wallets are supporting verifiable user-generated seeds from dice rolls.  Standards around user-generated seeds could allow users to verify their seed and address generation using multiple hardware wallets.

Multisig support has been improving.  I expect future wallets to store co-signer pubkeys and display multisig receive addresses.  Perhaps by the end of 2021 the best multisig practice will be using 3 different hardware devices paired with a mobile phone using QR codes, none of them ever plugged into a computer.

[air]: https://en.wikipedia.org/wiki/Air_gap_(networking)
[dice]: https://medium.com/cobo-vault/how-to-verify-the-recovery-phrase-created-by-dice-rolling-be86b30810c1