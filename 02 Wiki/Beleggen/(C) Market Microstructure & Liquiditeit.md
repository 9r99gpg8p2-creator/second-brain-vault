---
type: concept
id: e6a0b174-8c52-7d1e-df45-3a4b5c7f96a8
title: Market Microstructure & Liquiditeit
summary: De studie van hoe financiële markten operationeel functioneren — prijsvorming via orderboekmechanismen, de rol van market makers, de kosten van liquiditeit, en de informatie-economie van financieel handelen.
category: Beleggen
tags: [concept, beleggen, market-microstructure, liquiditeit, bid-ask-spread, market-makers, orderboek, prijsvorming, adverse-selection, HFT, transactiekosten, EMH]
aliases: [market microstructure, marktmicrostructuur, liquiditeitstheorie]
sources:
  - url: https://www.acsu.buffalo.edu/~keechung/MGF743/Readings/Market%20microstructure%20A%20surveyq.pdf
    title: "Madhavan, A. (2000). Market Microstructure: A Survey. Journal of Financial Markets 3, 205-258"
    trust_level: 10
    publication_date: 2000
  - url: https://www.bis.org/publ/cgfs11mura_a.pdf
    title: "Muranaga & Shimizu. Market Microstructure and Market Liquidity. BIS"
    trust_level: 9
    publication_date: 1999
  - url: https://arxiv.org/abs/2511.20606
    title: "Limit Order Book Dynamics in Matching Markets: Microstructure, Spread, and Execution Slippage (2025)"
    trust_level: 8
    publication_date: 2025
  - url: https://medium.com/@simomenaldo/market-microstructure-foundations-aabb765d9fd2
    title: "Menaldo, S. Market Microstructure Foundations. Medium"
    trust_level: 6
    publication_date: 2023
confidence_score: 0.86
quality_score: 0.85
freshness_score: 0.88
importance_score: 0.82
novelty_score: 1.0
knowledge_score: 0.84
usage_score: 0.0
related_nodes:
  - "02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese.md"
  - "02 Wiki/Beleggen/(C) Moderne Portefeuilletheorie.md"
  - "02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases.md"
  - "02 Wiki/Beleggen/(C) Risico vs. Onzekerheid — Knight's Onderscheid.md"
  - "02 Wiki/Beleggen/(C) Opties & Derivaten.md"
  - "02 Wiki/Beleggen/(C) Technische Analyse.md"
  - "02 Wiki/Filosofie/(C) Epistemologie & Kennistheorie.md"
revision_history:
  - version: 1
    date: 2026-07-04
    author: Knowledge-Hunter
    change: initial creation — gebaseerd op academische financiële literatuur
---

# Market Microstructure & Liquiditeit

**Kern:** Market microstructure bestudeert *hoe* markten feitelijk werken op transactieniveau — niet welke koersen zich vormen, maar via welk mechanisme koersen tot stand komen, wie de liquiditeit levert, welke informatie in koersen is verwerkt, en wat handelen kost. De discipline overbrugt de abstracte efficiëntie van de [[02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese.md|EMH]] met de concrete mechanica van orderboekmechanismen.

---

## Definitie en afbakening

Market microstructure is de studie van:
1. **Prijsvorming** (*price discovery*): hoe informatie zich vertaalt naar transactiekoersen
2. **Liquiditeit**: de kosten en capaciteit van het omzetten van bezit in geld
3. **Orderflow**: het mechanisme waarmee koop- en verkooporders bij elkaar komen
4. **Transactiekosten**: zichtbare en onzichtbare kosten van handelen

**FEIT:** De meeste beleggers denken in termen van rendementen en waarderingen; market microstructure legt bloot dat *hoe* je handelt minstens zo belangrijk kan zijn als *wat* je koopt.

---

## Het Orderboek (*Limit Order Book*)

Het **Limit Order Book (LOB)** is het centrale mechanisme van moderne effectenbeurzen:

- **Limietorder** (*limit order*): een koop- of verkooporder met een maximale of minimale koers
- **Marktorder** (*market order*): onmiddellijke uitvoering tegen de beste beschikbare koers
- Het orderboek bevat alle openstaande limietorders op elk prijsniveau, gerangschikt van beste naar slechtste prijs

### Structuur
```
VERKOPEN (Ask)
€102.50  ← 500 aandelen
€102.00  ← 200 aandelen
€101.75  ← 800 aandelen
─────────────── spread
€101.50  ← 300 aandelen
€101.25  ← 1000 aandelen
€101.00  ← 400 aandelen
KOPEN (Bid)
```

**FEIT:** "When two sides of the order book match, a trade happens — and that traded price becomes the new market price." Prijsvorming is dus een directe uitkomst van het orderboekmechanisme.

---

## Bid-Ask Spread

De **bid-ask spread** is het verschil tussen de hoogste biedkoers en de laagste vraagkoers:

> Spread = Ask − Bid

De spread is tegelijkertijd:
1. De **transactiekost** voor een belegger die onmiddellijk wil kopen en verkopen
2. De **brutowinst** van de market maker per transactie
3. Een **liquiditeitsindicator** — smal spread = liquide markt, breed spread = illiquide markt

### Componenten van de spread
De spread is niet slechts een "fee" maar compenseert drie factoren:

| Component | Inhoud |
|---|---|
| **Inventariskosten** | Market maker draagt prijsrisico op zijn posities |
| **Adverse selection** | Risico dat de tegenpartij beter geïnformeerd is |
| **Orderverwerking** | Operationele kosten van het uitvoeren van transacties |

