---
title: "Building a Bitcoin Cluster"
date: 2020-12-04T15:34:30-04:00
classes: wide
excerpt: "Showcase of how to build a Bitcoin node cluster"
image: "/assets/images/node5.jpg"
---
![custody](/assets/images/node5.jpg)
{: .image-title}

If you are a Bitcoin developer or tinkerer you might want to setup multiple Bitcoin nodes.  Here is how I built a Bitcoin cluster with three nodes:

### 1. Buy the case and ethernet switch ($120):
- [Cloudlet CASE](https://www.amazon.com/gp/product/B07D5NM9ZG) ($70)
- [4-port PoE (Power-over-Ethernet) Switch](https://www.amazon.com/gp/product/B076HZFY3F) ($50)

### 2. For each Bitcoin node buy the following ($190):
- [1TB Internal SSD](https://www.amazon.com/gp/product/B07NNRTTCM) ($90)
- [SATA3 to USB3 Adaptor Cable](https://www.amazon.com/gp/product/B083ZJZGH2) ($10)
- [1ft Ethernet Cable](https://www.amazon.com/gp/product/B06XBYGL2T) ($1)
- [PoE (Power-over-Ethernet) HAT for Raspberry Pi 4](https://www.amazon.com/gp/product/B07WD7HXSQ) ($20)
- [Raspberry Pi 4 (4 GB RAM)](https://www.amazon.com/gp/product/B07WHZW881) ($60)
- [SD Card 8GB+](https://www.amazon.com/gp/product/B083VMGDQC) ($5)
- M3 metric screws + spacers for mounting extra SSDs ($1)

![node1](/assets/images/node1.png)
{: .image-title}

### 3. Assemble each Raspberry Pi and SSD on the case bays
- Flash the SD card with a Bitcoin image ([MyNode](https://mynodebtc.com/download) and [Umbrel](https://github.com/getumbrel/umbrel-os) are popular)
- Insert SD card into Raspberry Pi
- Stick heatsink on Raspberry Pi’s CPU
- Push PoE HAT onto Raspberry Pi pins until fully down
- Screw Raspberry Pi into case bay (see images below)
- Screw SSD into case bay (see images below)

![node2](/assets/images/node2.png)
{: .image-title}

![node1](/assets/images/node3.png)
{: .image-title}

Make sure you get the orientation right when mounting on the bays.

### 4. Connect the bays in the case
- Screw the fan into the case
- Insert the Raspberry Pi and SSD bays into case
- Attach the fan to Raspberry Pi (Black wire -> ground pin, Red wire -> 3v pin)
- Connect the SSD to the Raspberry Pi with the adaptor cable
- Connect Raspberry Pi to the ethernet switch’s PoE slot

![node1](/assets/images/node6.jpg)
{: .image-title}

After you plug the ethernet cable in, the switch will automatically power on the Raspberry Pi.  The switch needs to be plugged in and connected to your home router/modem (using port #5 on the switch).

![node1](/assets/images/node7.jpg)
{: .image-title}

The Bitcoin cluster also makes a good cypherpunk night light.