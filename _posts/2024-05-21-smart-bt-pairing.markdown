---
layout:       post
title:        "Smart/Swift Bluetooth Pairing"
author:       "dabch"
header-style: text
catalog:      true
tags:
    - Bluetooth
---

> 萌新请参考: [用Github免费建立网站](https://www.bilibili.com/video/BV12H4y1N7Q4/)、[markdown常用语法](https://blog.csdn.net/Charmve/article/details/103717763)

### 
- Smart/Swift Bluetooth Pairing 是一种基于传统蓝牙配对的改进方案,旨在提供更简单、更快捷的配对体验。

主要特点包括:
- 快速配对: Smart/Swift Bluetooth Pairing 可以在几秒钟内完成配对过程,无需繁琐的步骤。这是通过使用近场通信(NFC)或其他快速发现机制实现的。
- 无需输入密码: 传统的蓝牙配对通常需要在设备上输入一个密码或PIN码进行身份验证。Smart/Swift Bluetooth Pairing 则无需输入任何密码,通过其他安全机制实现身份验证。
- 自动配对: 在某些情况下,Smart/Swift Bluetooth Pairing 可以自动完成设备之间的配对过程,无需用户任何操作。这通过设备之间的身份验证和密钥协商来实现。

实现Smart/Swift Bluetooth Pairing的关键步骤如下:
- 使用近场通信(NFC)或其他快速发现机制,让两个设备快速检测到对方的存在。
- 启动身份验证过程,通过安全的密钥协商实现双方设备的身份验证。这可以利用设备的唯一标识符或其他安全凭证。
- 建立加密链接,确保后续的数据传输得到保护。
- 完成配对过程,将两个设备的连接信息保存下来,以便后续快速重连。
- 整个过程都是自动完成的,用户无需任何手动操作。这为用户提供了无缝、快捷的蓝牙配对体验。

Google Fast Pairing
- Bluetooth LE
- Algorithms:
- AES-128, SHA-256, ECDH（Elliptic Curve Diffie-Hellman, ECDH是一种基于椭圆曲线密码学的密钥交换协议，用于安全地协商双方之间的共享密钥。它是一种非对称加密算法，可用于在蓝牙设备之间建立安全的通信连接。）
- Device有ECDH私钥

  
>dabch，记录自己的学习。

