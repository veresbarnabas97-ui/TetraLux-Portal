<div align="center">

<img src="logo.png" alt="TetraLux Official Logo" width="140" />

# 💎 TetraLux (TLX) — Hivatalos Whitepaper (v3.0)

**Következő generációs, deflációs Web3 DeFi likviditási ökoszisztéma a Solana blokkláncon.**

[![Solana Mainnet](https://img.shields.io/badge/Network-Solana_Mainnet-14F195?style=for-the-badge&logo=solana&logoColor=black)](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
[![Mint Revoked](https://img.shields.io/badge/Mint_Authority-Revoked_(Fix_Kínálat)-10B981?style=for-the-badge&logo=shield&logoColor=white)](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
[![LP Locked](https://img.shields.io/badge/LP_Locked-3x_StakePoint_Verified-8B5CF6?style=for-the-badge&logo=lock&logoColor=white)](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570)
[![Telegram](https://img.shields.io/badge/Telegram-@TetraLux00-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/TetraLux00)

**Verzió:** TetraLux v3.0 (MOST & 2027 Stratégiai Kiadás)  
**Kibocsátás dátuma:** 2026. november 12.  
**Hálózat:** Solana Mainnet (SPL Token)  
**Smart Contract (CA):** `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`  
**Hivatalos Web3 Portál:** [https://veresbarnabas97-ui.github.io/TetraLux-Portal/](https://veresbarnabas97-ui.github.io/TetraLux-Portal/)

</div>

---

## 1. Vezetői Összefoglaló (Executive Summary)

A **TetraLux (TLX)** egy közösségvezérelt, teljes mértékben transzparens és deflációs gazdasági modellre épülő decentralizált pénzügyi (DeFi) ökoszisztéma a Solana blokkláncon. A projekt fejlődése két világosan elkülönülő szakaszra épül:
1. **MOST (Genesis Fázis: 2026. 11. 12. – 2026. 12. 07.):** A biztonsági alapok lefektetése véglegesen kikapcsolt *Mint Authority* mellett, kettős Raydium AMM likviditási poolokkal (**SOL** és **USDC**), háromszoros StakePoint on-chain zárolással és a **TetraDiamond NFT** hozamprogrammal.
2. **2027 — TetraLux v3.0 Korszak (2026. 12. 08. után):** A jelenlegi zárolások feloldását követően a likviditási architektúra szimmetrikus, kerekített szintre lép (`1 SOL : 1,000,000 TLX` pool, `USDC : 1,000,000 TLX` pool és `2,000,000 TLX` stratégiai zárolás), amelyet közvetlenül a **+33,3%-os árfolyam-emelkedést célzó Mega Burn Event** követ.

---

## 2. Piaci Probléma és a TetraLux Megoldása

### 2.1. A Piaci Probléma
A decentralizált tőzsdéken (DEX) induló új projektek jelentős része három alapvető hiányossággal küzd:
1. **Inflációs kockázat:** A fejlesztők megtartják a tokenek kibocsátási jogát (*Mint Authority*), így bármikor új tokeneket hozhatnak létre, elértéktelenítve a meglévő tulajdonosok részesedését.
2. **Likviditási sebezhetőség:** Egyetlen kereskedési párra támaszkodnak, a likviditási pool (LP) tokeneket pedig nem zárolják, ami azonnali *rug pull* kockázatot jelent.
3. **Hasznosság (Utility) hiánya:** A legtöbb token nem rendelkezik saját, működő Web3 felülettel, kalkulátorokkal vagy hosszú távú tulajdonosi ösztönzőkkel.

### 2.2. A TetraLux v3.0 Megoldása
* **100% Fix Maximális Kínálat:** A TetraLux okosszerződésén a *Mint Authority* véglegesen visszavonásra (*Revoked*) került, így soha többé nem generálható új TLX token.
* **Háromszoros On-Chain Zárolás (StakePoint):** A likviditási poolok és a tartalék tokenek három különálló, nyilvánosan ellenőrizhető StakePoint okosszerződésben vannak zárolva.
* **Kettős Raydium AMM Likviditás:** Párhuzamos `SOL / TLX` és `USDC / TLX` poolok biztosítják a stabilitást és az azonnali átválthatóságot rejtett adók nélkül.
* **Integrált Web3 Portál és Telegram Ökoszisztéma:** Működő DeFi terminál valós idejű DexScreener API-integrációval, kombinálva a `@TetraLuxBot` automatizált közösségi rendszerével.

---

## 3. Technológiai Architektúra és Web3 Ökoszisztéma

### 3.1. Smart Contract Paraméterek
| Paraméter | Érték / Státusz |
| :--- | :--- |
| **Token Név** | TetraLux Token |
| **Ticker / Szimbólum** | `TLX` |
| **Protokoll Verzió** | `TetraLux v3.0` |
| **Blokklánc Hálózat** | Solana Mainnet (SPL Token) |
| **Smart Contract Cím (CA)** | `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3` |
| **Mint Authority (Új kibocsátás)** | 🚫 **Kikapcsolva (Revoked)** — 100% fix maximális készlet |
| **LP & Token Zárolás** | 🔒 **3x StakePoint On-Chain Lock** (`stakepoint.app`) |
| **Deflációs Esemény** | 🔥 **2027 Mega Burn Event** (+33.3% célzott árfolyamhatás) |

### 3.2. Hivatalos Web3 DeFi Portál (`TetraLux-Portal`)
A projekt központi felülete ([veresbarnabas97-ui.github.io/TetraLux-Portal/](https://veresbarnabas97-ui.github.io/TetraLux-Portal/)) közvetlenül a Solana hálózathoz kapcsolódik, és az alábbi modulokat kínálja:
* **Interaktív DeFi Swap Terminál:** Valós idejű árfolyam-szinkronizáció a DexScreener API-n keresztül (SOL és USDC párokon), állítható csúszási (*slippage*: 0.5%, 1.0%, 2.5%) paraméterekkel és közvetlen Raydium útvonalválasztással.
* **Natív Solana Tárca Integráció:** Közvetlen csatlakozás **Phantom** és **Solflare** Web3 tárcákkal.
* **Likviditási Arány- és Részesedés-kalkulátor:** Segítségével a likviditásszolgáltatók (LP-k) pontosan kiszámíthatják az 50/50 arányú pool-hozzájárulásukat és a várható pool-részesedésüket, amely után minden Raydium swap tranzakcióból **0,25% kereskedési díjban** részesülnek.
* **Staking Hozamszimulátor:** A közösségi staking poolban lekötött TLX tokenek után járó 30 napos (+5%) és évesített (~60% APY) jutalmak előrejelzése.

### 3.3. Telegram Ökoszisztéma és `@TetraLuxBot`
* **Hivatalos Hírcsatorna:** [`@TetraLux00`](https://t.me/TetraLux00)
* **Közösségi Csoport:** [Csatlakozás a közösséghez](https://t.me/+iWnFqlxTK6Y5ZTQ8)
* **Interaktív Telegram Bot:** [`@TetraLuxBot`](https://t.me/TetraLuxBot)

---

## 4. Likviditási Evolúció: „MOST” vs. „2027 TetraLux v3.0”

A TetraLux likviditási stratégiája két ütemben épül fel: a jelenlegi (2026. december 7-ig tartó) kezdeti zárolási szakaszból, valamint a 2026. december 8-i feloldást követő **TetraLux v3.0** szimmetrikus újrazárolásból.

### 4.1. „MOST” — Aktuális Állapot (2026. 11. 12. – 2026. 12. 07.)

| Likviditási Pár / Tartalék | Jelenlegi Mennyiség | Párosított Eszköz | StakePoint Zárolás (2026. dec. 7-ig) |
| :--- | :--- | :--- | :--- |
| **SOL / TLX Pool** | `750,000 TLX` | `0.75 – 0.93 SOL` | 🔒 [Lock #2 (`750 TLX-WSOL LP`)](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr) |
| **USDC / TLX Pool** | `293,250+ TLX` | `43.04+ USDC` | 🔒 [Lock #1 (`112.29 TLX-USDC LP`)](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570) |
| **Stratégiai Tartalék** | `2,000,000 TLX` | Önálló Token Lock | 🔒 [Lock #3 (`2,000,000 TLX`)](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw) |

#### Hitelesített On-Chain Likviditási Napló (Genesis Fázis)
| Művelet | Pool Pár | Hozzáadott TLX | Párosított Eszköz | Érték (USD) |
| :--- | :--- | :--- | :--- | :--- |
| **Add Liquidity** | `TLX / USDC` | `+125,300 TLX` | `+19.74 USDC` | `$39.50` |
| **Add Liquidity** | `TLX / USDC` | `+17,950 TLX` | `+2.847 USDC` | `$5.71` |
| **Add Liquidity** | `TLX / USDC` | `+150,000 TLX` | `+20.46 USDC` | `$20.45` |
| **Add Liquidity** | `TLX / SOL` | `+750,000 TLX` | `+0.7500 SOL` | `$67.71` |

---

### 4.2. „2027” — TetraLux Official NEWS: A v3.0 Likviditási Modell (2026. 12. 08. után)

2026. december 8-án, amikor az első fázis zárolásai feloldódnak, a TetraLux átáll a **v3.0-ás szimmetrikus likviditási modellre**, ahol összesen **4 000 000 TLX** kerül rögzítésre a likviditási poolokban és a tartalék zárolásban:

| v3.0 Pillér | Zárolt TLX Mennyiség | Párosított Eszköz / Arány | v3.0 Státusz (2026. dec. 8-tól) |
| :--- | :--- | :--- | :--- |
| **1. SOL / TLX Pool** | **`1,000,000 TLX`** | **`1.00 SOL`** (`1 : 1,000,000` arány) | 🔒 Újrazárolt LP (Raydium + StakePoint) |
| **2. USDC / TLX Pool** | **`1,000,000 TLX`** | **Dinamikus USDC** *(1 SOL USD-értékével egyező USDC az arbitrázsmentes árfolyamért)* | 🔒 Újrazárolt LP (Raydium + StakePoint) |
| **3. Stratégiai Token Lock** | **`2,000,000 TLX`** | **100% Zárolt TLX Tartalék** | 🔒 StakePoint On-Chain Token Lock |
| **ÖSSZESEN ZÁROLVA:** | **`4,000,000 TLX`** | **Kettős DEX Pool + Stratégiai Lock** | 💎 **TetraLux v3.0 Védelem** |

> **Árfolyam-szinkronizációs elv (Miért dinamikus az USDC oldal?):** Mivel a `SOL / TLX` poolban pontosan `1 SOL` áll szemben `1 000 000 TLX`-szel, az `USDC / TLX` poolban lévő `1 000 000 TLX` mellé az újrazárolás pillanatában érvényes SOL/USD árfolyammal megegyező USDC kerül (pl. $135-os SOL árnál 135 USDC), így mindkét pool azonos bázisáron indul.

---

## 5. TetraDiamond NFT Kollekció (`#001 – #100`)

<div align="center">
  <img src="diamond001.png" alt="TetraDiamond #001 NFT" width="260" />
</div>

A **TetraDiamond NFT** egy szigorúan limitált, összesen **100 egyedi darabból** álló Web3 kollekció, amelynek célja a TetraLux likviditási poolok tőkemélységének közvetlen erősítése és a hűséges támogatók jutalmazása:
* **Kibocsátási mennyiség:** Maximum 100 db (`DIAMOND #001 – #100`)
* **Fix belépési ár (Mint Price):** `$10 in SOL`
* **Tartási követelmény:** 3 hónap (90 nap) listázásmentes tartás a tulajdonos saját Solana tárcájában.
* **Garantált hozam:** **+10% jutalom** (`$1` értékű TLX token Airdrop formájában a 90. nap végén).

---

## 6. Deflációs Gazdasági Modell: A +33,3%-os Mega Burn Event

A december 8-i újrazárolást (`1M + 1M + 2M TLX`) követően lép életbe a **TetraLux v3.0** legfontosabb eseménye: a **Token Égetés (Mega Burn Event)**, amelynek célja egy **+33,3%-os egyensúlyi árfolyam-emelkedés** előidézése.

### Matematikai Hatásmechanizmus
Amikor a kínálat ($S_0$) egy adott százalékát ($b$) véglegesen elégetik (halott tárcába küldik), a megmaradó kínálat $S_1 = S_0 \times (1 - b)$ lesz. Változatlan piaci kapitalizáció mellett az 1 TLX-re jutó elméleti egyensúlyi árfolyamszorzó ($M$):

$$M = \frac{1}{1 - b}$$

A célzott **+33,3%-os emelkedés ($1{,}333\times$ szorzó)** eléréséhez pontosan **25%-os kínálatcsökkentés (Burn)** szükséges:

$$M = \frac{1}{1 - 0{,}25} = \frac{1}{0{,}75} = 1{,}3333 \quad (+33{,}3\%)$$

| Égetési Arány (Burn %) | Megmaradó Kínálat | Elméleti Árfolyamszorzó | Árfolyamváltozás | Státusz |
| :--- | :--- | :--- | :--- | :--- |
| **25% Burn (Elsődleges Cél)** | **`75%`** | **`1.33x`** | **`+33.3%`** | 🎯 **Kijelölt v3.0 Cél** |
| **40% Burn** | `60%` | `1.67x` | `+66.7%` | Másodlagos mérföldkő |
| **60% Max Burn** | `40%` | `2.50x` | `+150.0%` | Hosszú távú plafon |

---

## 7. Stratégiai Útvonalterv (Roadmap: MOST & 2027)

### 🚀 Phase 1: „MOST” — Alapozás, Biztonság & Indítás *(2026. 11. 12. – 2026. 12. 07. ✅)*
- [x] Solana SPL Smart Contract (`5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`) üzembe helyezése és a *Mint Authority* végleges visszavonása.
- [x] Kettős Raydium DEX likviditási poolok (`SOL/TLX` és `USDC/TLX`) elindítása.
- [x] Háromszoros on-chain likviditás- és tokenzárolás végrehajtása a StakePoint rendszerében 2026. december 7-ig.
- [x] Hivatalos interaktív Web3 DeFi Portál (`TetraLux-Portal`), Telegram közösség (`@TetraLux00`) és `@TetraLuxBot` elindítása.
- [x] **TetraDiamond NFT (100 db)** kollekció elindítása 90 napos, +10%-os TLX hozamgaranciával.

### ⚡ Phase 2: Átállás a TetraLux v3.0-ra *(2026. december 8.)*
- [ ] A kezdeti StakePoint zárolások feloldása 2026. december 8-án.
- [ ] **SOL / TLX Pool bővítése és zárolása:** Pontosan `1 SOL : 1,000,000 TLX` arányban.
- [ ] **USDC / TLX Pool bővítése és zárolása:** Pontosan `1,000,000 TLX` + árfolyam-szinkronizált USDC mennyiséggel.
- [ ] **Stratégiai Token Lock:** `2,000,000 TLX` ismételt on-chain zárolása.

### 🔥 Phase 3: 2027 Mega Burn Event (+33,3% Árfolyamhatás) *(2027 Q1)*
- [ ] **Token Égetés (25% Burn):** A +33,3%-os egyensúlyi árfolyam-emelkedést kiváltó on-chain égetés végrehajtása.
- [ ] **Buyback & Burn mechanizmus:** Az ökoszisztéma aktivitásából származó rendszeres visszavásárlási és égetési ciklusok bevezetése.
- [ ] DEX aggregátorok (DexScreener, Birdeye, DEXTools, GeckoTerminal), valamint CoinGecko és CoinMarketCap teljes integráció.

### 💎 Phase 4: Web3 Ökoszisztéma Bővítés & DAO Governance *(2027 Q2+)*
- [ ] Kiterjesztett Solana DeFi integrációk és optimalizált routing (Jupiter, Orca, Meteora).
- [ ] **TetraLux DAO & Governance:** On-chain közösségi szavazási rendszer bevezetése, ahol a TLX birtokosok közvetlenül dönthetnek a további égetési arányokról és fejlesztési irányokról.

---

## 8. Hivatalos Hivatkozások és Ellenőrző Linkek

* 🌐 **Web3 DeFi Portál:** [https://veresbarnabas97-ui.github.io/TetraLux-Portal/](https://veresbarnabas97-ui.github.io/TetraLux-Portal/)
* 📜 **Solana Smart Contract (CA):** `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`
* 🔍 **Solscan Explorer:** [https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
* 🔄 **Raydium Swap (SOL → TLX):** [https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3](https://raydium.io/swap/?inputMint=sol&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
* 💵 **Raydium Swap (USDC → TLX):** [https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3](https://raydium.io/swap/?inputMint=EPjFWdd5AufqSSqeM2qN1xzybapC8G4wEGGkZwyTDt1v&outputMint=5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
* 🔒 **StakePoint Lock #1:** [https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570)
* 🔒 **StakePoint Lock #2:** [https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr)
* 🔒 **StakePoint Lock #3:** [https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw)
* 📢 **Hivatalos Telegram Csatorna:** [https://t.me/TetraLux00](https://t.me/TetraLux00) (`@TETRALUX00`)
* 💬 **Telegram Közösség:** [https://t.me/+iWnFqlxTK6Y5ZTQ8](https://t.me/+iWnFqlxTK6Y5ZTQ8)
* 🤖 **Telegram Bot:** [https://t.me/TetraLuxBot](https://t.me/TetraLuxBot)

---

## 9. Jogi Nyilatkozat és Kockázati Figyelmeztetés (Disclaimer)

A jelen Whitepaper kizárólag tájékoztató jellegű, és nem minősül pénzügyi, befektetési, jogi vagy adózási tanácsadásnak. A kriptovaluták és a decentralizált pénzügyi (DeFi) eszközök magas volatilitással és technológiai kockázattal járnak. Bármilyen vásárlási, likviditásszolgáltatási vagy lekötési döntés meghozatala előtt minden résztvevőnek saját kutatást kell végeznie (**DYOR – Do Your Own Research**).

---
<div align="center">
  <sub>© 2026–2027 TetraLux Token (TLX) v3.0. Minden jog fenntartva. Solana Web3 Ecosystem.</sub>
</div>
