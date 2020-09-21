# :zap: The Lightning List :zap:

> A collection of the most interesting projects, companies, and tools in the Lightning Network ecosystem.

PRs are welcome!

Search using these tags:

`[tool]` `[company]` `[implementation]` `[wallet]` `[hardware]` `[gui]` `[android]` `[ios]` `[web]` `[local-web]` `[explorer]` `[community]`

## The List

### [ACINQ](https://acinq.co/)

- `[company]`
- "ACINQ is one of the leading companies working on Bitcoin scalability. Together with other members of the community, we are building an open standard for Lightning, a scalable instant payment network for the Bitcoin blockchain."
- ACINQ builds [Eclair](#elcair), Lightning's Scala implementation

### [Balance of Satoshis (bos)](https://github.com/alexbosworth/balanceofsatoshis)

- `[tool]`
- Command line tools for working with [LND](#lnd) balances.

### [Bitcoin Lightning Wallet](https://play.google.com/store/apps/details?id=com.lightning.walletapp)

- `[wallet]` `[android]`
- "This app contains a standalone Bitcoin and Lightning node in a single package. It allows to send and receive regular Bitcoin transactions as well as Lightning payments."

### [Bitrefill](https://www.bitrefill.com/)

- `[company]`
- "Purchase Gift Cards or Mobile Refills from more than 1650 businesses in 170 countries. Get eGifts & pay mobile bills quickly, safely, and privately with Bitcoin and other cryptocurrencies."

### [Blockstream](https://blockstream.com/)

- `[company]`
- "Blockstream is the leading provider of both open-source and commercial Bitcoin technologies. We deliver a range of products and services that make the adoption of Bitcoin and peer-to-peer finance easier than ever."
- Blockstream is building Lightning's C implementation, [c-lightning](#c-lightning)

### [Bluewallet](https://bluewallet.io/)

- `[wallet]` `[android]` `[ios]`
- Bitcoin and Lightning wallet.

### [Breez](https://breez.technology/)

- `[company]` `[wallet]` `[ios]` `[android]`
- "Breez is the simplest, fastest and safest way to spend your bitcoins. Breez aims to drive bitcoin adoption in everyday commerce by providing a seamless Bitcoin usage. All powered by Lightning Network."

### [c-Lightning](https://github.com/ElementsProject/lightning)

- `[implementation]`
- The Lightning protocol written in C.
- Built by [Blockstream](#blockstream).

### [Casa](https://keys.casa/index)

- `[company]` `[wallet]` `[hardware]`
- Builds [Casa Multisig](#casa-multisig), a multisig-based security service, and [Casa Node](#casa-node), a self-contained Bitcoin and Lightning hardware node.

### [chantools](https://github.com/guggero/chantools)

- `[tool]`
- "A loose collection of tools all somehow related to lnd and Lightning Network channels."
- (This set of tools is especially useful for recovering funds after having wallet/node issues.)

### [Elcair](https://github.com/ACINQ/eclair)

- `[implementation]`
- "Eclair (French for Lightning) is a Scala implementation of the Lightning Network."
- Built by [ACINQ](#acinq)

### [Eclair Mobile](https://play.google.com/store/apps/details?id=fr.acinq.eclair.wallet.mainnet2)

- `[wallet]` `[android]`
- "Eclair Mobile is a next generation, Lightning-ready Bitcoin wallet. It can be used as a regular Bitcoin wallet, and can also connect to the Lightning Network for cheap and instant payments."
- Built by [ACINQ](#acinq)

### [Faraday](https://github.com/lightninglabs/faraday)

- `[tool]`
- "Faraday is a suite of tools built to help node operators and businesses run lnd, the leading implementation of the Lightning Network. Faraday’s tools decrease the operational overhead of running a Lightning node and make it easier to build businesses on Lightning. The current features in the Faraday suite provide insight into node channel performance and support for accounting with both on-chain and off-chain reports for lnd."
- Built by [Lightning Labs](#lightning-labs)

### [Globular](https://gitlab.com/inbitcoin/globular)

- `[wallet]` `[android]`
- "The first cross-implementation LN Android remote wallet."

### [HTLC.me](https://htlc.me/)

- `[tool]`
- A simple tool to send and receive Lightning testnet sample payments.

### [Joule](https://lightningjoule.com/)

- `[web]`
- A browser extension-based Lightning node managmenet tool. Supports Chrome, Firefox, Opera, and Brave.

### [Lightning Labs](https://lightning.engineering/)

- `[company]`
- "At Lightning Labs, we develop software that powers the Lightning Network. Our open source, secure, and scalable Lightning systems enable users to send and receive money more efficiently than ever before. We also offer a series of verifiable, non-custodial Lightning-based financial services. We bridge the world of open source software and the next-generation of bitcoin financial software."
- Lightning Labs builds [LND](#lnd), [Lightning Terminal], Lightning Loop, Faraday, and more.

### [Lightning Terminal (LiT)](https://github.com/lightninglabs/lightning-terminal)

- `[local-web]` `[tool]`
- "Lightning Terminal (LiT) is a browser-based interface for managing the off-chain liquidity of your lnd Lightning Network node. It presents a visual representation of your channels and balances, while allowing you to perform submarine swaps via the [Lightning Loop](#lightning-loop) service using a graphical interface. With a bird's eye view of all of your open channels, you can instantly see which ones need your immediate attention."
- Built by [Lightning Labs](#lightning-labs)

### [Lightning Loop](https://lightning.engineering/loop/)

- `[tool]`
- "The easiest way to manage inbound and outbound liquidity on the Lightning Network. Keep your channels open and the funds flowing."
- Built by [Lightning Labs](#lightning-labs)

### [Lightning Network Explorer](https://explorer.acinq.co/)

- `[explorer]`
- "This explorer displays the topology of the Bitcoin Lightning Network and lists all known nodes."
- Built by [ACINQ](#acinq) using [Eclair](#elcair)

### [Lightning Network Faucet](https://faucet.lightning.community/)

- `[tool]`
- "The Testnet Lightning Faucet (TLF) is similar to other existing Bitcoin faucets. However, rather then sending bitcoin directly on-chain to a user of the faucet, the TLF will instead open a payment channel with the target user. The user can then either use their new link to the Lightning Network to facilitate payments, or immediately close the channel (which immediately credits them on-chain like regular faucets)."

### [lncli-web](https://github.com/mably/lncli-web)

- `[local-web]` `[tool]`
- A lightweight web client for [LND](#lnd), written in Node and Angular.

### [LND](https://github.com/lightningnetwork/lnd)

- `[implementation]`
- Lightning's Go implementation, built by [Lightning Labs](#lightning-labs).

### [LND Developer Community Slack](https://lightning.engineering/slack.html)

- `[community]`
- A free Slack community for all your questions and comments on [LND](#lnd by [Lightning Labs](#lightning-labs).

### [LNPay.co](https://lnpay.co)

- `[company]` `[tool]`
- "LNPay.co provides public facing tools for Lightning users/businesses/merchants."

### [Lnrpc](https://github.com/lightningnetwork/lnd/tree/master/lnrpc)

- `[tool]`
- "This lnrpc package implements both a client and server for [LNDs](#lnd) RPC system which is based off of the high-performance cross-platform gRPC RPC framework."

### [Muun](https://muun.com/)

- `[company]` `[wallet]` `[android]` `[ios]`
- A non-custodial Bitcoin and Lightning wallet.

### [Neutrino](https://github.com/lightninglabs/neutrino)

- `[tool]`
- "Neutrino is an experimental Bitcoin light client written in Go and designed with mobile Lightning Network clients in mind."
- Built by [Lightning Labs](#lightning-labs)

### [Overblock](https://www.overblock.dev/)

- `[tool]`
- "Buy fake items using the Lightning network on testnet."

### [Polar](https://github.com/jamaljsr/polar)

- `[tool]` `[local-web]`
- "One-click Bitcoin Lightning networks for local app development & testing."

### [RaspiBlitz](https://github.com/rootzoll/raspiblitz)

- `[tool]` `[hardware]`
- "Build your own Lightning Node on a RaspberryPi with a nice Display."

### [Ride the Lightning (RTL)](https://github.com/Ride-The-Lightning/RTL)

- `[gui]` `[tool]`
- "RTL is a full function, device agnostic, web user interface to help manage lightning node operations. RTL is available on [LND](#lnd), [C-Lightning](#c-lightning) and [Eclair](#elcair) implementations."

### [Spark Wallet](https://github.com/shesek/spark-wallet)

- `[wallet]` `[android]` `[web]`
- "A minimalistic wallet GUI for c-lightning, accessible over the web or through mobile and desktop apps."

### [Square (Square Crypto)](https://twitter.com/sqcrypto)

- `[company]`
- Square's crypto arm. Gives grants to open source software developers among other things.

### [Stekking](https://stekking.com/)

- `[company]`
- Cash back via Lightning when you spend Bitcoin.

### [Strike](https://strike.zaphq.io/)

- `[wallet]` `[ios]` `[android]` `[web]`
- A frictionless onramp from your fiat bank account to Lightning.

### [ThunderHub](https://github.com/apotdevin/thunderhub)

- `[gui]` `[tool]`
- "ThunderHub is an open-source LND node manager where you can manage and monitor your node on any device or browser. It allows you to take control of the lightning network with a simple and intuitive UX and the most up-to-date tech stack."

### [Y'alls](https://yalls.org/)

- `[tool]`
- "Read and write articles, with Lightning Network micropayments."

### [Zap](https://zaphq.io/)

- `[company]`
- Builds [Zap Desktop](#zap-desktop) and [Strike](#strike).

### [Zap Desktop](https://github.com/LN-Zap/zap-desktop)

- `[wallet]` `[android]` `[ios]` `[web]`

### [Zeus](https://zeusln.app/)

- `[wallet]` `[android]` `[gui]`
- An open-source tool to help you manage your Lightning node. Includes sending/receiving payments, managing channels, adjusting fees, and more.

---

## Lightning Investors

Raising funding? These firms and individuals have a history of investing in Lightning-based or Lightning-related companies.

- [Abstract Ventures](https://www.abstractvc.com/)
- [AXA Venture Partners](https://www.axavp.com/)
- [Boost VC](https://www.boost.vc/)
- [Castle Island Ventures](https://www.castleisland.vc/#)
- [Compound](https://compound.vc/) (the VC firm, not the protocol)
- [Craft Ventures](https://www.craftventures.com/)
- [Data Collective](https://www.dcvc.com/) (DCVC)
- [DG Daiwa Ventures](https://dg-daiwa-v.com/en/)
- [Digital Currency Group](https://dcg.co/)
- [DG Ventures](https://dgventures.com/en/)
- [Fabric Ventures](https://www.fabric.vc/)
- [Future Perfect Ventures](https://futureperfectventures.com/)
- [Greenoaks Capital](http://www.greenoakscap.com/)
- [Horizons Ventures](https://www.horizonsventures.com/)
- [Idinvest Partners](https://www.idinvest.com/en)
- [Jack Dorsey](https://twitter.com/jack)
- [Khosla Ventures](https://www.khoslaventures.com/)
- [Lerer Hippeau](https://www.lererhippeau.com/)
- [M13](https://m13.co/)
- [Meltem Demirors](https://twitter.com/Melt_Dem)
- [Morgan Creek Digital](https://www.morgancreekfunds.com/)
- [Mosaic Ventures](https://www.mosaicventures.com/)
- [Pegasus Tech Ventures](https://www.pegasustechventures.com/)
- [Proof of Capital](https://www.crunchbase.com/organization/proof-of-capital)
- [Real Ventures](https://www.realventures.com/)
- [Reid Hoffman](https://twitter.com/reidhoffman)
- [Ribbit Capital](https://ribbitcap.com/)
- [RRE Ventures](https://rre.com/)
- [Serena Ventures](https://www.serenaventures.com/)
- [Slow Ventures](http://www.slow.co/)
- [Square Crypto](https://twitter.com/sqcrypto)
- [Stillmark Ventures](http://stillmark.co/)
- [Tally Capital](https://tallycapital.com/)
