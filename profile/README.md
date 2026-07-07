# SECURITY WARNING: Unauthorized "Quantum Quasar" Protocol V4 Fork

**Date:** July 2026  
**Status:** Critical / Active Risk  

The Blackcoin Core Dev team is issuing a formal warning regarding an independent, unauthorized network fork circulating under the name **Blackcoin Quantum Quasar (Protocol V4 / v30.1.0)**

This software introduces radical, unvetted changes to Blackcoin's consensus layer, including a hybrid Argon2id CPU Proof-of-Work lane and an unverified post-quantum migration format. 

### Identified Risks to User Funds:
1. **Wallet Overwrite/Corruption:** Running the unauthorized client binary or Docker container within your existing environment can alter your node's data directory, risking the integrity of your `wallet.dat`.
2. **Irreversible Coin Migration:** The migration paths introduced in the Quantum Quasar code do not align with official mainnet rules. Interacting with these contracts or addresses can result in an permanent loss of asset control.
3. **Network Splitting:** This software does not track the legitimate Blackcoin Proof-of-Stake consensus. Coins moved on that fork will be exposed to replay attacks or left entirely isolated from legitimate exchanges and block explorers.

### Recommended Mitigation Steps for Users & Operators:
* **Isolate Your Node:** If you have experimented with the Quantum Quasar software, completely isolate it from your secure network environments. 
* **Secure Your Keys:** Ensure your official `wallet.dat` file is backed up externally on a separate, air-gapped device.
* **Filter Peers:** Official node operators are advised to reject connections from clients identifying with user-agents tied to the V4/Quantum Quasar build.

The core development team remains committed to the security of the native PoS chain. We are actively contacting infrastructure providers, application catalogs (including Unraid), and exchange partners to ensure this unauthorized software is isolated.


## Hi there 👋 Welcome to the Blackcoin Project!

Blackcoin is a pioneering Proof-of-Stake (PoS) cryptocurrency that focuses on speed, efficiency, and decentralization. The project was originally launched in 2014, and continues to evolve through the contributions of a global community of developers, stakers, and users.

---

### What is Blackcoin?

Blackcoin was one of the first cryptocurrencies to adopt a full Proof-of-Stake mechanism, making it an energy-efficient alternative to Proof-of-Work (PoW) cryptocurrencies. This means that instead of relying on high-power mining operations, Blackcoin uses a staking system, which secures the network and validates transactions.

### Our Mission

We aim to provide a robust, decentralized, and eco-friendly cryptocurrency solution, continuously improving through open collaboration and community feedback.

---

### Contributing to Blackcoin 📚

We welcome contributions from the community! Whether you're a seasoned blockchain developer or just getting started, there are many ways to get involved:

- **Code Contributions**: Help us improve the core codebase by submitting pull requests, fixing bugs, or adding new features.
- **Testing and Bug Reporting**: Identify issues or test new updates in our development branches.
- **Community Support**: Assist with documentation, answer questions on forums, or help new users in the Blackcoin community.

To get started, please check out our [contribution guidelines]([https://github.com/BlackcoinOrg/blackcoin/blob/master/CONTRIBUTING.md](https://github.com/coinblack/blackcoin-more/blob/26.x/CONTRIBUTING.md)).

---

### Documentation and Resources 📚

For developers and users alike, here are some key resources to help you explore Blackcoin:

- [Blackcoin Information](https://blackcoin.org/)
- [Blackcoin More GitHub Repo](https://github.com/coinblack/blackcoin-more)
- [Blackcoin Wallet Download](https://blackcoinmore.org)
- [Block Explorer](https://chainz.cryptoid.info/blk/)

---

### Fun Fact 🍿

The Blackcoin community is known for its innovation and resilience. Whether you're staking coins or contributing code, we always encourage new ideas and fresh perspectives. Oh, and we love discussing blockchain tech over a cup of coffee! ☕️

---

### Join the Discussion 🗣️

Stay up to date with the latest developments and engage with the community:

- [Discord](https://discord.blackcoin.nl)
- [Reddit](https://www.reddit.com/r/blackcoin)
- [Twitter](https://twitter.com/blackcoinorg)

Together, we can achieve mighty things with the power of blockchain technology!

