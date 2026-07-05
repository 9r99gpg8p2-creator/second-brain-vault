---
type: concept
id: 2c5d8e1f-3a4b-4c7d-9e0f-1a2b3c4d5e6f
title: Kelly Criterium & Optimale Positiegroottes
summary: "Het Kelly Criterium (Kelly 1956) is een wiskundig framework dat de optimale kapitaalfractie bepaalt bij herhaalde kansen met bekende waarschijnlijkheden; het maximaliseert de langetermijn groeisnelheid maar vereist psychologisch uitzonderlijke discipline."
category: Beleggen
tags: [concept, beleggen, risicobeheer, kansrekening, portefeuille, kwantitatief-beleggen, positiegrootte, quality-check-needed]
aliases: ["Kelly Criterion", "Full Kelly", "Half Kelly", "Optimale Positiegroottes"]
sources:
  - title: "Kelly, J.L. (1956). A New Interpretation of Information Rate. Bell System Technical Journal, 35(4), 917–926."
    trust_level: 10
  - title: "Thorp, E.O. (1962). Beat the Dealer. Blaisdell Publishing."
    trust_level: 8
  - title: "Thorp, E.O. (1969). Optimal gambling systems for favorable games. Review of the International Statistical Institute, 37(3), 273–293."
    trust_level: 8
  - title: "Poundstone, W. (2005). Fortune's Formula. Hill & Wang."
    trust_level: 7
  - title: "MacLean, L.C., Thorp, E.O. & Ziemba, W.T. (2010). The Kelly Capital Growth Investment Criterion. World Scientific."
    trust_level: 9
confidence_score: 0.85
quality_score: 0.75
freshness_score: 1.0
importance_score: 0.85
novelty_score: 1.0
knowledge_score: 0.83
usage_score: 0.0
related_nodes:
  - "02 Wiki/Beleggen/(C) Risico vs. Onzekerheid — Knight's Onderscheid"
  - "02 Wiki/Beleggen/(C) Moderne Portefeuilletheorie"
  - "02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases"
  - "02 Wiki/Beleggen/(C) Hyperbolic Discounting & Tijdspreferentie"
  - "02 Wiki/Beleggen/(C) Opties & Derivaten"
  - "02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese"
revision_history:
  - version: 1
    date: 2026-07-05
    author: Knowledge-Hunter
    change: initial creation — nieuw topic toegevoegd
  - version: 2
    date: 2026-07-05
    author: Brain-Guardian
    change: YAML geconverteerd naar standaard schema; quality-check-needed tag toegevoegd (bronnen zonder URL)
---

# Kelly Criterium & Optimale Positiegroottes

## Kernidee

Het Kelly Criterium, ontwikkeld door John L. Kelly Jr. in 1956, is een wiskundig framework dat de optimale fractie van een kapitaal bepaalt die ingezet moet worden bij een herhaalde gok of belegging met bekende kansen. Kelly maximaliseert de verwachte groeisnelheid van het kapitaal op lange termijn. Het is de wiskundige verbinding tussen informatietheorie en risicobeheer — en tegelijkertijd een professionele discipline die de meeste beleggers psychologisch niet aankunnen.

---

## Oorsprong: Bell Labs en de Informatietheorie

**John L. Kelly Jr.** (1923–1965) werkte als onderzoeker bij Bell Telephone Laboratories, het instituut dat ook Claude Shannon (grondlegger van de informatietheorie) had voortgebracht. In 1956 publiceerde Kelly "A New Interpretation of Information Rate" in het *Bell System Technical Journal*.

Kelly's originele probleem was informatie-theoretisch: hoe snel kan een belegger die *private* informatie heeft over een paardenrace zijn kapitaal laten groeien? Het antwoord bleek structureel identiek aan Shannon's informatie-entropieformule — geen toeval.

**Edward Thorp**, wiskundige aan MIT, vertaalde Kelly's formule naar praktisch gebruik:
- *Beat the Dealer* (1962): Kelly toegepast op blackjack (card counting)
- *Beat the Market* (1967): Kelly toegepast op aandelenopties
- Thorp's Princeton-Newport Partners (1969–1988): gemiddeld 20% rendement per jaar met Kelly-sizing

