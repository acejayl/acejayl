# Hi 👋, I'm Jacob (acejayl)

I ship small, verified fixes to open source projects. Mostly TypeScript/React frontends, Node backends, tests, and docs.

🔭 **How I work:** read the code first, keep the diff minimal, add a test that locks the fix in, and make sure the full suite is green before opening the PR. If I could not run something, I say so in the PR rather than implying I did.

## 🚢 Merged work

- [Micopay/micopay-protocol #366](https://github.com/Micopay/micopay-protocol/pull/366) — removed 7 dead buttons across the chat screens. `tsc --noEmit` clean, full suite green (86/86), vite build OK. Merged by the maintainer the same week it was assigned.
- [agnesnaomiolim-cloud/Stellar-K8s #147](https://github.com/agnesnaomiolim-cloud/Stellar-K8s/pull/147) — developer onboarding and local kind integration testing guide. DCO signed, PR template filled, every command grounded in the repo. Merged September 2026.

## 🔬 Work under review

- [ScrollPrize/villa #1669](https://github.com/ScrollPrize/villa/pull/1669) — in-place zarr recompression now frees chunks and never destroys the only copy. **Independently reproduced by another contributor** on Linux / Python 3.14.7 across zarr 2.18.7 and 3.3.0, including a negative control against `main`.
- [ScrollPrize/villa #1668](https://github.com/ScrollPrize/villa/pull/1668) — use the platform temp dir instead of a hardcoded `/tmp`.
- [ScrollPrize/villa #1545](https://github.com/ScrollPrize/villa/pull/1545) — hardened the ink-detection disk cache against concurrent access.

Each carries a regression test verified to fail against the unfixed tree and pass with the fix.

## 🌱 Currently

Contributing through **Stellar Wave (Drips)**: test fixes, docs alignment, and small bugfixes across Stellar ecosystem repos. Happy to take assigned issues and turn them around quickly.

## 🛠️ Stack

TypeScript / JavaScript, React, Node, Python, some Rust (Soroban), Jest / React Testing Library, pytest, GitHub Actions.
