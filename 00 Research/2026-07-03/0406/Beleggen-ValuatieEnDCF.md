# RAW DATA — Beleggen: Valuatie & DCF-analyse

**Status:** RAW DATA — geen interpretatie
**Datum:** 2026-07-03
**Agent:** Knowledge-Hunter
**Bron:** Synthese op basis van Damodaran (2002, 2012), Graham & Dodd (1934), Buffett brieven (1977–2023), Copeland et al. (1990), CFA Curriculum
**source_score:** 9/10
**confidence:** 0.90
**novelty:** 1.0 (ontbreekt volledig in wiki)
**trust_level:** hoog

---

## Definitie

- **Valuatie** = het proces van het bepalen van de intrinsieke waarde van een actief (aandeel, bedrijf, obligatie, vastgoed)
- **DCF (Discounted Cash Flow)** = valuatiemethode waarbij toekomstige kasstromen worden verdisconteerd naar de huidige waarde met een passende disconteringsvoet
- Grondprincipe: **een euro morgen is minder waard dan een euro vandaag** (tijdswaarde van geld)
- Alternatief voor marktprijsbepaling: intrinsieke waarde ≠ marktprijs → beleggingskansen bij divergentie

## Tijdswaarde van Geld — Fundament

### Basisformule
- **Toekomstige Waarde (FV):** FV = PV × (1 + r)^n
- **Huidige Waarde (PV):** PV = FV / (1 + r)^n
- **Perpetuïteit:** PV = C / r (oneindige kasstroom)
- **Groeiende perpetuïteit (Gordon Growth Model):** PV = C₁ / (r - g)

### Disconteringsvoet
- Weerspiegelt: tijdsvoorkeur + risicocompensatie
- **Risicovrije rente**: staatsoblgaties (bijv. 10-jaar US Treasury)
- **Risicopremie**: extra rendement voor het dragen van aandelenrisico (Damodaran: ~5-6% historisch)

## DCF-methodologie

### Stap 1: Projectie van Vrije Kasstromen (FCF)
- **Free Cash Flow to Firm (FCFF)** = EBIT × (1 - belastingvoet) + Afschrijvingen − ΔWerkkapitaal − Capex
- **Free Cash Flow to Equity (FCFE)** = Nettowinst + Afschrijvingen − ΔWerkkapitaal − Capex + Netto Leningen
- Projectieperiode: doorgaans 5–10 jaar expliciet

### Stap 2: Terminal Value (Eindwaarde)
- Meest kritische en onzekere component — ~70-80% van totale DCF-waarde
- **Gordon Growth Model**: TV = FCF_n × (1+g) / (WACC - g)
- **Exit Multiple methode**: TV = EBITDA_n × EV/EBITDA-multiple van comparables
- Sensitief voor aannames: 1% verschil in g of WACC → drastische waardewijziging

### Stap 3: Disconteringsvoet (WACC)
- **WACC** = Gewogen Gemiddelde Vermogenskostenvoet
- WACC = (E/V) × Re + (D/V) × Rd × (1-T)
  - E = marktwaarde eigen vermogen; D = marktwaarde vreemd vermogen; V = E+D
  - Re = kosten eigen vermogen (CAPM); Rd = kosten vreemd vermogen; T = belastingvoet

### Stap 4: CAPM voor Kosten Eigen Vermogen
- **Capital Asset Pricing Model**: Re = Rf + β × (Rm - Rf)
  - Rf = risicovrije rente
  - β (beta) = systematisch risico (marktgevoeligheid)
  - (Rm - Rf) = marktrisicopremie
- Kritiek op CAPM: Fama-French (1992) — beta alleen niet voldoende; grootte- en value-premie

### Stap 5: Enterprise Value → Equity Value
- Enterprise Value (EV) = Som van verdisconteerde FCF's + Terminal Value
- **Equity Value** = EV − Netto Schuld
- **Intrinsieke aandeelkoers** = Equity Value / Aantal aandelen uitstaand

## Alternatieve Valuatiemethoden

