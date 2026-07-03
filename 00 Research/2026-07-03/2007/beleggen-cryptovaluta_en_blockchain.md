# RAW DATA — Beleggen: Cryptovaluta & Blockchain

**Bron:** Model-synthesized knowledge (Wikipedia API niet beschikbaar — networkpolicy 403)
**Status:** RAW DATA — geen interpretatie
**Discipline:** Beleggen
**Datum:** 2026-07-03

---

## Wikipedia-equivalent kerndefinitie

A cryptocurrency is a digital currency designed to work as a medium of exchange through a computer network that is not reliant on any central authority, such as a government or bank, to uphold or maintain it. The first and most widely known is Bitcoin, created in 2009 by the pseudonymous Satoshi Nakamoto.

Blockchain: A distributed ledger technology (DLT) in which records (blocks) are cryptographically linked in a chain, replicated across a peer-to-peer network, making tampering computationally infeasible.

---

## Bitcoin — Basisarchitectuur

**Satoshi Nakamoto, "Bitcoin: A Peer-to-Peer Electronic Cash System" (2008 whitepaper):**
- Probleem: Double-spending zonder centrale autoriteit
- Oplossing: Proof-of-Work consensus + publieke blockchain

**Technische kern:**
- **Proof of Work (PoW):** Mining — cryptografische puzzels oplossen voor blokbeloning
- **UTXO-model:** Unspent Transaction Outputs als state-representatie
- **21 miljoen bitcoin cap:** Ingebakken deflationair schema via halving (~elke 4 jaar halvering blokbeloning)
- **Halving-schema:** 2009: 50 BTC/blok → 2012: 25 → 2016: 12.5 → 2020: 6.25 → 2024: 3.125

---

## Ethereum & Smart Contracts

**Vitalik Buterin (2013 whitepaper, 2015 launch):**
- Turing-complete blockchain — programmeerbare contracten
- **Smart contracts:** Zelfuitvoerende code op gedecentraliseerde computer (EVM)
- **ERC-20:** Tokenstandaard — basis voor ICOs en DeFi
- **ERC-721:** Non-fungible tokens (NFTs)
- **Proof of Stake (PoS):** "The Merge" (september 2022) — overgang van PoW naar PoS, energiereductie ~99.95%

---

## DeFi — Decentralized Finance

**Kernprincipes:**
- Financiële diensten zonder intermediairs (banken, brokers)
- Permissionless: iedereen met wallet kan deelnemen
- Transparant: code openbaar op blockchain

**Protocollen:**
- **Uniswap:** Automated Market Maker (AMM) — pricing via x*y=k algoritme
- **Aave/Compound:** Gedecentraliseerde leningen en kredieten
- **MakerDAO/DAI:** Crypto-gedekte stablecoin
- **Total Value Locked (TVL):** Maatstaf voor DeFi-marktgrootte

---

## Marktkarakteristieken

### Volatiliteit
- Bitcoin historische volatiliteit: 50-100% annualized (aandelen S&P500: ~15-20%)
- Correctionele periodes: -80% bear markets (2014, 2018, 2022)
- Bull-run patronen: Halving-cyclus als hypothetische driver

### Correlaties
- Historisch lage correlatie met traditionele activa (diversificatiepotentieel)
- Na 2020: toenemende correlatie met risicovol activa (tech-aandelen) tijdens risk-off periodes
- "Digital gold"-narratief vs. speculatief asset: ongoing debat

### Marktstructuur
- 24/7 handel (geen beursclosing)
- Hoge liquiditeitsfragmentatie over exchanges
- Whale-concentratie: top 1% adressen bezitten ~27% van Bitcoin supply

---

## Regulering

| Jurisdictie | Status |
|---|---|
| VS | Ongoing SEC vs. CFTC jurisdictiedebat; Bitcoin = commodity, rest = mogelijke securities |
| EU | MiCA (Markets in Crypto Assets) — 2024 volledig van kracht |
| China | Volledig verbod (2021) |
| El Salvador | Bitcoin als wettig betaalmiddel (2021) |
| Japan | Erkend als eigendom, niet als valuta |

