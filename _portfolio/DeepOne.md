---
title: "DeepOne"
excerpt: "LSA Function Hook"
collection: portfolio
---

DeepOne is a DLL that hooks a function used during the Windows authentication process. When a user attempts to authenticate, DeepOne - as NT AUTHORITY/SYSTEM - injeects a reverse shell into a specified process. I take no credit for the initial hook, which was developed by a member of the RITSEC Red Team, which I modified for process injection.
