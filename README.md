# greg0x

I'm Greg. I build wallets, privacy infrastructure, and tools for people and coding agents to work together.

Currently building **Berek**: people and AI agents working on your company's tasks together. AI does the work, a person decides, and every improvement builds on the last. Runs on infrastructure you control. A lot of that work is in private repos; here are some public things you can dig into.

**Code & contributions**

**ValarGroup / Zcash** — shielded voting across the stack. My contributions span Rust, Go, TypeScript, Swift and Kotlin:

- **Rust / PIR:** fetch, validate and cache PIR-backed nullifier non-membership proofs before delegation. [PIR proof cache](https://github.com/valargroup/zcash_voting/pull/31)
- **Voting chain:** move key-ceremony state into individual voting rounds in the Cosmos SDK chain. [Round lifecycle](https://github.com/valargroup/vote-sdk/commit/5d32b847f3d19e8d4b3488f0cabe0dfc46263e8f)
- **Operator tooling:** signed validator registration, admin approval, service discovery and automated TLS setup. [Registration API](https://github.com/valargroup/vote-shielded-vote-generator-ui/commit/79df7093f0ccf5526ab6a8b4244b8a3c797a9aba) · [Validator setup](https://github.com/valargroup/vote-sdk/commit/588dbf8cd6c57bde74806434f0806ab7f3361c5d)
- **Native wallets / SDKs:** connect voting to iOS and Android through Rust FFI, with persisted state and resumable submission. [Android recovery](https://github.com/zcash/zcash-android-wallet-sdk/pull/1953) · [iOS integration](https://github.com/zodl-inc/zodl-ios/pull/1744)

**Taho / Tally Ho** — Ethereum wallet internals: nonce handling across chains, detecting dropped transactions, and cleaning up retrieval state when the expected event never arrives.

[Nonce handling](https://github.com/tahowallet/extension/pull/2516) · [Dropped transactions](https://github.com/tahowallet/extension/pull/2527)

**Mobile → Solana ZK** — an end-to-end spike: generate a Groth16 proof in React Native with mopro, convert the proof encoding, and verify it in a Solana program.

[Code + debugging notes](https://github.com/greg0x/zk-solana-mobile-verifier)

**Cobold vs Hero** — a public workshop lab: Spring Boot, NestJS and Angular; API/browser checks, Helm/k3s PR previews, and explicit evidence approval before a change is ready.

[Repo](https://github.com/mimukodik/cobold-vs-hero) · [Preview + QA setup](https://github.com/mimukodik/cobold-vs-hero/pull/1) · [Evidence approval](https://github.com/mimukodik/cobold-vs-hero/pull/13)

The linked PRs are merged contributions. The mobile/Solana project is a proof of concept; Cobold is a workshop environment.

**Things I keep coming back to**

- Get the old system running. Turn its behavior into a spec you can execute against both implementations.
- Give agents a reproducible environment, a small diff, and a way to check the actual user workflow.
- Break the guard once. Make sure the test catches it.

[MI működik](https://mimukodik.hu) · [LinkedIn](https://www.linkedin.com/in/puffancs/)