### Relatieve Waardering (Multiples)
| Multiple | Formule | Gebruik |
|---------|---------|---------|
| P/E | Koers / Winst per aandeel | Winstgevende bedrijven |
| EV/EBITDA | Enterprise Value / EBITDA | Sector-onafhankelijk |
| EV/Sales | Enterprise Value / Omzet | Verlieslatende bedrijven |
| P/B | Koers / Boekwaarde | Financiële instellingen |
| P/FCF | Koers / Free Cash Flow | Volwassen bedrijven |

### Dividend Discount Model (DDM)
- Gordon (1956): P = D₁ / (k - g)
- Geschikt voor dividendbetalende volwassen bedrijven (nutsbedrijven, REIT's)
- Beperkingen: te afhankelijk van stabiele dividendgroei

### Liquidatiewaarde & Sum-of-the-Parts
- Netto Activa Waarde (NAV): marktwaarde activa − verplichtingen
- Relevant bij: holdingcompanies, conglomeraten, vastgoedbedrijven, banken

### Optie-gebaseerde Waardering (Real Options)
- Black-Scholes aanpassen voor strategische opties in bedrijven (bijv. mijnbouwrechten, farmaceutische pijplijn)
- Relevant wanneer conventionele DCF waarde systematisch onderschat

## Valkuilen & Gedragseconomische Biases

- **Garbage in, garbage out**: DCF zo goed als aannames — projecties zijn geen feiten
- **Anchoring**: eerste koers/multiple bepaalt anker voor all verdere aanpassingen
- **Overconfidence**: te smalle bandbreedtes bij projecties (Kahneman & Lovallo, 1993)
- **Confirmation bias**: selectief zoeken naar informatie die eigen thesis bevestigt
- **Recency bias**: groeiprojecties te sterk gebaseerd op recente trends
- **Precision illusion**: DCF geeft pseudoprecisie (getal met twee decimalen) terwijl aannames grove onzekerheid hebben

## Margin of Safety (Graham & Dodd)

- **Benjamin Graham** (*Security Analysis*, 1934; *The Intelligent Investor*, 1949): koop alleen als marktprijs substantieel onder intrinsieke waarde (30-50% korting)
- **Veiligheidsmarge**: buffer voor fouten in aannames en onvoorziene omstandigheden
- Buffett: "Price is what you pay. Value is what you get."
- Intrinsieke waarde is inherent onzeker → margin of safety compenseert voor die onzekerheid

## Verbindingen met Andere Disciplines

- **Hyperbolic Discounting**: mensen disconteren hyperbolisch (steil kortetermijn, vlak langetermijn) → onderinvestering in langetermijn groei; rationele DCF veronderstelt constante disconteringsvoet
- **Gedragseconomie**: cognitieve biases ondermijnen rationele DCF — marktprijzen reflecteren collectieve biases, niet intrinsieke waarden
- **Efficiënte Markt Hypothese**: als markten efficiënt zijn, is DCF futiel → fundamentele spanning met waardebeleggen
- **Psychologie (Ruminatie)**: angst en onzekerheid bij valuatie → paralysis door analyse
- **Filosofie (Epistemologie)**: wat kunnen we weten over toekomstige kasstromen? Fundamentele kenniskritiek
- **Geschiedenis**: beurscrises als case studies in valuation failure (dot-com: hoge groeiprojecties bij nulrente-disconto)

## Praktisch Gebruik

- **Bedrijfsovernames (M&A)**: DCF voor bod-bepaling; synergieberekening
- **IPO-waardering**: bank bepaalt uitgiftekoers via comparable company analysis + DCF
- **Private equity**: LBO-modellen (Leveraged Buy-Out) met FCF voor schuldaflossing
- **Vastgoed**: Netto Contante Waarde van huurinkomsten

## Sleutelliteratuur

- Graham, B. & Dodd, D. (1934). *Security Analysis*. McGraw-Hill.
- Damodaran, A. (2002). *Investment Valuation*. Wiley. [→ damodaran.com voor gratis tools]
- Copeland, T. et al. (1990). *Valuation: Measuring and Managing the Value of Companies*. McKinsey & Company.
- Buffett, W. (1977–2023). *Berkshire Hathaway Annual Letters to Shareholders*.
- CFA Institute. (2023). *CFA Program Curriculum*. Level 2: Equity Valuation.
- Kahneman, D. & Lovallo, D. (1993). Timid choices and bold forecasts. *Management Science*, 39(1), 17–31.
