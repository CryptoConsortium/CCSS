---
layout: post
title: Added PBKDF2 as Described in BIP39
tags: [Key Storage, BIP39]
author: Ryan X. Charles
---

[1.03 Key Storage](/CCSS/Details/#1.03) aspect was expanded to allow for Password-Based Key Derivation as an alternative to storing the key in an encrypted state. With Password-Based Key Derivation, the seed can be stored unencrypted as the password used to derive the key from the seed would accomplish the same as a passworded encryption layer on top of the seed. 

### References
* [http://en.wikipedia.org/wiki/PBKDF2](http://en.wikipedia.org/wiki/PBKDF2)
* [https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki)

### Contributor(s)
* Ryan X. Charles, [BitGo](https://bitgo.com)




