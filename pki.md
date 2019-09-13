---
layout: page
title: "Netzwerk Luginbash Public Key Infrastructure"
description: "PKI ran by the Netzwerk Luginbash"
---

Currently, we are running 3 Public Key Infrastrustures. 

* The Netzwerk Luginbash Public Key Infrastructure issues certificates for its cloud services with the public-facing network, sometimes also used by k8s pods. This is the public side of our PKI.
* 人理継続保障機関フィニス・カルデア is a smoke test Root CA that issues weird certificates to test SDKs and libraries. This should not be seen on the internet, even audit sites.
* Finis Chaldea Authority is the in-house CA used by radius and Windows domain. It runs on Windows CA, issues certificates inside the domain network. This can be seen on both internet, and affiliated networks.

We are trying to run the Luginbash Internet Root CA as close as to the Baseline Requirements of the CA/Browser Forum. However, some chapters that requirements are too expansive to comply as a hobbyist CA.



## Luginbash Issuing CA certificates

[Netzwerk Luginbash PKI](https://web.lug.sh/LugCA.crt)

## 	Certification Revocation List

[Luginbash Internet Authority CRL](https://web.lug.sh/pki/lug.crl)

