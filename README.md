# Hi, I'm Priyanshu 👋

**Full-stack engineer, backend-heavy: Go, Node.js/TypeScript, React, Solidity.** I build the backend systems that money moves through (trading engines, ledgers, indexers, L1 protocol code and the smart contracts around them), run the infrastructure they live on, and ship the frontend too.

5 years in production across a regulated tokenization marketplace, two L1 blockchains and an explorer/indexer stack.

- **Backend:** APIs, distributed services, workers and data pipelines in Go and Node.js/TypeScript on PostgreSQL and Redis.
- **Infra & DevOps:** I run production myself: servers, CI/CD and deploy pipelines, Docker and Kubernetes, AWS, monitoring with Prometheus and Grafana. Most of that lives on servers rather than in public repos.
- **Frontend:** React, Next.js and Tailwind. I move fast with AI-assisted development, so I can take a feature end to end. Based in Gurugram, India · open to backend, platform and blockchain roles (on-site or remote).

[Portfolio](https://pri-folio.vercel.app) · [LinkedIn](https://www.linkedin.com/in/priyanshu-rajput) · [dev.to](https://dev.to/priyanshu_2103)

---

## Featured projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| **[charter](https://github.com/pri-3x/charter)** | Runtime authorization and tamper-evident audit for AI agents: policy checks before an agent acts, plus a hash-chained ledger with Ed25519-signed Merkle checkpoints. Ships an MCP server. | TypeScript, PostgreSQL, Docker, Vitest | [usecharter.xyz](https://usecharter.xyz) |
| **[wallet-watcher](https://github.com/pri-3x/wallet-watcher)** | Multi-chain wallet monitoring SaaS (Ethereum, Solana, Polygon, Base, Arbitrum) with alerts and subscription billing via webhooks. | Next.js, Prisma, PostgreSQL, Redis | [Live](https://wallet-watcher-taupe.vercel.app) |
| **PREBELL** | Pump.fun-style launchpad for fictional pre-IPO meme coins, live on Sepolia: bonding-curve contracts (x·y=k, virtual reserves), an indexer with reorg rollback, a REST API and a trading terminal with candles, holders and portfolio P&L. 25 Foundry tests incl. fuzz and invariants. | Solidity, Foundry, Node.js, Fastify, PostgreSQL, Next.js, wagmi/viem | [Live demo](https://prebell.vercel.app) · repo private (client POC) |
| **[Trading Platform](https://github.com/pri-3x/trading-platform)** | Backend for trading tokenized pre-IPO shares: market/limit orders with partial fills, cash/share reservations, idempotent order placement, a per-asset circuit breaker, and portfolio history rebuilt from an **immutable double-entry ledger**. 174 tests, incl. PostgreSQL concurrency tests. | TypeScript, Fastify, PostgreSQL, Drizzle, Zod/OpenAPI, Vitest | [API docs (live)](https://trading-platform-eight-rho.vercel.app/docs) |
| **[enterprise-EVM-network](https://github.com/pri-3x/enterprise-EVM-network)** | Permissioned Ethereum network on Hyperledger Besu with 4 QBFT validators, access-controlled contracts, a Postgres indexer, an explorer and Prometheus/Grafana monitoring. | Besu, Solidity, Hardhat, Fastify, Drizzle, Next.js | |
| **[pong-arena](https://github.com/pri-3x/pong-arena)** | Real-time multiplayer game server on Kubernetes: server-authoritative simulation over WebSockets, Redis pub/sub, Helm + HPA, k6 load tests and chaos scripts. | TypeScript, WebSocket, Redis, PostgreSQL, Kubernetes | |

**Smaller Go projects (learning):** [Go-POW](https://github.com/pri-3x/Go-POW) (proof-of-work chain behind an HTTP API) · [Go-POS](https://github.com/pri-3x/Go-POS) (stake-weighted validator lottery over TCP) · [Gopher-marketplace](https://github.com/pri-3x/Gopher-marketplace) (auth and user microservices: Redis, PostgreSQL/GORM, JWT, Docker Compose). Most of my Go work is in employer L1 codebases (consensus, transaction validation, Cosmos SDK modules), which aren't public.

---

## Experience

- **LCX / Toto Finance**, Software Development Engineer (Jul 2025 – now): led the backend revamp of a regulated real-world-asset tokenization marketplace (listings, orders, on-chain indexing); shipped the airdrop system, a price oracle, and Cardano (Aiken) escrow and minting; own the backend, deploy pipelines and production servers.
- **BlockOn Ventures (Nufi)**, Blockchain Developer (Feb – Jul 2025): built the backend of the [NUFI block explorer](https://scan.nu.finance) with real-time chain indexing; worked on L1 consensus and transaction validation.
- **Redbelly Network**, Software Engineer, core blockchain (Mar 2024 – Feb 2025): Scalable EVM (reconfiguration, block revival, gas module, genesis contracts), node onboarding contract, CI with upgradeability checks, load tests (TPS, latency).
- **Grow Digi**, Core Blockchain Developer (Dec 2022 – Mar 2024): implemented PoS consensus for the JumboChain L1, custom Cosmos SDK modules (Go) and the Jumboscan explorer backend.
- **Queppelin Technologies**, Blockchain Developer (Jan – Dec 2022): ERC-20/721/1155 contracts and dApps.

---

## Toolbox

**Languages:** Go · TypeScript / Node.js · Solidity · Aiken · SQL<br>
**Frontend:** React · Next.js · Tailwind CSS · wagmi / viem<br>
**Backend:** Fastify · Express · REST / OpenAPI · WebSockets · PostgreSQL · Redis · Drizzle / Prisma<br>
**Blockchain:** Ethereum / EVM · Cosmos SDK · Cardano · Hyperledger Besu · Foundry · Hardhat · OpenZeppelin · indexers & explorers<br>
**Infra & DevOps:** AWS · Linux servers · Docker · Kubernetes (Helm, HPA) · CI/CD (GitHub Actions) · Prometheus / Grafana · Render · Vercel

---

<sub>Writing on dev.to: ERC-8004 and x402 · Best way to reach me: LinkedIn.</sub>
