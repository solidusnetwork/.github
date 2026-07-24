<p align="center">
  <img src="https://raw.githubusercontent.com/solidusnetwork/.github/main/profile/solidus_icon.png" alt="Solidus Network" height="120" />
</p>

<h3 align="center">Solidus Network</h3>

<p align="center">
  <em>An identity and wallet protocol designed and built for tomorrow's<br/>true decentralized economy and governance framework of human race.</em>
</p>

<p align="center">
  <a href="https://www.solidus.network">Website</a> &middot;
  <a href="https://docs.solidus.network/resources/whitepaper">Whitepaper</a> &middot;
  <a href="https://docs.solidus.network/resources/protocol-spec">Protocol Spec</a> &middot;
  <a href="https://github.com/solidusnetwork/did-solidus-spec/blob/v0.1.0/SPEC.md">did:solidus Method Spec</a>
</p>

---

**Solidus** replaces centralized identity providers with an open protocol. Built on an original HotStuff-BFT blockchain in Rust with W3C DIDs, Verifiable Credentials, BBS+ selective disclosure, and SD-JWT VC — eIDAS 2.0 / EUDI Wallet compatible.

**Key numbers:**
- **~95% cheaper** than Sumsub-style per-verification KYC via reusable VCs
- **~1.5s finality** via HotStuff BFT consensus
- **9 products live** on testnet
- **1B SLDS** fixed supply — no token is distributed before an audited mainnet

| Repository | Description |
|---|---|
| [**protocol**](https://github.com/solidusnetwork/protocol) | Original blockchain — HotStuff BFT consensus in Rust |
| [**sdk**](https://github.com/solidusnetwork/sdk) | TypeScript SDK — [`@solidus-network/sdk`](https://www.npmjs.com/package/@solidus-network/sdk) (plus `types`, `auth`, `bbs`) |
| [**did-solidus-spec**](https://github.com/solidusnetwork/did-solidus-spec) | The `did:solidus` DID Method Specification — [registered in the W3C DID Method Registry](https://github.com/w3c/did-extensions/blob/main/methods/solidus.json) |

**Products** — [Verify](https://verify.solidus.network) (KYC-as-a-Service — document verification + BBS+ issuance) &middot; [Identity](https://identity.solidus.network) (self-sovereign identity — DIDs, credentials, OIDC bridge). Source is not public.

Public docs at <https://docs.solidus.network>. Public testnet RPC at <https://rpc.solidus.network>.

<sub>Built with Rust, TypeScript, Ed25519, BLAKE3, BLS12-381, BBS+ on BLS12-381, and a vision for sovereign identity.</sub>
