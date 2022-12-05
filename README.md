# Metaverse-Anti-Cheat
[![](https://img.shields.io/badge/license-MIT-brightgreen)](LICENSE)

### Summary

This is a robust, flexible and scalable solution that prevents scenarios where a user is able to cheat in a digital world.
The solution is a contribution to the Tezos developer community - it's open source (MIT license)

![Metaverse_AntiCheat_Demo1](https://user-images.githubusercontent.com/2120817/205599045-5d3c278b-5b8e-4fdf-87a7-23bf3ce6057c.gif)

### Live Demo

https://metaverse-anti-cheat.netlify.app/ 

This is an implementation of Metaverse-Anti-Cheat with Flexcrow. It has been tested on testnet and is now deployed on mainnet. It requires .1 tez to play and winner gets .2 tez. Test the system by clicking the [JS Injection Cheat] button during gameplay.

### White Paper

https://blockchain-alchemy.gitbook.io/metaverse-anti-cheat-whitepaper/

### Concept
Metaverse Anti-Cheat addresses the most common vulnerabilities in blockchain gaming. It secures the vulnerability of JS injection, where an attacker will get between the game and web layer to spoof win scenarios.

### UI and UX

Metaverse Anti-Cheat is designed to work with [Flexcrow](https://github.com/Blockchain-Alchemy/Flexscrow), it uses best practices in UX, by implementing the [MUI  framework](https://mui.com/) in react and optimized Unity framework. 

### Smart Contracts

Mainnet:
- Escrow: "KT1R2Uo6Q3o4emoPekgbEPs2eQMpqXfravSC"
- uUSD: "KT1XRPEPXbZK25r3Htzp2o1x7xdMMmfocKNW"

JAKARTANET Testnet:
- Escrow: "KT1QqTCsHghND8gfeG55w2pWCskZpFFgjVCV"
- uUSD: "KT1Xf83TTyDDxYxr1x2jKFjHXcCsD4RSnaE5"


### System Diagram
![Metaverse Anti-Cheat Diagram](https://user-images.githubusercontent.com/2120817/205624891-151e4e8f-6519-4f36-917e-273596d98436.png)

### Limitations, Potential Risks and Security Questions

Metaverse Anti-Cheat is created to secure against the most common attack: JS injection, however attackers will find new attacks and this package will be maintained and used actively in the games we publish and deploy.

### Prerequisites
The following dependencies are required to run Flexscrow:

| Dependency | Version             |
| ---------- | ------------------- |
| Node       | `v12.18.4` or above |

### Recommended Use

Metaverse Anti-Cheat is designed to be used with [Flexcrow](https://github.com/Blockchain-Alchemy/Flexscrow) [![](https://img.shields.io/badge/license-MIT-brightgreen)](LICENSE)

### Maintain Support and Future Plans
Metaverse Anti-Cheat  is created to be the Anti-Cheat system we'll be using and updating for all our projects. Some projects that will implement Flexcrow are:
- PiXLtez
- Tez Run
