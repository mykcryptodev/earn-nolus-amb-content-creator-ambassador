# Nolus Ambassador — Messaging Framework

Guidelines for consistent, accurate Nolus communication across all platforms.

## Brand Voice

| Do | Don't |
|----|-------|
| Explain mechanics plainly | Use "revolutionary" / "game-changing" without substance |
| Cite specific features (fixed rate, partial liq, IBC) | Promise returns or imply guaranteed outcomes |
| Compare honestly to perps and overcollateralized lending | Attack competitors by name |
| Acknowledge risks (liquidation, market volatility, smart contract risk) | Hide or minimize risk |
| Link to official sources (nolus.io, hub.nolus.io, app.nolus.io) | Share unofficial links or unaudited forks |

**Tone:** Confident educator. Think "helpful DeFi analyst," not "hype account."

---

## Core Value Propositions (Always Accurate)

### 1. DeFi Lease — Asset-Backed Spot Margin

Nolus uses a **lease-based leverage model**: borrowers get up to **150% financing** on initial capital. Positions hold **real underlying tokens**, not synthetic claims. Users retain ownership of the asset throughout the lease.

**Analogy:** Traditional equipment lease — pay a fraction upfront, use the asset for the term, return or buy out at end.

### 2. Fixed Protocol Interest

Borrowing costs are **predictable for the full position lifecycle**. Contrast with perp funding rates that swing with market sentiment.

### 3. Structured Risk Controls

- **Partial liquidations** — only a portion of the position is liquidated, not the full stack
- **EMA oracle pricing** — smoothed price feeds reduce wick-based liquidations
- **MAG (Maximum Allowed Gap)** — additional safeguard against abrupt market moves

### 4. IBC-Native Cross-Chain

Nolus brings **IBC (Inter-Blockchain Communication)** to Solana connectivity. IBC is the battle-tested Cosmos cross-chain standard with **zero bridge hacks to date** in its core design — a credible interoperability story vs. traditional bridge trust assumptions.

### 5. Connected Liquidity Hubs

Liquidity is sourced from interconnected hubs (e.g., **Osmosis DEX**; **Solana via Metis API** coming soon), allowing the margin market to scale without holding all liquidity in-house.

### 6. Security

Audited by **Oak Security** (Nolus Core, Money Market) and **Halborn** (Money Market). Bug bounty program active.

---

## Key Differentiators vs. Alternatives

| Topic | Perpetual DEXs | Overcollateralized Money Markets | Nolus DeFi Lease |
|-------|----------------|----------------------------------|------------------|
| Exposure type | Synthetic / funding-based | Loan against locked collateral | Asset-backed spot margin |
| Cost predictability | Variable funding | Variable utilization rates | Fixed protocol interest |
| Liquidation | Full position common | Full liquidation common | Partial liquidation mechanism |
| Cross-chain | Bridge-dependent | Often single-chain | IBC-native interoperability |

---

## Approved Terminology

| Use | Avoid |
|-----|-------|
| DeFi Lease | "Guaranteed profits" |
| Spot margin | "Risk-free leverage" |
| Asset-backed positions | "Better than every perp DEX" |
| Fixed protocol interest | "Always cheaper" (without context) |
| Partial liquidations | "You can't get liquidated" |
| IBC interoperability | "Zero risk cross-chain" |

---

## Required Disclosures (Include in Long-Form Content)

> DeFi involves smart contract, market, and liquidity risks. Past performance does not guarantee future results. This is educational content, not financial advice. Always DYOR.

---

## Official Links (Always Current)

| Resource | URL |
|----------|-----|
| Website | https://nolus.io/ |
| dApp | https://app.nolus.io/leases |
| Knowledge Hub | https://hub.nolus.io/en/ |
| Discord | https://discord.com/invite/nolus-protocol |
| X | https://twitter.com/NolusProtocol |
| YouTube | https://www.youtube.com/@NolusProtocol |

---

## Content Pillars (Rotate Monthly)

1. **Education** — What is a DeFi Lease? How does spot margin work?
2. **Comparison** — Perps vs. spot margin; bridges vs. IBC
3. **Product** — Walkthroughs of opening/managing positions
4. **Risk** — Honest liquidation and market risk explainers
5. **Ecosystem** — Cross-chain, Osmosis hub, Solana expansion
6. **Community** — AMAs, Discord highlights, user questions answered
