# Citizen Doge 
##### A project on self-organising problem structuring
Citizen Doge is a philosophical, moral and technical exploration of what it means to be the potential "currency of the world" as well as "the people's coin". We seek clarifty and understanding and bridge the gaps between the nerds and everyone else.  

![Image of Shibe](https://www.nicepng.com/png/detail/22-226389_mlg-doge-png-clip-art-royalty-free-stock.png)

Dogecoin is the evolution of open source technology and digital currency. Contrary to popular belief, it is far from a joke. It's an example of sponstaneous decentrlaized commnity and self organising problem structuring. What this all means is that no one is in charge, there is no boss, no corporate structure and no hiring of employees. It depends on our natural ability to have a common goal, to build community and achieve it together. 


### Current Projects and Considerations

> If our transaction volume explodes, I think that we're bound to need cross-chain payment channel solutions at some point. It doesn't have to be Lightning as designed for Bitcoin, but the ability to at least set up payment channels without needing to pre-fund multisig addresses needs to be there if we'd want anything remotely like an L2 solution.
-patricklodder (DogeDev)

| Operation Such Frenzy | Next Major - 1.21 | Next Minor - 1.14.4
| -------------:| :-------------:| :-------------:| 
| QT UI | |  | 
|  | | 
|  |  | 
|  |  | 

## Upcoming Major Release (1.21)

> With the next major release, we plan to propose 2 protocol changes for activation at once: segwit and csv. Both have been deployed on Bitcoin's mainnet for a longer time and are considered non-contentious.
-patricklodder (DogeDev)

READ MORE >> https://github.com/dogecoin/dogecoin/issues/1798

### In Scope

| Proposed       | Reason           | Reference  |
| ------------- |:-------------:| -----:|
| Segwit (Segregated witness ) | Separates spending proofs (i.e. signatures) from transactions when embedded in blocks,  further reduces transaction malleability      | BIP141, BIP143 and BIP147  |
| P2W addressing |   |   |
| CSV (CheckSequenceVerify) | Allows consensus-enforced locking of an output until a relative time and exposes the field to redeem scripts, allows for much more sophisticated redeem scripts, must-have feature for Lightning-like L2 networks. | BIP68, BIP112 and BIP113 |

Reference
https://github.com/bitcoin/bips

### Deployment 

| Approval     | Definition  | Fork Identifiers | Reference |
| ------------- |:-------------:| -----:| -------------: |
| 95% Super Majority | Full activation with 1900 blocks having v5 in a 2000 block window | Block version 5 [0x00620104], Protocol version 70016 [0x00620104] | Similar to BIP65 soft fork that was proposed with Dogecoin Core 1.14 | 



### On the Shelf
| Proposed       | Reason           | Ref  |
| ------------- |:-------------:| -----:|
| VersionBits / BIP9      | Needs another, more dangerous soft-fork, see #1340 and #1344. Conflict in the version with AuxPow |  |
| TapRoot      | Not yet deployed on Bitcoin      |    |
| Extension Blocks | Not yet deployed on Litecoin      |     |
| Lightning | | 


Reference
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



## Motivation

Having experienced Occupy wall street and being one of the first protestors in sourthern california, I watched a crowd of 15-20 people in Los Angeles and San Diego turn into thousands. I was fascinated by the democratic processes employed to reach ocnsensus on objectives and the problems that were being solved collectively. Doge, defining itself as the people's coin and being decentralized, is reminscent and has larger implications in the futue being a form of currency. Being a coder myself, I couldn't resist getting involved. 
