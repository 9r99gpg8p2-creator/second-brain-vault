# RAW DATA — Beleggen: Market Microstructure & Liquiditeit
**Status: RAW DATA — geen interpretatie**
**Datum:** 2026-07-04
**Agent:** Agent1-KnowledgeHunter
**Bronnen:** WebSearch → Equiti, Tradeslayers, BIS, Medium/Menaldo, arXiv

---

## Definitie

- "Market microstructure studies how financial markets operate, focusing on order execution, price formation, and liquidity"
- "The detailed organisational and operational aspects of a financial market, including the different processes that facilitate the trading of financial instruments"

## Kerncomponenten

### Order Book
- "A constantly updating list of bids and asks, where buyers post the price they want to pay and sellers post the price they want to receive"
- Limit order book (LOB): bevat alle openstaande koop- en verkooporders op een specifiek prijsniveau
- "When two sides of the order book match, a trade happens — and that traded price becomes the new market price"
- Limit Order Book Dynamics onderwerp van actief onderzoek (arXiv:2511.20606)

### Bid-Ask Spread
- "The difference between the highest price a buyer is willing to pay (bid) and the lowest price a seller is willing to accept (ask)"
- Smal spread = hoge liquiditeit = lage transactiekosten
- Breed spread = lage liquiditeit = hoge transactiekosten
- Componenten van spread: (1) inventariskosten market maker, (2) adverse selection component, (3) orderverwerking

### Market Makers
- "Firms that are contractually obligated to provide liquidity by continuously quoting bid and ask prices"
- Risico: adverse selection — handelen met beter geïnformeerde partijen
- Verdienen aan spread maar lopen prijsrisico

### Liquiditeit
- "The ease with which an asset can be bought or sold without causing a significant change in its price"
- Dimensies: breedte (bid-ask spread), diepte (hoeveelheid orders), veerkracht (herstelsnelheid na shock)
- Liquiditeitsrisico: kan opdrogen bij stress (zie Flash Crash 2010)

### Prijsvorming (Price Discovery)
- "The process of determining a price of an asset, through market transactions between buyers and sellers"
- Efficiënte markt: nieuwe informatie verwerkt in prijs via orderflow
- Informed traders vs. uninformed traders

## Theoretische modellen

- **Glosten-Milgrom model (1985)**: adverse selection als verklaring voor bid-ask spread
- **Kyle model (1985)**: insider trading en market depth — hoe geïnformeerde handelaar informatie geleidelijk uitput
- **Amihud illiquiditeitsmaatstaf**: |rendement| / handelsvolume

## High-Frequency Trading (HFT)

- Handelt op microseconden, maakt gebruik van colocatie bij beurzen
- Debate: verbetert liquiditeit (narrowere spreads) vs. creates systemic risk (Flash Crash)
- Latency arbitrage: snelheidsvoordeel als winstbron

## Relevantie voor beleggers

- Transactiekosten zijn reëel en onderschat (spread + market impact)
- Liquiditeitsrisico als aparte risicofactor in portefeuille
- Slippage: verschil tussen verwachte en werkelijke uitvoerkoers bij grote orders

## Bronlinks

- https://www.equiti.com/sc-en/education/market-analysis/order-flow-and-market-microstructure/
- https://www.bis.org/publ/cgfs11mura_a.pdf
- https://medium.com/@simomenaldo/market-microstructure-foundations-aabb765d9fd2
- https://arxiv.org/abs/2511.20606
