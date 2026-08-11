---
title: "Shadowrocket Basic Settings: A Visual Guide"
description: "A visual walkthrough of the Shadowrocket home screen, interface language switch, and global routing settings."
keywords: ["Shadowrocket", "settings guide", "global routing"]
weight: 1
---

[Shadowrocket's interface has quite a few elements](https://shadowrocket.ink), and it's easy to feel unsure about what
each button does the first time you open it. This guide walks through the settings in order —
"Home screen → Interface language → Global routing" — explaining the main options one by one.

## 1. Getting to Know the Home Screen

When you first open the app, you land on the home screen:

![Shadowrocket home screen overview](https://shadowrocket.ink/img/shadowrocket-shezhi-1001.jpg)

From top to bottom, the home screen is made up of a few main areas:

- **The switch on the right**: This is the master switch, used to turn the proxy connection
  on or off. Its current state is "Not Connected."
- **Global routing**: Tapping this lets you choose how traffic is forwarded (covered in
  detail below). The text next to it shows the currently selected mode, and you generally
  don't need to change it often.
- **Connectivity test**: Tapping this checks whether your current configuration can reach
  the internet properly, making it easy to tell whether the configuration itself has a problem.
- **The list area**: This shows the configuration entries you've added, grouped together.
  Tap an entry to see its details, or tap a group header to expand or collapse it.
- **The bottom navigation bar**: Contains four entries — "Home," "Config," "Data," and
  "Settings." "Settings" is the button we'll use in the next step.

If you'd rather use the app in Chinese, follow the steps below to switch the interface
language to Simplified Chinese.

## 2. Switching the Interface Language to Chinese

Tap the "Settings" icon in the bottom-right corner of the home screen to open the settings page:

![Shadowrocket settings page language option](https://shadowrocket.ink/img/shadowrocket-shezhi-1002.jpg)

The "Language" option sits at the very top of the settings page. Tap it and choose
"简体中文" (Simplified Chinese), and the app's interface text will switch to Chinese,
making it easier to follow along with the rest of the settings.

Further down this page, you'll also find a few commonly used categories:

- **Advanced**: Contains more advanced options such as latency testing methods, the
  Today widget, on-demand connection, diagnostics, and colors. It's fine to leave these
  at their defaults when you're just getting started.
- **TUNNEL**: Contains lower-level parameters related to the proxy, TCP, and UDP.
  These usually don't need to be changed manually either.

## 3. Understanding the Global Routing Modes

Once the language is set, go back to the home screen and tap "Global routing" to see the
specific routing options:

![Shadowrocket global routing settings page](https://shadowrocket.ink/img/shadowrocket-shezhi-1003.jpg)

This page mainly includes:

- **Enable Fallback**: Off by default; it's generally fine to leave it that way.
- **Config**: Forwards traffic according to the rules in the configuration file you're
  currently using. This is the most commonly used option and is selected by default.
- **Proxy**: Routes all traffic through the proxy. This is useful when you need to
  temporarily switch to a global forwarding rule.
- **Direct**: Bypasses the proxy entirely and accesses the network directly from the
  device. This is handy when troubleshooting connection issues or checking whether a
  particular app actually needs the proxy.
- **Scenario**: Lets you set different forwarding rules for different usage scenarios
  (for example, different network environments). This suits users who keep multiple
  sets of habitual configurations.

Below that, the "Group" and "Scenario" entries are where you manage and edit the specific
content of these rules.

## Summary

The overall workflow can be summed up as: first check the master switch and current
routing mode on the home screen → switch the interface to Chinese in Settings if needed,
to make it easier to read the various options → and finally, choose the forwarding mode
that fits your situation under Global Routing. Once you're familiar with these three
areas, the rest of the app's settings will be much easier to understand.
