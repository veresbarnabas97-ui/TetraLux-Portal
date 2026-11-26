# 💎 TetraLux (`$TLX`) 2027 v3.0 — Official Web3 DeFi Portal & Ecosystem

[![Solana Mainnet](https://img.shields.io/badge/Solana-Mainnet-14F195?style=for-the-badge&logo=solana&logoColor=black)](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
[![Mint Authority](https://img.shields.io/badge/Mint_Authority-Revoked-10B981?style=for-the-badge)](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
[![StakePoint Locks](https://img.shields.io/badge/Liquidity-3x_StakePoint_Locked-06B6D4?style=for-the-badge)](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570)
[![TetraDiamond NFT](https://img.shields.io/badge/TetraDiamond_NFT-LIVE_(98%2F100)-A855F7?style=for-the-badge)](https://solscan.io/account/4d7R6FU4E7rrjU8Yfj24ffTNAEBgEVBBCNCdB3BihEKw)

> **Official Web3 Portal:** https://veresbarnabas97-ui.github.io/TetraLux-Portal/  
> **24/7 Telegram Web3 Assistant:** https://t.me/TetraLuxBot (`@TetraLuxBot`)  
> **Official Telegram Channel:** https://t.me/TetraLux00 (`@TetraLux00`)  
> **Community Group:** https://t.me/+iWnFqlxTK6Y5ZTQ8  
> **X / Twitter:** https://x.com/TetraL4212 (`@TetraL4212`)

---

## 📌 Overview / Áttekintés

**TetraLux (`$TLX`) 2027 v3.0** is a decentralized, deflationary Solana Web3 ecosystem combining:
1. **Zero-Inflation SPL Token (`$TLX`)** with permanently revoked `Mint Authority` and dual Raydium AMM liquidity pools (`SOL/TLX` & `USDC/TLX`).
2. **100x TetraDiamond NFT Collection (`#001 – #100`)** powered by **Metaplex Core** and an **Anchor 90-Day Yield Vault** (`$10 USD` in SOL entry -> `90-day` hold -> `+10%` / `$1 USD` in `$TLX` guaranteed yield).
3. **TetraComics 4-Part Digital Lore Series** (currently `75%` in production; unlocks for `$5 USD` worth of `$TLX`).
4. **2027 v3.0 Liquidity & Burn Architecture:** Symmetrical `4,000,000 TLX` relock (`1M SOL-LP + 1M USDC-LP + 2M Reserve`) followed by a `25%` permanent supply burn (`+33.3%` equilibrium price multiplier).

A **TetraLux (`$TLX`) 2027 v3.0** egy transzparens, deflációs Solana Web3 ökoszisztéma, amely valós időben kapcsolja össze a hivatalos DeFi portált (`TetraLux-Portal`), a 0–24 órában futó Railway Web3 Telegram asszisztenst (`@TetraLuxBot`) és a blokkláncos okosszerződéseket.

---

## 🔐 Verified On-Chain Addresses / Igazolt Blokklánc Címek

| Component / Komponens | Network / Standard | Address / Cím | Explorer |
| :--- | :--- | :--- | :--- |
| **TetraLux Token (`$TLX`) CA** | Solana SPL Token | `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3` | [Solscan](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3) |
| **Treasury & Liquidity Wallet** | Solana System Account | `4iubzdpP14Mo32iRseD7nZEhP1RVLWjjwbsh228uBk3z` | [Solscan](https://solscan.io/account/4iubzdpP14Mo32iRseD7nZEhP1RVLWjjwbsh228uBk3z) |
| **TetraDiamond Collection Mint** | Metaplex Core (`mpl-core`) | `4d7R6FU4E7rrjU8Yfj24ffTNAEBgEVBBCNCdB3BihEKw` | [Solscan](https://solscan.io/account/4d7R6FU4E7rrjU8Yfj24ffTNAEBgEVBBCNCdB3BihEKw) |
| **TetraDiamond Vault Contract** | Anchor Program (`0.30.1`) | `8t4FXwfejW9wypeyUEtTYwq6dqCnk5oEVNcss9cWrtAB` | [Solscan](https://solscan.io/account/8t4FXwfejW9wypeyUEtTYwq6dqCnk5oEVNcss9cWrtAB) |

### 🔒 Active StakePoint Locks (Phase A — Active through Dec 7, 2026)
- **Lock #1 (`TLX-USDC LP` — `112.29 LP`):** https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570
- **Lock #2 (`TLX-WSOL LP` — `750.00 LP`):** https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr
- **Lock #3 (`TLX Reserve` — `2,000,000 TLX`):** https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw

---

## 🏗️ Multi-Repository Ecosystem Architecture

The TetraLux infrastructure is modularized across four dedicated repositories synchronized via `ecosystem.json` and Solana Mainnet RPC:

```text
TetraLux Ecosystem
├── TetraLux-Portal (Public — GitHub Pages)
│   ├── index.html            # Bilingual (HU/EN) Web3 Portal, Jupiter v3 Terminal, NFT Mint UI & Burn Simulator
│   ├── ecosystem.json        # Unified live configuration & progress feed synced with @TetraLuxBot
│   ├── Whitepaper.md         # Official English & Hungarian Technical Specification (2027 v3.0)
│   ├── Roadmap.md            # Strategic Execution Plan & On-Chain Milestones (2026–2027)
│   ├── README.md             # Ecosystem Documentation & On-Chain Registry
│   └── DIAMOND/
│       ├── images/           # 001.png – 100.png high-resolution card artwork
│       └── metadata/         # 001.json – 100.json + collection.json Metaplex Core metadata
│
├── TetraLux-Telegram (Private — Railway Cloud Worker)
│   ├── bot.py                # 24/7 Web3 Telegram Assistant, On-Chain Verifier & Metaplex Core Auto-Minter
│   ├── requirements.txt      # python-telegram-bot[job-queue], aiohttp, solders
│   └── Procfile              # Railway worker entrypoint (`worker: python bot.py`)
│
├── TetraDiamondNFT (Solana Anchor & Metaplex Core)
│   ├── Anchor.toml           # Program ID: 8t4FXwfejW9wypeyUEtTYwq6dqCnk5oEVNcss9cWrtAB
│   ├── programs/             # Rust Anchor smart contract (`tetradiamond_nft_vault`)
│   └── scripts/              # Metaplex Core collection/mint scripts & Vault initializer
│
└── TetraComics (In Production — 75% Complete)
    └── Chapters I–IV         # Token-gated 4-part sci-fi/Web3 comic series ($5 USD in $TLX)
```

---

## 🤖 `@TetraLuxBot` Web3 Commands

| Command | Description (EN) | Leírás (HU) |
| :--- | :--- | :--- |
| `/start` | Launch bilingual Web3 dashboard or handle deep links (`mint_XXX`, `claim_XXX`, `presale_X`) | Kétnyelvű Web3 menü vagy közvetlen portál hivatkozások indítása |
| `/price` | Live `$TLX` & `SOL` prices, 24h volume, and pooled liquidity from DexScreener | Élő `$TLX` és `SOL` árfolyam, 24h forgalom és likviditás |
| `/wallet <ADDRESS>` | Register Solana wallet for VIP Whitelist & NFT tracking | Solana tárcacím rögzítése a VIP Whitelisthez |
| `/verify_nft <WALLET> <TX> [001-100]` | Verify `$10` SOL payment on-chain & auto-mint Metaplex Core NFT to buyer wallet | `$10` SOL befizetés igazolása és azonnali automatikus NFT mintelés |
| `/my_nfts` | Check owned TetraDiamond NFTs & 90-day `+10%` `$TLX` yield countdown | Saját TetraDiamond NFT-k és a 90 napos hozam visszaszámlálója |
| `/verify_presale <WALLET> <TX>` | Verify SOL presale deposit (`+15%` `$TLX` bonus) | Presale SOL befizetés hitelesítése (`+15%` `$TLX` bónusz) |
| `/verify_comic <TX>` | Verify `$5 USD` worth of `$TLX` SPL token payment for TetraComics | `$5 USD` értékű `$TLX` fizetés igazolása a képregényhez |

---

## 🔄 Real-Time `ecosystem.json` Synchronization

Both `index.html` and `bot.py` consume `https://veresbarnabas97-ui.github.io/TetraLux-Portal/ecosystem.json` so that updates to comic production progress (`progress_percent`), collection metadata, or official links propagate automatically across the Web3 Portal and Telegram Assistant without requiring frontend code edits.

---

## 🔗 Quick Trade & Analytics Links

- **Buy `$TLX` with SOL (Raydium):** https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3
- **Buy `$TLX` with USDC (Raydium):** https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3
- **Trade on Jupiter Aggregator:** https://jup.ag/swap/SOL-5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3
- **Live Chart (DexScreener):** https://dexscreener.com/solana/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3
- **Live Analytics (Birdeye):** https://birdeye.so/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3?chain=solana