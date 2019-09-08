---
layout: page
title: "Certification Authority"
description: "PKI ran by the Luginbash Network"
---

Currently we are running 3 Network Authorities. 

* The Luginbash Internet Authority issues certificates for its cloud services with public facing network, sometimes also used by k8s pods.
* 人理継続保障機関フィニス・カルデア is an smoke test Root CA that issues weird certificates to test SDKs and libraries.  
* Finis Chaldea Authority is the in-house CA used by radius and Windows domain, it runs on Windows CA, issues certificates inside the domain network.

The Luginbash Internet Root CA is the one CA we are trying to follow a subset of the Baseline Requirements of the CA/Browser Forum, the exclusion criteria is financial stress and personnel number requirements.



## Luginbash Issuing CA certificates

[Luginbash Internet Authority](https://web.lug.sh/LugCA.crt)

## 	Certification Revocation List

[Luginbash Internet Authority CRL](https://web.lug.sh/pki/lug.crl)

