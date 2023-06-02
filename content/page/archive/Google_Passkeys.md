---
title: "Google Passkeys"
date: 06/01/2023
author: "Miles Wallace"
description: "Google Passkeys."
tags: ["Google", "passkeys", "phishing-proof", "QR-code", "Bluetooth", "key cryptography", "public key", "private key", "phone", "website", "cloud backups", "usernames", "Windows Hello", "iOS", "Android", "FIDO Alliance",  ]
#font: ""
---
## "Google Passkeys"
#### _06/01/2023_  
____
Google has introduced a new technology called passkeys, which aims to replace passwords for logging into accounts. Passkeys are easier to use than passwords and are designed to be phishing-proof. They work by scanning a QR code using a phone instead of typing a password. Even if a scammer tricks someone into scanning the code, they still won't be able to log in without physical access to the device via Bluetooth.

Passkeys are based on private key cryptography, where each website and account has its own private key. When logging in, the website displays a QR code that poses a question that only the person with the private key can answer. The phone uses the private key stored in its secure element to provide the answer without revealing the private key to the website.

Passkeys require the user's phone to have a lock screen pin or biometric authentication enabled. If the phone is lost, Google and Apple provide cloud backups of passkeys that are encrypted and can be synced to a new device. Passkeys also eliminate the need to remember usernames, as each account has its own passkey associated with it.

Setting up passkeys on a Google account involves going to the security settings and selecting passkeys. For Windows users with Windows Hello, the setup is straightforward. For iOS and Android users, scanning the QR code with the phone's camera initiates the setup process.

Passkeys are currently supported by a limited number of websites, but with Google's implementation, it is expected that more companies will adopt this technology in the future. Passkeys provide an additional layer of security and convenience for users, making them an attractive alternative to traditional passwords. 