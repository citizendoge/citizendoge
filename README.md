| Dogecoin Protocol 💎️
| -------------:|



| Protocol | Feature | Reason | Ref| Risk |
| -------------:| ------:| -----:| -----:| -----:|
|Core|Bitcoin Core Implementation | | | 🟢 ⚠️ Needs another
|POW Protocol|Namecoin's Aux Protocol| Enables low power mining | | 🟢
|Mining Algorithm|Litecoin's Scrypt | Has enabled a handful of wallet/service integrations that would otherwise have been difficult and maybe would not have happened at all | | 🟢

| Current Projects
| -------------:|

| Operation Such Frenzy | Next Major - 1.21 | Next Minor - 1.14.4
| -------------:| :-------------:| :-------------:| 

Over the last few months, Doge has gone an increase in interest driven by Elon Musk and endorsement from Mark Cuban. For years, Doge developers have maintained their repository and achieved the goal of sustaining the project. As demand increases, they are faced with new challenges. The goal is to outline those challenges and provide a snapshot of the next major release. 


| Next Major - 1.21 🚀 [^1]
| -------------:|

[^1]: https://github.com/dogecoin/dogecoin/issues/1340

| Proposed       | Reason           | Ref  |  Risk[^2] |
| ------------- |:-------------:| -----:| -----:|
| Segwit (Segregated witness ) | Separates spending proofs (i.e. signatures) from transactions when embedded in blocks,  further reduces transaction malleability      | BIP141, BIP143 and BIP147  |🟢
| P2W addressing |   |   | | |🟢
| CSV (CheckSequenceVerify) | Allows consensus-enforced locking of an output until a relative time and exposes the field to redeem scripts, allows for much more sophisticated redeem scripts, must-have feature for Lightning-like L2 networks. | BIP68, BIP112 and BIP113 |  |🟢
| VersionBits / BIP9      |  |  | ⚠️ Needs another, more dangerous soft-fork, see #1340 and #1344. Conflict in the version with AuxPow|
| TapRoot      |      |    |⚠️ Not yet deployed on Bitcoin and not field tested |
| Extension Blocks | |  |⚠️ Not yet deployed on Litecoin |
| Lightning | | |️|

| Deployment 🎢
| -------------:|

| Consensus    | Definition  | Fork Identifiers | Reference |
| ------------- |:-------------:| -----:| -------------: |
| 95% Super Majority | Full activation with 1900 blocks having v5 in a 2000 block window | Block version 5 [0x00620104], Protocol version 70016 [0x00620104] | Similar to BIP65 soft fork that was proposed with Dogecoin Core 1.14 | 

Risk Profile
🟢 - Low to no risk, undergoing implimentation or currently implimented
⚠️ - Current or future compatability issue considered low to medium risk level 
⛔️ - High Risk feature, implimentation greatly risk security, scalability and cohesiveness of the protocol
🚼 - New feature (alpha, beta) in protocol that is not field tested and may cause unknown bugs if implimented.



Reference
https://github.com/bitcoin/bips
https://github.com/dogecoin/dogecoin/issues/1340

## Terms to understand

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| Fork Activation      | Takes a very long time, impacts  | |
| BlockSize      | Higher size generally means a decrease in transaction time      |  |
| Transaction Time | Doge has a transaciton time of 1 minute      |  |
| Malleability | | |
| Hard Fork | | |
| Soft Fork | | |
| Layer 1 | May potentially be able to handle all the worlds transactions | Elon Tweet 😫|

The basis of the above changes are encouraged to be explored but seem rational given updates should happen incrementally and not commit with underlying funcitonal technology. Major upgrades take time, programming effort and robust testing.  

| Info |  |
| ------ | ------ |
| Doge Projects | https://github.com/dogecoin/dogecoin/projects |
| Doge Repo | https://github.com/dogecoin/ |
| Submit Code Related Issues | https://github.com/dogecoin/dogecoin/issues |
| Software Releases | https://github.com/dogecoin/dogecoin/releases |
| Submit Ideas on Reddit | https://www.reddit.com/r/dogecoindev |


# Citizen Doge ✨
##### A project on self-organising problem structuring
Citizen Doge is a philosophical, moral and technical exploration of what it means to be the potential "currency of the world" as well as "the people's coin". 

![Image of Shibe](https://www.nicepng.com/png/detail/22-226389_mlg-doge-png-clip-art-royalty-free-stock.png)

Dogecoin is the evolution of open source technology and digital currency. Contrary to popular belief, it is far from a joke. It's an example of sponstaneous decentrlaized commnity and self organising problem structuring. What this all means is that no one is in charge, there is no boss, no corporate structure and no hiring of employees. It depends on our natural ability to have a common goal, to build community and achieve it together in a decentralized manner. 

## Motivation

Having experienced Occupy wall street and being one of the first protestors in sourthern california, I watched a crowd of 15-20 people in Los Angeles and San Diego turn into thousands. I was fascinated by the democratic processes employed to reach ocnsensus on objectives and the problems that were being solved collectively. Doge, defining itself as the people's coin and being decentralized, is reminscent and has larger implications in the futue being a form of currency. Being a coder myself, I couldn't resist getting involved. 





