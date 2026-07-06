---
type: concept
id: a1c4e827-3d9f-4e0b-b2a5-8f1c2d3e4567
title: Moderne Portefeuilletheorie
summary: "MPT (Markowitz, 1952) is het wiskundige raamwerk voor optimale portefeuillesamenstelling via mean-variance optimalisatie; diversificatie reduceert niet-systematisch risico terwijl CAPM (Sharpe, 1964) de verwachte rendementen koppelt aan marktrisico (beta)."
category: Beleggen
tags: [concept, beleggen, portefeuilletheorie, markowitz, MPT, risicobeheer, diversificatie, CAPM, gedragseconomie, efficiënte-grens, beta, sharpe-ratio]
aliases: ["MPT", "Mean-Variance Analysis", "Moderne Portefeuilletheorie", "Portfolio Theory", "CAPM"]
sources:
  - url: https://doi.org/10.2307/2975974
    title: "Markowitz, H. (1952). Portfolio Selection. Journal of Finance, 7(1), 77–91."
    trust_level: 10
    publication_date: 1952
  - url: https://doi.org/10.2307/2977928
    title: "Sharpe, W.F. (1964). Capital Asset Prices. Journal of Finance, 19(3), 425–442."
    trust_level: 10
    publication_date: 1964
  - url: https://doi.org/10.2307/2328832
    title: "Fama, E.F. & French, K.R. (1992). The Cross-Section of Expected Stock Returns. Journal of Finance, 47(2), 427–465."
    trust_level: 10
    publication_date: 1992
  - url: https://en.wikipedia.org/wiki/Modern_portfolio_theory
    title: "Wikipedia — Modern Portfolio Theory (overview)"
    trust_level: 6
    publication_date: 2024
confidence_score: 0.90
quality_score: 0.85
freshness_score: 0.80
importance_score: 0.92
novelty_score: 0.88
knowledge_score: 0.87
usage_score: 0.102
related_nodes:
  - "02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases"
  - "02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese"
  - "02 Wiki/Beleggen/(C) Waardebeleggen"
  - "02 Wiki/Beleggen/(C) Obligaties & Vastrentende Waarden"
  - "02 Wiki/Beleggen/(C) Factor Investing"
  - "02 Wiki/Beleggen/(C) Marktpsychologie & Beurscrises"
  - "02 Wiki/Filosofie/(C) Falsifieerbaarheid & Wetenschapsfilosofie"
  - "02 Wiki/Psychologie/(C) Cognitie & Gedrag"
revision_history:
  - version: 1
    date: 2026-07-02
    author: Knowledge-Hunter
    change: initial creation (non-standard schema, geen bronnen)
  - version: 2
    date: 2026-07-02
    author: Brain-Guardian
    change: "kwaliteitscontrole — YAML schema herbouwd naar standaard; bronnen toegevoegd (Markowitz 1952, Sharpe 1964, Fama-French 1992); related_nodes gesynchroniseerd; Bronnen-sectie toegevoegd aan body;  tag"
---

# Moderne Portefeuilletheorie (MPT)

> Diversificatie is het enige gratis middageten in beleggen. — Harry Markowitz

---

## Definitie

De Moderne Portefeuilletheorie (MPT; ook: *Mean-Variance Analysis*) is een wiskundig raamwerk voor de optimale samenstelling van beleggingsportefeuilles. Het doel: **het verwachte rendement maximaliseren bij een gegeven risiconiveau**, of risico minimaliseren bij een gegeven rendement.

Ontwikkeld door **Harry Markowitz** in zijn baanbrekende artikel *"Portfolio Selection"* (Journal of Finance, 1952). Nobelprijs voor Economie in 1990 (gedeeld met William Sharpe en Merton Miller).

---

## Kernprincipes

### 1. Risico = Volatiliteit
MPT definieert risico als de **standaarddeviatie van rendementen** — de mate van spreiding rond het gemiddelde. Dit is meetbaar maar reduceert risico tot één dimensie.

