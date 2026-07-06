# RAW DATA — Beleggen: Shortsellen & Contraire Beleggingsstrategieën

**Status:** RAW DATA — geen interpretatie, alleen bronmateriaal  
**Agent:** Agent1-KnowledgeHunter  
**Datum:** 2026-07-06  
**Databron:** Trainingskennis (Wikipedia-API geblokkeerd door egressbeleid)  
**source_score:** 8/10  
**confidence:** 0.87  
**novelty:** 1.0  
**trust_level:** hoog  

---

## Kernbronnen

- Fabozzi, F.J. (ed.) (2004). *Short Selling: Strategies, Risks, and Rewards*. Wiley.
- Shiller, R.J. (2000). *Irrational Exuberance*. Princeton University Press.
- Kindleberger, C.P., & Aliber, R.Z. (2005). *Manias, Panics, and Crashes*. Palgrave Macmillan.
- Lamont, O.A., & Thaler, R.H. (2003). Can the market add and subtract? Mispricing in tech stock carve-outs. *Journal of Political Economy*, 111(2), 227–268.
- D'Avolio, G. (2002). The market for borrowing stock. *Journal of Financial Economics*, 66(2–3), 271–306.
- Asquith, P., Pathak, P., & Ritter, J.R. (2005). Short interest, institutional ownership, and stock returns. *Journal of Financial Economics*, 78(2), 243–276.
- Soros, G. (1994). *The Alchemy of Finance*. Wiley.

---

## Definitie & Mechanisme

- **Short selling (shortsellen):** strategie waarbij een belegger aandelen leent, ze verkoopt op de markt, en ze later terugkoopt (hopelijk voor een lagere prijs) om ze terug te geven aan de uitlener.
- Doel: profiteren van koersdaling.
- Winst = verkoopprijs − terugkoopprijs − kosten (leenkosten, dividendbetalingen).

### Stappen
1. Belegger leent aandelen bij broker of andere partij (securities lending).
2. Verkoopt de geleende aandelen onmiddellijk op de markt (short entry).
3. Wacht op koersdaling.
4. Koopt aandelen terug op de markt (covering the short).
5. Geeft aandelen terug aan uitlener.

---

## Risicoprofiel

- **Onbeperkt verliesrisico:** een long-positie kan maximaal 100% verliezen; een short-positie heeft theoretisch onbeperkt verlies (aandelenkoers kan onbeperkt stijgen).
- **Short squeeze:** als koers stijgt, worden shortverkopers gedwongen te coveren → dit drijft koers verder op → cascade.
  - Beroemd voorbeeld: GameStop (GME), januari 2021 — Reddit-gemeenschap (r/WallStreetBets) drijft koers van ~$20 naar ~$483.
  - Historisch: Volkswagen short squeeze (2008) — tijdelijk duurste bedrijf ter wereld door Porsche-aankondiging.
- **Margin calls:** broker kan extra onderpand eisen als verlies oploopt.
- **Borrowing costs:** moeilijk te lenen aandelen (hard-to-borrow) hebben hoge leenrente.
- **Dividendrisico:** shortverkoper moet dividend betalen aan uitlener.

---

## Marktfunctie van Short Selling

- **Prijsontdekking:** shortverkopers brengen negatieve informatie in de prijs → marktefficiëntie verbeterd.
- **Liquiditeit:** grotere handel → smaller bid-ask spreads.
- **Bescherming tegen bubbels:** short selling remt overmatige koersstijgingen.
- Bewijs: markten met short-selling verboden (China 2015, diverse markten tijdens crises) tonen grotere bubbels en snellere crashes.
- Fama & French: shortsellers zijn on average goed geïnformeerd; hun signalen zijn informatief.

---

## Regulering & Beperkingen

