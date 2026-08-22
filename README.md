# Hi, I'm Zimmah 👋

I've been in crypto since 2013 and writing code since childhood. These days I focus on the intersection of the two: building systems that operate reliably in the fast, adversarial environment of live financial markets.

By day I'm the sole engineer behind a business-critical logistics platform (Node.js, event-driven, Docker/Kubernetes) serving 200+ daily users at a fast-growing transport company, covering backend, frontend, infrastructure, and integrations end to end. By night I build low-latency market infrastructure in Rust: async WebSocket clients, real-time order book management, and algorithmic detection of trading opportunities.

I care about correctness first (checksums, precise decimal arithmetic, and explicit error handling over convenient shortcuts) and performance second.

---

## What I'm building

### 🦀 [arbitrage-scouter](https://github.com/zimmah/arbitrage-scouter)
Real-time triangular arbitrage detection over Kraken's WebSocket v2 API, built in async Rust with Tokio.

- Maintains live order books for multiple trading pairs, validated against Kraken's CRC32 checksums, with automatic resync on checksum failure
- Depth-aware, VWAP-based book walking to model price impact and liquidity constraints instead of naive best bid/ask
- Resilient connection handling: automatic reconnection with backoff, ping/pong monitoring, graceful shutdown across all tasks
- Live terminal UI (ratatui) with spread display and opportunity tracking

Next up: extracting the WebSocket and order book layer into a standalone, publishable crate.

---
## Background
Over a decade of building across fintech and web3: front- and backend work on a European centralized exchange, smart contracts and full-stack development at a DeFi options protocol, data-driven ecosystem analysis at a major web3 gaming company, and more trading bots and market tools than I can count. I was one of the first to reverse-engineer the CryptoKitties genome.

That history means I understand how exchanges behave under stress, why precision matters in financial arithmetic, and what separates a system that works in testing from one that holds up on mainnet.

## Why crypto

I'm not here for the trading. I believe economic freedom is a fundamental issue: people should have sovereignty over their own money without depending on institutions that may not have their interests at heart. Decentralisation isn't just a technical property to me, it's the point. That conviction is what drew me into this space a decade ago, and it pushes me to build these systems properly.

## Stack & interests

**Languages:** Rust · Python · Go · JavaScript/TypeScript · Solidity   
**Domain:** Crypto markets · Exchange infrastructure · WebSocket protocols · Order book mechanics · Event-driven systems   
**Interests:** Decentralisation · Financial systems · Protocol design · Open source

---

I'm based in the Netherlands. You can find me as **@zimmah** on most platforms, and on-chain as **zimmah.eth**.

---

*Always interested in roles and collaborations at the intersection of systems engineering and crypto infrastructure.*

<!--
**zimmah/zimmah** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
