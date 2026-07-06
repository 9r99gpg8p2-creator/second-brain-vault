---
type: concept
id: f84bb1e3-c0cc-4fc8-81d7-1b600c27f597
title: Opties & Derivaten
summary: Derivaten zijn financiële contracten waarvan de waarde afgeleid is van een onderliggend actief; het Black-Scholes model (1973) leverde de eerste wiskundig rigoureuze prijsformule voor opties en fundamenteerde de moderne derivatenmarkt.
category: Beleggen
tags: [concept, beleggen, opties, derivaten, Black-Scholes, Greeks, hedging, leverage, risicomanagement]
aliases: [Options, Derivatives, Black-Scholes, Call, Put, Greeks]
sources:
  - url: https://www.jstor.org/stable/1831029
    title: "Black & Scholes (1973) — The Pricing of Options and Corporate Liabilities"
    trust_level: 10
    publication_date: 1973
  - url: https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_model
    title: "Wikipedia — Black–Scholes model"
    trust_level: 7
    publication_date: 2024
  - url: https://www.mdpi.com/2227-7390/13/7/1234
    title: "MDPI Mathematics (2025) — General Conformable Black-Scholes Equation"
    trust_level: 8
    publication_date: 2025
confidence_score: 0.87
quality_score: 0.88
freshness_score: 0.88
importance_score: 0.88
novelty_score: 0.88
knowledge_score: 0.88
usage_score: 0.034
related_nodes: []
revision_history:
  - version: 1
    date: 2026-07-01
    author: Knowledge-Synthesizer
    change: initial creation
---

# Opties & Derivaten

**Kern:** Derivaten zijn financiële contracten waarvan de waarde afgeleid is van een onderliggend actief; opties geven het *recht* maar niet de plicht om te kopen of verkopen, en het Black-Scholes model (1973) biedt de eerste rigoureuze wiskundige grondslag voor hun waardering.

## Inhoud

### FEIT: Definitie en classificatie van derivaten

Een **derivaat** (derivative) is een financieel contract waarvan de waarde volledig afgeleid is van een **onderliggend actief** (aandeel, index, grondstof, valuta, rente, krediet). Derivaten worden gebruikt voor drie doelen:

1. **Hedging**: bescherming van een portefeuille tegen neerwaarts risico
2. **Speculatie**: gericht wedden op prijsbewegingen met leverage
3. **Arbitrage**: risicoloos winst maken van prijsverschillen

Soorten derivaten: opties, futures, forwards, swaps, credit default swaps (CDS), collateralized debt obligations (CDO).

### FEIT: Opties — definitie en basisstructuur

**Call-optie**: geeft de koper het *recht* (niet de plicht) om het onderliggend actief te **kopen** tegen de afgesproken uitoefenprijs (strike price) vóór of op de expiratiedatum.

**Put-optie**: geeft de koper het *recht* (niet de plicht) om het onderliggend actief te **verkopen** tegen de strike price.

De **premie** is de prijs die de koper betaalt voor dit recht; de verkoper (schrijver) ontvangt de premie maar neemt onbeperkte risico's (bij call-verkoop).

**Europese optie**: alleen uitoefenbaar op expiratiedatum. **Amerikaanse optie**: uitoefenbaar op elk moment vóór expiratie. Black-Scholes geldt formeel voor Europese opties.

### FEIT: Black-Scholes model (1973)

Fischer Black en Myron Scholes publiceerden in 1973 in het *Journal of Political Economy* de eerste formule voor de theoretische prijs van Europese opties. Robert Merton breidde het model uit; Scholes en Merton ontvingen in 1997 de Nobelprijs voor Economie (Black was in 1995 overleden).

De formule berekent de theoretische optieprijs als functie van:
- **S**: huidige aandeelprijs
- **K**: strike price
- **T**: resterende looptijd (in jaren)
- **r**: risicovrije rente
- **σ** (sigma): volatiliteit van de onderliggende waarde

