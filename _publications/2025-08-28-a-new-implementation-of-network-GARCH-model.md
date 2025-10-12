---
title: "Master thesis: a new implementation of network GARCH model"
collection: publications
permalink: /publication/2025-08-28-a-new-implementation-of-network-GARCH-model
date: 2025-08-28
venue: 'Imperial College London, institutional repository'
slidesurl: 'http://PZhou114.github.io/files/Master_Presentation.pdf'
paperurl: 'http://PZhou114.github.io/files/Master_Thesis.pdf'
citation: 'Peiyi Zhou. (2025). &quot;A new implementation of Network GARCH Model.&quot;'
---

**This report has been uploaded and made available within Imperial College London institutional repository. All code for this paper is accessible in my Github repository ['GNGARCH_coding'](https://github.com/PZhou114/GNGARCH_coding), detailed instructions are in the repository's README.txt file.** 

Volatility clustering and spillovers are key features of real-world financial time series when there are a lot of cross-sectional financial assets. While network analysis helps connect stocks that are `similar' or `correlated', which is effective to link volatility spillovers between stocks, contemporary multivariate ARCH–GARCH formulations struggle to represent structured network dependence and remain parsimonious. We introduce the Generalised Network GARCH (GNGARCH) model as a network volatility model that embeds the GARCH dynamics within the Generalised Network Autoregressive (GNAR) framework, to capture the dynamic volatility of financial asset return by both the asset itself and its `neighbouring' assets from the constructed virtual network. The proposed volatility model GNGARCH also addresses the limitations for current studies of network GARCH by adapting neighbouring volatility persistence, dynamic conditional covariance updates, and allowing higher-order neighbouring effects rather than only immediate neighbours. This thesis provides the model derivation, vectorisation and conversion, stationarity conditions, and also an extension by incorporating threshold coefficients to capture leverage effects. We show that the GNGARCH is a valid volatilty model satisfying the stylised facts of financial return series through simulation. Parameter estimation is then performed by using squared returns as variance proxy and minimising a loss function that is either mean squared error (MSE) or quasi-likelihood (QLIKE). We apply our model on 75 of the most active US stocks under a virtual network, and highlight the model's ability in volatility estimation and forecast.