**Howey Test (SEC):** Belegging in gemeenschappelijke onderneming met verwachting winst primair via inspanningen van anderen → security. Veel altcoins vallen hieronder.

---

## Gedragseconomische aspecten

### Speculative Bubbles
- Crypto-markten vertonen klassieke bubble-patronen (Hyman Minsky):
  - Displacement → Boom → Euphoria → Profit Taking → Panic
- 2017 ICO-bubbel, 2021 NFT-bubbel, 2022 Terra/Luna-collapse ($40B verdampt in 72 uur)

### FOMO & Herd Behavior
- Sociale media-versterking van kuddegedrag (Twitter, Reddit/r/wallstreetbets)
- Influencer-gestuurd marktgedrag (Elon Musk tweets en Dogecoin)
- Anchoring op ATH (all-time high) — referentiepunt-vertekening

### Loss Aversion & HODLing
- "HODL" (Hold On for Dear Life): Emotionele aanleiding tot niet-rationeel vasthouden
- Sunk cost fallacy in bear markets: 80% downdraws worden vastgehouden

### Dunning-Kruger in decentrale financiering
- Technische complexiteit leidt tot vertrouwen op "experts" en influencers
- Asymmetrische informatie: insiders (devs, whales) vs. retailbeleggers

---

## Institutionele adoptie

- **ETF:** Spot Bitcoin ETF goedgekeurd VS (januari 2024) — BlackRock, Fidelity, etc.
- **MicroStrategy (nu Strategy):** ~2% van Bitcoin supply in bedrijfskas
- **Centrale Bank Digital Currencies (CBDCs):** Overheidsalternatief — e-Euro, e-Yuan in pilot
- **Custody:** Coinbase Custody, Anchorage Digital als institutionele bewaarplaatsen

---

## Verbindingen met bestaande wiki-notes

- → [[Gedragseconomie & Cognitieve Biases]] (FOMO, loss aversion, herding in crypto-markten)
- → [[Marktpsychologie & Beurscrises]] (crypto-crashes als extreme versie van beursbubbels)
- → [[Efficiënte Markt Hypothese]] (crypto als testlab voor EMH — sterke inefficiënties zichtbaar)
- → [[Inflatie & Koopkrachtbescherming]] (Bitcoin als anti-inflatie hedge — discutabel)
- → [[Opties & Derivaten]] (crypto-derivatenmarkt; perpetual futures, options op Deribit)
- → [[Waardebeleggen]] (ontbreekt intrinsieke waarde-basis → challenge voor value-investeerders)
- → [[Hyperbolic Discounting & Tijdspreferentie]] (present bias: snel-rijk-worden vs. langetermijn)
- → [[Sociale Psychologie]] (sociale media en kuddegedrag in crypto-markten)
- → [[Falsifieerbaarheid & Wetenschapsfilosofie]] (is de "Bitcoin als store of value"-these falsifieerbaar?)

---

## Onderzoeksvragen voor Knowledge Graph

1. Is Bitcoin een fundamenteel nieuw asset class of een digitaal equivalent van goud (commodity) met speculatieve premie?
2. Hoe verklaart de neuroeconomie de extreme risicotolerantie bij cryptobeleggers — dopaminesysteem en uncertainty reward?
3. Zijn stablecoins (USDC, USDT) een systeemrisico voor het financiële stelsel — structurele parallellen met money market funds (2008)?
4. Wat zijn de filosofische implicaties van trustless systems (blockchain) voor Rousseau's sociaal contract en institutioneel vertrouwen?

---

## Bronlinks (niet opgehaald — proxy-blokkade)

- Wikipedia: https://en.wikipedia.org/wiki/Cryptocurrency
- Nakamoto (2008) — "Bitcoin: A Peer-to-Peer Electronic Cash System"
- Buterin (2013) — Ethereum Whitepaper
- Minsky (1992) — "The Financial Instability Hypothesis"
- MiCA Regulation (EU) 2023/1114