- **Naked short selling:** verkopen zonder aandelen daadwerkelijk te lenen → illegaal in de VS (SEC Rule 10b-21, 2008) en EU.
- **Uptick rule (VS, 1938–2007, heringevoerd 2010):** short selling alleen toegestaan op uptick (stijgende koers) — bedoeld om paniekverkopen te beperken.
- **Short-selling verboden:** tijdens financiële crisissen (2008: financiële aandelen VS/EU; COVID-19 2020: diverse Europese markten).
- Regelgevers: SEC (VS), AFM (NL), ESMA (EU).
- Transparantie: meldplicht bij short-posities > 0,5% (EU Short Selling Regulation, 2012).

---

## Contraire Beleggingsstrategieën

- **Contraire strategie:** positie innemen tegen de heersende marktsentiment.
- Theoretische basis: mean reversion — buitensporig gestegen of gedaalde assets keren terug naar gemiddelde.
- **Value investing als contraire strategie:** kopen wat anderen dumpen (Graham, Buffett).
- **Short interest ratio:** hoge short interest als contrair koopsignaal (Asquith et al., 2005 — stocks with high short interest underperform).
- Soros' reflexiviteitstheorie: markten beïnvloeden de fundamentals die ze proberen te meten → mogelijkheid voor contraire posities op zelfreferentiële bubbels.

### Bekende Contraire Shortposities
- **Michael Burry (2005–2007):** short op subprime mortgage-backed securities → $700 mln+ winst (boek/film: *The Big Short*).
- **Jim Chanos (2001):** short Enron voordat fraude publiek bekend werd.
- **George Soros (1992):** short op het Britse pond → "the man who broke the Bank of England" → £1 mrd winst in één dag.

---

## Short Selling & Gedragseconomie

- **Overoptimisme bias:** beleggers systematisch te positief → prijzen structureel te hoog → ruimte voor shorters.
- **Limits to arbitrage (Shleifer & Vishny, 1997):** rationele arbitrageurs (inclusief shortverkopers) kunnen niet altijd mispricing corrigeren:
  - Kosten en risico's van short selling zijn hoog.
  - Irrationeel gedrag kan langer aanhouden dan short-positie houdbaar is.
  - "The market can remain irrational longer than you can remain solvent" (toegeschreven aan Keynes).
- **Herding & momentum:** kortetermijn momentum werkt tegen contraire posities.
- **Regret aversion:** shorters die verliezen maken zijn zichtbaar "fout" → psychologische druk om te sluiten.

---

## Short Interest als Signaal

- **Short interest ratio (SIR) / Days to cover:** hoe lang om alle shortposities te coveren gegeven dagelijks handelsvolume.
- Hoge SIR + dalende fundamentals = bearish signaal.
- Hoge SIR + stijgende koers = squeeze-risico.
- Empirisch: stocks met hoge short interest hebben lagere toekomstige rendementen (Asquith et al., 2005; Desai et al., 2002).

---

## Securities Lending Markt

- Omvang: biljoenen dollars dagelijks.
- Partijen: institutionele beleggers (pensioenfondsen, ETF-beheerders) lenen aandelen uit voor extra rendement.
- Kosten: uitgedrukt als jaarlijkse spread (borrow rate); normaal 0,25–1%; voor hard-to-borrow stocks: >50%.
- Bijdrage van securities lending aan rendement: pensioenfondsen halen soms 0,1–0,3% extra p.j.

---

## Verbindingspunten (voor Knowledge Graph)

- → Efficiënte Markt Hypothese (short selling verbetert of weerlegt EMH)
- → Marktbubbels & Irrational Exuberance (Shiller; short selling als bubbel-rem)
- → Gedragseconomie & Cognitieve Biases (limits to arbitrage; overoptimisme)
- → Marktpsychologie & Beurscrises (short squeeze, paniek, GameStop)
- → Risico vs. Onzekerheid — Knight's Onderscheid (onbeperkt verliesrisico)
- → Market Microstructure & Liquiditeit (securities lending, bid-ask)
- → Waardebeleggen (contraire strategie)
- → Antifragiliteit & Complexe Systemen (Taleb shorted subprime)
- → Narratieve Economie & Virale Financiële Verhalen (GameStop als meme-aandeel)
