---
layout: default
title: Reliable Internet
nav_order: 2
has_children: true
has_toc: false
---
# {{page.title}}
[Supporting Research](../research#reliable-internet)

Internet access is what makes remote work possible. Still, it's easy to take the internet for granted when selecting a provider and hardware. This leads to unreliable internet access that can cause many issues:
- Unavailable (or effectively unavailable) internet makes it so you can't show up for work. While you might be able to do some offline coding, chances are your productivity will be massively reduced. In the case of a time-critical issue or meeting, this can be massively disruptive.
- Bad upload speeds can make you appear pixelated over video chat and fill your audio with artifacts. This makes it much harder to communicate effectively and get your points across. Additionally, it can vastly increase testing time whenever you need to upload an artifact; for example, uploading a Docker image to test a cloud system.
- Bad download speed can make it harder for you to hear and see your coworkers. It can also make it time-consuming to download the latest Docker image or do large Git pulls, adding friction.
- Unreliable or intermittent internet adds friction to everything. One particularly striking example is remote computer access, for which reliability is more important than speed. Remote Desktop Protocol only needs [10Mbps](https://learn.microsoft.com/en-us/azure/virtual-desktop/rdp-bandwidth). For SSH, 128Kbps is more than enough. However, unreliable access to remote computers can cause you to make mistakes, like running the wrong shell command or dragging and dropping a file incorrectly. At best, using a remote computer with network lag is a frustrating experience.

To make the internet more reliable, you'll need to set up more reliable service and remove points of failure.

_Note: We're starting with the hardest section first because it is so critical and also has the longest lead times (setting up appointments, etc). But don't worry, you've got this, and everything after is easier._

<br><br>

| Next: [Reliable Service](service)|