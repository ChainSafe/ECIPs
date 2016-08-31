# EIP (or ECIP)
Ethereum (classic) improvement proposals (EIPs or ECIPs), are technical write-ups that describe suggested changes to the Ethereum Protocol. Finalized proposals agreed up by volunteer client developers, and the users of the Ethereum classic main net blockchain are implemented by Ethereum classic client developers.

People wishing to submit EIPs, start by writing a draft EIP using the [EIP mediawiki template](EIP-0000.mediawiki.           template) and creating a pull request.

Every pull request will be reviewed and discussed by volunteer Ethereum classic client developers and any developers on github willing to contribute their well reasoned opinions. Regardless if there is general agreement you are able to use the information generated from the discussion to create a a second draft. This can be done by either updating the pull request or submitting a new pull request. This process can be repeated (See figure 1) until the volunteer developer community agrees to add the pull request.

![Figure 1: The cyclic process of proposal and review](./process.png
"Figure 1: The process of proposal and review")

Having an EIP within the folder of the repository does not make it a formally accepted standard until its status becomes Active. For a EIP to become Active requires the mutual consent of the community. Those proposing changes should consider that ultimately consent may rest with the consensus of the Ethereum users.

EIPs (or ECIP) grew out of the now hard-forked Ethereum DAO hard-fork (or ETF) repository, the are currently no other differences between Ethereum classic/original main net and and EThereum DAO hard-forked besides the DAO hard-fork but future changes may be added like early defusal of the difficulty bomb.

# Network split

Pushing changes to the protocol without consensus will cause
a network split. The EIP process should not be skipped, as previously done by Ethereum Foundation
developers unilaterally implementing a rushed hard-fork in the most
widely used client creating a network split at block 1920000.

The Ethereum Foundation raised money from the community to work towards
the "mission to promote and support research, development and education
to bring decentralized protocols", and failed when shortly after the DAO
exploit was used Vitalik Buterin announced using the Ethereum Foundation blog that a they had already
unilaterally decided on forking. A [chat log](http://pastebin.com/raw/aMKwQcHR) from an internal chat reveals this decision was made prior to the announcement, and comments like "default behavior of Geth to be pro-fork as per internal discussions" found in DAO hard-fork [pull requests](https://github.com/ethereum/go-ethereum/pull/2814) and the unwillingness to use their own proposal system show the narrative that the Ethereum Foundation followed the will of the community is clearly wrong. What the Ethereum foundation did the opposite of decentralized decesion making decision making. 

Decentralized decesion making is part of the defense in depth security that protects the intergrity of the Ethereum blockchain, it is critical to keep the promise of "applications that run exactly as programmed without any possibility of downtime, censorship, fraud or third party interference."

# Getting started contributing
The sample EIP is the best place to start, the sample was updated for Ethereum use by Martin Becze, it was predominantly derived from the Bitcoin improvement proposal based on the Python improvement proposal system [EIP mediawiki sample](./EIP-0000.mediawiki.sample). Clone/fork the repository and add your EIP to it, then use the provided [EIP mediawiki template](EIP-0000.mediawiki.template). Submit by creating a Pull Request to the Ethereum classic [EIPs repository](./EIPs).

# Current EIPs
| Number        |Title         | Author | Type  | Layer        | Status / Discussion |
| ------------- | ------------ | ------ | ----- | -------------| ------------------- |
| [1](EIPS/EIP-1001.mediawiki)    | Homestead Hard-fork Changes | Vitalik Buterin | Standard | Homestead (hard-fork) | Accepted |
| [2](EIPS/EIP-1002.mediawiki)    | Addition of CALLDEPTH opcode | Martin Holst Swende | Standard | Consensus (hard-fork) | [Draft](https://github.com/ethereum/EIPs/issues/25) |
| [3](EIPS/EIP-1003.mediawiki)    | EIP Classification | Joseph Chow | Meta | | Draft |
| [4](EIPS/EIP-1004.md)    | Gas Usage for `RETURN` and `CALL*` | Christian Reitwiessner | Standard | Consensus (hard-fork) | [Draft](https://github.com/ethereum/EIPs/issues/8) |
| [5](EIPS/EIP-1005.md)    | Renaming Suicide Variable | Hudson Jameson | Meta |  | [Draft](https://github.com/ethereum/EIPs/pull/42) |
| [6](EIPS/EIP-1006.md)    | DELEGATECALL | Vitalik Buterin | Standard | homestead (hard-fork) | [Accepted](https://github.com/ethereum/EIPs/issues/23) |
| [7](EIPS/EIP-1007.md)    | devp2p Forward Compatibility Requirements for Homestead | Felix Lange | Standard | Networking | [Accepted](https://github.com/ethereum/EIPs/pull/49) |
| [8](EIPS/EIP-1008.md)    | Serenity Currency and Crypto Abstraction | Vitalik Buterin | Standard | Serenity feature | Draft |
| [9](EIPS/EIP-1009.md)    | Ethereum Domain Name Service - Specification | Felix Lange | Standard | Informational | Draft |
