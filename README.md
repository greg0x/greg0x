I'm Greg (Nagy Gergő), a software engineer in Budapest. Most of my recent public work is wallets, privacy infrastructure and mobile ↔ Rust plumbing. Now I help teams make AI useful in their actual work, and I'm building the platform for it.

**Now**

**[MI működik](https://mimukodik.hu)** — my practice. I work inside a team, on their systems: find where the work gets stuck, build what it needs (integrations, automation, AI or a focused application), and help make it part of everyday work. I also run practical AI workshops on tasks that look like the team's daily work; two four-week programs in Hungarian telecommunications so far. The name is Hungarian: "AI works" and "what works?" in one.

**[Berek](https://berek.dev)** — the platform I'm building: people and AI agents working on your company's tasks together. AI does the work, a person decides, and every improvement builds on the last. Runs on infrastructure you control. Early product; I'm looking for 1–3 design partners.

Most of that code is private. The public window into the method is **Cobold vs Hero**, a workshop lab: Spring Boot, NestJS and Angular; API/browser checks, Helm/k3s PR previews, and explicit evidence approval before a change is ready.

[Repo](https://github.com/mimukodik/cobold-vs-hero) · [Preview + QA setup](https://github.com/mimukodik/cobold-vs-hero/pull/1) · [Evidence approval](https://github.com/mimukodik/cobold-vs-hero/pull/13)

**How I work**

- Get the old system running. Turn its behavior into a spec you can execute against both implementations.
- Give agents a reproducible environment, a small diff, and a way to check the actual user workflow.
- Break the guard once. Make sure the test catches it.
- Useful is something you can check. Compare against where you started, and count the review work and the failed attempts too.

**Code and contributions**

Public work you can dig into. Linked PRs and commits are merged; the Solana project is a proof of concept.

**Zcash shielded voting (Valar Group)** — across the stack, in Rust, Go, TypeScript, Swift and Kotlin:

- **Rust / PIR:** fetch, validate and cache PIR-backed nullifier non-membership proofs before delegation. [PIR proof cache](https://github.com/valargroup/zcash_voting/pull/31)
- **Voting chain:** move key-ceremony state into individual voting rounds in the Cosmos SDK chain. [Round lifecycle](https://github.com/valargroup/vote-sdk/commit/5d32b847f3d19e8d4b3488f0cabe0dfc46263e8f)
- **Operator tooling:** signed validator registration, admin approval, service discovery and automated TLS setup. [Registration API](https://github.com/valargroup/vote-shielded-vote-generator-ui/commit/79df7093f0ccf5526ab6a8b4244b8a3c797a9aba) · [Validator setup](https://github.com/valargroup/vote-sdk/commit/588dbf8cd6c57bde74806434f0806ab7f3361c5d)
- **Native wallets / SDKs:** connect voting to iOS and Android through Rust FFI, with persisted state and resumable submission. [Android recovery](https://github.com/zcash/zcash-android-wallet-sdk/pull/1953) · [iOS integration](https://github.com/zodl-inc/zodl-ios/pull/1744)

**Taho / Tally Ho** — Ethereum wallet internals: nonce handling across chains, detecting dropped transactions, and cleaning up retrieval state when the expected event never arrives.

[Nonce handling](https://github.com/tahowallet/extension/pull/2516) · [Dropped transactions](https://github.com/tahowallet/extension/pull/2527)

**Mobile → Solana ZK** — an end-to-end spike: generate a Groth16 proof in React Native with mopro, convert the proof encoding, and verify it in a Solana program.

[Code + debugging notes](https://github.com/greg0x/zk-solana-mobile-verifier)

**Work with me**

[mimukodik.hu](https://mimukodik.hu) · hello@mimukodik.hu · [LinkedIn](https://www.linkedin.com/in/puffancs/)