---

## De Kelly Formule

### Voor Binaire Uitkomsten (win/verlies)

$$f^* = \frac{bp - q}{b}$$

Waarbij:
- **f*** = optimale fractie van het kapitaal (tussen 0 en 1)
- **b** = netto winstfactor (bij 2:1 odds is b = 2; bij gelijke odds b = 1)
- **p** = kans op winst
- **q** = kans op verlies = 1 - p

**Voorbeeld**: je hebt een kans van 60% om te winnen; bij verlies verlies je de inzet, bij winst win je 1× je inzet (b = 1):
- f* = (1 × 0.60 − 0.40) / 1 = 0.20 → zet 20% van je kapitaal in

### Vereenvoudigd (gelijke odds, b = 1):
$$f^* = p - q = 2p - 1$$

### Voor Continue Verdelingen (beleggen):
$$f^* = \frac{\mu}{\sigma^2}$$

Waarbij:
- **μ** = verwacht rendement (excess return boven risicovrije rente)
- **σ²** = variantie van het rendement

---

## Wiskundige Eigenschappen

### Wat Kelly Garandeert
1. **Maximaliseert de verwachte logaritme van rijkdom** op elke tijdstap
2. **Maximaliseert de langetermijn groeisnelheid** van het kapitaal bijna zeker
3. **Versloeg op de lange termijn elke andere strategie** die consistent afwijkt
4. **Leidt nooit tot ruin** als de fractie ≤ f* is

### Drawdown bij Full Kelly
- Kelly biedt goede groei maar *hoge volatiliteit*
- Verwachte drawdown bij Full Kelly: 50% drawdown is statistisch normaal
- Maximale drawdown hangt af van de kansverdeling

---

## Strategieën: Kelly en zijn Varianten

| Strategie | Fractie | Groeisnelheid | Volatiliteit |
|---|---|---|---|
| **Full Kelly** | f* | Maximaal | Hoog (50%+ drawdowns) |
| **Half Kelly** | f*/2 | 75% van Kelly-groei | Laag (halve volatiliteit) |
| **Quarter Kelly** | f*/4 | ~56% van Kelly-groei | Zeer laag |
| **Vaste fractie** | bijv. 2% per trade | Sub-optimaal | Laag |
| **Martingale** | Verdubbelen na verlies | Negatief op lange termijn | Ruin |
| **Gelijke gewichten** | 1/N | Sub-optimaal t.o.v. Kelly | Afhankelijk van N |

**Professionele praktijk**: de meeste kwantitatieve fondsen gebruiken Half Kelly of minder — de reductie in drawdown weegt op tegen het verlies in groeisnelheid, en emotionele discipline is makkelijker te behouden.

---

## Vergelijking met Moderne Portefeuilletheorie (Markowitz)

| Aspect | Markowitz (MPT) | Kelly Criterium |
|---|---|---|
| Doel | Maximaliseer rendement per eenheid risico | Maximaliseer groeisnelheid kapitaal |
| Input | Verwacht rendement + covariantiematrix | Kansen + odds |
| Tijdshorizon | Enkelvoudige periode | Meervoudige periodes |
| Uitkomst | Efficiënte frontier (portefeuille) | Optimale inzetfractie per positie |
| Ruin | Geen garantie | Kelly garandeert geen ruin als f ≤ f* |

Kelly en Markowitz geven voor dezelfde inputs verschillende adviezen. Bij een lang-termijnhorizon is Kelly theoretisch superieur; Markowitz is praktischer voor periodieke portefeuilleoptimalisatie.

---

## Psychologische Uitdagingen

### Het Kelly-discipline Probleem
Full Kelly implies soms grote inzetten — 30–50% van het kapitaal — die psychologisch extreem moeilijk zijn:
- Verlieshate (loss aversion — Kahneman & Tversky): verliezen voelen 2× zo erg als winsten
- Na een reeks verliezen neigt de belegger te *verkleinen* (sub-Kelly) precies wanneer de kansen het meest gunstig zijn
- **Overkill-fout**: beleggers overschatten hun edge (p) → over-Kelly → hogere drawdowns dan verwacht

