# Citizen Doge ✨
##### A project on self-organising problem structuring
Citizen Doge is a philosophical, moral and technical exploration of what it means to be the potential "currency of the world" as well as "the people's coin". 

| Dogecoin Protocol 💎️ |  [Open Projects](https://github.com/dogecoin/dogecoin/projects) |
 -------------:| --------: | 

***********************

| [Operation Such Frenzy](https://github.com/dogecoin/dogecoin/projects/5) | [Next Major - 1.21](https://github.com/dogecoin/dogecoin/projects/4) | [Next Minor - 1.14.4](https://github.com/dogecoin/dogecoin/projects/3)
| -------------:| :-------------:| :-------------:| 
***********************

| Protocol | Feature | Reason | Ref| Risk [^1] |
| -------------:| ------:| -----:| -----:| -----:|
|Core|Bitcoin Core Implementation | Standard structs/serialization | [Bitcoin Docs](https://developer.bitcoin.org/) | 🟢 ⚠️ May impact scalability negatively in the future
|POW Protocol|Namecoin's Aux Protocol| Allows merged and energy efficient mining | [Namecoin Repo](https://github.com/namecoin/namecoin-core) | 🟢
|Mining Algorithm|Litecoin's Scrypt | Has enabled a handful of wallet/service integrations that would otherwise have been difficult aor non existent | [Litecoin.org](https://litecoin.org/) | 🟢

Over the last few months, Doge has received an increase in interest driven by Elon Musk and endorsements from Mark Cuban. For years, Doge developers have maintained their repository and achieved the goal of sustaining the project. As demand increases, they are faced with new challenges. The goal is to outline those challenges and provide a technical snapshot of the next major release. 
**********************

| Next Major - 1.21 🚀 [^2]
| -------------:|
> Current proposal is the most feasible as it's only touching well known, field-proven implementations on which scalability solutions can quickly be adapted.


| Proposed       | Reason           | Ref  |  Risk [^1] |
| ------------- |:-------------:| -----:| -----:|
| Segregated Witness (SegWit) | Separates spending proofs (i.e. signatures) from transactions when embedded in blocks,  further reduces transaction malleability      | [BIP141](https://github.com/bitcoin/bips/blob/master/bip-0141.mediawiki), [BIP143](https://github.com/bitcoin/bips/blob/master/bip-0143.mediawiki) and [BIP147](https://github.com/bitcoin/bips/blob/master/bip-0147.mediawiki)  |🟢
| Check Sequence Verify (CSV) | Allows consensus-enforced locking of an output until a relative time and exposes the field to redeem scripts, allows for much more sophisticated redeem scripts, must-have feature for Lightning-like L2 networks. Allows for bi-directional payment channels using P2SH. So this is more of an enabler than a feature. | [BIP68](https://github.com/bitcoin/bips/blob/master/bip-0068.mediawiki), [BIP112](https://github.com/bitcoin/bips/blob/master/bip-0112.mediawiki) and [BIP113](https://github.com/bitcoin/bips/blob/master/bip-0113.mediawiki) | 🟢 |
| Version Bits      | Version bits with timeout and delay. It relies on interpreting the version field as a bit vector, where each bit can be used to track an independent change. These are tallied each retarget period. | [Bip9](https://github.com/bitcoin/bips/blob/master/bip-0009.mediawiki) | ⛔️ Needs another, more dangerous soft-fork, see [#1340](https://github.com/dogecoin/dogecoin/issues/1340) and [#1344](https://github.com/dogecoin/dogecoin/issues/1344). Conflict in the version with AuxPow|
| Tap Root  |    Enhances privacy while reducing the amount of data needed, thereby lowering transaction costs   |[Taproot Bitcoin Proposal](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2018-January/015614.html)  |⚠️🚼 Not yet deployed on Bitcoin and not field tested |
| Extension Blocks (EB) | Litecoin's Mimblewimble privacy feature is code complete.Only part of the code has been submitted for review, and a review of the code may take weeks or months. The feature is nevertheless close to going live on Litecoin's mainnet sometime this year. | [cryptobriefing.com](https://cryptobriefing.com/litecoins-mw-privacy-feature-is-now-code-complete/) |⚠️ Not yet deployed on Litecoin |
| Lightning (L2) | Layer 2 (L2) payment protocol designed to be layered on top of a blockchain-based cryptocurrency such as bitcoin. Designed to deal with scalability issues in bitcoin. Transparent payment channels with cross-chain settlement |[Wiki](https://en.wikipedia.org/wiki/Lightning_Network), [Git Repo](https://github.com/lightningnetwork/lnd)|️⚠️ Compatibility issues|
| P2W Addressing |   |   | | |

***********************

| Deployment 🎢
| -------------:|

| Consensus    | Definition  | Identifiers | Reference |
| ------------- |:-------------:| -----:| -------------: |
| 95% Super Majority | Full activation with 1900 blocks having v5 in a 2000 block window | Block version 5 [0x00620104], Protocol version 70016 [0x00620104] | Similar to BIP65 soft fork that was proposed with Dogecoin Core 1.14 | 

***********************

| Terms        | Definition         | 
| ------------- |:-------------:|
| Fork Activation      | Takes a very long time, impacts  | 
| BlockSize      | Higher size generally means a decrease in transaction time      |  |
| Transaction Time | Doge has a transaciton time of 1 minute      |  
| Malleability | The ability of someone to change (mutate) unconfirmed transactions without making them invalid, which changes the transaction’s txid, making child transactions invalid. | 
| Hard Fork | A hard fork requires all nodes or users to upgrade to the latest version of the protocol software. | 
| Soft Fork | Backwards-compatible fork that requires only a majority of the miners upgrading to enforce the new rules. | 

[Learn More - Bitcoin Glossary](https://developer.bitcoin.org/glossary.html)


| Links |  |
| ------ | ------ |
| Doge Repo | https://github.com/dogecoin/ |
| Doge Projects | https://github.com/dogecoin/dogecoin/projects |
| Submit Code Related Issues | https://github.com/dogecoin/dogecoin/issues |
| Software Releases | https://github.com/dogecoin/dogecoin/releases |
| Submit Ideas on Reddit | https://www.reddit.com/r/dogecoindev |
| Bitcoin Bips | https://github.com/bitcoin/bips |
| Bitcoin Glossary | https://developer.bitcoin.org/glossary.html |


![Image of Shibe](https://www.nicepng.com/png/detail/22-226389_mlg-doge-png-clip-art-royalty-free-stock.png)

Dogecoin is the evolution of open source technology and digital currency. Contrary to popular belief, it is far from a joke. It's an example of sponstaneous decentrlaized commnity and self organising problem structuring. What this all means is that no one is in charge, there is no boss, no corporate structure and no hiring of employees. It depends on our natural ability to have a common goal, to build community and achieve it together in a decentralized manner. 

## Motivation

Having experienced Occupy wall street and being one of the first protestors in sourthern california, I watched a crowd of 15-20 people in Los Angeles and San Diego turn into thousands. I was fascinated by the democratic processes employed to reach ocnsensus on objectives and the problems that were being solved collectively. Doge, defining itself as the people's coin and being decentralized, is reminscent and has larger implications in the futue being a form of currency. Being a coder myself, I couldn't resist getting involved. 

[^1]: Risk Keys 
🟢 - Low to no risk, undergoing implimentation or currently implimented.
⚠️ - Current or future compatability issue considered low to medium risk level 
⛔️ - High Risk feature, implimentation greatly risks security, scalability and unity of the protocol. Known conflicts and compatibility issues.
🚼 - New feature (alpha, beta) in protocol that is not field tested and may cause unknown bugs if implimented.
