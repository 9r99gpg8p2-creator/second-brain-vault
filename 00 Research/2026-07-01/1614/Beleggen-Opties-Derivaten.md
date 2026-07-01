# RAW DATA — Opties & Derivaten
> Label: RAW DATA | Agent: Knowledge-Hunter | Datum: 2026-07-01 16:14
> source_score: 8 | confidence: 0.87 | novelty: 0.88 | trust_level: hoog

## Bronnen
- FXOptions.com — "Understanding the Black-Scholes Model: Key Insights & Applications"
- Wikipedia — "Black–Scholes model"
- FasterCapital — "Black-Scholes Model: How to Price Options and Derivatives"
- MDPI Mathematics (2025) — "A General Conformable Black–Scholes Equation for Option Pricing"
- arXiv — numerieke methoden voor Black-Scholes vergelijkingen

## Kernpunten

### Definitie derivaten
- Derivaat: financieel contract waarvan de waarde afgeleid is van een onderliggende waarde (aandeel, index, grondstof, valuta, rente)
- Doel: risicobeheer (hedging), speculatie, arbitrage
- Soorten: opties, futures, forwards, swaps

### Opties — basis
- **Call-optie**: recht (niet plicht) om onderliggend te KOPEN tegen afgesproken prijs (strike) vóór/op expiratie
- **Put-optie**: recht (niet plicht) om onderliggend te VERKOPEN tegen strike
- **Premie**: prijs die koper betaalt voor het recht
- **Europese optie**: alleen uitoefenbaar op expiratie
- **Amerikaanse optie**: uitoefenbaar op elk moment tot expiratie

### Black-Scholes model (1973)
- Ontwikkeld door Fischer Black en Myron Scholes (1973); Nobel Economie 1997 (Scholes + Merton)
- "Mathematical model for the dynamics of a financial market containing derivative investment instruments"
- Formule berekent theoretische prijs van Europese opties op basis van: huidige aandeelprijs, strike, looptijd, risicovrije rente, volatiliteit (σ)
- Aannames: continue handel, geen dividenden, constante volatiliteit, log-normale prijsverdeling
- Kritiek: volatiliteit is in werkelijkheid niet constant (volatility smile/skew)

### Griekse letters (Greeks) — risicomanagement
- **Delta (Δ)**: gevoeligheid optieprijs voor prijsverandering onderliggende
- **Gamma (Γ)**: snelheid waarmee delta verandert
- **Theta (Θ)**: tijdsverval van optiewaarde (time decay)
- **Vega (ν)**: gevoeligheid voor volatiliteitsveranderingen
- **Rho (ρ)**: gevoeligheid voor renteveranderingen

### Risicomanagement met derivaten
- "Derivatives help in managing risks by allowing banks, companies, organizations to divide their risk into several pieces passed off to other entities"
- Hedging: portefeuille beschermen tegen neerwaarts risico via put-opties
- Systematisch risico vs. idiosyncratisch risico: derivaten kunnen specifiek risico isoleren

### Gevaren
- Leverage: kleine premieinvestering controleert grote positie
- Counterparty risk: bij OTC-derivaten (niet via beurs)
- Complexiteit: 2008-crisis deels veroorzaakt door mispricing van complexe derivaten (CDO's, CDS's)

## Kernprincipes
- **Feit**: Black-Scholes is wiskundig fundament voor optiewaardering
- **Feit**: opties geven rechten, geen verplichtingen
- **Interpretatie**: Black-Scholes veronderstelt constant volatiliteit — in praktijk onjuist
- **Risico**: derivaten zijn tweesnijdend zwaard; zowel hedge als hefboom

## Verbindingen met bestaande wiki
- [[Moderne Portefeuilletheorie]] — risico-rendementrelatie; diversificatie
- [[Efficiënte Markt Hypothese]] — zijn optieprijzen efficiënt?
- [[Gedragseconomie & Cognitieve Biases]] — optiehandel en cognitieve fouten (overconfidence, loss aversion)
- [[Rente & Centrale Bankpolitiek]] — rente als input in Black-Scholes; rentegevoeligheid via rho