**Fundamentele aannames van Black-Scholes:**
- Continu verhandelbare markten (geen marktsluitingen)
- Geen dividenden
- Constante volatiliteit (σ is vast gedurende de looptijd)
- Log-normale verdeling van prijsrendementen
- Geen transactiekosten of belastingen

### INTERPRETATIE: Beperkingen van Black-Scholes

De aanname van **constante volatiliteit** is empirisch onjuist. In de praktijk vertoont geïmpliceerde volatiliteit een **volatility smile** of **skew**: opties ver buiten het geld (deep out-of-the-money) hebben hogere geïmpliceerde volatiliteit dan het model voorspelt. Na de beurskrach van 1987 werd dit patroon permanent zichtbaar.

Stochastische volatiliteitsmodellen (Heston, SABR) en jump-diffusion modellen zijn ontwikkeld als uitbreiding. Black-Scholes blijft de industriestandaard als referentiekader.

### FEIT: De Greeks — risicomanagement

De Greeks zijn partiële afgeleiden van de optieprijs naar de modelinputs; zij kwantificeren de gevoeligheid van de optiewaarde voor veranderingen in marktomstandigheden:

| Greek | Definitie | Gebruik |
|---|---|---|
| Delta (Δ) | Verandering optieprijs per €1 stijging onderliggende | Delta-hedging: neutraliseren van richtingsrisico |
| Gamma (Γ) | Verandering van delta per €1 stijging | Convexiteit van de optiewaarde |
| Theta (Θ) | Tijdsverval per dag | Time decay: opties verliezen waarde naarmate expiratie nadert |
| Vega (ν) | Verandering per 1% volatiliteitsstijging | Volatiliteitsrisico |
| Rho (ρ) | Verandering per 1% rentestijging | Rentegevoeligheid |

### INTERPRETATIE: Gevaren van derivaten

Derivaten zijn een tweesnijdend zwaard. Als hedging-instrument verminderen ze risico. Als speculatief instrument versterken ze door **leverage** verliezen exponentieel: een premieinvestering van €1.000 kan een positie van €100.000 controleren.

Systeemrisico: de financiële crisis van 2008 werd mede veroorzaakt door mispricing en gebrek aan transparantie in complexe derivaten (CDO's op subprime hypotheken, CDS's zonder adequate onderpandseisen). Zie [[Marktpsychologie & Beurscrises]].

## Klinische Relevantie

Niet direct van toepassing op klinische neuropsychologie. Indirect verband: gokstoornis (Gambling Disorder) deelt neurale mechanismen met speculatieve optiehandel — het dopaminerge beloningssysteem reageert op onzekerheid en potentiële winst op identieke wijze. Zie [[Beloningssysteem & Dopamine]].

## Verbanden

- [[Moderne Portefeuilletheorie]] — opties als instrument voor risicomanagement; putopties als verzekering voor een portefeuille
- [[Efficiënte Markt Hypothese]] — zijn optieprijzen efficiënt? Volatility smile als bewijs van marktinefficiëntie?
- [[Gedragseconomie & Cognitieve Biases]] — optiehandel en cognitieve fouten: overconfidence bij schrijvers, loss aversion bij kopers
- [[Rente & Centrale Bankpolitiek]] — rente (r) als directe input in Black-Scholes; rente-derivaten als afzonderlijke markt
- [[Marktpsychologie & Beurscrises]] — derivaten als versterker van systeemrisico; rol van CDO's in 2008-crisis
- [[Beloningssysteem & Dopamine]] — neurologische parallel: speculatieve optiehandel en dopaminerg beloningssysteem

## Bronnen

- Black, F. & Scholes, M. (1973). The pricing of options and corporate liabilities. *Journal of Political Economy*, 81(3), 637–654.
- Merton, R.C. (1973). Theory of rational option pricing. *Bell Journal of Economics and Management Science*, 4(1), 141–183.
- Hull, J.C. (2022). *Options, Futures, and Other Derivatives* (11th ed.). Pearson.
- MDPI Mathematics (2025). A General Conformable Black-Scholes Equation for Option Pricing.

> Status: Verwerkt door Knowledge-Synthesizer | 2026-07-01
