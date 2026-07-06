---
type: concept
id: 99fc6c5e-7eae-3d3e-af26-930baae63ef3
title: TOE - Statistiek
summary: "Statistische methoden toegepast op psychologisch onderzoek — van beschrijvende statistiek tot inferentiële toetsen in JASP."
category: Psychologie
tags: [concept, statistiek, onderzoek, jaar-1, blok-3]
aliases: ["TOE - Statistiek"]
sources:
  - type: raw
    path: "01 Raw/Psychologie/Jaar 1 BSc/TOE - J1 B3 - UU./Toepassing van statistiek samenvatting J1 B3..docx"
    trust_level: 7
confidence_score: 0.75
quality_score: 0.7
freshness_score: 0.8
importance_score: 0.88
novelty_score: 1.0
knowledge_score: 0.782
usage_score: 0.0136
related_nodes:
  - "02 Wiki/Psychologie/(C) Psychologie als Wetenschap"
  - "02 Wiki/Psychologie/(C) Cognitie & Gedrag"
  - "02 Wiki/Psychologie/(C) Ontwikkelingspsychologie"
revision_history:
  - version: 1
    date: 2026-07-01
    author: Brain-Guardian
    change: initial YAML scaffolding by guardian routine
  - version: 2
    date: 2026-07-02
    author: Brain-Guardian
    change: kwaliteitscontrole — uitgebreid met effectgroottes, Type I/II fouten, poweranalyse, pre-registratie; wikilinks naar Falsifieerbaarheid en Epistemologie toegevoegd
---

# TOE — Toepassing van Statistiek

**Vak:** BSc Jaar 1 | Blok 3
**Kern:** Statistische methoden toegepast op psychologisch onderzoek — van beschrijvende statistiek tot inferentiële toetsen in JASP.

---

## Kernconcepten

- **Beschrijvende statistiek** — gemiddelde, mediaan, standaarddeviatie, variantie
- **Kansrekening** — normale verdeling, z-scores, betrouwbaarheidsintervallen
- **T-toetsen** — one-sample, independent samples, paired samples
- **ANOVA** — one-way, factorial; post-hoc toetsen
- **Regressie** — enkelvoudig, meervoudig; voorspellen en verklaren
- **Correlatie** — Pearson, Spearman; causaal vs. associatief
- **Betrouwbaarheidsanalyse** — Cronbach's alpha, interne consistentie
- **JASP** — statistische software; Bayesiaanse en frequentistische analyses
- **APA-rapportage** — statistische resultaten correct rapporteren

---

## Gebruikte datasets

- Reactietijden (CG-experiment)
- Theory of Mind — kinderen & adolescenten
- PTSD-schaal
- Persoonlijkheidstest
- Slaapproblemen
- Rekenprestaties

---

## Diepere Analyse

### Effectgrootte — het ontbrekende stuk

Een statistisch significante *p*-waarde zegt niets over de *grootte* van het effect. Bij grote steekproeven is vrijwel elk triviaal verschil significant. De effectgrootte kwantificeert de praktische betekenis:

- **Cohen's d** (voor t-toetsen): d = 0.2 (klein), 0.5 (middelgroot), 0.8 (groot)
- **η² / ω²** (voor ANOVA): proportie verklaarde variantie
- **Pearson's r** (voor correlaties): r = 0.1 (klein), 0.3 (middelgroot), 0.5 (groot)

### Type I en Type II Fouten

Twee fundamentele fouten in inferentiële statistiek:
- **Type I fout** (α): ten onrechte H₀ verwerpen — een effect zien dat er niet is (vals positief). Conventioneel α = 0.05 betekent 5% kans op een Type I fout.
- **Type II fout** (β): ten onrechte H₀ accepteren — een effect missen dat er wél is (vals negatief). Power = 1 − β; gebruikelijke norm is power ≥ 0.80.

Met kleine steekproeven is de power laag: echte effecten worden gemist. Poweranalyse *vóór* het onderzoek (a priori) bepaalt de benodigde steekproefgrootte.

### Pre-registratie en Open Science

Om *p*-hacking en HARKing te voorkomen, registreert de onderzoeker vóór dataverkrijging: hypothesen, design, analysemethoden en uitsluitingscriteria. Platforms: **OSF** (Open Science Framework), **AsPredicted.org**. Pre-registratie maakt het onderscheid tussen exploratief (hypothesegenerend) en confirmatief (hypothesetoetsend) onderzoek expliciet — een fundamenteel methodologisch onderscheid dat in reguliere publicaties zelden wordt gemaakt.

## Verbanden

- [[Psychologie als Wetenschap]] — statistiek is het gereedschap van wetenschappelijk redeneren
- [[Cognitie & Gedrag]] — reactietijddata geanalyseerd
- [[Ontwikkelingspsychologie]] — ToM-data geanalyseerd
- [[Falsifieerbaarheid & Wetenschapsfilosofie]] — de replicatiecrisis raakt direct aan Popperiaanse falsificeerbaarheid
- [[Epistemologie & Kennistheorie]] — statistische inferentie als kennistheorie: wat weten we eigenlijk na *p* < .05?

---

## Bronnen

- `01 Raw/Psychologie/Jaar 1 BSc/TOE - J1 B3 - UU./Toepassing van statistiek samenvatting J1 B3..docx`

---

> **Status:** Basis aangemaakt — uitbreiden na bestudering samenvatting
