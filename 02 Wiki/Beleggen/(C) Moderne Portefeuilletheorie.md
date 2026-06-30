---
type: concept
tags: [beleggen, portefeuilletheorie, risicobeheer, diversificatie, Markowitz, financiën, evidence-based]
discipline: Beleggen
---

# Moderne Portefeuilletheorie (MPT)

## Oorsprong en kern

Harry Markowitz publiceerde in 1952 het artikel "Portfolio Selection" in het *Journal of Finance* — een van de meest invloedrijke publicaties in de financiële economie, waarvoor hij in 1990 de Nobelprijs Economie ontving.

**Feit:** MPT formuleert wiskundig hoe een rationele belegger een portefeuille kan samenstellen die het verwachte rendement maximaliseert voor een gegeven risicotolerantie, of het risico minimaliseert voor een gegeven verwacht rendement.

## Kernconcepten

### Risico en rendement
- **Verwacht rendement (μ):** gewogen gemiddelde van mogelijke uitkomsten
- **Risico (σ):** standaarddeviatie van rendementen — maat voor de spreiding/volatiliteit

**Interpretatie:** De gelijkstelling van risico met volatiliteit is een vereenvoudiging. Beleggers onderscheiden doorgaans neerwaarts risico (verlies) van opwaartse volatiliteit (winst) — een beperking die later door modellen als de Sortino-ratio wordt geadresseerd.

### Correlatie en diversificatie
De kern van MPT: door activa te combineren die **niet perfect positief gecorreleerd** zijn (correlatie < 1), kan de totale portefeuillevolatiliteit worden verlaagd *zonder* evenredige reductie van het verwacht rendement.

**Formule (portefeuillevariantie voor twee activa):**
σ²_p = w²_A · σ²_A + w²_B · σ²_B + 2 · w_A · w_B · σ_A · σ_B · ρ_AB

waarbij ρ_AB de correlatie is tussen activa A en B.

**Feit:** Bij perfecte negatieve correlatie (ρ = −1) kan risico theoretisch tot nul worden gereduceerd. In de praktijk bestaan zulke perfecte hedges niet.

### De efficiënte frontier
Alle optimale portefeuilles — maximaal rendement per eenheid risico — liggen op de **efficiënte frontier** in de rendement-risico-ruimte. Portefeuilles *onder* de frontier zijn suboptimaal.

### Het Capital Asset Pricing Model (CAPM)
Voortbouwend op MPT ontwikkelden Sharpe (1964), Lintner (1965) en Mossin (1966) het CAPM:

**E(R_i) = R_f + β_i · (E(R_m) − R_f)**

- R_f = risicovrij rendement
- β_i = gevoeligheid van actief i voor marktbewegingen (systematisch risico)
- E(R_m) = verwacht marktrendement

**Theorie:** CAPM stelt dat alleen systematisch risico (β) gecompenseerd wordt; idiosyncratisch risico (bedrijfsspecifiek) kan worden weggediversifieerd en verdient geen risicopremie.

**Kritiek (empirisch):** Fama & French (1992) toonden aan dat CAPM het verwachte rendement onvoldoende verklaart — grootte (small-cap premie) en waarde (value premium) voegen verklaringskracht toe. CAPM is empirisch onvoldoende maar conceptueel onmisbaar als startpunt.

## Praktische implicaties

1. **Diversificeer breed:** indexfondsen spreiden over honderden tot duizenden activa, elimineren idiosyncratisch risico en reduceren kosten (Bogle, 1976 — de Vanguard-filosofie)
2. **Actief versus passief:** de meeste actieve fondsen presteren na kosten onder de marktindex over lange perioden (SPIVA-rapporten, S&P Global)
3. **Asset allocatie bepaalt rendement:** Brinson, Hood & Beebower (1986) stelden dat >90% van de langetermijnrendementsvariatie verklaard wordt door asset allocatie, niet door effectenselectie

**Speculatie:** Of MPT in een wereld met dikstaartsverdelingen (*fat tails*), correlatieveranderingen in crises, en behavioral biases volledig toepasbaar is, is fundamenteel betwist. Nassim Taleb (*The Black Swan*, 2007) betoogt dat Gaussiaanse risicomodellen catastrofale risico's systematisch onderschatten.

## Verbanden binnen het Second Brain

- [[02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases]] — MPT assumeert rationaliteit; gedragseconomie toont systematische afwijkingen
- [[03 Knowledge Graph/(KG) Rationaliteit, Oordeel & Besluitvorming]] — de rationele belegger als theoretisch construct versus menselijke besluitvorming
- [[03 Knowledge Graph/(KG) Neuroplasticiteit, Leren & Aanpassing]] — risicoperceptie als adaptief mechanisme
- [[02 Wiki/Filosofie/(C) Falsifieerbaarheid & Wetenschapsfilosofie]] — zijn financiële modellen falsifieerbaar?

## Bronnen

- Markowitz, H. (1952). Portfolio selection. *Journal of Finance, 7*(1), 77–91.
- Sharpe, W.F. (1964). Capital asset prices: A theory of market equilibrium under conditions of risk. *Journal of Finance, 19*(3), 425–442.
- Fama, E.F., & French, K.R. (1992). The cross-section of expected stock returns. *Journal of Finance, 47*(2), 427–465.
- Brinson, G.P., Hood, L.R., & Beebower, G.L. (1986). Determinants of portfolio performance. *Financial Analysts Journal, 42*(4), 39–44.
- Taleb, N.N. (2007). *The Black Swan: The Impact of the Highly Improbable*. Random House.
- Bogle, J.C. (2007). *The Little Book of Common Sense Investing*. Wiley.
