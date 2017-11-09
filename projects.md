---
title: Projects
layout: page
---

# Projects

## Bitcoin tools [![](../assets/images/github-logo.png)](https://github.com/sr-gi/bitcoin_tools/)

Bitcoin tools is a Python library created for teaching and researching purposes. It's main objective is twofold. First it 
aims to ease the understanding of Bitcoin transaction creation, by using well-documented and easy to understand
python code. Second, it aims to provide a tool able to create custom `transactions` / `scripts`. Either `scriptSig` and `scriptPubKey` can be built from human redable strings created using `Script` sintax. 

## STATUS [![](../assets/images/github-logo.png)](https://github.com/sr-gi/bitcoin_tools/tree/dev/bitcoin_tools/analysis/status)



**STATUS** (**ST**atistical **A**nalysis **T**ool for **U**txo **S**et) is an open source tool that provides an easy way to access, decode and analyze data from the Bitcoin's `utxo set`.

STATUS is coded in Python 2 and works for both the existing versions of Bitcoin Core's `utxo set`, that is, the first defined format (versions 0.8 - 0.14) and the recently defined one (version 0.15). 

STATUS reads from a LevelDB folder (usually located under `.bitcoin/chainstate`) and parses all the `utxo` entries into a `json` file. From the parsed file, STATUS allows you to perform two type of analysis, a `utxo` based one, and a `transaction` based one, by decoding all the parsed information from the chainstate. 