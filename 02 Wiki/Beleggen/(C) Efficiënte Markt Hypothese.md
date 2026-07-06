---
type: concept
id: 752e76fb-59e2-9943-4f4d-ef220796c31e
title: Efficiënte Markt Hypothese
summary: "De EMH stelt dat activaprijzen altijd alle beschikbare informatie volledig weerspiegelen, waardoor het systematisch verslaan van de markt in de prakti"
category: Beleggen
tags: [concept, beleggen, EMH, marktefficiëntie, fama, financiële-theorie, passief-beleggen, gedragseconomie]
aliases: ["EMH", "Efficiënte Markt Hypothese", "Efficient Market Hypothesis", "marktefficiëntie", "Fama"]
sources:
  - title: "Fama, E. F. (1970). Efficient capital markets: A review of theory and empirical "
    trust_level: 8
  - url: "Wikipedia — Efficient-market hypothesis: https://en.wikipedia.org/wiki/Efficient-market_hypothesis"
    trust_level: 9
  - url: "Wikipedia — Eugene Fama: https://en.wikipedia.org/wiki/Eugene_Fama"
    trust_level: 9
  - url: "arXiv 2012.11594 (insider trading voor fusies): https://arxiv.org/pdf/2012.11594"
    trust_level: 9
  - url: "arXiv 2305.17419 (random generators & efficiëntie): https://arxiv.org/pdf/2305.17419"
    trust_level: 9
  - url: "arXiv 2208.07254 (Bitcoin & EMH): https://arxiv.org/pdf/2208.07254"
    trust_level: 9
  - url: "arXiv 1909.05151 (ML & zwakke-vorm EMH): https://arxiv.org/pdf/1909.05151"
    trust_level: 9
  - title: "Lo, A. W. (2004). The Adaptive Markets Hypothesis. *Journal of Portfolio Managem"
    trust_level: 8
confidence_score: 0.9
quality_score: 0.92
freshness_score: 0.8
importance_score: 0.85
novelty_score: 1.0
knowledge_score: 0.868
usage_score: 0.0816
related_nodes:
  - "02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases"
  - "02 Wiki/Beleggen/(C) Moderne Portefeuilletheorie"
  - "02 Wiki/Beleggen/(C) MOC - Beleggen"
  - "02 Wiki/Filosofie/(C) Falsifieerbaarheid & Wetenschapsfilosofie"
  - "02 Wiki/Filosofie/(C) Epistemologie & Kennistheorie"
  - "02 Wiki/Psychologie/(C) Cognitie & Gedrag"
  - "03 Knowledge Graph/(KG) Rationaliteit, Oordeel & Besluitvorming"
  - "03 Knowledge Graph/(KG) Kennis, Rede & Verlichting"
revision_history:
  - version: 1
    date: 2026-07-01
    author: Brain-Guardian
    change: initial YAML scaffolding by guardian routine
---

# Efficiënte Markt Hypothese (EMH)

**Kern:** De EMH stelt dat activaprijzen altijd alle beschikbare informatie volledig weerspiegelen, waardoor het systematisch verslaan van de markt in de praktijk onmogelijk is — met directe consequenties voor de waarde van actief beheer.

---

## Definitie en Oorsprong

**Feit:** De Efficiënte Markt Hypothese werd geformaliseerd door Eugene Fama (Universiteit van Chicago) in zijn sleutelartikel uit 1970:

> *"Efficient Capital Markets: A Review of Theory and Empirical Work"*, Journal of Finance, mei 1970.

**Kernstelling:** Activaprijzen weerspiegelen op elk moment *volledig* alle beschikbare informatie. Dit betekent dat het onmogelijk is om op systematische wijze abnormaal rendement te behalen op basis van informatie die al beschikbaar is.

**Feit:** Fama ontving in 2013 de Nobelprijs voor Economie (samen met Lars Peter Hansen en Robert Shiller — ironisch, want Shiller is de prominentste criticus van EMH).

---

## De Drie Vormen van Marktefficiëntie

**Feit (Fama 1970):** Marktefficiëntie wordt niet als binair concept behandeld maar als spectrum met drie vormen, gedefinieerd door de informatieverzameling die verdisconteerd is in de prijs:

### Zwakke Vorm (Weak Form)
**Informatieverzameling:** Historische prijzen en handelsvolumes
**Implicatie:** Technische analyse (patroonherkenning in historische prijsdata) genereert geen abnormaal rendement.
**Testmethode:** Random walk-tests, autocorrelatie-analyse
**Empirische status:** Grotendeels bevestigd voor liquide markten; recent ML-onderzoek vindt zwakke maar inconsistente patronen

