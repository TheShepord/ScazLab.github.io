---
layout: post
title: How to connect to YaleSecure on Ubuntu 14.04
author: Alessandro Roncone
description: ""
tags: [tutorial,ubuntu]
categories: [wiki]
comments: false
excerpt_separator: <!-- More -->
---

Here are the settings to help you connect to `YaleSecure` on Ubuntu 14.04:

<!-- More -->

 * _Security_: **WPA & WPA2 Enterprise**
 * _Authentication_: **Protected EAP (PEAP)**
 * _Anonymous identity_: **leave blank**
 * _CA Certificate_: **navigate to `/etc/ssl/certs/ and select GlobalSign_Root_CA.pem`**
 * _PEAP version_: **Automatic**
 * _Inner authentication_: **MSCHAPv2**
 * _Username_: `your_netID`
 * _Password_: `your_netID_password`