**Onderscheid feit/interpretatie:** dit is een modellering, geen objectieve waarheid. Risico heeft ook dimensies die MPT negeert (liquiditeitsrisico, politiek risico, staartrisico).

### 2. Diversificatie reduceert risico
Door activa te combineren die **niet perfect positief gecorreleerd** zijn, daalt het portefeuillerisico zonder evenredig rendementverlies.

- **Systematisch risico** (marktrisico, beta): geldt voor de gehele markt — *niet te diversifiëren*
- **Niet-systematisch risico** (bedrijfsspecifiek): uniek per aandeel — *volledig weg te diversifiëren*

### 3. Correlatie is de sleutel

| Correlatie (ρ) | Effect |
|---|---|
| ρ = +1 | Geen diversificatievoordeel |
| 0 < ρ < +1 | Gedeeltelijk voordeel |
| ρ = 0 | Volledig onafhankelijk — goed diversificatievoordeel |
| ρ = -1 | Perfecte negatieve correlatie — risico tot nul reduceerbaar |

---

## De Efficiënte Grens (Efficient Frontier)

De verzameling van **optimale portefeuilles** — elke portefeuille op de grens biedt het hoogste mogelijke rendement voor dat risiconiveau.

- Portefeuilles **onder** de grens zijn suboptimaal (zelfde risico, lager rendement)
- Portefeuilles **boven** de grens zijn niet bereikbaar
- De **minimumvariantiepunt** is het laagst bereikbare risiconiveau

---

## Wiskundige Kern

**Verwacht rendement portefeuille:**
$$E(R_p) = \sum_{i} w_i \cdot E(R_i)$$

**Variantie portefeuille:**
$$\sigma^2_p = \sum_i \sum_j w_i \cdot w_j \cdot \text{Cov}(R_i, R_j)$$

**Correlatie:**
$$\rho_{ij} = \frac{\text{Cov}(R_i, R_j)}{\sigma_i \cdot \sigma_j}$$

Waarbij $w_i$ de wegingen zijn, $E(R_i)$ de verwachte rendementen, en $\sigma$ de standaarddeviaties.

---

## Capital Asset Pricing Model (CAPM)

Uitbreiding door **William Sharpe (1964)**, Lintner (1965) en Mossin (1966):

$$E(R_i) = R_f + \beta_i \cdot (E(R_m) - R_f)$$

- $R_f$ = risicovrije rente (staatsobligatie)
- $\beta_i$ = beta — gevoeligheid actief voor marktbewegingen
- $(E(R_m) - R_f)$ = marktrisicopremie

**Beta-interpretatie:**
- β = 1: beweegt mee met de markt
- β > 1: agressiever dan de markt (groter risico én rendement)
- β < 1: defensiever dan de markt

**Sharpe Ratio:**
$$S = \frac{R_p - R_f}{\sigma_p}$$
Rendement per eenheid risico. Hogere Sharpe Ratio = betere risico-gecorrigeerde prestatie.

---

## Veronderstellingen en Kritiek

### Veronderstellingen MPT (theoretisch ideaal)
1. Beleggers zijn rationeel en risicoavers
2. Markten zijn efficiënt (Efficient Market Hypothesis)
3. Rendementen zijn normaal verdeeld
4. Correlaties zijn stabiel in de tijd
5. Geen transactiekosten of belastingen
6. Beleggers denken in één tijdshorizon

### Kritiek

**Empirisch:**
- Rendementen zijn **niet** normaal verdeeld — *fat tails* (extremere uitschieters dan normaalverdeling voorspelt)
- Nassim Taleb: *Black Swans* — zeldzame, onverwachte gebeurtenissen met enorm effect
- Correlaties **stijgen** in crises, precies wanneer diversificatie het meest nodig is (*correlation breakdown*)

**Gedragseconomisch:**
- Kahneman & Tversky: beleggers zijn niet rationeel — prospect theory, verliesaversie, mentale boekhouding
- Mental accounting: beleggers denken in mentale potten, niet in totale portefeuille

