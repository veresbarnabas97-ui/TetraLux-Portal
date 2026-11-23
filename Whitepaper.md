# 💎 TetraLux ($TLX) — Official Whitepaper (2027 v3.0 Edition)
### Solana Web3 DeFi Liquidity, Smart NFTs & Digital Lore Ecosystem
### Hivatalos Technikai Dokumentáció (Angol / Magyar)

---

* **Version / Verzió:** `2027.3.0-OFFICIAL`
* **Network / Hálózat:** Solana Mainnet (SPL Token Standard)
* **Smart Contract Address (CA):** `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`
* **Treasury & Vault Address:** `4iubzdpP14Mo32iRseD7nZEhP1RVLWjjwbsh228uBk3z`
* **Official Portal:** https://veresbarnabas97-ui.github.io/TetraLux-Portal/
* **Solscan Explorer:** https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3
* **Official Channels:** [Telegram Channel (@TetraLux00)](https://t.me/TetraLux00) | [Community Chat](https://t.me/+iWnFqlxTK6Y5ZTQ8) | [24/7 Bot (@TetraLuxBot)](https://t.me/TetraLuxBot) | [X / Twitter (@TetraL4212)](https://x.com/TetraL4212)

---

## 🇬🇧 PART I — ENGLISH SPECIFICATION

### 1. Executive Summary
**TetraLux ($TLX)** is a transparent, deflationary Web3 ecosystem built on the Solana blockchain. Designed to eliminate common DeFi vulnerabilities—such as hidden minting privileges and unlocked liquidity—TetraLux combines **verifiable on-chain liquidity locks**, a **100-piece smart-contract-backed NFT collection (TetraDiamond)**, and **token-gated digital media (TetraComics)** into a unified, real-time synchronized infrastructure.

### 2. Core Ecosystem Architecture (Three Pillars)

#### Pillar 1: TetraLux Token ($TLX) & Dual-Pool DeFi Liquidity
* **Zero Inflation Guarantee:** The SPL Token `Mint Authority` has been permanently revoked on-chain. No additional `$TLX` tokens can ever be minted.
* **Dual Raydium AMM Pools:** `$TLX` trades permissionlessly on Raydium and Jupiter Aggregator across two primary pairs:
  * **SOL / TLX Pool:** [Swap SOL → TLX](https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  * **USDC / TLX Pool:** [Swap USDC → TLX](https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  * **Liquidity Provision:** [Add Liquidity on Raydium](https://raydium.io/liquidity-pools/?token=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)

#### Pillar 2: TetraDiamond NFT Collection (`#001 – #100`)
* **Strict Scarcity:** Limited to exactly **100 serialized digital assets** (`DIAMOND #001` through `DIAMOND #100`).
* **On-Chain Anchor Vault (`tetradiamond_nft_vault`):**
  * **Mint Entry Price:** Fixed at **$10.00 USD** equivalent in SOL.
  * **90-Day Hold Protocol:** Upon minting, an on-chain `DiamondCertificate` PDA records the ownership timestamp and initiates a **90-day (`7,776,000 seconds`)** unlisted holding period.
  * **Guaranteed +10% Yield:** Holders who keep their TetraDiamond NFT unlisted in their original wallet for 90 days automatically qualify to claim a guaranteed **+10% (`$1.00 USD` equivalent in `$TLX`)** reward from the on-chain Reward Vault PDA.
* **Ecosystem Utilities:**
  * Tiered Staking & LP reward boost multipliers.
  * VIP early access to TetraComics chapters.
  * DAO governance voting weight and priority holder airdrop eligibility.

#### Pillar 3: TetraComics (4-Part Original Web3 Series)
* **Concept & Lore:** A four-chapter sci-fi/Web3 illustrated comic series (*Part I: Genesis & The Code*, *Part II: 100 Diamonds*, *Part III: 3x Shield Lock*, *Part IV: 2027 Mega Burn*) currently in active production.
* **Direct Token Utility:** Upon release, the complete 4-part digital bundle unlocks exclusively for **$5.00 USD worth of `$TLX`**, verified automatically on-chain via `@TetraLuxBot` (`/verify_comic`), creating sustained organic demand for `$TLX`.

---

### 3. Liquidity Security & 2027 v3.0 Evolution

#### Phase A: Verified Genesis Locks (Active until December 7, 2026)
All initial liquidity pool tokens and strategic reserves are publicly locked on StakePoint:

| Lock ID | Asset / Pair | Locked Amount | On-Chain Verification Link |
| :--- | :--- | :--- | :--- |
| **Lock #1** | `TLX-USDC LP` | `112.29 LP` | [Verify on StakePoint ↗](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570) |
| **Lock #2** | `TLX-WSOL LP` | `750.00 LP` | [Verify on StakePoint ↗](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr) |
| **Lock #3** | `TLX Reserve` | `2,000,000 TLX` | [Verify on StakePoint ↗](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw) |

#### Phase B: 2027 v3.0 Symmetrical Relock Architecture (`4,000,000 TLX`)
Following the scheduled unlock window after December 7, 2026, TetraLux transitions into its symmetrical **2027 v3.0 Liquidity Architecture**, locking a total of **4,000,000 TLX** across three pillars:
1. **SOL–TLX Pool Lock:** `1 SOL : 1,000,000 TLX`
2. **USDC–TLX Pool Lock:** `USD Equivalent of 1 SOL in USDC : 1,000,000 TLX` (arbitrage-free parity)
3. **Strategic Reserve Lock:** `2,000,000 TLX` re-locked via StakePoint smart contract

#### Phase C: 2027 Mega Burn Event (`+33.3%` Equilibrium Surge)
Immediately following the `4,000,000 TLX` v3.0 relock, **25% of the circulating token supply** is scheduled for permanent on-chain burn. Under constant market capitalization, reducing supply by 25% yields a mathematical equilibrium price multiplier of:

$$\text{Multiplier} = \frac{100\%}{100\% - 25\%} = \frac{100}{75} \approx 1.3333\times \quad (+33.3\%)$$

### 4. Real-Time Synchronized Infrastructure
Both the official Web3 Portal (`TetraLux-Portal`) and the 24/7 Railway-hosted Telegram Assistant (`@TetraLuxBot`) share a unified state layer (`ecosystem.json`) and live DexScreener / Solana Mainnet RPC feeds, ensuring consistent pricing, NFT mint verification, and progress tracking in English and Hungarian.

---
---

## 🇭🇺 II. RÉSZ — MAGYAR NYELVŰ SPECIFIKÁCIÓ

### 1. Vezetői Összefoglaló
A **TetraLux ($TLX)** egy átlátható, deflációs Web3 ökoszisztéma a Solana blokkláncon. A projekt célja, hogy kiküszöbölje a hagyományos DeFi kockázatokat (rejtett tokenkibocsátás, fedezetlen likviditás), és egyetlen valós időben szinkronizált rendszerben egyesítse az **igazolt on-chain likviditási zárolásokat**, a **100 darabos, okosszerződéssel védett TetraDiamond NFT kollekciót**, valamint a **token-alapú TetraComics digitális képregény-univerzumot**.

### 2. Az Ökoszisztéma Három Alappillére

#### 1. Pillér: TetraLux Token ($TLX) és Kettős DeFi Likviditás
* **Zéró Inflációs Garancia:** Az SPL token `Mint Authority` jogosultsága véglegesen visszavonásra került a blokkláncon. Soha többé nem hozható létre új `$TLX` token.
* **Kettős Raydium AMM Pool:** A `$TLX` szabadon kereskedhető a Raydium és a Jupiter felületén két párhuzamos likviditási párral:
  * **SOL / TLX Pool:** [Vásárlás: SOL → TLX](https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  * **USDC / TLX Pool:** [Vásárlás: USDC → TLX](https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  * **Likviditás Hozzáadása:** [Raydium Liquidity Pools](https://raydium.io/liquidity-pools/?token=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)

#### 2. Pillér: TetraDiamond NFT Kollekció (`#001 – #100`)
* **Szigorú Ritkaság:** Összesen **100 egyedi, sorszámozott digitális kártya** (`DIAMOND #001` – `DIAMOND #100`).
* **On-Chain Anchor Vault (`tetradiamond_nft_vault`):**
  * **Fix Belépési Ár:** **$10.00 USD** értékű SOL.
  * **90 Napos Tartási Protokoll:** Minteléskor egy blokklánc-tanúsítvány (`DiamondCertificate` PDA) rögzíti a tulajdonjog kezdetét és elindítja a **90 napos (`7 776 000 másodperces`)** listázásmentes tartási időszakot.
  * **Garantált +10% Hozam:** Azok a tulajdonosok, akik 90 napon keresztül listázás nélkül az eredeti tárcájukban tartják a kártyát, automatikusan jogosulttá válnak a garantált **+10% (`$1.00 USD` értékű `$TLX`)** jutalom lehívására a Reward Vault PDA-ból.
* **Okosfunkciók (Smart Utilities):**
  * Többszintű Staking és LP hozamnövelő szorzók.
  * VIP korai hozzáférés a TetraComics fejezeteihez.
  * Közösségi szavazati jog és elsőbbségi holder airdrop jogosultság.

#### 3. Pillér: TetraComics (4 Részes Eredeti Web3 Képregény)
* **Történet és Felépítés:** Négyrészes sci-fi/Web3 digitális képregénysorozat (*I. Genesis & A Kód*, *II. A 100 Gyémánt*, *III. A 3x Pajzs Zárolás*, *IV. 2027 Mega Burn*), amely jelenleg aktív gyártás alatt áll.
* **Közvetlen Token Utility:** Megjelenés után a teljes 4 részes csomag kizárólag **$5.00 USD értékű `$TLX` tokenért** oldható fel a `@TetraLuxBot` (`/verify_comic`) automatikus blokklánc-ellenőrzőjén keresztül.

---

### 3. Likviditásvédelem és a 2027 v3.0 Evolúció

#### A. fázis: Igazolt Genesis Zárolások (2026. december 7-ig)
Minden kezdeti likviditási pool token és tartalék nyilvánosan zárolva van a StakePoint felületén:

| Zárolás | Eszköz / Pár | Zárolt Mennyiség | On-Chain Igazolás |
| :--- | :--- | :--- | :--- |
| **Lock #1** | `TLX-USDC LP` | `112.29 LP` | [Ellenőrzés StakePointon ↗](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570) |
| **Lock #2** | `TLX-WSOL LP` | `750.00 LP` | [Ellenőrzés StakePointon ↗](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr) |
| **Lock #3** | `TLX Tartalék` | `2 000 000 TLX` | [Ellenőrzés StakePointon ↗](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw) |

#### B. fázis: 2027 v3.0 Szimmetrikus Újrazárolási Architektúra (`4 000 000 TLX`)
A 2026. december 7-i zárolási ciklus lejárta után a TetraLux átáll a szimmetrikus **2027 v3.0 likviditási struktúrára**, amely összesen **4 000 000 TLX** tokent rögzít három pillérben:
1. **SOL–TLX Pool Lock:** `1 SOL : 1 000 000 TLX`
2. **USDC–TLX Pool Lock:** `1 SOL USD-értékének megfelelő USDC : 1 000 000 TLX` (arbitrázsmentes árfolyam-paritás)
3. **Stratégiai Tartalék Lock:** `2 000 000 TLX` ismételt on-chain zárolása StakePoint okosszerződéssel

#### C. fázis: 2027 Mega Burn Esemény (`+33,3%` Egyensúlyi Árfolyamhatás)
A `4 000 000 TLX` v3.0 újrazárolását követően a forgalomban lévő kínálat **25%-a véglegesen elégetésre kerül**. Változatlan piaci kapitalizáció mellett a 25%-os kínálatcsökkenés matematikai egyensúlyi árfolyamszorzója:

$$\text{Szorzó} = \frac{100\%}{100\% - 25\%} = \frac{100}{75} \approx 1.3333\times \quad (+33.3\%)$$

---

### 4. Kockázati Nyilatkozat / Disclaimer
*Cryptocurrency and DeFi assets involve market volatility. Always verify the official Smart Contract Address (`5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`) and Conduct Your Own Research (DYOR).*
*A kriptovaluták és DeFi eszközök árfolyama ingadozhat. Mindig ellenőrizd a hivatalos szerződéscímet (`5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`), és végezz saját kutatást (DYOR).*
