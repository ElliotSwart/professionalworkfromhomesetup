---
layout: default
title: Hub / Docking Station
nav_order: 10
has_children: false
has_toc: false
---

# {{page.title}}
> This is a difficult product category. Unlike the others, there is no near-perfect option. Your needs will vary with your computer and what standards it supports. If work supplies you with a docking station to go with your laptop, that will generally be the best option. If you're provisioning a flex space, you'll need to choose a lowest common denominator hub that works with your entire laptop fleet. If you have a desktop, you can skip this section. If you have better recommendations, please submit a pull request.

[Supporting Research](research#dock)
## Criteria

The purpose of a dock is to connect all your displays, peripherals, and ideally wired ethernet, into your laptop. This can end up being aspirational if your laptop does not support the right standard. The Thunderbolt standard is built on top of USB and has particular ways of supporting multiple displays and even PCIe passthrough. It enables plug-and-play behavior, which is exactly what you want from a dock. 

All docks must be compatible with Mac, Windows and Linux. Linux compatibility is important for programming, but it also indicates both the manufacturers' compliance with standards and interest in supporting programmers.

Ideally, a dock would support at least 2 displays, however, in many cases, supporting one display and using a separate port for the second display may be needed.

You should select docks in the following order, but only if your computer supports it:
- Thunderbolt 4
- Thunderbolt 3
- USB 3 / USB-C
- USB 2

These categories and recommendations for them are presented below.

_Note: The fundamental budget recommendation is to get a USB hub (See the USB 3 / USB-C section), and wire your displays in separately. A dock is fundamentally a convenience to save friction when you attach your laptop. That can be a bit annoying, but an extra 20 seconds every time you move your laptop will not significantly degrade productivity._

## Thunderbolt 4
This is the first standard that is a good answer to the problem. It allows 2 4K monitors to be connected, as well as high-speed networking, charging, and all your peripherals. Thunderbolt 4 is the only standard that can be counted on across operating systems. Sadly it was only released in late 2020, and so is only in most computers manufactured 2021-present. If you have it, make sure you buy a dock that supports it.

Some thunderbolt docks don't have displays out, just more thunderbolt 4 ports. In this case, buy two of these cables.

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[USB C to DisplayPort Cable (Thunderbolt 3/4 Compatible)](https://www.amazon.com/Cable-Matters-DisplayPort-USB-C-Supporting/dp/B01J6DT070) | $19 | On Amazon |

The recommendations below are somewhat limited because I stop when I find a dock that works. Google ```Best Thunderbolt 4 dock``` and there are plenty of review sites, such as [this one](https://www.pcworld.com/article/393714/best-thunderbolt-docks-for-a-laptop-pc.html).

### Recommendation

The Dell WD22TB4 is Linux compatible and has 2 DisplayPort outs, as well as ethernet and enough ports to wire your entire setup into it. I like it because it implements the standard, but doesn't try to be too clever. For a dock, I'll take boring reliability over feature-richness any day.

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[Dell WD22TB4](https://www.amazon.com/Dell-WD22TB4-Thunderbolt-Dock-USB/dp/B0B13Y2QVW) | $218 | On Amazon |

The Dell dock is also pretty much the cheapest Thunderbolt 4 dock you can find. You can go far more expensive if you have specific needs.

                                                                                                                                                                                                                                                                 
## Thunderbolt 3
Thunderbolt 3 is well supported on Mac, but has incomplete support on Windows. Just to make it more confusing, some of the Thunderbolt 3 docks advertise themselves as USB-C docks (but then supply a compatibility list). You will need to test your Thunderbolt 3 dock with your computer.

You can generally only connect a single display to a thunderbolt port. This means the most a dock can provide is 1 display, along with power and all peripherals/ethernet. This does free up your other ports for other displays. Here is Apple's page on the [subject](https://support.apple.com/guide/mac-help/connect-an-external-display-mchl7c7ebe08/mac).

You should likely buy another Thunderbolt 3 to DisplayPort cable or adapter:

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[USB C to DisplayPort Cable (Thunderbolt 3/4 Compatible)](https://www.amazon.com/Cable-Matters-DisplayPort-USB-C-Supporting/dp/B01J6DT070) | $19 | On Amazon |

### Recommendation

The Dell WD19TBS is the dock I have for my older MacBook pro. Overall, it does its job well, though only having one display plugged in means that I use a second thunderbolt port for my second display. It also works on Linux.

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[Dell WD19TBS](https://www.amazon.com/Dell-Thunderbolt-Dock-WD19TB-Delivery/dp/B0916F5DTM) | $209 | On Amazon |

### Budget Recommendation

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[Dell WD19TBS](https://www.amazon.com/Dell-Thunderbolt-Dock-WD19TB-Delivery/dp/B0916F5DTM) | $209 | On Amazon |

## Only USB 3 / USB-C

With only USB 3 / USB-C you will need to get more creative. However, laptops without Thunderbolt 3 or better generally ship with both a mini-DisplayPort and an HDMI port. It is also possible to connect a display via USB-C, however, this can be flaky. I have listed some products below that might be helpful, however, cannot give meaningful guidance as to what will work.

|Product| Cost | Reviews |
|:------|:-----|:-----|
|[Plugable USB 3.0 Universal Laptop Docking Station](https://www.amazon.com/dp/B00ECDM78E) | $129 | On Amazon |
|[EZQuest USB-C Multimedia Hub](https://www.amazon.com/dp/B07PBF97M1) | $65 | On Amazon |
|[Yeolibo 9-in-1 USB C Hub](https://www.amazon.com/dp/B09M2T1GR6)| $25 | On Amazon |
|[Amazon Basics Mini-Displayport to Displayport Cable](https://www.amazon.com/dp/B013PWQPFS) | $14 | On Amazon |

## USB 2
At this point, you are limited to hubs for your laptop and mouse. If this is what your laptop supports, it is time to insist on a new laptop.

 <br><br>

| Next: [Password Manager](password-manager)|