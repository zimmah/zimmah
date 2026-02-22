# Hi, I'm Zimmah 👋

I've been in crypto since 2013 and writing code since childhood. These days I focus on the intersection of the two — building systems that operate reliably in the fast, adversarial environment of live financial markets.

My current focus is **low-latency market infrastructure in Rust**: async WebSocket clients, real-time order book management, and algorithmic detection of trading opportunities. I care about correctness first — checksums, precise decimal arithmetic, and explicit error handling over convenient shortcuts — and performance second.

---

## What I'm building

### 🦀 [arbitrage-scouter](https://github.com/zimmah/arbitrage-scouter)
Real-time triangular arbitrage detection over Kraken's WebSocket v2 API, built in async Rust with Tokio.

- Maintains live order books for multiple trading pairs, validated against Kraken's CRC32 checksums at depth 10
- Multi-level book walking (VWAP-based) to accurately model price impact and liquidity constraints — not just best bid/ask (WIP)
- Automatic resync on checksum failure via a dedicated mpsc channel
- Terminal UI (ratatui) with live spread display and opportunity tracking

---

## Why crypto

I'm not here for the trading. I'm here because I believe economic freedom is a fundamental issue: that people should have sovereignty over their own money without depending on institutions that may not have their interests at heart.

Decentralisation isn't just a technical property to me, it's the point. A financial system that is open, permissionless, and resistant to arbitrary control is genuinely worth building toward. That belief is what drew me into this space a decade ago and it's what keeps me here.

I find that conviction makes me a better engineer in this domain. Understanding *why* these systems matter pushes me to build them properly.

## Stack & interests

**Languages:** Rust · Python · Go · JavaScript/TypeScript · Solidity   
**Domain:** Crypto markets · Exchange infrastructure · WebSocket protocols · Order book mechanics · Web3   
**Interests:** Decentralisation · Financial systems · Protocol design · Open source

---

## Background

Over a decade following and participating in crypto markets gives me context that's hard to get from documentation alone.   
I understand how exchanges behave under stress, why precision matters in financial arithmetic, and what the difference is between a system that works in testing and one that holds up on mainnet.

I'm based in the Netherlands. You can find me as **@zimmah** on most platforms, and on-chain as **zimmah.eth** or **zimmah.ron**.

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
