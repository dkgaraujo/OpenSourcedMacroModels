# OpenSourcedMacroModels


## Objective
The goal of this repository is to collect in one place the open-sourcd macroeconomic models, in particular (but not limited to) those used by central banks, ministries of finance and other offical sector agencies.

If you know a model that is not listed here, please open up a pull request [here](https://github.com/dkgaraujo/OpenSourcedMacroModels/pulls). PRs for corrections are also very welcome.

## Official sector models

The table below lists models that were open sourced by official sector entities themselves.

| Jurisdiction | Institution | Model name | Model type | Link to code | Programming language | License | About |
|---|---|---|---|---|---|---|---|
| Denmark | Ministry of Finance | MAKRO | Deterministic perfect forecast model | https://github.com/DREAM-DK/MAKRO | GAMS | MIT License | |
| Germany | Federal Ministry for Economic Affairs and Climate Action |  | Production function methodology | https://www.bmwi.de/Redaktion/DE/Downloads/G/ergaenzende-unterlagen-zu-den-berechnungsgrundlagen-fuer-die-bestimmung-des-gesamtwirtschaftlichen-produktionspotenzials.zip?__blob=publicationFile&v=14 | EViews | Same as for the website | https://www.bmwi.de/Redaktion/DE/Downloads/G/ergaenzende-unterlagen-zu-den-berechnungsgrundlagen-fuer-die-bestimmung-des-gesamtwirtschaftlichen-produktionspotenzials.html |
| Euro Area | European Central Bank (ECB) | Bayesian Estimation, Analysis and Regression toolbox (BEAR) | Bayesian vector autoregression (VAR) | https://github.com/european-central-bank/BEAR-toolbox/ | Matlab | Custom end-user license agreement | |
| Finland | Bank of Finland | Aino | DSGE | https://helda.helsinki.fi/bof/handle/123456789/14144 (v2.0) | Matlab/Octave + Dynare | https://helda.helsinki.fi/bof/copyright | [Aino 2.0](https://helda.helsinki.fi/bof/bitstream/handle/123456789/14144/BoF_DP_1616.pdf). Note: current version (no code available) is [Aino 3.0](https://helda.helsinki.fi/bof/handle/123456789/17442) |
| UK | HM Treasury and Office for Budget Responsibility | OBR model | Large-scale macro-econometric model | https://obr.uk/download/obr-macroeconomic-model-code/ | EViews | Last paragraph of [this page](https://obr.uk/forecasts-in-depth/obr-macroeconomic-model/) | https://obr.uk/forecasts-in-depth/obr-macroeconomic-model/ |
| USA | Federal Reserve Bank of New York (FRBNY) | | Dynamic stochastic general equilibrium (DSGE) | https://github.com/FRBNY-DSGE/DSGE.jl | Julia | BSD-3-Clause License | [Blog post](https://libertystreeteconomics.newyorkfed.org/2015/12/the-frbny-dsge-model-meets-julia/) |
| USA | Federal Reserve Board | FRB/US | Large-scale, general equilibrium model | https://www.federalreserve.gov/econres/us-models-package.htm | EViews | Same as for the website | https://www.federalreserve.gov/econres/us-models-about.htm |
| USA | Federal Reserve Board | Estimated Dynamic Optimization (EDO) Model | DSGE | https://www.federalreserve.gov/econres/edo-model-package.htm | Matlab/Octave + Dynare | Same as for the website | https://www.federalreserve.gov/econres/edo-models-about.htm |

## Other related resources

Below are other resources that are worth consulting for their wealth of model code.

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
