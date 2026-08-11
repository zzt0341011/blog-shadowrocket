---
title: "What's the Difference Between VPN and VPS? What Are Shadowrocket, Clash, V2Ray, and a Router-Based Setup"
description: "A conceptual breakdown of the difference between VPN and VPS, and what terms like Shadowrocket, Clash, V2Ray, and router-based setups actually refer to and when each one applies."
keywords: ["VPN", "VPS", "Shadowrocket", "Clash", "V2Ray", "router-based setup"]
weight: 1
---

When you first run into this space, terms like "VPN," "VPS," "Shadowrocket," "Clash,"
"V2Ray," and "router-based setup" are easy to mix up, but they actually belong to
different layers: some are service types, some are client apps, some are protocols,
and one is a hardware/deployment form. This guide sorts them out in the order of
"clarify the concepts first, then clarify the tools."

## 1. VPN and VPS Are Two Different Things

These two terms look similar, but they don't describe the same kind of thing.

- **VPN (Virtual Private Network)**: describes a "way of connecting." It sets up an
  encrypted tunnel between your device and a target server, routing your network
  traffic through that tunnel. Common uses include securing communication on public
  Wi-Fi, or accessing services as if you were exiting from a different network. A VPN
  itself is a technical approach — it can be provided as a ready-made commercial
  service, or you can build one yourself.

- **VPS (Virtual Private Server)**: describes a "compute resource." Put simply, it's a
  virtual machine you rent in a cloud provider's data center, giving you an independent
  environment where you can install your own OS and configure your own software — a
  completely different layer from a VPN. A VPS can be used to host websites, run
  programs, or deploy all kinds of server-side services; "setting up a VPN service on a
  VPS" is just one of its many possible uses.

In short: **a VPN is a connection technology, a VPS is a server resource**. Once you
have a VPS, you can choose to deploy all sorts of services on it, including a VPN — but
the two terms aren't interchangeable.

## 2. [What Are Shadowrocket](https://shadowrocket.ink), Clash, and V2Ray

These three are often discussed together, but they don't occupy the same position.

- **Shadowrocket**: an iOS client app that forwards network traffic on your phone
  according to the rules you've configured. Its strength is a clean interface and a
  quick learning curve — rules and settings are all configured within the app, making
  it a good fit for everyday users who don't want to fuss over too many parameters.

- **Clash**: strictly speaking, this is an implementation of a "proxy core + rule
  engine." It originally appeared as a command-line/background service, and later grew
  into many graphical clients covering Windows, macOS, Android, and other platforms.
  Its strength is powerful rule configuration — supporting fine-grained routing by
  domain, IP, region, and more — making it a good fit for users who like customizing
  rules and want a consistent experience across platforms.

- **V2Ray**: more precisely, an underlying proxy protocol/framework. It doesn't
  emphasize a graphical interface on its own; many client apps (including some
  mentioned above) support V2Ray-related protocols internally as one of their
  connection methods. You can think of it as the "protocol layer," while apps like
  Shadowrocket and Clash are concrete "application layer" implementations — they don't
  replace each other, they sit at different layers.

A simple analogy: if forwarding network traffic is like shipping a package, V2Ray is
more like the standards and routing protocols that shipping follows, while Shadowrocket
and Clash are like different courier company apps, each with its own interface and
rules for carrying out that process.

## 3. What Is a Router-Based Setup

The tools above are all software installed on a phone or computer. A **router-based
setup** refers to a different deployment form: running router-system software on a
device with enough processing power (either a dedicated small appliance or router
hardware flashed with a specific firmware), so that the "router" itself gains richer
network management capabilities instead of just forwarding signals.

The relationship between a router-based setup and the client-side tools mentioned
earlier can be understood as a difference in "coverage":

- A client on your phone or computer (such as Shadowrocket or the desktop version of
  Clash) only affects the single device it's installed on.
- A router-based setup handles things centrally at the network entry point — every
  device connected to that router at home (phones, computers, tablets, smart home
  devices, and so on) is covered together, without needing to install or configure
  software on each device individually.

So a router-based setup is better suited for scenarios where you "want every device in
the house to follow the same set of rules without configuring each one separately," at
the cost of a higher upfront bar for hardware and system configuration compared to just
installing an app on your phone.

## Summary

Putting these terms side by side makes things clearer:

- **VPN** is a connection technology, **VPS** is a server resource — they aren't the
  same kind of concept.
- **Shadowrocket** and **Clash** are client apps that run on a specific device, while
  **V2Ray** leans toward being an underlying protocol that clients may support as one
  of their implementations.
- A **router-based setup** pushes similar capabilities down to the network entry
  device, enabling unified management for the whole household, as opposed to a
  phone/computer client that only affects a single device.

Once you understand how these layers relate to each other, it becomes much easier to
look at the specific settings screens of any given tool and tell whether an option is
operating at the "connection method" layer or the "resource/deployment" layer.

* The providers below are billed by data. Each site has software usage and installation guides.
* Once you buy data, there's no time limit — it lasts until the data runs out.
* If a site won't load, it has likely been blocked — just switch to another site.

| Name | Price | Data | Nodes |
| :--- | :--- | :--- | :--- |
| [魔戒 (Mojie)](https://1.jnk.ink/L4q20S) | ¥1 | 1G | 30 |
| [网际快车 (Wangji Kuaiche)](https://1.jnk.ink/ad2RVl) | ¥7 | 20G | 54 |
| [牛逼 (Niubi)](https://1.jnk.ink/LYet7x) | ¥14 | 200G | 31 |
| [飞鸟 (Feiniao)](https://1.jnk.ink/i7OhaC) | ¥10 | 200G | 25 |
| [皮卡丘 (Pikachu)](https://1.jnk.ink/d07dCA) | ¥15 | 20G | 40 |
| [happy猫 (Happy Cat)](https://1.jnk.ink/5KiTxY) | ¥20 | 200G | 27 |
| [农夫山泉 (Nongfu Shanquan)](https://1.jnk.ink/i1fXTMYk)  | ¥45   | 200G | 40 |
| [宝贝云 (Baobei Yun)](https://1.jnk.ink/xxPwfy) | ¥55 | 600G | 64 |
| [自由猫 (Ziyou Mao)](https://1.jnk.ink/haO8Dr) | ¥89 | 200G | 71 |
| [飞兔 (Feitu)](https://1.jnk.ink/bbXkiN) | ¥30 | 100G | 80 |
