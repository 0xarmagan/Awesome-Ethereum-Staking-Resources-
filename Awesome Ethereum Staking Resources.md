# Awesome Ethereum Staking Resources 

![](https://i.imgur.com/GkHMBtQ.png)

:::info
:bulb: This document is under development. Last update: Feb 23, 23
:::

:::success

This is an open source work. Those who want to add content or contribute can send a pr from [Github](https://github.com/0xarmagan/Awesome-Ethereum-Staking-Resources-/blob/main/Awesome%20Ethereum%20Staking%20Resources.md).


Follow me on [Twitter](https://twitter.com/0xarmagan)
Support:  [armagan.eth](https://etherscan.io/address/0x4dd05e12d0244575c77c31c24f0e273610c085d9)

:::

“The health, resilience, and censorship resistance of blockchains depend on having many independently operated and geographically dispersed full nodes. Each full node can help other new nodes obtain the block data to bootstrap their operation, as well as offer the operator an authoritative and independent verification of all transactions and contracts”.


### Topics

* **[Clients](https://hackmd.io/qSzUlW7qQ-WD95H7bbmMcw?view#Clients)**
* **[Solo Staking](https://hackmd.io/qSzUlW7qQ-WD95H7bbmMcw?view#Solo-Staking)**
* **[LSD](https://hackmd.io/qSzUlW7qQ-WD95H7bbmMcw?view#LSD---Liquid-Staking-Derivatives)**
* **[DVT](https://hackmd.io/qSzUlW7qQ-WD95H7bbmMcw?view#DVT---Distributor-Validator-Technology-DVT)**
* [**What is Beacon Chain?**](https://hackmd.io/qSzUlW7qQ-WD95H7bbmMcw?view#What-is-Beacon-Chain) 




---


### Clients

* **Execution Layer**
    * [Geth](https://geth.ethereum.org/)
      * [Kite's Nest (v1.11.2)](https://github.com/ethereum/go-ethereum/releases) Feb 22, 2022
    * [Nethermind](http://nethermind.io/)
      * [v1.17 ](https://github.com/NethermindEth/nethermind/releases/tag/1.17.0) Feb 17, 2023
    * [Erigon](https://github.com/ledgerwatch/erigon#erigon)
      * [v2.38.1](https://github.com/ledgerwatch/erigon/releases/tag/v2.38.1) Feb 7, 2023
    * [Besu](https://hyperledger.org/use/besu) 
      * [23.1.0](https://github.com/hyperledger/besu-docs/releases/tag/23.1.0) Feb 17, 2023
    * [Reth](https://github.com/paradigmxyz/reth) Pre-Alpha
    * [Silkworm](https://github.com/torquem-ch/silkworm#about-silkworm) Pre-Alpha


* **Consensus Layer**
    * [Lodestar](https://lodestar.chainsafe.io/)
      * [v1.4.0](https://blog.chainsafe.io/lodestar-v1-4-0-release-and-a-look-ahead-8f0a99c2e708) Jan 31, 2023 
    * [Teku](https://consensys.net/knowledge-base/ethereum-2/teku/)
      * [v23.2.0](https://github.com/ConsenSys/teku/releases/tag/23.2.0) Feb 17, 2023
    * [Prysm](https://prysmaticlabs.com/)
      * [v3.2.1](https://t.co/wNBzalLIdr) Feb 13,2022
    * [Nimbus](https://nimbus.team/)
      * [v23.2.0](https://github.com/status-im/nimbus-eth2/releases/tag/v23.2.0) Feb 20, 2023
      * [Design notes for decoupled EIP4844](https://github.com/status-im/nimbus-eth2/pull/4550)
    * [Lighthouse](https://lighthouse.sigmaprime.io/)
      * [v3.5.0 Gazorpazorpfield](https://github.com/sigp/lighthouse/releases/tag/v3.5.0) Feb 22, 2023

:::danger 

🚨Check 👉 [Client Diversity](https://clientdiversity.org/)🚨

:::

:::info

**Client Diversity Is Not Optional - It's critical**

Many know client diversity is important for a more resilient network, but they don't understand why or just how essential it is. It's not only important — **it's critical**  
:::


## Solo Staking

Solo staking is the act of running an Ethereum node connected to the internet and depositing 32 ETH to activate a validator, giving you the ability to participate directly in network consensus.

Solo staking increases the decentralization of the Ethereum network, making Ethereum more censorship-resistant and robust against attacks. Other staking methods may not help the network in the same ways. Solo staking is the best staking option for securing Ethereum. [*](https://ethereum.org/en/staking/solo/)

### Communities, Explorers, Tools and Platforms

**Community**
  * [EthStaker](https://ethstaker.cc/)
    * [EthStaker YouTube](https://www.youtube.com/@ETHStaker)
    * [Reddit](https://www.reddit.com/r/ethstaker/)
    * [Twitter ](https://twitter.com/ethStaker)
* [Ethereum On Arm](https://ethereum-on-arm-documentation.readthedocs.io/)

**Platforms**
  * [Nice Node](https://www.nicenode.xyz/) - node management kit
  * [Stereum](https://stereum.net/) - manage staking from windows
  * [DappNode](https://dappnode.com/) - Webui
  * [Avado](https://ava.do/) - Webui

**Explorers, Analytics, Statistics**
  * [Etherscan](https://etherscan.io/)
  * [EtherNodes](https://ethernodes.org/)
  * [Nodewatch](https://nodewatch.io/)
  * [Beaconcha.in Gnosis](https://beacon.gnosischain.com/)
  * [Beaconcha.in Ethereum](https://beaconcha.in/dashboard)
    * [Mainnet](https://beaconchain.com/)
    * [Gnosis](https://beacon.gnosischain.com/)
  * [ETH Deposits to Beacon Chain Stats](https://dune.com/LidoAnalytical/eth-deposits-stats)
  * [Migalabs](https://migalabs.es/crawler/dashboard)
  * [ethstaker.tax](https://ethstaker.tax/)
  * [ETH Staking Ecosystem](https://dune.com/obol_labs/eth-staking-ecosystem)
  *  [Project Sunshine - A dashboard to measure the health of Ethereum's decentralization](https://ethsunshine.com/)

**Tools**
  * [EthDocker](https://eth-docker.net/)
  * [Ethwizard](https://github.com/stake-house/eth-wizard)

---


### Set-Up Guides

* [Ethereum official](https://launchpad.ethereum.org/en/)
* [Checklist](https://launchpad.ethereum.org/en/checklist)
* [Ethereum On Arm Quick Start Guide](https://ethereum-on-arm-documentation.readthedocs.io/en/latest/quick-guide/about-quick-start.html)
* [Official Ethereum Launchpad](https://launchpad.ethereum.org/en/)
* [EthStaker How To Stake](https://www.reddit.com/r/ethstaker/comments/tvlnck/how_to_stake_on_ethereum_april_2022_edition/)
* [Rocketpool](https://docs.rocketpool.net/guides/staking/overview.html)
* [DappNode](https://docs.dappnode.io/user/quick-start/first-steps)
* [Stereum](https://stereum.net/)
* [GLC - Set up an Ethereum /Gnosischain validator in under 30mins](https://mirror.xyz/0xf3bF9DDbA413825E5DdF92D15b09C2AbD8d190dd/n0AOGKh6Ck068icgY78i9DA3xPYWlWLGlE8HXnJeSl0)
* [Guide on how to do monitoring for an Ethereum validator](https://github.com/eth-educators/ethstaker-guides/blob/main/monitoring.md)
* [Guide on how to do alerting for an Ethereum validator](https://github.com/eth-educators/ethstaker-guides/blob/main/alerting.md)
* [Guide on how to prepare a staking machine for the Merge](https://github.com/eth-educators/ethstaker-guides/blob/main/prepare-for-the-merge.md)
* [Guide on how to join the Goerli/Prater merge testnet (Geth/Lighthouse)](https://github.com/eth-educators/ethstaker-guides/blob/main/merge-goerli-prater.md)
* [Guide on how to join the Goerli/Prater merge testnet (Besu/Teku)](https://github.com/eth-educators/ethstaker-guides/blob/main/merge-goerli-prater-alt.md)
* [Coincashew - How to setup a validator for Ethereum staking on mainnet](https://www.coincashew.com/coins/overview-eth/guide-or-how-to-setup-a-validator-on-eth2-mainnet)
* [Guide to Staking on Ethereum (Ubuntu/Lodestar)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-lodestar-193a2553a161?source=user_profile---------0----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Goerli/Lodestar)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-goerli-lodestar-f3c8f77e7097?source=user_profile---------1----------------------------)
* [Supplementary Guide to Staking on Ethereum For Existing Stakers](https://someresat.medium.com/supplementary-guide-to-staking-on-ethereum-for-existing-stakers-57493678a460?source=user_profile---------2----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Nimbus)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-nimbus-31f56657ea8f?source=user_profile---------3----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Prysm)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-prysm-581fb1969460?source=user_profile---------4----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Lighthouse)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-lighthouse-773f5d982e03?source=user_profile---------5----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Teku)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-teku-f09ecd9ef2ee?source=user_profile---------6----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Goerli/Prysm)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-goerli-prysm-4a640794e8b5?source=user_profile---------7----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Goerli/Nimbus)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-goerli-nimbus-3b0e2c0c6e0e?source=user_profile---------8----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Goerli/Lighthouse)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-g%C3%B6erli-lighthouse-8d0a2a811e6e?source=user_profile---------9----------------------------)
* [Guide to Staking on Ethereum (Ubuntu/Goerli/Teku)](https://someresat.medium.com/guide-to-staking-on-ethereum-ubuntu-g%C3%B6erli-teku-6512b26f1372?source=user_profile---------10----------------------------)
* [Ethereum Staker Migration Guide — Migrating from Prysm to Nimbus](https://someresat.medium.com/ethereum-staker-migration-guide-migrating-from-prysm-to-nimbus-b802a7dcb31e?source=user_profile---------11----------------------------)
* [Ethereum Staker Migration Guides — Introduction](https://someresat.medium.com/ethereum-staker-migration-guides-introduction-45505079b1f0?source=user_profile---------12----------------------------)
* [Guide to RocketPool Staking on Ethereum 2.0 For Existing Solo Stakers](https://medium.com/@gethwethreth/guide-to-rocketpool-staking-on-ethereum-2-0-for-existing-solo-stakers-87aeb1dfbb76)


---

### Blogs, Videos, Podcasts, FAQs

* [Everything a Solo Staker Should Know for the Next Phase of Ethereum by Pol | Devcon Bogotá](https://www.youtube.com/watch?v=F-mlHOAtq2c&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=2)
* [Promoting Small and Independent Stakers: Q&A with the Ethereum Staking Protocols | Devcon Bogotá](https://www.youtube.com/watch?v=Exh-hQOV8kE&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=4)
* [Like a Kindergeburtstag - Ethereum Node in under 3 minutes with Stereum by Stefan Kobrc](https://www.youtube.com/watch?v=hIArOBKtV3U&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=9)
* [Validating Made Light and Simple](https://www.youtube.com/watch?v=kX-Q2fiLecY&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=19)
* [Why and How to Run a Node! (No ETH Required) by Johns Gresham | Devcon Bogotá](https://www.youtube.com/watch?v=6yWmF4hiAsA&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=17)
* [How to Run a Validator From Zero on Resource-Constrained and Low Powered Devices by Diego Losada](https://www.youtube.com/watch?v=lPjsXJX6skI&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=18)
* [Run Your Own Beaconcha.in | Devcon Bogotá](https://www.youtube.com/watch?v=diQvWsWHARE&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=15)
[Client Diversity Matters: Thinking Independently Together](https://www.youtube.com/watch?v=OTqzkQVKuA0&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=20)
* [What’s New in Eth2](https://hackmd.io/@benjaminion/eth2_news/https%3A%2F%2Fhackmd.io%2F%40benjaminion%2Fwnie2_220826)
* [Weekinethereum ](https://weekinethereumnews.com/)
* [EthStaker knowledge base](https://ethstaker.gitbook.io/ethstaker-knowledge-base)
* [Ethereum Withdrawal Call Series](https://www.youtube.com/watch?v=dGGMNYbWnP4)
* [Withdrawal Call Series #2](https://www.youtube.com/watch?v=J0u13RokzFg)
* [ETH Withdrawals FAQ](https://notes.ethereum.org/@launchpad/withdrawals-faq)
* [BLS Signatures & Withdrawals](https://medium.com/nethermind-eth/bls-signatures-withdrawals-bbf38658c242)
* [How Proof of Stake on Ethereum works](https://stonecoldpat.substack.com/p/how-proof-of-stake-ethereum-works)
* [Guide on how to join the Zhejiang testnet (Geth/Lighthouse)](https://github.com/eth-educators/ethstaker-guides/blob/main/zhejiang.md)


---

## Meetup/Community Call/Event

### Upcoming 
* 


### Past
* [Gnosis Validator Meetup with Nethermind](https://www.youtube.com/watch?v=P7nuPNZZjJQ)
* [Jan 31 :  EthStaker community withdrawals call](https://www.reddit.com/r/ethstaker/comments/10p3uen/ethstaker_community_withdrawals_call_january_31/)
* [Feb 1 :  Gnosis Ecosystem Wednesday with Beaconcha.in](https://discord.gg/nTK23HqK?event=1068254375832715315)
* [Feb 1 Gnosis Core Devs Call ](https://www.youtube.com/watch?v=NxPWQLd8H7g)
* [Feb 2 AllCoreDev Call](https://t.co/cGHswIbfER)
* [Gnosis Validator Meetup with Erigon](https://twitter.com/gnosischain/status/1625822421440667648)
* * [EthStaker community calls with Lodestar](https://www.youtube.com/watch?v=h8dZ9wa7mZY)

### MEV

**Relay List**
* [MEV relay list for Mainnet](https://github.com/eth-educators/ethstaker-guides/blob/main/MEV-relay-list.md)

**Relay Monitoring**
* [Mevboost](https://www.mevboost.org/)
* [Mevwatch](https://www.mevwatch.info/)
* [MEVPanda](https://www.mevpanda.com/)
* [mevboost.pics ](https://www.mevboost.pics/)
* [Relay Scan](https://www.relayscan.io/)
* [Relays from beaconcha.in](https://beaconcha.in/relays)

### Blogs, Podcasts, Videos

* [MEVDay](https://mevday.org/)
* [MEV.wtf Virtual Summit](https://hackmd.io/ivUzk3piQEG8ALzCGbxlag)
* [What is MEV (Miner Extractable Value)?](https://www.youtube.com/watch?v=XbMtIg5OgCc)
* [What is Miner Extractable Vaule?](https://www.youtube.com/watch?v=zliSbdLwy5U)
* [Enter the Dark Forest: the terrifying world of MEV and Flash bots](https://www.youtube.com/watch?v=Wd0at2Pu6xY)
* [Dive Back into MEV with Alex Stokes and Chris Hager](https://zeroknowledge.fm/243-2/)
* [This is MEV by Sxysun, Devcon 2022](https://archive.devcon.org/archive/watch/6/this-is-mev/?tab=YouTube)
* [Block Building after the merge by Alex Stokes, Devcon 2022](https://archive.devcon.org/archive/watch/6/block-building-after-the-merge/?tab=YouTube)
* [Cost of Feudalism by Tarun Chitra and Guillermo Angeris, Devcon 2022](https://archive.devcon.org/archive/watch/6/cost-of-feudalism-towards-a-theory-of-mev/?tab=YouTube)
* [MEV: Maximal Extractable Value Part 2: The Rise of the Builders](https://www.galaxy.com/research/whitepapers/mev-the-rise-of-the-builders/)
* [Flashbots Transparency Report for December + January](https://t.co/0KNmbhufos) 


---



## LSD - Liquid Staking Derivatives

Liquid staking allows users with less than 32 ETH to receive staking yields by swapping ether for a token representing staked ether that can be used in DeFi. However, the incentives and market dynamics associated with liquid staking are still being discovered, as well as its effect on Ethereum's security (e.g. centralization risks). [*](https://ethereum.org/en/community/research/#liquid-staking-and-derivatives)


**Risks of Liquid Staking Derivatives**

* Danny Ryan: [The Risks of LSD](https://notes.ethereum.org/@djrtwo/risks-of-lsd)
  * Smart contract security risk
  * ETH 2.0 Technical risk
  * DAO key management risk 
  * Slashing risk
  * stETH price risk
  * Centralization and liquidity risk
  * Cartelization risk


### Platforms

* [Lido](https://lido.fi/)
* [Coinbase Wrapped Staked ETH](https://help.coinbase.com/en/coinbase/trading-and-funding/staking-rewards/cbeth)
* [RocketPool](https://rocketpool.net/)
* [Stakewise](https://stakewise.io/)
* [FraxEth](https://docs.frax.finance/frax-ether/frxeth-and-sfrxeth)
* [Ankr](https://www.ankr.com/)
* [StakeHound](https://stakehound.com/blog/)
* [Bitfrost](https://bifrost.finance/)
* [Stafi](https://www.stafi.io/)
* [Shared Stake](https://www.sharedstake.org/)
* [GETH](https://guarda.com/staking/ethereum-staking/)

### Liquidity pools (LP)

Mainnet  

* Curve
  * Mainnet
    * [Curve ETH​+frxETH pool ](https://curve.fi/#/ethereum/pools/frxeth/deposit)
    * [Curve stETH concentrated](https://curve.fi/#/ethereum/pools/factory-v2-117/deposit)
    * [Curve rETH/wstETH](https://curve.fi/#/ethereum/pools/factory-v2-89/deposit)
    *  [Curve ETH​+cbETH pool ](https://curve.fi/#/ethereum/pools/factory-crypto-91/deposit)
    *  [Curve ETH​+rETH pool](https://curve.fi/#/ethereum/pools/reth/deposit)
    *  [Curve ETH​+ankrETH pool](https://curve.fi/#/ethereum/pools/ankreth/deposit)

* Convex
  * Mainnet
    * [Curve ETH​+cbETH pool ](https://curve.fi/#/ethereum/pools/factory-crypto-91/deposit) - [Convex LP Token Address](https://etherscan.io/address/0x5b6C539b224014A09B3388e51CaAA8e354c959C8)
    * [Curve rETH​+wstETH pool](https://curve.fi/#/ethereum/pools/factory-v2-89/deposit) - [Convex LP Token Address](https://etherscan.io/address/0x447Ddd4960d9fdBF6af9a790560d0AF76795CB08)
    * [Curve ETH​+rETH pool](https://curve.fi/#/ethereum/pools/reth/deposit) - [Convex LP Token Address](https://etherscan.io/address/0xF403C135812408BFbE8713b5A23a04b3D48AAE31) 
    * [Curve ETH​+stETH pool](https://curve.fi/#/ethereum/pools/steth/deposit) - [Convex LP token Address](https://etherscan.io/address/0x06325440D014e39736583c165C2963BA99fAf14E)
    *  [Curve ETH​+ankrETH pool](https://curve.fi/#/ethereum/pools/ankreth/deposit) - [Convex LP Token Address ](https://etherscan.io/address/0xaA17A236F2bAdc98DDc0Cf999AbB47D47Fc0A6Cf)

* Balancer
  * Mainnet
      * [Balancer rETH/WETH](https://app.balancer.fi/#/ethereum/pool/0x1e19cf2d73a72ef1332c882f20534b6519be0276000200000000000000000112)
      * [Balancer wstETH/sfrxETH/rETH](https://app.balancer.fi/#/ethereum/pool/0x8e85e97ed19c0fa13b2549309965291fbbc0048b0000000000000000000003ba)
      * [Balancer wstETH/WETH](https://app.balancer.fi/#/ethereum/pool/0x32296969ef14eb0c6d29669c550d4a0449130230000200000000000000000080)
      * [Balancer wstETH/cbETH](https://app.balancer.fi/#/ethereum/pool/0x4edcb2b46377530bc18bb4d2c7fe46a992c73e100000000000000000000003ec)
 
* [Diversified Staked ETH Index ($dsETH)](https://twitter.com/indexcoop/status/1617932168428421121  )

### Lending Market

* [Aave wstETH pool](ipns://app.aave.com/reserve-overview/?underlyingAsset=0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0&marketName=proto_mainnet_v3)
* [Aave rETH pool](http://app-aave-com.ipns.localhost:48084/reserve-overview/?underlyingAsset=0xae78736cd615f374d3085123a210448e74fc6393&marketName=proto_mainnet_v3)
* [Aave cbETH pool](http://app-aave-com.ipns.localhost:48084/reserve-overview/?underlyingAsset=0xbe9895146f7af43049ca1c1ae358b0541ea49704&marketName=proto_mainnet_v3)
* [Euler wsETH pool](https://app.euler.finance/market/0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0)
* [Euler cbETH pool](https://app.euler.finance/market/0xbe9895146f7af43049ca1c1ae358b0541ea49704)
* [Euler stETH pool](https://app.euler.finance/market/0xae7ab96520de3a18e5e111b5eaab095312d7fe84)


### Analytics, Statistics

* [Eth2 Liquid Staking](https://dune.com/ratedw3b/Eth2-Liquid-Staking)
* [ETH Deposits to Beacon Chain Stats](https://dune.com/LidoAnalytical/eth-deposits-stats)
* [DefiLlama LSD ](https://defillama.com/lsd)

### Research and Development

* [Ethresear.ch liquid staking](https://ethresear.ch/search?q=liquid%20staking)
* [On Staking Pools and Staking Derivatives](https://research.paradigm.xyz/staking)

### Blogs, Videos, Podcasts

* [Validator Receipts: an Alternative to Liquid Staking Derivatives by Steve Berryman](https://www.youtube.com/watch?v=f39WG1N3lUg)
* [Rocket Pool — Staking Protocol Part 1](https://medium.com/rocket-pool/rocket-pool-staking-protocol-part-1-8be4859e5fbd)
* [High on LSD 💊😵 ETH "Liquid Staking Derivatives" War Grows](https://www.youtube.com/watch?v=9gGuSEkizT0)
* [The Future of Liquid Staking by Vasiliy Shapovalov | Devcon Bogotá](https://www.youtube.com/watch?v=AZzEX_tl4QU)
* [Treatise of the Great $sETH 🙏](https://curve.substack.com/p/january-17-2023-treatise-of-the-great)
* [Rocketpool.community](https://rocketpool.community/resources/)
* [Arkham's Liquid Staking Derivatives analysis](https://twitter.com/ArkhamIntel/status/1612880801502461952)
* [How to Build a Decentralized Ethereum Liquid Staking Protocol? by Darren Langley | Devcon Bogotá](https://www.youtube.com/watch?v=CY_KnhS5Fhc)
* [LSD endgame](https://medium.com/@MarkoInEther/lsd-endgame-dfe5b80fb882)
* [Shanghai Upgrade implications for LSDs](https://twitter.com/RiddlerDeFi/status/1619727324324192257 )
* [swETH token- what is it?](https://twitter.com/swellnetworkio/status/1618728811083997184)
* [How to decentralize LSD Staking](https://twitter.com/superphiz/status/1620423244720537603)
* [dsETH | Liquid Staking Panel](https://twitter.com/indexcoop/status/1621237773654192129)
* [Your weekly liquid staking updates 🧵 Feb 4, 2023](https://twitter.com/macflapd/status/1621488354037747712)
* [Why Rocket Pool is Poised to Take Over in 2023 | The Edge Podcast](https://www.youtube.com/watch?v=8JGGpg8e5FE&t=1s)
* [The State of Staking in January 2023](https://consensys.net/blog/codefi/codefi-staking/the-state-of-staking-in-january-2023/)


## DVT - Distributor-Validator-Technology (DVT)

DVT is a technology primitive that allows an Ethereum PoS Validator to be run on more than one node or machine. This allows a cluster of nodes run by an individual, group, or community of operators to act together as a single validator on Ethereum. Running a validator as a cluster of nodes improves its resiliency while greatly reducing the slashing risk of honest validators, regardless of its size. This makes staking more robust and accessible for all validators. [[*](https://blog.obol.tech/what-is-dvt-and-how-does-it-improve-staking-on-ethereum/)]

* [SSV](https://ssv.network/)
* [Diva](https://divalabs.medium.com/here-comes-the-diva-liquid-staking-powered-by-distributed-validators-9e5c3bd38896) 
* [Obol Network](https://obol.tech/)
* [Stader Labs](https://twitter.com/staderlabs_eth)

### Blogs, Videos, Podcasts

* [[SSV] The Evolution of ETH Staking - Distributed Validator Technology Explained](https://www.youtube.com/watch?v=TV70EgAKkrI)
* [Community Call #26: SSV](https://www.youtube.com/watch?v=vGfD-aGAaiQ)
* [[SSV] Conference - Alon (CEO) ssv.network @ETHStaker Gathering | Devconnect | Amsterdam](https://www.youtube.com/watch?v=uInJN4novoQ)
* [How to Design DVT While Ensuring Non-Correlation | Devcon Bogotá](https://www.youtube.com/watch?v=ZbTerJXs23E&list=PLaM7G4Llrb7zL1YvK2DN4OGT4Kr3fwN__&index=8)
* [EthStaker Presents: Securing Your Rocket Pool Node w/ Mentor](https://www.youtube.com/watch?v=ZqIS0LUdhZ4)
* [Distributed Validators on Eth2 with Obol Network](https://www.youtube.com/watch?v=ruMMjpTSCXw)
* [Gnosis Meetup with DIVA](https://www.youtube.com/watch?v=CLbVto-1Aos)
* [Hudson Sets Up A Rocket Pool Node!](https://www.youtube.com/watch?v=qINfnVPSQ1U)
* [SSV node: Shifu V2. 🎉](https://blog.ssv.network/get-ready-for-shifu-v2-multi-duty-feb-2023-5166753a2c94)
* [DVT landscape part 1 
](https://medium.com/@MarkoInEther/dvt-landscape-part-1-a6ea7bae458b)
* [The future of DVT…🚀](https://medium.com/@MarkoInEther/the-future-of-dvt-dcc4abc9dec1?source=user_profile---------3----------------------------)
* [What is DVT and why do we need it?](https://medium.com/@MarkoInEther/what-is-dvt-and-why-do-we-need-it-1d7b58d1130c)
* [Lido on Ethereum: DVT Pilot with SSV Network](https://blog.lido.fi/ssv-network-pilot/)
* [Sorting out Distributed Validator Technology](https://medium.com/nethermind-eth/sorting-out-distributed-validator-technology-a6f8ca1bbce3)
* [A tour of Verifiable Secret Sharing schemes and Distributed Key Generation protocols.](https://medium.com/nethermind-eth/a-tour-of-verifiable-secret-sharing-schemes-and-distributed-key-generation-protocols-3c814e0d47e1)
* [How to reach consensus with strangers](https://medium.com/nethermind-eth/how-to-reach-consensus-with-strangers-9b57264afd65)
* [Threshold Signature Schemes](https://medium.com/nethermind-eth/threshold-signature-schemes-36f40bc42aca)
* [SSV Developer ecosystem update 2023/02](https://forum.ssv.network/t/ssv-developer-ecosystem-update-2023-02/929)
* [DVStakers](https://www.dvstakers.com)

### Set-up Guides

* [Obol Network - Easy Guide](https://mirror.xyz/0xf3bF9DDbA413825E5DdF92D15b09C2AbD8d190dd/XJ8RU00PsYXaU4A1sRYvu6OSw8aumuAiY9nCEzzTCAg)
* [DV Launchpad Walkthrough - Leader Cluster Configuration](https://www.youtube.com/watch?v=OK6WE8te33Q)
* [Community Guide | @cryptomanufaktur8842 - How To Setup a Node On SSV Testnet V2](https://www.youtube.com/watch?v=X85Sxe9yS5U)
* [Obol key splitting tutorial | DVStakers](https://www.dvstakers.com/dvt-configuration/obol-dvt/validator-keyshares/split-existing-keys)


### Grants

* [SSV Ecosystem Fund & Grant Program](https://ssv.network/get-funded/)
* [Rocketpool Grants/Bounties](https://dao.rocketpool.net/c/grant-bounties/13)
 


---

## What is Beacon Chain?
The Beacon Chain was the name of the original proof-of-stake blockchain that was launched in 2020. It was created to ensure the proof-of-stake consensus logic was sound and sustainable before enabling it on Ethereum Mainnet. Therefore, it ran alongside the original proof-of-work Ethereum. Switching off proof-of-work and switching on proof-of-stake on Ethereum required instructing the Beacon Chain to accept transactions from the original Ethereum chain, bundle them into blocks and then organize them into a blockchain using a proof-of-stake based consensus mechanism. At the same moment, the original Ethereum clients turned off their mining, block propagation and consensus logic, handing that all over to the Beacon Chain.[*](https://ethereum.org/en/upgrades/beacon-chain/#what-is-the-beacon-chain) 

Gnosis runs the same client software as Ethereum, with minor parameter tweaks. As such, Gnosis is a Proof-of-Stake network that uses Ethereum's Beacon Chain consensus.

### Timeline - Ethereum

- [x] The Beacon Chain shipped on December 1, 2020
- [x] Bellatrix Hard-Fork September 6, 2022
- [x] Paris Hard-Fork September 14, 2022
- [x] The Merge September 15, 2022

![](https://i.imgur.com/ReBVtnM.png)

### Timeline - Gnosis Chain

- [x] The Beacon Chain shipped on December 8, 2021
- [x] Bellatrix Hard-Fork November 30, 2022
- [x] The Merge December 8, 2022

#### [HAPPY MERGE EVERYONE 🐼👉👈🐼 ](https://twitter.com/gnosischain/status/1600925552575418369)

Thank you








