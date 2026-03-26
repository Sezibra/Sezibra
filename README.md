# Computational Conflict Research

An eight-project portfolio applying computational social science methods to armed conflict data. Each project addresses a different analytical question about the Ethiopia/Tigray conflict (2020–2022) using data from UCDP, the UN, GDELT, satellite imagery, and other sources.

The portfolio covers geospatial analysis, NLP and text-as-data, network analysis, machine learning forecasting, causal inference, satellite-based damage detection, agent-based modeling, and digital trace data collection. Together, these projects represent the core methodological toolkit of computational conflict research as practiced in 2025–2026.

## Projects

| # | Project | Methods | Repository |
|---|---------|---------|------------|
| 1 | **Conflict Event Data Analysis & Geospatial Visualization** | pandas, geopandas, folium, DBSCAN, matplotlib | [conflict-event-analysis](https://github.com/Sezibra/conflict-event-analysis) |
| 2 | **LLM-Powered Conflict Text Analysis** | BERTopic, zero-shot classification, sentence-transformers, UMAP, HDBSCAN | [conflict-text-analysis](https://github.com/Sezibra/conflict-text-analysis) |
| 3 | **Conflict Actor Network Analysis** | NetworkX, community detection, centrality metrics | [conflict-network-analysis](https://github.com/Sezibra/conflict-network-analysis) |
| 4 | **Conflict Forecasting with Machine Learning** | Random Forest, temporal cross-validation, SHAP, panel data | [conflict-forecasting-ml](https://github.com/Sezibra/conflict-forecasting-ml) |
| 5 | **Causal Inference for Conflict with ML** | Double Machine Learning, Causal Forests, EconML (PyWhy), sensitivity analysis | [conflict-causal-inference](https://github.com/Sezibra/conflict-causal-inference) |
| 6 | **Satellite Imagery for Conflict Damage Assessment** | Google Earth Engine, Sentinel-1 SAR, change detection, transfer learning | [conflict-satellite-damage](https://github.com/Sezibra/conflict-satellite-damage) |
| 7 | **Agent-Based Modeling for Conflict Dynamics** | Agent-based simulation, computational modeling | [conflict-abm-simulation](https://github.com/Sezibra/conflict-abm-simulation) |
| 8 | **Digital Trace Data Collection** | ReliefWeb API, GDELT via BigQuery, web scraping, data pipeline design | [conflict-data-collection](https://github.com/Sezibra/conflict-data-collection) |

All eight projects are complete.

## Case Study: Ethiopia/Tigray (November 2020 – November 2022)

All projects use the same conflict case: the war in the Tigray region of Ethiopia, bounded by the start of hostilities in November 2020 and the Cessation of Hostilities Agreement in November 2022. The UCDP dataset contains 1,764 georeferenced events across state-based conflict, one-sided violence, and non-state conflict. Dominant regions include Tigray, Oromiya, and Amhara.

This case was selected for its analytical clarity: a defined start and end date, multiple conflict actors with distinct operational patterns, and high-quality event data.

## Data Sources

- **UCDP GED v25.1** — Uppsala Conflict Data Program Georeferenced Event Dataset (Projects 1–5, 7)
- **UN Security Council meeting records** — Official speeches on Ethiopia/Tigray (Project 2)
- **Sentinel-1 SAR imagery** via Google Earth Engine (Project 6)
- **Google Open Buildings** — Building footprint data for Tigray cities (Project 6)
- **ReliefWeb API** — UN humanitarian reports (Project 8)
- **GDELT v2 via Google BigQuery** — Global media event data (Project 8)

## Methodological Progression

The projects build on each other in a deliberate sequence:

- **Project 1** establishes data handling and spatial analysis skills
- **Project 2** adds NLP, LLM-based annotation, and text-as-data methods
- **Project 3** adds network thinking and relational analysis of conflict actors
- **Project 4** synthesizes data from multiple sources and introduces ML pipelines for prediction
- **Project 5** adds causal reasoning on top of ML, addressing the prediction-vs-explanation gap
- **Project 6** adds computer vision and remote sensing for conflict damage assessment
- **Project 7** introduces simulation-based approaches to model conflict dynamics
- **Project 8** demonstrates data engineering: building collection pipelines from APIs, databases, and web sources

## Key References

### Conflict Data and Geospatial Analysis
- Sundberg, R. and Melander, E. (2013). Introducing the UCDP Georeferenced Event Dataset. *Journal of Peace Research*, 50(4), 523–532.
- Raleigh, C. et al. (2010). Introducing ACLED: An Armed Conflict Location and Event Dataset. *Journal of Peace Research*, 47(5), 651–660.
- Tollefsen, A.F. et al. (2012). PRIO-GRID: A Unified Spatial Data Structure. *Journal of Peace Research*, 49(2), 363–374.
- Gleditsch, K.S. (2020). Advances in Data on Conflict and Dissent. In E. Deutschmann et al. (Eds.), *Computational Conflict Research* (pp. 23–38). Springer.

### Text as Data and NLP
- Grimmer, J. and Stewart, B. (2013). Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts. *Political Analysis*, 21(3), 267–297.
- Maerz, S.F. and Puschmann, C. (2020). Text as Data for Conflict Research: A Literature Survey. In E. Deutschmann et al. (Eds.), *Computational Conflict Research* (pp. 43–65). Springer.
- Grootendorst, M. (2022). BERTopic: Neural Topic Modeling with a Class-Based TF-IDF Procedure. *arXiv:2203.05794*.
- Törnberg, P. (2025). How to Use LLMs for Text Analysis. *Social Science Computer Review*.

### Network Analysis
- Donnay, K. et al. (2019). Integrating Conflict Event Data. *Journal of Conflict Resolution*, 63(5), 1258–1282.
- Cederman, L.-E. and Gleditsch, K.S. (2009). Special Issue on Disaggregating Civil War. *Journal of Conflict Resolution*, 53(4), 487–495.

### Conflict Forecasting
- Hegre, H. et al. (2019). ViEWS: A Political Violence Early-Warning System. *Journal of Peace Research*, 56(2), 155–174.
- Cederman, L.-E. and Weidmann, N.B. (2017). Predicting Armed Conflict: Time to Adjust Our Expectations? *Science*, 355(6324), 474–476.
- Hofman, J.M., Sharma, A., and Watts, D.J. (2017). Prediction and Explanation in Social Systems. *Science*, 355(6324), 486–488.
- Lundberg, S. and Lee, S.-I. (2017). A Unified Approach to Interpreting Model Predictions. *NeurIPS*.

### Causal Inference
- Chernozhukov, V. et al. (2018). Double/Debiased Machine Learning for Treatment and Structural Parameters. *The Econometrics Journal*, 21(1), C1–C68.
- Athey, S. and Wager, S. (2018). Estimation and Inference of Heterogeneous Treatment Effects Using Random Forests. *Journal of the American Statistical Association*.
- Wager, S. (2025). *Causal Inference: A Statistical Learning Approach*. Stanford.
- Koch, T. et al. (2025). Deep Learning for Causal Inference: A Primer. *Sociological Methods and Research*.

### Satellite Imagery and Computer Vision
- Law, T. and Roberto, E. (2025). Generative Multimodal Models for Social Science. *Sociological Methods and Research*.
- Warnke, A. and Runfola, D. (2024). Predicting Protest Locations from Satellite Imagery Using ResNet CNNs.
- Gupta, R. et al. (2019). xBD: A Dataset for Assessing Building Damage from Satellite Imagery. *arXiv:1911.09296*.
- Jean, N. et al. (2016). Combining Satellite Imagery and Machine Learning to Predict Poverty. *Science*, 353(6301), 790–794.

### Agent-Based Modeling
- Salvi, A. et al. (2020). On the Beaten Path: Violence Against Civilians and Simulated Conflict Along Road Networks. In E. Deutschmann et al. (Eds.), *Computational Conflict Research* (pp. 185–200). Springer.
- Cremaschi, S. et al. (2020). Generative Models and Simulation of Non-State Armed Group Attacks. In E. Deutschmann et al. (Eds.), *Computational Conflict Research* (pp. 163–183). Springer.

### Computational Social Science (General)
- Lazer, D. et al. (2009). Computational Social Science. *Science*, 323(5915), 721–723.
- Deutschmann, E. et al. (Eds.) (2020). *Computational Conflict Research*. Springer.
- Hox, J.J. (2017). Computational Social Science Methodology, Anyone? *Methodology*, 13(Supplement), 3–12.
- Cioffi-Revilla, C. (2014). *Introduction to Computational Social Science*. Springer.

## Technical Environment

- Python 3.11 (Anaconda)
- Jupyter Notebooks
- Libraries: pandas, geopandas, folium, scikit-learn, matplotlib, seaborn, BERTopic, sentence-transformers, NetworkX, EconML, earthengine-api

## About

This portfolio is designed to demonstrate quantitative and computational methods for conflict research. Each repository contains Jupyter notebooks with step-by-step analysis, explanatory markdown guides, and reproducible code.
