---
title: "Sleeper Agent"
excerpt: "DLL Injection without DLLmain()"
collection: portfolio
---

Sleeper Agent is a DLL Injection technique developed for educational use in CSEC 559/659. In this technique, payload execution is temporally separated from injection. Rather than including the payload inside DLLMain and triggering the payload during the DLL import, the payload is written in another exported function. The location of that function is then discovered at a time of the attacker's choosing by finding walking the list of DLLs in the remote process, finding the base address of the injected DLL, and adding the offset of the payload function.