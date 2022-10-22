---
layout: default
title: Password Manager
nav_order: 11
has_children: false
has_toc: false
---

# {{page.title}}
[Supporting Research](research#password-managers)

## Criteria

The rest of this guide talks about software, so you might be wondering why we are including a piece of software. The reason is simple, as a programmer you need to be able to securely have access to an arbitrary number of systems provided by your employer. A surprising number of programmers reuse the same couple of passwords for everything. This is a massive security liability. A password manager is therefore a piece of equipment every programmer must have. Some companies provide password managers to you. If this is the case, use that password manager to store automatically generated passwords for all your work systems. You should still have a personal password manager, both to store the password to your work password manager, and to securely navigate the internet for your personal use.

There are two broad criteria for a password manager
- Security: Is it built in a way that is hard to breach? Can someone steal all your passwords? If so, that is an unacceptable password manager.
- Ergonomics: Is it available on all of your devices? Do they have the right web browser extensions, iPhone API integrations, etc so that you can autofill passwords? This is critical because unless it is convenient enough to use for everything, you won't get the benefits of the manager.

## Recommendation

I highly recommend Dashlane, because it is the most secure of the market-leading password managers. They have integrations with all major browsers and platforms for a relatively ergonomic experience. LastPass gets compromised way more often, but is still "pretty safe".

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[Dashlane](https://www.amazon.com/dp/B07YWK2TJH) | $36 per year | [SafetyDetectives](https://www.safetydetectives.com/best-password-managers/dashlane/) |


## Budget Recommendation

The only thing significantly cheaper than a Dashlane subscription is to use an open-source password manager. [KeePass](https://keepass.info/) is a solid one. However, you will need to manually set it up / host it properly, and it likely isn't worth the hassle. Additionally, getting it everywhere you need it will be difficult, and unless you can use it for everything, a password manager does not give proper returns.

Also, unless you plan to host a KeePass server for multiple devices, the Dashlane free plan gives you 1 device.

## 2Factor Setup

2Factor authentication often goes along with a password manager and all the major password managers support it. This section will discuss considerations more generally.

From a security perspective, the following are 2Factor methods from least to most secure. 

- Email / Phone
- App Based
- Hardware Based

You should use the most secure method that you can realistically use without the risk of losing access to your accounts. This is not a trivial consideration. Imagine you lose your hardware device, how do you gain access to your system? In corporate environments, you can talk to your system administrator who can work with you to regain access. For personal accounts, it is very possible to lose access to them forever. 

### Email / Phone
This is the standard method of 2Factor, and it is much better than nothing. When attempting to log in, a code is either emailed or texted to you. If you input it and your password, you get access to the system.

Different email providers may or may not be able to give you access to your email if you forget your password. If you lose your phone, your carrier can authenticate you with ID or other means, and send you a new phone with the same number. This is convenient because someone can help you. This is the least secure method, partially because social engineering hackers may be able to game the system and get access to your 2Factor.

### App Based
A large number of services, especially technical ones, support 2Factor with apps based on the [Time-based one-time password](https://en.wikipedia.org/wiki/Time-based_one-time_password) algorithm. Generally you scan a QR code from the app, input some codes, and then for all future login attempts, you input that same code. Examples of these apps include:
- [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2&hl=en_US&gl=US)
- [Microsoft Mobile Phone Authenticator App](https://www.microsoft.com/en-us/security/mobile-authenticator-app)

If you lose your phone, you can lose access to your accounts. Services such as Gmail offer a way to download recovery codes, however, those need to be stored securely as well.

### Hardware Based
The most secure kind of 2Factor by far is hardware based. Yubico provides the most ergonomic and secure solutions for this purpose. For most people, the YubiKey 5C NFC is the correct purchase. You can plug it into USB-C connectors on laptops / desktops or tap it against your phone. You should buy 2, one as a primary, one as a spare.

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[YubiKey 5C NFC](https://www.yubico.com/product/yubikey-5c-nfc/) | $55 per key | [PCMag](https://www.pcmag.com/reviews/yubico-yubikey-5c-nfc) |

YubiKey has an authenticator app, where the secrets are stored on the YubiKey. One of the killer features of this app is you can back up your credentials onto a spare YubiKey as described at the bottom of [this article](https://support.yubico.com/hc/en-us/articles/360013789259-Using-Your-YubiKey-with-Authenticator-Codes). If you have access to critical systems with no other means of regaining access, you may want to program those credentials into a spare YubiKey and store them in a safety deposit box at a bank. For most people, it will suffice to keep it in a secure location where it won't get lost.

| Next: [Calculating ROI](calculating-roi)|