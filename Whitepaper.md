<div align="center">

# 💎 TetraLux (TLX) — Hivatalos Whitepaper (v1.0)

**Következő generációs, deflációs Web3 DeFi likviditási ökoszisztéma a Solana blokkláncon.**

[![Solana Mainnet](https://img.shields.io/badge/Network-Solana_Mainnet-14F195?style=for-the-badge&logo=solana&logoColor=black)](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
[![Mint Revoked](https://img.shields.io/badge/Mint_Authority-Revoked_(Fix_Kínálat)-10B981?style=for-the-badge&logo=shield&logoColor=white)](https://solscan.io/token/5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3)
[![LP Locked](https://img.shields.io/badge/LP_Locked-3x_StakePoint_Verified-8B5CF6?style=for-the-badge&logo=lock&logoColor=white)](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570)
[![Telegram](https://img.shields.io/badge/Telegram-@TetraLux00-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/TetraLux00)

**Kibocsátás dátuma:** 2026. november 12.  
**Hálózat:** Solana Mainnet (SPL Token)  
**Smart Contract (CA):** `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`  
**Hivatalos Web3 Portál:** [https://veresbarnabas97-ui.github.io/TetraLux-Portal/](https://veresbarnabas97-ui.github.io/TetraLux-Portal/)

</div>

---

## 1. Vezetői Összefoglaló (Executive Summary)

A **TetraLux (TLX)** egy közösségvezérelt, teljes mértékben transzparens és deflációs gazdasági modellre épülő decentralizált pénzügyi (DeFi) ökoszisztéma a Solana blokkláncon. A projekt elsődleges célja, hogy kiküszöbölje a kriptopiacon gyakori biztonsági kockázatokat (mint a készlethígítás vagy a likviditás kivonása), miközben valós idejű Web3 eszközöket, kétcsatornás decentralizált likviditást (**SOL** és **USDC**), NFT-alapú hozamtermelést (**TetraDiamond NFT**) és egy matematikailag megalapozott kínálatcsökkentési stratégiát (**2027 Mega Burn Event**) kínál a tokentulajdonosok számára.

---

## 2. Piaci Probléma és a TetraLux Megoldása

### 2.1. A Piaci Probléma
A decentralizált tőzsdéken (DEX) induló új projektek jelentős része három alapvető hiányossággal küzd:
1. **Inflációs kockázat:** A fejlesztők megtartják a tokenek kibocsátási jogát (*Mint Authority*), így bármikor új tokeneket hozhatnak létre, elértéktelenítve a meglévő tulajdonosok részesedését.
2. **Likviditási sebezhetőség:** Egyetlen kereskedési párra támaszkodnak, a likviditási pool (LP) tokeneket pedig nem zárolják, ami azonnali *rug pull* kockázatot jelent.
3. **Hasznosság (Utility) hiánya:** A legtöbb token nem rendelkezik saját, működő Web3 felülettel, kalkulátorokkal vagy hosszú távú tulajdonosi ösztönzőkkel.

### 2.2. A TetraLux Megoldása
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
| **Blokklánc Hálózat** | Solana Mainnet (SPL Token) |
| **Smart Contract Cím (CA)** | `5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3` |
| **Mint Authority (Új kibocsátás)** | 🚫 **Kikapcsolva (Revoked)** — 100% fix maximális készlet |
| **LP & Token Zárolás** | 🔒 **3x StakePoint On-Chain Lock** (`stakepoint.app`) |
| **Deflációs Esemény** | 🔥 **2027 Mega Burn Event** (Ütemezett kínálatcsökkentés) |

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

## 4. Likviditási Architektúra és Biztonsági Zárolások (Proof of Lock)

### 4.1. Kétcsatornás Raydium DEX Poolok
A TetraLux mind a Solana natív eszközével (**SOL**), mind a vezető dolláralapú stabilcoinnal (**USDC**) közvetlen likviditási párban áll a Raydium AMM és a Jupiter aggregátor felületén:

| Likviditási Pár | Poolban lévő TLX | Párosított Eszköz | Kereskedési Díj (LP-knek) | Státusz |
| :--- | :--- | :--- | :--- | :--- |
| **SOL / TLX** | `750,000 TLX` | `0.75 – 0.93 SOL` | `0.25% / swap` | 🔒 Aktív & Zárolt |
| **USDC / TLX** | `293,250+ TLX` | `43.04+ USDC` | `0.25% / swap` | 🔒 Aktív & Zárolt |

### 4.2. Hitelesített On-Chain Likviditási Napló
| Művelet | Pool Pár | Hozzáadott TLX | Párosított Eszköz | Érték (USD) |
| :--- | :--- | :--- | :--- | :--- |
| **Add Liquidity** | `TLX / USDC` | `+125,300 TLX` | `+19.74 USDC` | `$39.50` |
| **Add Liquidity** | `TLX / USDC` | `+17,950 TLX` | `+2.847 USDC` | `$5.71` |
| **Add Liquidity** | `TLX / USDC` | `+150,000 TLX` | `+20.46 USDC` | `$20.45` |
| **Add Liquidity** | `TLX / SOL` | `+750,000 TLX` | `+0.7500 SOL` | `$67.71` |

### 4.3. Háromszoros StakePoint On-Chain Zárolás (2026. december 7-ig)
A likviditási pool (LP) tokenek és a stratégiai tartalékok a **StakePoint** (`stakepoint.app`) okosszerződéseiben vannak zárolva:
1. **StakePoint Lock #1 (USDC-TLX LP):** `112.29 TLX-USDC LP` zárolva 2026. december 7-ig.  
   🔗 [On-Chain Igazolás #1 (`cmw62o5iy0000l608kgfr77xs`)](https://stakepoint.app/locks/cmw62o5iy0000l608kgfr77xs?t=1794058570)
2. **StakePoint Lock #2 (TLX-WSOL LP):** `750 TLX-WSOL LP` zárolva 2026. december 7-ig.  
   🔗 [On-Chain Igazolás #2 (`cmw6g1zur0000lf08y2zt7tdr`)](https://stakepoint.app/locks/cmw6g1zur0000lf08y2zt7tdr)
3. **StakePoint Lock #3 (Token Tartalék):** `2,000,000 TLX` zárolva 2026. december 7-ig.  
   🔗 [On-Chain Igazolás #3 (`cmw6gvtej0000jx08bpj4h9pw`)](https://stakepoint.app/locks/cmw6gvtej0000jx08bpj4h9pw)

---

## 5. TetraDiamond NFT Kollekció (`#001 – #100`)

A **TetraDiamond NFT** egy szigorúan limitált, összesen **100 egyedi darabból** álló Web3 kollekció, amelynek célja a TetraLux likviditási poolok tőkemélységének közvetlen erősítése és a hűséges támogatók jutalmazása:
* **Kibocsátási mennyiség:** Maximum 100 db (`DIAMOND #001 – #100`)
* **Fix belépési ár (Mint Price):** `$10 in SOL`
* **Tartási követelmény:** 3 hónap (90 nap) listázásmentes tartás a tulajdonos saját Solana tárcájában.
* **Garantált hozam:** **+10% jutalom** (`$1` értékű TLX token Airdrop formájában a 90. nap végén).

---

## 6. Deflációs Gazdasági Modell: A 2027 Mega Burn Event

Mivel a TetraLux okosszerződésén az új tokenek kibocsátása (*Mint Authority*) véglegesen le van tiltva, a kínálat kizárólag csökkenhet. A projekt legfontosabb makrogazdasági eseménye a **2027-es Mega Burn Event**, valamint az azt követő *Buyback & Burn* (visszavásárlási és égetési) ciklusok.

### Matematikai Hatásmechanizmus
Amikor a forgalomban lévő kínálat ($S_0$) egy adott százalékát ($b$) véglegesen elégetik (halott tárcába küldik), a megmaradó kínálat $S_1 = S_0 \times (1 - b)$ lesz. Változatlan piaci kapitalizáció mellett az 1 TLX-re jutó elméleti egyensúlyi árfolyamszorzó ($M$):

$$M = \frac{1}{1 - b}$$

| Égetési Arány (Burn %) | Megmaradó Kínálat | Elméleti Árfolyamszorzó | Árfolyamváltozás |
| :--- | :--- | :--- | :--- |
| **25% Burn** | `75%` | `1.33x` | `+33.3%` |
| **40% Burn** | `60%` | `1.67x` | `+66.7%` |
| **60% Max Burn** | `40%` | `2.50x` | `+150.0%` |

---

## 7. Stratégiai Útvonalterv (Roadmap 2026–2027)

### 🚀 Phase 1: Indítás, Biztonság & Alapok *(Teljesítve — 100% ✅)*
- [x] Solana SPL Smart Contract (`5vxfqnLVETP6xqZAjebckEbRCkwyzHFoDUoBjXhxEqA3`) üzembe helyezése és a *Mint Authority* végleges visszavonása.
- [x] Kettős Raydium DEX likviditási poolok (`SOL/TLX` és `USDC/TLX`) elindítása.
- [x] Háromszoros on-chain likviditás- és tokenzárolás végrehajtása a StakePoint rendszerében.
- [x] Hivatalos interaktív Web3 DeFi Portál (`TetraLux-Portal`) és Telegram közösség (`@TetraLux00`) elindítása.

### 🌐 Phase 2: Közösség, NFT & Likviditás Mélyítés *(Aktív fázis ⚡)*
- [ ] **TetraDiamond NFT (100 db)** kollekció értékesítése 90 napos, +10%-os TLX hozamgaranciával.
- [ ] Közösségi Staking Pool elindítása a StakePoint felületén a hosszú távú tulajdonosok jutalmazására.
- [ ] DEX aggregátorok (DexScreener, Birdeye, DEXTools, GeckoTerminal) teljes körű metaadat-integrációja, valamint CoinGecko és CoinMarketCap listázások.
- [ ] A `SOL/TLX` és `USDC/TLX` likviditási poolok tőkemélységének folyamatos bővítése az árfolyam-csúszás (*slippage*) minimalizálására.

### 🔥 Phase 3: 2027 Mega Burn Event & Deflációs Stratégia *(Célidőszak: 2027 Q1–Q2)*
- [ ] **2027 Mega Burn Event:** Ütemezett, nagyarányú, on-chain igazolt tokenégetés végrehajtása.
- [ ] **Buyback & Burn mechanizmus:** Az ökoszisztéma aktivitásából származó rendszeres visszavásárlási és égetési ciklusok bevezetése.
- [ ] A likviditási pool tokenek zárolási periódusának meghosszabbítása és fokozatos LP-égetési mérföldkövek teljesítése.
- [ ] Exkluzív hűség-airdropok a 2027-es Burn Event előtt csatlakozott likviditásszolgáltatók és aktív közösségi tagok számára.

### 💎 Phase 4: Web3 Ökoszisztéma Bővítés & DAO Governance *(2027 Q2+)*
- [ ] Kiterjesztett Solana DeFi integrációk és optimalizált routing (Jupiter, Orca, Meteora).
- [ ] Stratégiai Web3 partnerkapcsolatok és kereszt-staking (*cross-staking*) lehetőségek más ellenőrzött Solana projektekkel.
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
  <sub>© 2026–2027 TetraLux Token (TLX). Minden jog fenntartva. Solana Web3 Ecosystem.</sub>
</div>