### Verbinding met Hyperbolic Discounting
- Kelly-investeerders moeten disciplined sub-Kelly blijven over lange tijdshorizonten
- Hyperbolisch discounten → aanwezigheidsdruk → de belegger "trekt de stekker eruit" bij drawdown
- De wiskundige optimaliteit van Kelly vereist tijdconsistente voorkeuren — psychologisch zeldzaam

### Aron Brown's Observatie (risicobeheerder)
- "Most people are half-Kelly by temperament, and that's probably appropriate."
- De emotionele tolerantie voor drawdowns is de bindende beperking, niet de wiskunde

---

## Toepassingen

### Kwantitatief Beleggen
- Renaissance Technologies (Jim Simons) gebruikte Kelly-gebaseerde positiegroottes
- Statistische arbitrage: Kelly voor het schalen van delta-neutrale posities
- Optie-market making: Kelly voor het bepalen van handelsvolumes

### Sport-betting en Poker
- Professionele sportwedders gebruiken Kelly voor kapitaalbeheer
- Pokertheorie: Kelly-sizing voor toernooi-stack-management

### Praktische Beperkingen in Beleggen
- **p is onbekend**: kansen in beleggen zijn niet precies bepaalbaar zoals in blackjack
- Foutieve p-schatting → over-Kelly → verhoogd ruinrisico
- **Discrete posities**: fractionele inzetten zijn niet altijd mogelijk
- **Transactiekosten**: veelvuldige herbalancering is kostbaar

---

## Shannon's Verbinding: Informatie en Rijkdom

Claude Shannon en Kelly werkten parallel. Shannon toonde aan dat Kelly's formule wiskundig equivalent is aan de informatie-entropyformule:

$$H = -\sum p_i \log(p_i)$$

De snelheid van rijkdomsgroei is gelijk aan de informatiesnelheid van het signaal. Als de belegger *geen* privé-informatie heeft, is Kelly = 0 (niet spelen). Dit is ook de formele verbinding tussen informatietheorie en de Efficiënte Markt Hypothese: als markten volledig efficiënt zijn, is de edge = 0, en Kelly adviseert niet te spelen.

---

## Verbindingen

- **[[02 Wiki/Beleggen/(C) Risico vs. Onzekerheid — Knight's Onderscheid]]**: Kelly vereist bekende kansen (risico); bij Knightiaanse onzekerheid is Kelly ontoepasbaar
- **[[02 Wiki/Beleggen/(C) Moderne Portefeuilletheorie]]**: alternatief optimalisatiekader; Kelly superieur op lange termijn
- **[[02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases]]**: verlieshate maakt Full Kelly psychologisch onhoudbaar
- **[[02 Wiki/Beleggen/(C) Hyperbolic Discounting & Tijdspreferentie]]**: discipline-probleem: tijdconsistente voorkeuren vereist voor Kelly-strategie
- **[[02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese]]**: als markten efficiënt zijn, is Kelly-edge = 0

---

## Feiten vs. Interpretaties

| Categorie | Stelling |
|---|---|
| **Feit** | Kelly publiceerde "A New Interpretation of Information Rate" (1956, Bell System Technical Journal) |
| **Feit** | Thorp paste Kelly succesvol toe in blackjack (1962) en aandelenmarkten |
| **Feit** | Full Kelly maximaliseert de verwachte logaritme van rijkdom wiskundig |
| **Feit** | Half Kelly geeft 75% van de Kelly-groeisnelheid met halve variantie |
| **Interpretatie** | Kelly is de optimale strategie voor beleggen |
| **Interpretatie** | Renaissance Technologies gebruikte Kelly-sizing (niet publiekelijk bevestigd) |
| **Speculatie** | Kwantitatieve fondsen met Kelly-discipline zullen op lange termijn alle discretionare fondsen verslaan |

---

*Aangemaakt door Agent1-KnowledgeHunter op 2026-07-05 | Nieuw topic — geen kennishiaat-event aanwezig*
