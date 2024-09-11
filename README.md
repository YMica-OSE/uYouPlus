# uYouPlus
### IMPORTANT: Regarding the bundle ID (since no one mentioned it)
It took me a while to fully understand this concept, but for those who were like me and was worried about identical bundle ID causing issues (since the "Run workflow" drop down has a field for it):  
There are primarily 2 methods of loading the IPA onto the phone: _Sideloading_ (Sideloadly, AltStore,...), and _TrollStore_. 
- With _TrollStore_, the process is exactly as if you were to install an APK on an Android phone. Therefore if the modded IPA has the same bundle ID, it will indeed overwrite the stock app.
- _Sideloading_ is different. Since you are installing the IPA as a "test" app, that is, something that isn't signed by the original publisher and verified by the Apple, overwriting is not possible with iOS's security model. Thus, what happens is your sideloaded app's bundle ID gets **attached with your team ID at the end**, effectively making it a separate app. 
<p align="center">
  <img src="https://github.com/user-attachments/assets/61fdca89-fd3a-4e65-9474-95a6388bd03b">
</p> 

Since most people won't have TrollStore (which I consider a form of jailbreak since it relies on a CoreTrust bug), sideloading would be the answer, which will always guarantee a separate app upon installation. 

**<ins>TL;DR:</ins> You are fine if you are not jailbroken.**

---
See [here](https://github.com/qnblackcat/uYouPlus) for the official repository of this project. This repository was created per the instructions described in its [build wiki](https://github.com/qnblackcat/uYouPlus/wiki/Building) and is just for performing the build. 

All rights belongs to **qnblackcat** and **MiRO92**.

---
![Image 2](https://github.com/qnblackcat/uYouPlus/assets/77606385/c1a1c58a-5d4d-48a6-bb98-d00086719ccc)
