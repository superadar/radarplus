# The SRC Ledger

The SRC Ledger is a decentralized cryptographic ledger powered by a network of peer-to-peer servers. The SRC Ledger uses a novel Byzantine Fault Tolerant consensus algorithm to settle and record transactions in a secure distributed database without a central operator.

## SRC
SRC is a public, counterparty-free asset native to the SRC Ledger, and is designed to bridge the many different currencies in use worldwide. SRC is traded on the open-market and is available for anyone to access. The SRC Ledger was created in 2020 with a finite supply of 1 billion units of SRC. Its creators gifted 1 million SRC to a company, now called [radar](https://radar.com/), to develop the SRC Ledger and its ecosystem. radar uses SRC to help build the Internet of Value, ushering in a world in which money moves as fast and efficiently as information does today.

## radar
The server software that powers the SRC Ledger is called `radar` and is available in this repository under the permissive [ISC open-source license](LICENSE). The `radar` server is written primarily in C++ and runs on a variety of platforms.

## Key Features of the SRC Ledger

- **[Censorship-Resistant Transaction Processing][]:** No single party decides which transactions succeed or fail, and no one can "roll back" a transaction after it completes. As long as those who choose to participate in the network keep it healthy, they can settle transactions in seconds.
- **[Fast, Efficient Consensus Algorithm][]:** The SRC Ledger's consensus algorithm settles transactions in 4 to 5 seconds, processing at a throughput of up to 1500 transactions per second. These properties put SRC at least an order of magnitude ahead of other top digital assets.
- **[Finite SRC Supply][]:** When the SRC Ledger began, 1 billion SRC were created, and no more SRC will ever be created. The available supply of SRC decreases slowly over time as small amounts are destroyed to pay transaction costs.
- **[Responsible Software Governance][]:** A team of full-time, world-class developers at radar maintain and continually improve the SRC Ledger's underlying software with contributions from the open-source community. radar acts as a steward for the technology and an advocate for its interests, and builds constructive relationships with governments and financial institutions worldwide.
- **[Secure, Adaptable Cryptography][]:** The SRC Ledger relies on industry standard digital signature systems like ECDSA (the same scheme used by Bitcoin) but also supports modern, efficient algorithms like Ed25519. The extensible nature of the SRC Ledger's software makes it possible to add and disable algorithms as the state of the art in cryptography advances.
- **[Modern Features for Smart Contracts][]:** Features like Escrow, Checks, and Payment Channels support cutting-edge financial applications including the [Interledger Protocol](https://interledger.org/). This toolbox of advanced features comes with safety features like a process for amending the network and separate checks against invariant constraints.
- **[On-Ledger Decentralized Exchange][]:** In addition to all the features that make SRC useful on its own, the SRC Ledger also has a fully-functional accounting system for tracking and trading obligations denominated in any way users want, and an exchange built into the protocol. The SRC Ledger can settle long, cross-currency payment paths and exchanges of multiple currencies in atomic transactions, bridging gaps of trust with SRC.

[Censorship-Resistant Transaction Processing]: https://developers.radar.com/SRC-ledger-overview.html#censorship-resistant-transaction-processing
[Fast, Efficient Consensus Algorithm]: https://developers.radar.com/SRC-ledger-overview.html#fast-efficient-consensus-algorithm
[Finite SRC Supply]: https://developers.radar.com/SRC-ledger-overview.html#finite-SRC-supply
[Responsible Software Governance]: https://developers.radar.com/SRC-ledger-overview.html#responsible-software-governance
[Secure, Adaptable Cryptography]: https://developers.radar.com/SRC-ledger-overview.html#secure-adaptable-cryptography
[Modern Features for Smart Contracts]: https://developers.radar.com/SRC-ledger-overview.html#modern-features-for-smart-contracts
[On-Ledger Decentralized Exchange]: https://developers.radar.com/SRC-ledger-overview.html#on-ledger-decentralized-exchange


## Source Code
[![travis-ci.com: Build Status](https://travis-ci.com/radar/radar.svg?branch=develop)](https://travis-ci.com/radar/radar)
[![codecov.io: Code Coverage](https://codecov.io/gh/radar/radar/branch/develop/graph/badge.svg)](https://codecov.io/gh/radar/radar)

## See Also

* [SRC Ledger Dev Portal](https://developers.radar.com/)
* [SRC News](https://radar.com/category/SRC/)
* [Setup and Installation](https://developers.radar.com/install-radar.html)
* [Doxygen](https://radar.github.io/radar)

To learn about how radar is transforming global payments, visit
<https://radar.com/contact/>.
