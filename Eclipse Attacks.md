# Eclipse Attacks

## Definition
In an eclipse attack, the attacker monopolizes all of the victim’s incoming and outgoing connections, thus isolating the victim from the rest of its peers in the network. The attacker can then filter the victim’s view of the blockchain, force the victim to waste compute power on obsolete views of the blockchain, or coopt the victim’s compute power for its own nefarious purposes. -Eclipse Attacks on Bitcoin’s Peer-to-Peer Network

* underlying this security analysis is the crucial assumption of perfect information; namely, that all members of the bitcoin ecosystem can observe the proofs-of-work done by their peers.

* Each node uses a randomized protocol to select eight peers with which it forms long-lived outgoing connections, and to propagate and store addresses of other potential peers in the network. 

* Nodes with public IPs also accept up to 117 unsolicited incoming connections from any IP address. 



## Countermeasures
Large miners, merchant clients and online wallets have been known to modify bitcoin’s networking code to reduce the risk of network-based attacks. Two countermeasures are typically recommended [3]: (1) disabling incoming connections, and (2) choosing ‘specific’ outgoing connections to well-connected peers or known miners (i.e., use whitelists). However, there are several problems with scaling this to the full bitcoin network. First, if incoming connections are banned, how do new nodes join the network? Second, how does one decide which ‘specific’ peers to connect to? Should bitcoin nodes form a private network? If so, how do they ensure compute power is sufficiently decentralized to prevent mining attacks?

## Reference 
* Eclipse Attacks on Bitcoin’s Peer-to-Peer Network Ethan Heilman
* SoK: P2PWNED — Modeling and Evaluating the Resilience of Peer-to-Peer Botnets
* A survey of attacks on Ethereum smart contracts
* Low-Resource Eclipse Attacks on Ethereum’s Peer-to-Peer Network
* On the Security and Performance of Proof of Work Blockchains
* Enhancing Bitcoin Security and Performance with Strong Consistency via Collective Signing
* Stubborn Mining: Generalizing Selfish Mining and Combining with an Eclipse Attack
* Ethereum Eclipse Attacks

