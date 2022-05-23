---
title: "My First Post"
date: 2022-05-22T19:54:08+07:00
draft: true
---

**Hello, apa kabar?**

*Note: my article was originally published on IstroSec blog*

In the second part of our overview we continue with the selection of the most used and most usable malware analysis tools. Moreover, we select the tools which are freely available. This time, we focus on tools for analysis other types of the files instead of the native binaries from the previous blog.


Wireshark
Wireshark is the well known tool for analysis of network traffic and network protocols. It can do a realtime capture and analysis as well as dump the captured traffic for later offline analysis. It supports powerful filters and thanks to the integration of plenty of the dissectors it can understand and parse a wide range of network protocols. Last, but not least, it can decrypt SSL/TLS traffic, if we provide private key associated with the server certificate. This is especially useful in case of malware traffic analysis, when we want to analyze the communication with C&C server - with a SSL proxy we can intercept and decrypt its traffic.