# greg0x

I'm Greg. I build wallets, wire mobile apps to Rust, and work on the plumbing around coding agents.

Currently building **Berek**: multiplayer tooling for people and AI, with shared context across the whole delivery flow. A lot of that work is in private repos; here are some public things you can dig into.

**Code & contributions**

| Project | Some of my work | Dig in |
| --- | --- | --- |
| **Zcash / Zodl** | Shielded voting across native wallets and Rust. Kotlin/JNI recovery state, commitment persistence and share tracking; SwiftUI/TCA orchestration, proof generation and resumable submission. | [Android SDK recovery](https://github.com/zcash/zcash-android-wallet-sdk/pull/1953) · [iOS integration](https://github.com/zodl-inc/zodl-ios/pull/1744) |
| **Taho / Tally Ho** | Ethereum wallet internals: nonce handling across chains, detecting dropped transactions, and cleaning up retrieval state when the expected event never arrives. | [Nonce handling](https://github.com/tahowallet/extension/pull/2516) · [Dropped transactions](https://github.com/tahowallet/extension/pull/2527) |
| **Mobile → Solana ZK** | An end-to-end spike: generate a Groth16 proof in React Native with mopro, convert the proof encoding, and verify it in a Solana program. | [Code + debugging notes](https://github.com/greg0x/zk-solana-mobile-verifier) |
| **Cobold vs Hero** | A public workshop lab: Spring Boot, NestJS and Angular; API/browser checks, Helm/k3s PR previews, and explicit evidence approval before a change is ready. | [Repo](https://github.com/mimukodik/cobold-vs-hero) · [Preview + QA setup](https://github.com/mimukodik/cobold-vs-hero/pull/1) · [Evidence approval](https://github.com/mimukodik/cobold-vs-hero/pull/13) |

The linked PRs are merged contributions. The mobile/Solana project is a proof of concept; Cobold is a workshop environment.

**Things I keep coming back to**

- Get the old system running. Turn its behavior into a spec you can execute against both implementations.
- Give agents a reproducible environment, a small diff, and a way to check the actual user workflow.
- Break the guard once. Make sure the test catches it.

[MI működik](https://mimukodik.hu) · [LinkedIn](https://www.linkedin.com/in/puffancs/)