De **adverse selection component** is theoretisch de meest interessante: market makers weten dat sommige tegenpartijen handelen op privé-informatie. De spread compenseert hen voor het verlies op die transacties.

---

## Liquiditeit

Liquiditeit is meerdimensionaal:

| Dimensie | Definitie | Maatstaf |
|---|---|---|
| **Breedte** | Kosten van een kleine transactie | Bid-ask spread |
| **Diepte** | Hoeveel volume beschikbaar bij huidige prijs | Orderboekdiepte |
| **Veerkracht** | Snelheid waarmee de markt herstelt na een klap | Orderflow-persistentie |
| **Onmiddellijkheid** | Hoe snel kan ik uitvoeren? | Uitvoeringstijd |

**FEIT:** Liquiditeit is geen constante maar fluctueert sterk met marktomstandigheden. In crisistijd droogt liquiditeit op wanneer je haar het meest nodig hebt — liquiditeitsrisico als *endogeen* systeemrisico.

### Amihud Illiquiditeitsmaatstaf
Een veelgebruikte maatstaf (Amihud, 2002):

> ILLIQ = |rendement| / handelsvolume (in euro's)

Hogere waarde = hogere illiquiditeit = grotere koersimpact per verhandeld euro.

---

## Market Makers

**Market makers** zijn partijen (banken, gespecialiseerde handelsfirma's) die continu koop- en verkoopkoersen quoteren:

- **Functie**: leveren van liquiditeit — ze staan altijd klaar om te kopen (tegen bid) en te verkopen (tegen ask)
- **Verdienmodel**: de spread
- **Risico**: adverse selection + inventarisrisico (prijs beweegt tegen je positie)

**FEIT:** Zonder market makers zou het onmogelijk zijn grote aandelen onmiddellijk te verhandelen — zij absorberen de tijdsgebonden mismatch tussen vraag en aanbod.

---

## Theoretische modellen

### Glosten-Milgrom Model (1985)
Verklaart de bid-ask spread vanuit **informatieasymmetrie**:
- Market maker handelt met twee typen tegenpartijen: geïnformeerde (insiders) en ongeïnformeerde (liquiditeitshandel)
- Market maker past spread aan zodat verlies op geïnformeerde handelaars wordt gecompenseerd door winst op ongeïnformeerde

**Implicatie:** Hoe meer insiderhandel in een markt, hoe groter de spread — een adverse-selection premie.

### Kyle Model (1985)
Modelleert hoe een **geïnformeerde handelaar** zijn informatievoordeel uitbuit:
- Geïnformeerde handelaar spreidt orders over de tijd om de markt niet te alarmeren
- Market maker leart geleidelijk uit de orderflow
- **Market depth** (λ): hoe gevoelig de koers is voor ordervolume — hogere λ = minder diepte

---

## High-Frequency Trading (HFT)

HFT-bedrijven handelen op micro- of milliseconden, gebruik makend van colocatie bij beurzen:

**Pro-liquiditeitsargument:**
- Smallers spreads door toegenomen concurrentie
- Snellere prijsaanpassing aan nieuwe informatie

**Anti-liquiditeitsargument:**
- **Flash Crash (6 mei 2010)**: Dow daalde in minuten ~1000 punten door HFT-feedback loops
- **Latency arbitrage**: winst door informatievoorsprong van microseconden, ten koste van traditionele beleggers
- Liquiditeit die snel *verdwijnt* bij stress is geen echte liquiditeit

**AANNAME:** De netto welvaartsimpact van HFT is omstreden in de academische literatuur.

---

## Praktische implicaties voor beleggers

### Transactiekosten zijn groter dan ze lijken
Een belegger die een aandeel koopt en verkoopt betaalt:
1. Zichtbare commissie
2. Helft van de bid-ask spread (bij kopen én verkopen)
3. **Market impact**: bij grotere orders beweegt de prijs *door* het order — *slippage*

**FEIT:** Voor grote institutionele orders kan market impact de grootste kostenpost zijn.

### Liquiditeitsrisico als portefeuillerisico
- Illiquide assets bieden hogere verwachte rendementen (**liquiditeitspremie**)
- In crises correleert illiquiditeit met andere risicofactoren — diversificatie werkt minder
- Zie [[02 Wiki/Beleggen/(C) Moderne Portefeuilletheorie.md]] voor portefeuilletheorie en risicofactoren

---

## Verbinding met de EMH

De [[02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese.md|Efficiënte Markt Hypothese]] veronderstelt dat koersen alle beschikbare informatie weerspiegelen. Market microstructure analyseert het *mechanisme* waarlangs dit plaatsvindt:

- **Informatieve orderflow**: geïnformeerde handelaars drukken nieuwe informatie in koersen via hun orders
- **Limits to arbitrage**: transactiekosten en liquiditeitsbeperkingen verhinderen perfecte efficiëntie
- **INTERPRETATIE:** Markten zijn niet effiiciënt *ondanks* microstructuurwrijvingen, maar *via* het gedrag van winstzoekende handelaars die tegelijkertijd liquiditeit leveren

---

## Onderzoeksvragen

1. In hoeverre heeft de opkomst van HFT de traditionele functie van market makers overgenomen — en is dit stabiel of fragiel?
2. Hoe gedraagt liquiditeit zich in **gedecentraliseerde markten** (DeFi, AMM's) vergeleken met traditionele orderboekmechanismen?
3. Wat is de optimale spread vanuit maatschappelijk welzijnsperspectief — en wie betaalt de kosten van liquiditeitsvoorziening?
