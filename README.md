# Multi Party EdDSA signatures
Rust implementation of multiparty Ed25519 signature scheme.

#### Currently supporting:
* [Aggregated Signatures](https://github.com/KZen-networks/multi-party-ed25519/wiki/Aggregated-Ed25519-Signatures)
* [Accountable-Subgroup Multisignatures](https://github.com/KZen-networks/multi-party-schnorr/blob/master/papers/accountable_subgroups_multisignatures.pdf).

The above protocols are for Schnorr signature system. EdDSA is a variant of Schnorr signature system with (possibly twisted) Edwards curves. We adopt the multi party implementations to follow Ed25519 methods for private key and public key generation according to [RFC8032](https://tools.ietf.org/html/rfc8032#section-5.1) 

License
-------
This library is released under the terms of the GPL-3.0 license. See [LICENSE](LICENSE) for more information.

Development Process
-------------------
The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Contact
-------------------
Feel free to [reach out](mailto:github@kzencorp.com) or join the KZen Research [Telegram]( https://t.me/kzen_research) for discussions on code and research.
