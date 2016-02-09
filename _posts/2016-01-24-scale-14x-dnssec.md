---
layout: post
title: "SCaLE 14x - DNSSEC"
# date: 2015-11-15 16:25:06 -0700
comments: false
tags: presentation
description: "Carlos' presentation on DNSSEC: Solving A Decades-Old Vulnerability"
toc: false
---
## Abstract

Carlos' [DNSSEC](https://www.socallinuxexpo.org/scale/14x/presentations/dnssec) talk at [SCaLE](https://www.socallinuxexpo.org/). January 24, 2016 @ 11:30AM in RM103

DNS (Domain Name System) is an integral part of the Internet, unfortunately it is insecure. DNSSEC is a major upgrade to the security of the Internet. It provides us with authentication of DNS data, data integrity, and authenticated denial of existence. “DNSSec is an absolute requirement if we want to . . . use the Internet for anything non-trivial,” Cricket Liu. I will give an overview of how DNS works and why it is vulnerable, then how DNSSEC addresses these issues. I will discuss the challenges of DNSSEC deployment, but also the additional possibilities it provides, such as DANE.

## Presentation

<iframe width="560" height="315" src="https://www.youtube.com/embed/99NLF2cfLvo" frameborder="0" allowfullscreen></iframe>


- [Google Presentation](https://docs.google.com/presentation/d/1KBHVeMywWarpe29X_gFqST_kCrWQDDfAbqfv5r_V6WI/edit?usp=sharing)
- SlideShare - comming soon

## Resources
The following links assisted me with understanding some of the finer detials of DNSSEC and with articulating concepts.

- Mike Lucas - DNSSEC in 50 Minutes
  - [part 1](https://www.youtube.com/watch?v=lY6HgZmAfqc)
  - [part 2](https://www.youtube.com/watch?v=Hm93GhenqXo)
- [Men & Mice - DNSSEC best practices](https://www.menandmice.com/resources/educational-resources/webinars/dnssec-best-practices-webinar/)
- [ISC BIND DNSSEC Guide](http://users.isc.org/~jreed/dnssec-guide/dnssec-guide.html)
- [SIDN DNSSEC Course](http://www.dnsseccursus.nl/)
- [RIPE NCC - DNSSEC Training Slides](https://www.ripe.net/support/training/material/dnssec-training-course/DNSSEC-Slides-Single.pdf)
- [Internet Society](http://www.internetsociety.org/deploy360/dnssec/)
- [Verisign Labs with DANE](http://www.verisign.com/en_US/innovation/verisign-labs/dane-protocol/index.xhtml)
- [An Illustrated Guide to the Kaminsky DNS Vulnerability](http://unixwiz.net/techtips/iguide-kaminsky-dns-vuln.html)

###References

- [Domain Name System (DNS) Parameters](http://www.iana.org/assignments/dns-parameters/dns-parameters.xhtml)
- [DNS Glossary](http://www.menandmice.com/support-training/support-center/knowledgehub/dns-glossary/)
- [DNSSEC RFCs](https://www.icann.org/resources/pages/standards-2012-02-25-en)