**Modelmatig:**
- MPT kijkt achteruit voor inputs (historische correlaties, rendementen)
- Factor investing (Fama-French, 1992): beta alleen verklaart rendementen onvoldoende; grootte (SMB) en waarde (HML) zijn aanvullende factoren

---

## Praktische Toepassingen

| Toepassing | Hoe MPT gebruikt wordt |
|---|---|
| Asset allocatie | Optimale mix aandelen/obligaties/alternatieven |
| Indexfondsen / ETFs | Benadering marktportefeuille (Bogle/Vanguard) |
| Risicobeheer | VaR (Value at Risk); CVaR (Conditional VaR) |
| Rebalancing | Periodiek terugbrengen naar doelgewichten |
| Pensioenfondsen | ALM (Asset Liability Management) |

---

## Sleutelfiguren

| Figuur | Bijdrage |
|---|---|
| Harry Markowitz (1927-2023) | Portfolio Selection (1952); grondlegger MPT; Nobel 1990 |
| William Sharpe (1934) | CAPM (1964); Sharpe Ratio; Nobel 1990 |
| Eugene Fama (1939) | Efficient Market Hypothesis; Fama-French factormodel; Nobel 2013 |
| Robert Merton & Myron Scholes | Optiewaardering (Nobel 1997); uitbreiding risicomodellering |
| John C. Bogle (1929-2019) | Oprichter Vanguard; indexfondsen als MPT-implementatie |
| Daniel Kahneman (1934-2024) | Gedragseconomische kritiek op rationele actor; Nobel 2002 |

---

## Verband met Gedragseconomie

MPT en gedragseconomie staan op gespannen voet:

| MPT-aanname | Gedragseconomische realiteit |
|---|---|
| Rationele beleggers | Systematische cognitieve biases |
| Risicoaversie symmetrisch | Verliesaversie asymmetrisch (Prospect Theory) |
| Totale portefeuilleoptimalisatie | Mental accounting — denken in potten |
| Stabiele preferenties | Ankeringseffect, kuddegedrag, FOMO |

**Implicatie:** MPT beschrijft hoe beleggers *zouden* moeten handelen. Gedragseconomie beschrijft hoe ze *werkelijk* handelen.

---

## Verbanden

- [[Gedragseconomie & Cognitieve Biases]] — irrationele belegger vs. rationele MPT-actor; prospect theory vs. mean-variance optimalisatie
- [[Efficiënte Markt Hypothese]] — MPT veronderstelt EMH; feitelijk zijn beide theorieën onlosmakelijk verbonden
- [[Waardebeleggen]] — tegenstelling: waardebeleggen concentreert portfolio's; MPT raadt maximale diversificatie aan
- [[Obligaties & Vastrentende Waarden]] — obligaties als asset class in mean-variance optimalisatie
- [[Factor Investing]] — Fama-French uitbreiding: size en value als factoren naast beta
- [[Marktpsychologie & Beurscrises]] — correlaties stijgen in crises; diversificatie faalt precies wanneer het nodig is
- [[Falsifieerbaarheid & Wetenschapsfilosofie]] — is MPT falsifieerbaar? (Fama's efficient market tests)
- [[Cognitie & Gedrag]] — cognitieve processen achter beleggingsbeslissingen; dual-process theorie

## Bronnen

- Markowitz, H. (1952). Portfolio Selection. *Journal of Finance*, 7(1), 77–91. https://doi.org/10.2307/2975974
- Sharpe, W.F. (1964). Capital asset prices: A theory of market equilibrium under conditions of risk. *Journal of Finance*, 19(3), 425–442. https://doi.org/10.2307/2977928
- Fama, E.F. & French, K.R. (1992). The cross-section of expected stock returns. *Journal of Finance*, 47(2), 427–465. https://doi.org/10.2307/2328832
- Taleb, N.N. (2007). *The Black Swan: The Impact of the Highly Improbable*. Random House.
- Kahneman, D. & Tversky, A. (1979). Prospect theory: An analysis of decision under risk. *Econometrica*, 47(2), 263–291.

> **Status:** Verwerkt door Brain-Guardian | 2026-07-02