### Semi-Sterke Vorm (Semi-Strong Form)
**Informatieverzameling:** Alle openbaar beschikbare informatie (jaarverslagen, winstcijfers, nieuws, macro-data)
**Implicatie:** Fundamentele analyse (waardering op basis van publieke informatie) genereert geen abnormaal rendement. Koersen passen zich onmiddellijk aan op nieuwe publieke informatie.
**Testmethode:** Event studies (hoe snel en volledig reageren koersen op nieuws?)
**Empirische status:** Grotendeels bevestigd voor grote liquide markten; anomalieën bestaan maar zijn inconsistent

### Sterke Vorm (Strong Form)
**Informatieverzameling:** *Alle* informatie, inclusief private (insider) informatie
**Implicatie:** Zelfs insiders kunnen geen abnormaal rendement behalen.
**Empirische status:** **Verworpen.** Insider trading is empirisch aantoonbaar winstgevend (en om die reden illegaal). Studie naar fusie-aankondigingen (arXiv 2012.11594) toont systematische abnormale koersbewegingen vóór publieke bekendmaking.

---

## Het Joint Hypothesis Probleem

**Theorie:** Fama identificeerde een fundamenteel epistemologisch probleem voor EMH-tests:

> Je kunt marktefficiëntie niet testen zonder tegelijkertijd een model van *normale rendementen* te specificeren.

**Implicatie:** Als een studie een anomalie vindt (abnormaal rendement), zijn er twee mogelijke verklaringen:
1. De markt is inefficiënt (EMH klopt niet)
2. Het gebruikte model voor normale rendementen is incorrect

Dit maakt EMH **moeilijk te falsifiëren** — een eigenaardigheid die Popper zou herkennen als problematisch vanuit wetenschapsfilosofisch perspectief.

**Interpretatie:** Het joint hypothesis problem is geen zwakte van EMH maar een fundamenteel kenmerk van alle empirische tests van rationaliteitsmodellen.

---

## Marktanomalieën die EMH Uitdagen

**Feit:** Diverse empirisch gedocumenteerde anomalieën zijn lastig te verzoenen met de semi-sterke EMH:

| Anomalie | Beschrijving | Mogelijke Verklaring |
|---|---|---|
| **Momentum-effect** | Aandelen die recent stegen, stijgen korte termijn door | Psychologische vertraging in informatieverwerking; underreaction |
| **Value premium** | Goedkope aandelen (lage P/B ratio) presteren beter | Risicofactor (Fama-French) vs. behaviorele verklaring (Shiller) |
| **Post-earnings announcement drift (PEAD)** | Koers blijft driften na winstverrassing | Trage informatieverwerking; anchoring |
| **Januari-effect** | Aandelen stijgen meer in januari | Belasting-gedreven verkoop in december; kleine-bedrijven-effect |
| **Kleine-bedrijven-effect** | Kleinere bedrijven presteren gemiddeld beter | Illiquiditeitspremie vs. risicofactor |
| **Crypto-markt inefficiënties** | Bitcoin vertoont voorspelbare patronen (arXiv 2208.07254) | Jonge markt met minder professionele arbitrageurs |

**Interpretatie:** Fama's eigen verklaring (Fama-French model): veel anomalieën zijn compensatie voor hogere risico's, niet bewijs van inefficiëntie. Gedragseconomen (Shiller, Thaler) interpreteren dezelfde data als bewijs van psychologische marktonregelmatigheden.

---

## EMH vs. Gedragseconomie

**Feit:** EMH veronderstelt rationele actoren die informatie onmiddellijk en volledig verwerken. Gedragseconomie (Kahneman, Thaler) toont empirisch aan dat beleggers systematisch irrationeel gedrag vertonen.

**De Adaptive Market Hypothesis (AMH)** — Andrew Lo (2004):
- Marktefficiëntie is niet statisch maar evolutionair: markten zijn efficiënt in de mate dat slimme actoren inefficiënties weghandelen
- Wanneer omgevingscondities veranderen (crises, nieuwe instrumenten), verschijnen tijdelijk nieuwe inefficiënties die verdwijnen zodra arbitrageurs ze ontdekken
- **Interpretatie:** Een synthese die de contradictie tussen EMH en gedragseconomie verdoet door evolutionaire dynamiek te introduceren

---

## Implicaties voor Beleggen

**Feit:** Als de semi-sterke EMH klopt — en dit is de meest empirisch verdedigde positie voor liquide markten — dan zijn de praktische consequenties:

