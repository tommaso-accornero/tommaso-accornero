### Hi, I'm Tommaso
**Computational Social Scientist | Economics + Data**

I use R, Python, and SQL to turn messy social and economic data into research I can defend. NLP on IMF policy documents, trade networks, regional inequality, or even a model that's fairly confident Spain wins the World Cup.

---

### Background
- MSc Computational Social Science @ Universidad Carlos III de Madrid (2026) — top 1–2% of cohort; thesis graded 10/10, cum laude decision pending (UC3M caps cum laude at two per cohort and waits on the full cohort)
- Currently in a second Master's in Economics: Empirical Applications and Policies (EAP) @ EHU/UPV, Bilbao (2026–)
- Research Assistant @ Sciences Po – InclusiveParl Project (Dec 2025 – May 2026): SPARQL + web scraping for European parliamentary representation data
- BSc Economics and Business Economics @ Utrecht University (2022)
- Family connection: AccorneroVini, a winery in Monferrato, Piedmont, where I first got interested in market data

### What I'm Working On
- Finding a path to publish my thesis (BERT classification of ~12,000 IMF conditions, 1980–2024).
- Building out the econometrics and causal-inference side of my toolkit through the EAP program
- A working paper on degrowth readiness typologies across 254 EU regions, SSRN upload and a VoxEU column still pending

### Featured Projects

**[MSc Thesis — BERT Classification of IMF Conditionality](https://github.com/tommaso-accornero/bert-imf-conditionality)**
NLP classification of ~12,000 IMF loan conditions, 1980–2024, testing whether conditionality scope expanded over time. Graded 10/10, cum laude pending.
`Python` `BERT` `R`

**[World Cup 2026 Prediction Model](https://github.com/tommaso-accornero/wc2026-prediction)**
ELO ratings back to 1994, a Poisson expected-goals model, and manual overrides for the ~16 teams where the numbers miss what watching too much football actually tells you, carried through the knockouts with a bracket simulator. Finished top 100 of ~6,600 entries in a DataCamp forecasting competition. (Model has Spain winning it all!)
`R` `Poisson` `Forecasting`

**[European Degrowth Typology](https://github.com/tommaso-accornero/european-regional-degrowth-typology)**
PCA + hierarchical and K-means clustering on 254 EU NUTS-2 regions to identify structural typologies of degrowth readiness. Validated externally against CO₂ emissions and life expectancy.
`R` `Eurostat` `ggplot2`

**[Italian Wine Export Market Analysis](https://github.com/tommaso-accornero/wine-export-market-analysis)**
Panel regression on 103 wine-importing countries (615 country-year observations, 2018–2024, UN Comtrade + World Bank) testing whether GDP per capita predicts Italian wine market share. Found a threshold near $8,000 GDP per capita — below it, income growth barely moves market share; above it, the effect more than doubles. Fixed-effects specification confirmed via Hausman test, with regional and robustness checks throughout. Grew up around this problem before I had the tools to study it properly.
`R` `plm` `Panel Data`

**[Product Space — Network Analysis of Global Trade Complexity](https://github.com/tommaso-accornero/product-space-analysis)**
Reproduced Hidalgo & Hausmann (2007) using Python and NetworkX. Structural analysis of 774 economic products: power-law degree distribution, Louvain community detection (35 sectors, modularity = 0.76), centrality analysis, configuration model test (Z = 160).
`Python` `NetworkX` `Network Science`

**[Roma Acceptance in the EU — Multilevel Analysis](https://github.com/tommaso-accornero/roma-multilevel-eu)**
Multilevel model (lme4) on Eurobarometer 493 — 27,438 respondents across 28 EU countries. Multiple imputation via mice. Individual- and country-level drivers of Roma workplace acceptance.
`R` `lme4` `Survey Methods`

**[Customer Churn ML — Telco](https://github.com/tommaso-accornero/churning-customers-ml)**
Supervised ML pipeline on IBM Telco data (7,043 records): churn classification and total-charges regression across nine models. Focus on class imbalance, cost-sensitive thresholds, and interpretable business insight.
`R` `caret` `glmnet`

**[Spanish Schools Heat Vulnerability Pipeline](https://github.com/tommaso-accornero/spanish-schools-heat-vulnerability-scraper)**
Production-ready R pipeline integrating four government APIs (CartoCiudad, Nominatim, Catastro, AEMET) to assess climate heat vulnerability across 999 schools — 261,406 observations. Diagnosed a silent API failure that was quietly dropping data before it reached the model.
`R` `API` `Policy`

**[Changing Fortunes — FT Visualization Replication](https://github.com/tommaso-accornero/changing-fortunes-dataviz)**
Full replication and redesign of the Financial Times "Changing Fortunes" slope chart on US median household income inequality (1999–2014).
`R` `ggplot2` `Data Visualization`

### Tech Stack
`R` `Python` `SQL` `Git`

**Methods:** Regression · Causal Inference · Machine Learning · NLP / Text Classification · Multilevel Modeling · PCA & Clustering · Survey Analysis · Web Scraping · Data Visualization
**Libraries:** tidyverse · ggplot2 · lme4 · mice · caret · glmnet · randomForest · xml2 · sf · factoextra
**Data Sources:** Eurostat · Eurobarometer · IMF MONA · World Bank · Catastro · AEMET · CartoCiudad

### Research & Writing
- **IMF Conditionality Thesis** — BERT classification of ~12,000 IMF conditions across 44 years. Graded 10/10; working on a route to publication.
- **Sciences Po – InclusiveParl** — Web scraping + SPARQL pipelines for European parliamentary representation databases.
- **Wine Export Panel** — Fixed-effects panel analysis of 103 countries' wine trade; AAWE conference abstract under review.

### Get in Touch
- Email: tommaso.accornero@outlook.com
- LinkedIn: linkedin.com/in/tommaso-accornero-4084931a9
- Location: Bilbao, Spain
- Looking for: a path to a PhD in political economy / computational social science (targeting Fall 2027 applications) — open to a strong analytics or research role in the meantime
