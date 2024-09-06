<h1 align="center">
Dogmcoin Core [DOGM]  
<br/><br/>
<img src="https://64.media.tumblr.com/279188bca12976f5d7aa2cfac378a2ef/7fbc8b27b8232f02-96/s540x810/84e9b6e0ac8c3bfaefb5e17d6662ec2f7df96ad2.pnj" alt="Dogmcoin" width="300"/>
</h1>

<div align="center">

</div>

Select language: EN | [CN](./README_zh_CN.md)

Dogmcoin is a split from Dogecoin,This will be a fork of the Dogecoin blockchain.
Dogmcoin is a community-driven cryptocurrency that was inspired by a Shiba Inu meme. The Dogmcoin Core software allows anyone to operate a node in the Dogmcoin blockchain networks and uses the Scrypt hashing method for Proof of Work. It is adapted from Bitcoin Core and other cryptocurrencies.

For information about the default fees used on the Dogmcoin network, please
refer to the [fee recommendation](doc/fee-recommendation.md).

**Website:** [dogmcoin.com](https://dogmcoin.com)

## Usage 💻

To start your journey with Dogmcoin Core, see the [installation guide](INSTALL.md) and the [getting started](doc/getting-started.md) tutorial.

The JSON-RPC API provided by Dogmcoin Core is self-documenting and can be browsed with `dogmcoin-cli help`, while detailed information for each command can be viewed with `dogmcoin-cli help <command>`. Alternatively, see the [Bitcoin Core documentation](https://developer.bitcoin.org/reference/rpc/) - which implement a similar protocol - to get a browsable version.

### Such ports

Dogmcoin Core by default uses port `22171` for peer-to-peer communication that
is needed to synchronize the "mainnet" blockchain and stay informed of new
transactions and blocks. Additionally, a JSONRPC port can be opened, which
defaults to port `22172` for mainnet nodes. It is strongly recommended to not
expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   22171 |   35981 |   46331 |
| RPC      |   22172 |   35982 |   46332 |

## Ongoing development - Moon plan 🌒

Dogmcoin Core is an open source and community driven software. The development
process is open and publicly visible; anyone can see, discuss and work on the
software.

Main development resources:

* [Github Projects](https://github.com/dogmcoin/dogmcoin/projects) is used to
  follow planned and in-progress work for upcoming releases.
* [Github Discussion](https://github.com/dogmcoin/dogmcoin/discussions) is used
  to discuss features, planned and unplanned, related to both the development of
  the Dogmcoin Core software, the underlying protocols and the DOGM asset.  
* [Dogmcoin Reddit](https://www.reddit.com/r/dogmcoin/)

### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

## Contributing 🤝

If you find a bug or experience issues with this software, please report it
using the [issue system](https://github.com/dogmcoin/dogmcoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Please see [the contribution guide](CONTRIBUTING.md) to see how you can
participate in the development of Dogmcoin Core. There are often
[topics seeking help](https://github.com/dogmcoin/dogmcoin/labels/help%20wanted)
where your contributions will have high impact and get very appreciation. wow.

## Communities 🚀🍾

You can join the communities on different social media.
To see what's going on, meet people & discuss, find the lastest meme, learn
about Dogmcoin, give or ask for help, to share your project.

Here are some places to visit:

* [Dogmcoin Bitcointalk](https://bitcointalk.org/index.php?topic=5400580.0)
* [Dogmcoin Reddit](https://www.reddit.com/r/dogmcoin/)
* [Dogmcoin Discord](https://discord.gg/bYsZGSVf6e)
* [Dogmcoin Twitter](https://twitter.com/dogmcoin)

## Very Much Frequently Asked Questions ❓

Do you have a question regarding Dogmcoin? An answer is perhaps already in the
[FAQ](doc/FAQ.md) or the
[Q&A section](https://github.com/dogmcoin/dogmcoin/discussions/categories/q-a)
of the discussion board!

## License - Much license ⚖️
Dogmcoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)
