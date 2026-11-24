# Awesome Macroeconomics 🌐📊📈🏛️

*A curated, exhaustive list of awesome frameworks, libraries, lecture notes, textbooks, seminal papers, datasets, computational tools, and open-source models for studying and researching Macroeconomics.*

## 📖 Table of Contents

* [Foundational Concepts & Pillars](#-foundational-concepts--pillars)
* [Textbooks & Reading Lists](#-textbooks--reading-lists)
  * [Undergraduate Level](#undergraduate-level)
  * [Graduate Level (PhD Core)](#graduate-level-phd-core)
  * [Advanced & Field Specializations](#advanced--field-specializations)
* [Seminal Economic Papers & Journals](#-seminal-economic-papers--journals)
* [Open Access Courses & Lecture Notes](#-open-access-courses--lecture-notes)
* [Computational Tools & Programming](#-computational-tools--programming)
  * [Python Macro Ecosystem](#python-macro-ecosystem)
  * [MATLAB & Julia Frameworks](#matlab--julia-frameworks)
  * [Specialized Macro Software & DSGE Solvers](#specialized-macro-software--dsge-solvers)
* [Macroeconomic Models & Open Source Codebases](#-macroeconomic-models--open-source-codebases)
* [Comprehensive Datasets & APIs](#-comprehensive-datasets--apis)
* [Central Banks, Think Tanks & Policy Institutions](#-central-banks-think-tanks--policy-institutions)
* [Blogs, Podcasts, & Newsletters](#-blogs-podcasts--newsletters)
* [Contributing](#-contributing)
* [License](#-license)

---

## 🧠 1. Foundational Concepts & Pillars

A structured breakdown of core theoretical pillars across short, medium, and long horizons:

* **National Income Accounting & Measurement:** GDP approaches (expenditure, income, value added), GDP Deflator vs. Consumer Price Index (CPI) vs. Personal Consumption Expenditures (PCE) price index, Labor Force Statistics, Okun's Law, and the Balance of Payments / National Saving Identity.
* **Short-Run Fluctuations (Keynesian & Neo-Keynesian):** Closed and open economy IS-LM, Mundell-Fleming model (Fixed vs. Flexible exchange rates, capital mobility, Impossible Trinity), Fiscal and Monetary policy transmission mechanisms and multipliers.
* **Medium-Run Aggregate Supply & Demand:** Labor market equilibrium, wage-setting and price-setting curves, structural unemployment, Natural Rate of Unemployment (NAIRU), expectations-augmented Phillips Curve, and Stagflation dynamics.
* **Long-Run Economic Growth:** Solow-Swan neoclassical growth model, transitional dynamics, steady-state properties, golden rule of capital accumulation, conditional vs. absolute convergence, Ramsey-Cass-Koopmans optimal saving model, Overlapping Generations (OLG) framework, and Endogenous Growth Theory (Romer varieties, Lucas human capital, Schumpeterian creative destruction).
* **Advanced Macro Dynamics & General Equilibrium:** Dynamic Stochastic General Equilibrium (DSGE) frameworks, Real Business Cycle (RBC) theory, Asset Pricing and Lucas asset pricing model, Heterogeneous Agent New Keynesian (HANK) models, and optimal monetary/fiscal policy under commitment vs. discretion (Time Inconsistency problem).

---

## 📚 2. Textbooks & Reading Lists

### Undergraduate Level
* *Macroeconomics* - Olivier Blanchard (The gold standard for understanding transition mechanisms from short-run to long-run).
* *Macroeconomics* - N. Gregory Mankiw (Exceptional clarity, pedagogical structure, and balanced classical/keynesian views).
* *Macroeconomics in the Global Economy* - Jeffrey Sachs & Felipe Larraín (Essential for open economies, debt crises, and emerging markets).
* *Intermediate Macroeconomics* - Robert J. Barro (Rigorous micro-founded approach with strong classical footing).
* *Macroeconomics: Canadian/Global Edition* - Stephen D. Williamson (Strong focus on modern general equilibrium microfoundations at the undergraduate level).

### Graduate Level (PhD Core)
* *Advanced Macroeconomics* - David Romer (The mandatory entry point for first-year PhD students covering structural growth and cycle models).
* *Recursive Macroeconomic Theory* - Lars Ljungqvist & Thomas J. Sargent (The definitive masterclass on dynamic programming, dynamic games, and recursive methods).
* *Economic Dynamics: Computation and Model Building* - John Stachurski (Bridging abstract macro theory with concrete computational implementations).
* *Macroeconomic Theory* - Michael Wickens (Comprehensive analytical treatment of general equilibrium macro systems).
* *Lectures on Macroeconomics* - Olivier Blanchard & Stanley Fischer (The classic foundation for advanced monetary and business cycle theory).

### Advanced & Field Specializations
* *Methods for Applied Macroeconomic Research* - Fabio Canova (Advanced structural identification, vector autoregressions, and Bayesian estimation).
* *Foundations of International Macroeconomics* - Maurice Obstfeld & Kenneth Rogoff (The foundational reference for intertemporal open-economy macro).
* *Inequality and Macroeconomics* - Various compilations on HANK frameworks and wealth distribution dynamics.
* *Monetary Policy, Inflation, and the Business Cycle* - Jordi Gali (The definitive textbook for New Keynesian framework derivation and monetary policy analysis).

---

## 📄 3. Seminal Economic Papers & Journals

Core papers that shaped modern macroeconomic thought:

* **Solow (1956)** - *"A Contribution to the Theory of Economic Growth"* (Quarterly Journal of Economics).
* **Kydland & Prescott (1977)** - *"Rules Rather than Discretion: The Inconsistency of Optimal Plans"* (Journal of Political Economy).
* **Lucas (1976)** - *"Econometric Policy Evaluation: A Critique"* (Carnegie-Rochester Conference Series on Public Policy).
* **Kydland & Prescott (1982)** - *"Time to Build and Aggregate Fluctuations"* (Econometrica - Birth of RBC theory).
* **Calvo (1983)** - *"Staggered Prices in a Utility-Maximizing Framework"* (Journal of Monetary Economics - Calvo pricing mechanism).
* **Taylor (1993)** - *"Discretion versus Policy Rules in Practice"* (Carnegie-Rochester Conference Series - Taylor Rule).
* **Kaplan, Moll & Violante (2018)** - *"Monetary Policy According to HANK"* (American Economic Review - Heterogeneous Agent models).

---

## 🎓 4. Open Access Courses & Lecture Notes

* [MIT OpenCourseWare (Graduate Macroeconomics)](https://ocw.mit.edu/) - Olivier Blanchard and Iván Werning's classic PhD syllabi, problem sets, and exams.
* [QuantEcon Lectures](https://quantecon.org/) - Comprehensive quantitative economics curriculum built by Thomas J. Sargent and John Stachurski using Python and Julia.
* [UCLA Graduate Macroeconomics Notes](https://www.econ.ucla.edu/) - Advanced mathematical formulations of dynamic general equilibrium.
* [Stanford University Macro Courses](https://www.stanford.edu/) - Cutting-edge structural estimation, monetary frameworks, and dynamic optimization.
* [Chicago Booth Macroeconomics Archives](https://www.chicagobooth.edu/) - Deep dive into modern asset pricing, business cycles, and monetary policies.

---

## 💻 5. Computational Tools & Programming

### Python Macro Ecosystem
* [`QuantEcon.py`](https://github.com/QuantEcon/QuantEcon.py) - Official Python ecosystem for quantitative economic modeling and dynamic programming.
* [`statsmodels`](https://www.statsmodels.org/) - Standard package for classical econometrics, time-series analysis (ARIMA, VAR, VECM, Impulse Response Functions), and statistical testing.
* [`arch`](https://github.com/bashtage/arch) - Autoregressive conditional heteroskedasticity (ARCH/GARCH) modeling for macroeconomic and financial market volatility.
* [`linearmodels`](https://github.com/bashtage/linearmodels) - Panel data models, instrumental variables, and system regressions.
* [`Quantecon Data Hub`](https://github.com/QuantEcon) - Specialized datasets and utilities for computational notebooks.

### MATLAB & Julia Frameworks
* **MATLAB / GNU Octave** - Traditional numerical powerhouse for perturbation methods, value function iterations, and policy simulations.
* **Julia (`QuantEcon.jl`)** - High-performance modern dynamic language gaining massive adoption for high-dimensional computational macro.

### Specialized Macro Software & DSGE Solvers
* **Dynare** - The global industry-standard platform for solving, simulating, and estimating DSGE and overlapping-generations models using perturbation or projection methods. Integrates directly with MATLAB, Octave, and Python.
* **IRIS Toolbox** - Advanced macro-modeling environment for MATLAB focused on forecasting, policy analysis, and Structural Vector Autoregressions (SVARs).
* **GAMS (General Algebraic Modeling System)** - High-level modeling system for mathematical programming and complex economic equilibrium computations.

---

## ⚙️ 6. Macroeconomic Models & Open Source Codebases

* **Real Business Cycle (RBC) Models:** Classic neoclassic models featuring stochastic productivity shocks, capital accumulation, and labor-leisure trade-offs.
* **Standard 3-Equation New Keynesian Models:** IS curve, Phillips curve, and monetary policy rule (Taylor Rule) with sticky prices.
* **Heterogeneous Agent New Keynesian (HANK) Models:** Advanced frameworks incorporating idiosyncratic income risk, borrowing constraints, and wealth distribution effects into monetary transmissions.
* **Open-Economy DSGE Templates:** Models incorporating nominal exchange rates, international risk sharing, and terms-of-trade shocks.
* **Bayesian Estimation Toolkits:** Markov Chain Monte Carlo (MCMC) and Metropolis-Hastings algorithms for estimating structural macro parameters.

---

## 📈 7. Comprehensive Datasets & APIs

* [FRED API (Federal Reserve Economic Data)](https://fred.stlouisfed.org/) - The definitive repository for US and international financial and macroeconomic time series.
* [World Bank Open Data](https://data.worldbank.org/) - World Development Indicators (WDI) covering global poverty, education, health, and economic output.
* [IMF Data (International Monetary Fund)](https://www.imf.org/en/Data) - International Financial Statistics (IFS), Direction of Trade Statistics (DOTS), and World Economic Outlook (WEO).
* [OECD Statistics](https://stats.oecd.org/) - Cross-country comparative data on labor markets, tax burdens, productivity, and macroeconomic performance.
* [Penn World Table (PWT)](https://www.rug.nl/ggdc/productivity/pwt/) - Purchasing power parity (PPP) and national income accounts across 180+ countries spanning decades.
* [Bank for International Settlements (BIS) Statistics](https://www.bis.org/statistics/) - Global credit statistics, debt aggregates, property price indices, and foreign exchange data.
* [Eurostat](https://ec.europa.eu/eurostat) - Official statistical office of the European Union providing detailed eurozone macroeconomic metrics.
* [Calibration Ledger](https://apify.com/publicrecords/calibration-ledger) - Forecast track records (IMF, OECD, Fed, ECB SPF): forecast errors and bias by organization (Apify Actor, API + MCP).

---

## 🏛️ 8. Central Banks, Think Tanks & Policy Institutions

* **Federal Reserve System (FED):** Research papers, Beige Books, and monetary policy statements from the Board of Governors and regional Federal Reserve Banks (e.g., New York, St. Louis, Minneapolis).
* **European Central Bank (ECB):** Research bulletins, macroeconomic projections, and monetary policy reviews for the Eurozone.
* **Bank of England (BoE):** Inflation reports, financial stability papers, and core macro modeling codebases (like CompNet).
* **National Bureau of Economic Research (NBER):** The premier US private research organization for business cycle dating and macroeconomic working papers.
* **Center for Economic and Policy Research (CEPR):** European network for economic policy research and VoxEU commentary.

---

## 🎙️ 9. Blogs, Podcasts, & Newsletters

* **Podcasts:**
  * *EconTalk* (Russ Roberts) - Deep-dive conversations with leading economists on theory and public policy.
  * *Central Banking Podcast* - Discussions on monetary policy, central bank digital currencies, and inflation trends.
  * *Freakonomics Radio* - Applied behavioral and economic insights.
* **Research Blogs & Aggregators:**
  * *VoxEU (CEPR)* - Expert policy analysis and summaries of recent economic research.
  * *Liberty Street Economics* (FRBNY) - Frontline insights from Federal Reserve Bank of New York economists.
  * *NBER Digest* - Monthly summaries of breakthrough National Bureau of Economic Research papers.
  * *Bruegel* - European economic think-tank providing analysis on global macro policy.

---

## 🤝 10. Contributing

Contributions are **always welcome**! Whether you want to fix a typo, add a seminal textbook, introduce a useful Python package, or expand model descriptions, please follow these steps:

1. **Fork** the Repository.
2. Create your Feature Branch (`git checkout -b feature/AwesomeMacroExpansion`).
3. Commit your Changes (`git commit -m 'Add advanced DSGE toolkits and datasets'`).
4. Push to the Branch (`git push origin feature/AwesomeMacroExpansion`).
5. Open a **Pull Request**.

Please ensure that all added links are active, properly categorized, and maintain alphabetical order where applicable.

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---
<p align="center"><em>Maintained with 📊 and 📈 for macroeconomists, researchers, and students worldwide.</em></p>
