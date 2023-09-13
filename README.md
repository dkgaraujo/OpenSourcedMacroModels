# OpenSourcedMacroModels


## Objective
The goal of this repository is to collect in one place the open-sourced macroeconomic models, in particular (but not limited to) those used by central banks, ministries of finance and other offical sector agencies.

If you know a model that is not listed here, please open up a pull request [here](https://github.com/dkgaraujo/OpenSourcedMacroModels/pulls). PRs for corrections are also very welcome. Alternatively, feel free to reach out to me on [Twitter](https://twitter.com/DouglasKGAraujo).

## Official sector models

The table below lists models that were open sourced by official sector entities themselves.

| Jurisdiction | Institution | Model name | Model type | Link to code | Programming language | License | About |
|---|---|---|---|---|---|---|---|
| Australia | Reserve Bank of Australia | MARTIN | Economy-wide model based on error-correction equations | https://www.rba.gov.au/publications/rdp/2019/2019-07.html<br/>(click on "supplementary information") | EViews | "Disclaimer" section at https://www.rba.gov.au/publications/rdp/2019/2019-07/read-me.html | Model described in the paper at https://www.rba.gov.au/publications/rdp/2019/2019-07.html |
| Chile | Banco Central de Chile | MSEP | Semi-structural model | https://www.bcentral.cl/documents/33528/2246274/sec3_3_1_structural_domestic_MSEP.zip/1d5236d2-4db2-b687-bd73-08a09fb5b316?t=1586981365357 | Matlab/Octave + Dynare | Same as for the website | Section 3.3.1 of https://www.bcentral.cl/documents/33528/2246274/Uso_de_modelos_en_el_BCCh_2020.pdf/08cdce8e-7344-4af8-01a3-93c0dc7f39db?t=1586968478573 |
| Chile | Banco Central de Chile | XMAS | DSGE | https://www.bcentral.cl/documents/33528/2246274/sec3_3_2_structural_domestic_XMAS.zip/726db955-2713-c7d5-9ed8-9ef65eef7475?t=1586981406890 | Matlab/Octave + Dynare | Same as for the website | Section 3.3.2 of https://www.bcentral.cl/documents/33528/2246274/Uso_de_modelos_en_el_BCCh_2020.pdf/08cdce8e-7344-4af8-01a3-93c0dc7f39db?t=1586968478573 |
| Denmark | Ministry of Finance | MAKRO | Deterministic perfect forecast model | https://github.com/DREAM-DK/MAKRO | GAMS | MIT License | |
| Euro Area | European Central Bank (ECB) | Bayesian Estimation, Analysis and Regression toolbox (BEAR) | Bayesian vector autoregression (VAR) | https://github.com/european-central-bank/BEAR-toolbox/ | Matlab | Custom end-user license agreement | |
| European Union | European Commission | Output gap model | | https://circabc.europa.eu/ui/group/671d465b-0752-4a2e-906c-a3effd2340ba/library/b9482682-d5a0-47a1-9281-bc7d8a214629 | WinRATS |  | |
| Finland | Bank of Finland | Aino | DSGE | https://helda.helsinki.fi/bof/handle/123456789/14144 (v2.0) | Matlab/Octave + Dynare | https://helda.helsinki.fi/bof/copyright | [Aino 2.0](https://helda.helsinki.fi/bof/bitstream/handle/123456789/14144/BoF_DP_1616.pdf). Note: current version (no code available) is [Aino 3.0](https://helda.helsinki.fi/bof/handle/123456789/17442) |
| France | French Ministry of Economics and Finance | Mésange | DSGE | https://github.com/InseeFr/Mesange | Troll | https://raw.githubusercontent.com/InseeFr/Mesange/master/LICENSE.txt | https://github.com/InseeFr/Mesange/raw/master/Document%20de%20travail%20Mesange%202017.pdf |
| France | French Ministry of Economics and Finance | Modèle Opale | | https://github.com/DGTresor/Opale | Troll | https://github.com/DGTresor/Opale/blob/master/LICENSE | https://github.com/DGTresor/Opale/blob/master/doc/Document_de_travail_Opale__2017_.pdf |
| France | French Ministry of Economics and Finance | Modèle Saphir | | https://github.com/DGTresor/Saphir | SAS | https://github.com/DGTresor/Saphir/blob/master/LICENSE |  |
| Germany | Federal Ministry for Economic Affairs and Climate Action |  | Production function methodology | https://www.bmwi.de/Redaktion/DE/Downloads/G/ergaenzende-unterlagen-zu-den-berechnungsgrundlagen-fuer-die-bestimmung-des-gesamtwirtschaftlichen-produktionspotenzials.zip?__blob=publicationFile&v=14 | EViews | Same as for the website | https://www.bmwi.de/Redaktion/DE/Downloads/G/ergaenzende-unterlagen-zu-den-berechnungsgrundlagen-fuer-die-bestimmung-des-gesamtwirtschaftlichen-produktionspotenzials.html |
| Iceland | Central Bank of Iceland | Quarterly Macroeconomic Model (QMM) | Structural econometric model | https://www.cb.is/monetary-policy/central-bank-of-iceland-economic-forecasts/ | Not clear | https://www.cb.is/other/copyright/ | https://www.cb.is/library/Skraarsafn---EN/Working-Papers/WP82_net |
| Italy | Bank of Italy | Black-box abm calibration kit | Agent-based model | https://github.com/bancaditalia/black-it | Python | https://github.com/bancaditalia/black-it/blob/main/LICENSE | https://github.com/bancaditalia/black-it/blob/main/docs/description.md |
| Japan | Bank of Japan | Quarterly Japanese Economic Model (Q-JEM) | Large-scale semi-structural model | https://www.boj.or.jp/en/research/wps_rev/wps_2019/data/wp19e07.zip | EViews and Python | Custom, found in "Disclaimer.pdf" | https://www.boj.or.jp/en/research/wps_rev/wps_2019/wp19e07.htm |
| Sweden | Riksbank | Ramses II | Dynamic stochastic general equilibrium (DSGE) | https://www.riksbank.se/contentassets/e01d64fc644b462cb345ba0f4c85cf24/ramsesii_dynarecode_occasionalpaperno12.zip | Matlab/Octave + Dynare | Same as for the website | https://www.riksbank.se/sv/press-och-publicerat/publikationer/working-paper-series/occasional-paper-series/no.-12-ramses-ii--model-description/ |
| UK | HM Treasury and Office for Budget Responsibility | OBR model | Large-scale macro-econometric model | https://obr.uk/download/obr-macroeconomic-model-code/ | EViews | Last paragraph of [this page](https://obr.uk/forecasts-in-depth/obr-macroeconomic-model/) | https://obr.uk/forecasts-in-depth/obr-macroeconomic-model/ |
| USA | Federal Reserve Bank of New York (FRBNY) | | Dynamic stochastic general equilibrium (DSGE) | https://github.com/FRBNY-DSGE/DSGE.jl | Julia | BSD-3-Clause License | [Blog post](https://libertystreeteconomics.newyorkfed.org/2015/12/the-frbny-dsge-model-meets-julia/) |
| USA | Federal Reserve Board | FRB/US | Large-scale, general equilibrium model | https://www.federalreserve.gov/econres/us-models-package.htm | EViews, Python | Same as for the website | Eviews version: https://www.federalreserve.gov/econres/us-models-about.htm<br/>Python version: https://www.federalreserve.gov/econres/us-models-python.htm |
| USA | Federal Reserve Board | Estimated Dynamic Optimization (EDO) Model | DSGE | https://www.federalreserve.gov/econres/edo-model-package.htm | Matlab/Octave + Dynare | Same as for the website | https://www.federalreserve.gov/econres/edo-models-about.htm |

## Other related resources

Below are other resources that are worth consulting for their wealth of model code. The table below lists policy models open sourced by entities not in the official sector. Other sources are listed after the table.

| Jurisdiction | Institution | Model name | Model type | Link to code | Programming language | License | About |
|---|---|---|---|---|---|---|---|
| General | [Policy Simulation Library](https://pslmodels.org/) | [`OG-Core`](https://github.com/PSLmodels/OG-Core) | Large-scale overlapping generations model | https://github.com/PSLmodels/OG-Core | Python | [CC0 1.0 Universal Summary](https://github.com/PSLmodels/OG-Core/blob/master/LICENSE.md) | This core model can be run on its own. But more effective is to create a country-specific calibration that uses `OG-Core` as a dependency (e.g., [`OG-USA`](https://github.com/PSLmodels/OG-USA) and [`OG-UK`](https://github.com/PSLmodels/OG-UK)). [`OG-Core` documentation](https://pslmodels.github.io/OG-Core/) is thorough and up-to-date. |
| UK | [Policy Simulation Library](https://pslmodels.org/) | [`OG-UK`](https://github.com/PSLmodels/OG-UK) | Large-scale overlapping generations model | https://github.com/PSLmodels/OG-UK | Python | [CC0 1.0 Universal Summary](https://github.com/PSLmodels/OG-UK/blob/main/LICENSE.md) | This model is currently under development. Large-scale overlapping generations model of U.K. fiscal policy. It uses as a dependency the [`OG-Core`](https://github.com/PSLmodels/OG-Core) model logic and interfaces with the [`OpenFisca-UK`](https://policyengine.github.io/openfisca-uk/) open-source microsimulation model. [`OG-UK` documentation](https://pslmodels.github.io/OG-UK/) is also under development. |
| USA | [Policy Simulation Library](https://pslmodels.org/) | [`OG-USA`](https://github.com/PSLmodels/OG-USA) | Large-scale overlapping generations model | https://github.com/PSLmodels/OG-USA | Python | [CC0 1.0 Universal Summary](https://github.com/PSLmodels/OG-USA/blob/master/LICENSE.md) | Large-scale overlapping generations model of U.S. fiscal policy. It uses as a dependency the [`OG-Core`](https://github.com/PSLmodels/OG-Core) model. `OG-USA` is currently set up to inteface with the open-source [`Tax-Calculator`](https://github.com/PSLmodels/Tax-Calculator) microsimulation model. However, it has been used with other microsimulation models as well (e.g., Tax Policy Center microsimulation model). [`OG-USA` documentation](https://pslmodels.github.io/OG-USA/) is thorough and up-to-date. |

⭐️ https://www.macromodelbase.com
* Repository of multiple macroeconomic models designed to enable systematic model comparison.
* The site contains an online comparison tool, in which you can choose amongst many different models (all well-categorised for ease of reference) and compare their outcome in terms of impulse response functions, etc for given shocks.

⭐️ https://github.com/JohannesPfeifer/DSGE_mod
* Repository of multiple academic macroeconomic models

⭐️ https://www.bankofengland.co.uk/ccbs/applied-bayesian-econometrics-for-central-bankers-updated-2017
* Material demonstrating very clearly Bayesian econometric tools that are often employed for macroeconomic models, namely:
  *  Bayesian vector autorregressions (VAR),
  *  VAR with time-varying parameters, and
  *  dynamic factor models

⭐️ https://github.com/shade-econ/nber-workshop-2022
* NBER Spring 2022 heterogeneous-agent macro workshop
  * Jupyter notebooks in Python, very clear to follow and learn from
  * Tutorials range from setting up models to estimating them using data
