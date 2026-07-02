# RAW DATA — Beleggen: Factor Investing

> Label: RAW DATA | Agent: Agent1-KnowledgeHunter | Datum: 2026-07-02 07:00 UTC
> Bronnen: Fama-French originele papers, Quantt, Verified Investing, Alpha Architect, WebSearch

---

## Kernbronnen

- Quantt: Fama-French Model Explained 2026 (https://www.quantt.co.uk/resources/fama-french-model-explained)
- Verified Investing: Factor Investing – Smart Beta (https://verifiedinvesting.com/blogs/education/factor-investing-smart-beta-from-ivory-tower-theory-to-mainstream-etf-revolution)
- Alpha Architect: The Investment Factor (https://alphaarchitect.com/dissecting-the-investment-factor/)
- Grokipedia: Factor Investing (https://grokipedia.com/page/Factor_investing)

---

## Definitie

- Factor investing: beleggingsstrategie waarbij portefeuilles worden geconstrueerd op basis van specifieke karakteristieken ("factoren") van effecten die historisch verklaren waarom bepaalde aandelen hogere rendementen behalen
- Doel: systematisch extra rendement (alpha) verdienen boven de markt via bewezen factorpremies
- Ook bekend als: smart beta, systematic investing, style investing, quantitative investing

---

## Historische Ontwikkeling

### CAPM (1964–1966)
- Capital Asset Pricing Model: Sharpe, Lintner, Mossin
- Enige factor: marktrisico (beta) → verwacht rendement
- Probleem: empirisch onvoldoende verklarend

### Fama-French 3-Factor Model (1992–1993)
- Eugene Fama & Kenneth French: baanbrekend paper
- Drie factoren:
  1. **Markt** (Rm - Rf): marktpremie
  2. **SMB** (Small Minus Big): small-cap premie
  3. **HML** (High Minus Low): waardepremie (hoge book-to-market vs. lage)
- t-statistieken: HML = 2,91; SMB = 1,73 (over 1963–1991)
- Conclusie: value en size verklaren rendementen die CAPM mist

### Fama-French 5-Factor Model (2015)
- Uitbreiding met twee additionele factoren:
  4. **RMW** (Robust Minus Weak): winstgevendheidspremie
  5. **CMA** (Conservative Minus Aggressive): investeringsfactor
- Bedrijven met lage investeringen presteren beter dan bedrijven met hoge investeringen

### Momentum Factor (Jegadeesh & Titman 1993)
- Aandelen die de afgelopen 3–12 maanden goed presteerden, presteren volgend jaar ook beter
- Sterkste en meest robuuste factor over markten
- Niet opgenomen in Fama-French (anomalie voor efficient market hypothesis)

---

## De Zes Klassieke Factoren

| Factor | Definitie | Premie-verklaring |
|---|---|---|
| **Waarde** (Value) | Goedkope aandelen (lage P/B, P/E) | Risico-gebaseerd of behavioraal (irrationele afkeer) |
| **Grootte** (Size) | Small-cap aandelen | Hogere liquiditeitsrisico; neglect effect |
| **Momentum** | Recente winnaars | Behavioraal: underreaction, trend-following |
| **Kwaliteit** (Quality) | Winstgevende, lage-schuld bedrijven | Veiligheidsvoorkeur; pricing inefficiëntie |
| **Lage Volatiliteit** (Low Vol) | Aandelen met lage koersfluctuaties | Anomalie: zou theoretisch lager rendement geven |
| **Winstgevendheid** (Profitability) | Hoge brutomargebedrijven | Operational efficiency als onderschatting |

---

## Empirisch Bewijs

- Value-premie: consistent aangetoond over 1926–2000 in VS; zwakker na 2000 (technologiebubble)
- Momentum: meest robuust internationaal (VS, Europa, Azië, emerging markets)
- Size-premie: zwak tot afwezig na liquiditeitscorrectie in sommige markten
- International markets: factoren aanwezig maar in verschillende magnitude
- Recente kritiek: factor crowding — naarmate meer geld factoren volgt, slinkt de premie

---

## Verklaring van Factorpremies

### Risico-gebaseerde verklaring (Fama-French zelf)
- Factoren compenseren voor systematisch risico dat CAPM mist
- Value-aandelen zijn risicovoller in slechte economische tijden (distress risk)

### Behaviorale verklaring (Shleifer, Thaler, De Bondt)
- Beleggers maken systematische fouten (overreactie op nieuws → value; onderreactie → momentum)
- Cognitieve biases: representativiteitsheuristiek, verankering, kuddegedrag

---

## Praktische Implementatie

### Smart Beta ETF's
- Goedkope, passieve fondsen die factorblootstelling bieden
- Voorbeelden: iShares Edge MSCI Value Factor ETF; Vanguard Value ETF; AQR Momentum ETF
- Voordeel: lage kosten, systematisch, gedisciplineerd
- Nadeel: factor crowding; moeilijk tijden overleven (drawdowns soms jaren)

### Multi-Factor Portefeuilles
- Combineren factoren voor diversificatie van factor-specifiek risico
- Correlatie tussen factoren: value en momentum zijn negatief gecorreleerd (goede diversifier)

---

## Kritiek & Beperkingen

- Data mining: met genoeg variabelen vind je altijd iets dat historisch werkt
- Publication bias: alleen succesvolle factoren worden gepubliceerd
- Transactiekosten: momentum vereist frequent handelen → hoge kosten
- Factor timing: welke factor wanneer over- of onderpresteren is onbekend
- International applicability: factoren werken niet uniform over alle markten

---

## Verbindingen (bestaande wiki)

- [[02 Wiki/Beleggen/(C) Moderne Portefeuilletheorie]] — CAPM als startpunt van factordiscussie
- [[02 Wiki/Beleggen/(C) Efficiënte Markt Hypothese]] — factoren als bewijs tégen EMH
- [[02 Wiki/Beleggen/(C) Gedragseconomie & Cognitieve Biases]] — behaviorale verklaring factorpremies
- [[02 Wiki/Beleggen/(C) Marktpsychologie & Beurscrises]] — momentum als groepsgedrag

---

## Annotaties

- source_score: 8/10 (academische papers, gespecialiseerde financiële bronnen)
- confidence: 0.87
- novelty: 1.0 (geen wiki-pagina over factor investing)
- trust_level: hoog