1. **Actief beheer voegt geen waarde toe** — gemiddeld genomen, na kosten
   - SPIVA-data: >85% van actieve fondsbeheerders versloeg de benchmark niet over 15 jaar
   - Buffett's wed (2008–2017): S&P 500 indexfonds versloeg hedge funds

2. **Basis voor passief beleggen (indexbeleggen)**
   - Jack Bogle (Vanguard): als je de markt niet kunt verslaan, koop de markt dan tegen minimale kosten
   - Logische consequentie van semi-sterke EMH

3. **Fundamentele analyse als nulsomspel** — voor elke koper die een ondergewaardeerd aandeel koopt, is er een verkoper die het ondergewaardeerde aandeel verkoopt; gemiddeld genomen is de markt de beste prijsschatting

---

## Feiten vs. Theorie vs. Interpretatie

| Status | Claim |
|---|---|
| **Feit** | Fama (1970) formuleerde de EMH en ontving de Nobelprijs in 2013 |
| **Feit** | Sterke-vorm EMH is empirisch verworpen (insider trading is aantoonbaar winstgevend) |
| **Feit** | Actieve fondsen presteren mediaan slechter dan de benchmark na kosten (SPIVA-data) |
| **Theorie** | Semi-sterke EMH als beste beschrijving van liquide aandelenmarkten — brede consensus maar niet onomstreden |
| **Interpretatie** | Of marktanomalieën bewijs zijn van inefficiëntie of van niet-gemodelleerde risicofactoren — kernvraag in de financiële economie |
| **Speculatie** | Of cryptocurrency-markten fundamenteel anders zijn dan aandelenmarkten m.b.t. efficiëntie |

---

## Verbanden

- [[(C) Gedragseconomie & Cognitieve Biases]] — gedragseconomie als het meest serieuze intellectuele alternatief voor EMH; systematische biases als bron van tijdelijke inefficiënties
- [[(C) Moderne Portefeuilletheorie]] — MPT (Markowitz) en EMH delen de veronderstelling van rationele actoren; maar terwijl EMH gaat over informatieverwerking, gaat MPT over optimale portefeuilleconstructie
- [[(C) MOC - Beleggen]] — EMH als fundamenteel theoretisch kader voor alle beleggingsvragen
- [[02 Wiki/Filosofie/(C) Falsifieerbaarheid & Wetenschapsfilosofie]] — het joint hypothesis probleem als filosofisch probleem van falsifieerbaarheid (Popper)
- [[02 Wiki/Filosofie/(C) Epistemologie & Kennistheorie]] — EMH als epistemologische claim over de grenzen van individuele kennis t.o.v. collectieve marktkennis
- [[02 Wiki/Psychologie/(C) Cognitie & Gedrag]] — cognitieve biases als mechanisme dat semi-sterke EMH tijdelijk ondermijnt
- [[03 Knowledge Graph/(KG) Rationaliteit, Oordeel & Besluitvorming]] — EMH vs. gedragseconomie als het empirisch meest nauwkeurig onderzochte domein van rationeel vs. irrationeel gedrag
- [[03 Knowledge Graph/(KG) Kennis, Rede & Verlichting]] — EMH als Verlichtingsideaal van informatieefficiëntie; de gedragseconomische kritiek als de grenzen van rationeel handelen
- [[(C) ESG & Duurzaam Beleggen]] — als ESG-informatie volledig ingeprijsd is (EMH), levert het per definitie geen extra rendement; inconsistente ratings suggereren informatie-inefficiëntie

---

## Bronnen

- Fama, E. F. (1970). Efficient capital markets: A review of theory and empirical work. *Journal of Finance, 25*(2), 383–417.
- Wikipedia — Efficient-market hypothesis: https://en.wikipedia.org/wiki/Efficient-market_hypothesis
- Wikipedia — Eugene Fama: https://en.wikipedia.org/wiki/Eugene_Fama
- arXiv 2012.11594 (insider trading voor fusies): https://arxiv.org/pdf/2012.11594
- arXiv 2305.17419 (random generators & efficiëntie): https://arxiv.org/pdf/2305.17419
- arXiv 2208.07254 (Bitcoin & EMH): https://arxiv.org/pdf/2208.07254
- arXiv 1909.05151 (ML & zwakke-vorm EMH): https://arxiv.org/pdf/1909.05151
- Lo, A. W. (2004). The Adaptive Markets Hypothesis. *Journal of Portfolio Management, 30*(5), 15–29.

> **Status:** Verwerkt door Wiki-Agent
> **Laatste update:** 2026-07-01
