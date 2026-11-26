# 💎 TetraLux (`$TLX`) — Official Whitepaper (2027 v3.0 Edition)
### Solana Web3 DeFi Liquidity, Metaplex Core Smart NFTs & Token-Gated Digital Lore
### Hivatalos Technikai Dokumentáció (English / Magyar)

---

- **Document Version / Verzió:** `2027.3.0-LIVE` (Updated: `2026-11-26`)
- **Blockchain Network / Hálózat:** Solana Mainnet (SPL Token + Metaplex Core + Anchor Framework)
- **TLX Smart Contract Address (CA):** `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`
- **Treasury & Liquidity Wallet:** `4iubzdpP14Mo32iRseD7nZEhP1RVLWjjwbsh228uBk3z`
- **TetraDiamond Collection Mint (Metaplex Core):** `4d7R6FU4E7rrjU8Yfj24ffTNAEBgEVBBCNCdB3BihEKw`
- **TetraDiamond Vault Program ID (Anchor):** `8t4FXwfejW9wypeyUEtTYwq6dqCnk5oEVNcss9cWrtAB`
- **Official Web3 Portal:** https://veresbarnabas97-ui.github.io/TetraLux-Portal/
- **Live Ecosystem Sync Feed:** https://veresbarnabas97-ui.github.io/TetraLux-Portal/ecosystem.json
- **Solscan Explorer:** https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3
- **Official Channels:** [Telegram Channel (`@TetraLux00`)](https://t.me/TetraLux00) | [Community Chat](https://t.me/+iWnFqlxTK6Y5ZTQ8) | [24/7 Assistant (`@TetraLuxBot`)](https://t.me/TetraLuxBot) | [X / Twitter (`@TetraL4212`)](https://x.com/TetraL4212)

---

## 🇬🇧 PART I — ENGLISH SPECIFICATION

### 1. Executive Summary
**TetraLux (`$TLX`)** is a transparent, deflationary Web3 DeFi and digital collectible ecosystem built on the Solana blockchain. Designed to eliminate common decentralized finance vulnerabilities—such as hidden minting privileges and unlocked liquidity—TetraLux integrates **verifiable StakePoint on-chain liquidity locks**, a **100-piece Metaplex Core & Anchor-backed NFT collection (`TetraDiamond`)**, and **token-gated digital media (`TetraComics`)** into a unified, real-time synchronized infrastructure.

### 2. Core Ecosystem Architecture (Three Pillars)

#### Pillar 1: TetraLux Token (`$TLX`) & Dual-Pool DeFi Liquidity
- **Zero-Inflation Guarantee:** The SPL Token `Mint Authority` has been permanently revoked on Solana Mainnet. No additional `$TLX` tokens can ever be created.
- **Dual Raydium AMM & Jupiter Pools:** `$TLX` trades permissionlessly across two primary liquidity pairs, supported by an embedded Jupiter Terminal v3 interface directly on the official Web3 Portal:
  - **SOL / TLX Pool:** [Swap SOL to TLX on Raydium](https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  - **USDC / TLX Pool:** [Swap USDC to TLX on Raydium](https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  - **Jupiter Aggregator Route:** [Trade on Jupiter](https://jup.ag/swap/SOL-5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  - **Liquidity Provision:** [Add Liquidity on Raydium](https://raydium.io/liquidity-pools/?token=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)

#### Pillar 2: TetraDiamond NFT Collection (`#001 – #100`) — LIVE
- **Strict Scarcity:** Strictly capped at **100 serialized digital assets** (`DIAMOND #001` through `DIAMOND #100`) under verified Metaplex Core Collection `4d7R6FU4E7rrjU8Yfj24ffTNAEBgEVBBCNCdB3BihEKw`.
- **Hybrid Metaplex Core & Anchor Vault Architecture:**
  - **Mint Entry Price:** Fixed at **`$10.00 USD`** equivalent in SOL, sent directly to the TetraLux Liquidity Treasury (`4iubzdpP14Mo32iRseD7nZEhP1RVLWjjwbsh228uBk3z`).
  - **Instant Automatic On-Chain Delivery:** Upon payment verification via `@TetraLuxBot` (`/verify_nft`), the backend mints the exact requested Metaplex Core Asset (`CoREENxT6tW1HoK8ypY1SxRMZTcVPm7R94rH4PZNhX7d`) directly to the buyer's Solana wallet.
  - **90-Day Hold Protocol:** The `tetradiamond_nft_vault` Anchor program (`8t4FXwfejW9wypeyUEtTYwq6dqCnk5oEVNcss9cWrtAB`) records a `DiamondCertificate` PDA with a **90-day (`7,776,000 seconds`)** unlisted holding timer.
  - **Guaranteed +10% Yield:** Holders who keep their TetraDiamond NFT unlisted in their original wallet for 90 consecutive days qualify to claim a guaranteed **`+10%` (`$1.00 USD` equivalent in `$TLX`)** reward from the on-chain `RewardVault` PDA.
- **Mainnet Genesis Mint Proof:** Collection minting is officially live on Solana Mainnet (`DIAMOND #001` and `DIAMOND #024` minted; `98 / 100` remaining).
- **Holder Utilities:**
  - Tiered Staking and LP reward boost multipliers.
  - VIP early access to TetraComics chapters.
  - Community governance voting weight and priority holder airdrop eligibility.

#### Pillar 3: TetraComics (4-Part Original Web3 Lore Series)
- **Concept & Chapters:** A four-part sci-fi/Web3 illustrated comic series currently in active production (**75% complete**):
  - *Part I: Genesis & The Code*
  - *Part II: 100 Diamonds*
  - *Part III: 3x Shield Lock*
  - *Part IV: 2027 Mega Burn*
- **Direct `$TLX` Token Utility:** Upon release, the complete 4-chapter digital bundle unlocks exclusively for **`$5.00 USD` worth of `$TLX`**, verified automatically on-chain via SPL token balance inspection (`/verify_comic` in `@TetraLuxBot`), driving recurring organic demand for `$TLX`.

---

### 3. Liquidity Security & 2027 v3.0 Deflationary Architecture

#### Phase A: Verified Genesis Locks (Active until December 7, 2026)
All initial Raydium liquidity pool tokens and strategic reserves are publicly verifiable on StakePoint:

| Lock ID | Asset / Pair | Locked Amount | On-Chain Verification Link |
| :--- | :--- | :--- | :--- |
| **Lock #1** | `TLX-USDC LP` | `112.29 LP` | [Verify on StakePoint](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570) |
| **Lock #2** | `TLX-WSOL LP` | `750.00 LP` | [Verify on StakePoint](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr) |
| **Lock #3** | `TLX Reserve` | `2,000,000 TLX` | [Verify on StakePoint](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw) |

#### Phase B: 2027 v3.0 Symmetrical Relock Architecture (`4,000,000 TLX`)
Following the scheduled unlock window after December 7, 2026, TetraLux transitions into its symmetrical **2027 v3.0 Liquidity Architecture**, locking a total of **`4,000,000 TLX`** across three pillars:
1. **SOL–TLX Pool Lock:** `1 SOL : 1,000,000 TLX`
2. **USDC–TLX Pool Lock:** `USD Equivalent of 1 SOL in USDC : 1,000,000 TLX` (arbitrage-free parity)
3. **Strategic Reserve Lock:** `2,000,000 TLX` re-locked via StakePoint smart contract

#### Phase C: 2027 Mega Burn Event (`+33.3%` Equilibrium Surge)
Immediately following the `4,000,000 TLX` v3.0 relock, **`25%` of the circulating token supply** is scheduled for permanent on-chain burn. Under constant market capitalization ($MC$), reducing circulating supply ($S$) by $25\%$ yields an exact mathematical equilibrium price multiplier:

$$\text{Multiplier} = \frac{100\%}{100\% - 25\%} = \frac{100}{75} \approx 1.3333\times \quad (+33.3\%)$$

### 4. Real-Time Synchronized Infrastructure
The public Web3 Portal (`TetraLux-Portal`) and the 24/7 Railway-hosted Telegram Assistant (`@TetraLuxBot`) share a unified state layer (`ecosystem.json`), persistent volume storage (`/data/bot_state.json`), and live DexScreener / Solana Mainnet RPC feeds, ensuring consistent pricing, NFT serial availability, and comic production tracking in both English and Hungarian.

---
---

## 🇭🇺 II. RÉSZ — MAGYAR NYELVŰ SPECIFIKÁCIÓ

### 1. Vezetői Összefoglaló
A **TetraLux (`$TLX`)** egy átlátható, deflációs Web3 DeFi és digitális gyűjthető eszközökre épülő ökoszisztéma a Solana blokkláncon. A projekt célja, hogy kiküszöbölje a hagyományos DeFi kockázatokat (rejtett tokenkibocsátás, fedezetlen likviditás), és egyetlen valós időben szinkronizált rendszerben egyesítse az **igazolt StakePoint on-chain likviditási zárolásokat**, a **100 darabos, Metaplex Core és Anchor okosszerződéssel védett `TetraDiamond` NFT kollekciót**, valamint a **token-alapú `TetraComics` digitális képregény-univerzumot**.

### 2. Az Ökoszisztéma Három Alappillére

#### 1. Pillér: TetraLux Token (`$TLX`) és Kettős DeFi Likviditás
- **Zéró Inflációs Garancia:** Az SPL token `Mint Authority` jogosultsága véglegesen visszavonásra került a Solana Mainneten. Soha többé nem hozható létre új `$TLX` token.
- **Kettős Raydium AMM és Jupiter Poolok:** A `$TLX` szabadon kereskedhető két párhuzamos likviditási párral, valamint a hivatalos portálba beépített Jupiter Terminal v3 felületen keresztül:
  - **SOL / TLX Pool:** [Vásárlás: SOL → TLX (Raydium)](https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  - **USDC / TLX Pool:** [Vásárlás: USDC → TLX (Raydium)](https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  - **Jupiter Aggregator:** [Kereskedés Jupiteren](https://jup.ag/swap/SOL-5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
  - **Likviditás Hozzáadása:** [Raydium Liquidity Pools](https://raydium.io/liquidity-pools/?token=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)

#### 2. Pillér: TetraDiamond NFT Kollekció (`#001 – #100`) — ÉLES
- **Szigorú Ritkaság:** Összesen **100 egyedi, sorszámozott digitális kártya** (`DIAMOND #001` – `DIAMOND #100`) az igazolt `4d7R6FU4E7rrjU8Yfj24ffTNAEBgEVBBCNCdB3BihEKw` Metaplex Core kollekció alatt.
- **Hibrid Metaplex Core és Anchor Vault Architektúra:**
  - **Fix Belépési Ár:** **`$10.00 USD`** értékű SOL, amely közvetlenül a TetraLux likviditási kincstárba (`4iubzdpP14Mo32iRseD7nZEhP1RVLWjjwbsh228uBk3z`) érkezik.
  - **Azonnali Automatikus On-Chain Kézbesítés:** A `@TetraLuxBot` (`/verify_nft`) tranzakció-ellenőrzése után a rendszer azonnal leminteli a választott Metaplex Core Assetet (`CoREENxT6tW1HoK8ypY1SxRMZTcVPm7R94rH4PZNhX7d`) közvetlenül a vásárló Solana tárcájára.
  - **90 Napos Tartási Protokoll:** A `tetradiamond_nft_vault` Anchor okosszerződés (`8t4FXwfejW9wypeyUEtTYwq6dqCnk5oEVNcss9cWrtAB`) egy blokklánc-tanúsítványt (`DiamondCertificate` PDA) hoz létre **90 napos (`7 776 000 másodperces`)** listázásmentes időzítővel.
  - **Garantált +10% Hozam:** Azok a tulajdonosok, akik 90 napon keresztül listázás nélkül az eredeti tárcájukban tartják a kártyát, automatikusan jogosulttá válnak a garantált **`+10%` (`$1.00 USD` értékű `$TLX`)** jutalom lehívására az on-chain `RewardVault` PDA-ból.
- **Élő Mainnet Igazolás:** A kollekció mintelése aktívan fut a Solana Mainneten (`DIAMOND #001` és `DIAMOND #024` már lemintelve; `98 / 100` elérhető).
- **Okosfunkciók (Smart Utilities):**
  - Többszintű Staking és LP hozamnövelő szorzók.
  - VIP korai hozzáférés a TetraComics fejezeteihez.
  - Közösségi szavazati jog és elsőbbségi holder airdrop jogosultság.

#### 3. Pillér: TetraComics (4 Részes Eredeti Web3 Képregény)
- **Történet és Fejezetek:** Négyrészes sci-fi/Web3 illusztrált képregénysorozat, amely jelenleg aktív gyártás alatt áll (**75%-os készültség**):
  - *I. Rész: Genesis & A Kód*
  - *II. Rész: A 100 Gyémánt*
  - *III. Rész: A 3x Pajzs Zárolás*
  - *IV. Rész: 2027 Mega Burn*
- **Közvetlen `$TLX` Token Utility:** Megjelenés után a teljes 4 részes digitális csomag kizárólag **`$5.00 USD` értékű `$TLX` tokenért** oldható fel a `@TetraLuxBot` (`/verify_comic`) automatikus SPL token egyenleg-ellenőrzőjén keresztül.

---

### 3. Likviditásvédelem és a 2027 v3.0 Evolúció

#### A. fázis: Igazolt Genesis Zárolások (2026. december 7-ig)
Minden kezdeti likviditási pool token és tartalék nyilvánosan zárolva van a StakePoint felületén:

| Zárolás | Eszköz / Pár | Zárolt Mennyiség | On-Chain Igazolás |
| :--- | :--- | :--- | :--- |
| **Lock #1** | `TLX-USDC LP` | `112.29 LP` | [Ellenőrzés StakePointon](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570) |
| **Lock #2** | `TLX-WSOL LP` | `750.00 LP` | [Ellenőrzés StakePointon](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr) |
| **Lock #3** | `TLX Tartalék` | `2 000 000 TLX` | [Ellenőrzés StakePointon](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw) |

#### B. fázis: 2027 v3.0 Szimmetrikus Újrazárolási Architektúra (`4 000 000 TLX`)
A 2026. december 7-i zárolási ciklus lejárta után a TetraLux átáll a szimmetrikus **2027 v3.0 likviditási struktúrára**, amely összesen **`4 000 000 TLX`** tokent rögzít három pillérben:
1. **SOL–TLX Pool Lock:** `1 SOL : 1 000 000 TLX`
2. **USDC–TLX Pool Lock:** `1 SOL USD-értékének megfelelő USDC : 1 000 000 TLX` (arbitrázsmentes árfolyam-paritás)
3. **Stratégiai Tartalék Lock:** `2 000 000 TLX` ismételt on-chain zárolása StakePoint okosszerződéssel

#### C. fázis: 2027 Mega Burn Esemény (`+33,3%` Egyensúlyi Árfolyamhatás)
A `4 000 000 TLX` v3.0 újrazárolását követően a forgalomban lévő kínálat **`25%`-a véglegesen elégetésre kerül**. Változatlan piaci kapitalizáció ($MC$) mellett a $25\%$-os kínálatcsökkenés pontos matematikai egyensúlyi árfolyamszorzója:

$$\text{Szorzó} = \frac{100\%}{100\% - 25\%} = \frac{100}{75} \approx 1.3333\times \quad (+33.3\%)$$

---

### 4. Kockázati Nyilatkozat / Disclaimer
*Cryptocurrency and DeFi assets involve market volatility. Always verify the official Smart Contract Address (`5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`) and Conduct Your Own Research (DYOR).*  
*A kriptovaluták és DeFi eszközök árfolyama ingadozhat. Mindig ellenőrizd a hivatalos szerződéscímet (`5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`), és végezz saját kutatást (DYOR).*