---
layout: page
title: "Certification Authority"
description: "PKI ran by the Luginbash Network"
---

Currently, we are running 3 Network Authorities. 

* The Luginbash Internet Authority issues certificates for its cloud services with the public-facing network, sometimes also used by k8s pods.
* 人理継続保障機関フィニス・カルデア is a smoke test Root CA that issues weird certificates to test SDKs and libraries.  
* Finis Chaldea Authority is the in-house CA used by radius and Windows domain. It runs on Windows CA, issues certificates inside the domain network.

We are trying to run the Luginbash Internet Root CA as close as to the Baseline Requirements of the CA/Browser Forum. However, some chapters that requirements are too expansive to comply as a hobbyist CA.



## Luginbash Issuing CA certificates

[Luginbash Internet Authority](https://web.lug.sh/LugCA.crt)

## 	Certification Revocation List

[Luginbash Internet Authority CRL](https://web.lug.sh/pki/lug.crl)

