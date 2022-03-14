---
title: Projects
layout: page
---

# Projects

## The Eye of Satoshi [![](../assets/images/python-logo.png)](https://github.com/talaia-labs/python-teos/) [![](../assets/images/rust-logo.png)](https://github.com/talaia-labs/rust-teos/)
The Eye of Satoshi is a Lightning watchtower compliant with BOLT13. There are two implementatios of `teos`, the original (discontinued) python codebase, and the new rust codebase building on top of the [Lightning Dev Kit](https://lightningdevkit.org/).

## Talaia Labs [![](../assets/images/talaia-logo.png)](https://talaia.watch/)
Talaia Labs mission is to work on the security and privacy of the Lightning Network to ensure it can become a global, censorship-resistant and peer-to-peer payment network.

Our current focus is providing an open-source and standardised implementation of Watchtowers which is a fundamental building block that secures the network. This effort is independent of any lightning wallet provider and its main purpose is to allow users to run and hook to standalone towers.


## PISA [![](../assets/images/pisa-logo.png)](https://pisa.watch)

Our focus is building an accountable watching service, PISA, to support off-chain protocols in Bitcoin and Ethereum. Off-chain protocols assume users are always online. We will alleviate this assumption by watching off-chain protocols on behalf of users.

## Bitcoin tools [![](../assets/images/github-logo.png)](https://github.com/sr-gi/bitcoin_tools/)

Bitcoin tools is a Python library created for teaching and researching purposes. It's main objective is twofold. First it 
aims to ease the understanding of Bitcoin transaction creation, by using well-documented and easy to understand
python code. Second, it aims to provide a tool able to create custom `transactions` / `scripts`. Either `scriptSig` and `scriptPubKey` can be built from human readable strings created using `Script` syntax. 

## STATUS [![](../assets/images/github-logo.png)](https://github.com/sr-gi/bitcoin_tools/tree/dev/bitcoin_tools/analysis/status)



**STATUS** (**ST**atistical **A**nalysis **T**ool for **U**txo **S**et) is an open source tool that provides an easy way to access, decode and analyze data from the Bitcoin's `utxo set`.

STATUS is coded in Python 2 and works for both the existing versions of Bitcoin Core's `utxo set`, that is, the first defined format (versions 0.8 - 0.14) and the recently defined one (version 0.15). 

STATUS reads from a LevelDB folder (usually located under `.bitcoin/chainstate`) and parses all the `utxo` entries into a `json` file. From the parsed file, STATUS allows you to perform two type of analysis, a `utxo` based one, and a `transaction` based one, by decoding all the parsed information from the chainstate. 

<!--## Bitcoin network health dashboard [![](../assets/images/grafana-logo.png)](http://charts.satoshi.uab.cat)

The site provides graphs about Bitcoin network health for `mainnet` and `testnet`, such as transaction and block propagation times. Metrics are computed over `inventory messages` received by our custom node, and provide `50th percentile` and `85th percentile` propagation times. Data is obtained using `hyperion`[[code](https://github.com/sr-gi/hyperion)] building on top of a coinscope instance (A. Miller et al. [[paper](http://www.cs.umd.edu/projects/coinscope/coinscope.pdf)][[code](https://github.com/jameslitton/coinscope)]). Our node can be identified by the version string `UAB-Coinscope:0.2`.
-->