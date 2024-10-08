# Applied Analytics & Computational Statistics

This repository showcases projects that focus on the application of statistical analysis methods, including exploration of the statistical methodology and implementation of computationally expensive techniques. Each project provides a thorough analysis of the theory alongside practical applications tailored to different domains.

- [Bayesian Hierarchical Meta-Analysis](#bayesian-hierarchical-meta-analysis)
- [Statistical Network Analysis](#statistical-network-analysis)
- [Adaptive Rejection Metropolis Samping](#adaptive-rejection-metropolis-samping)
- [Linear Regression Modelling](#linear-regression-modelling)


# Bayesian Hierarchical Meta-Analysis

><b>Quantifying the Effect of Beta Blockers on Mortality</b>

The aim of the analysis is to investigate the efficacy of beta-blockers in reducing mortality rates after a cardiac event. A **meta-analysis** of 15 clinical studies was implemented, which showed a significant reduction in long-term mortality but inconclusive short-term effects, highlighting the complexity of treatment efficacy and the potential influence of publication bias.

<p align="center">
  <img src="https://github.com/dontkillourjoy/stat_analytics/blob/main/bayesian_hierarchical/aux_files/forest_plot.png" alt="Forest plot for empirical logits" width="700" height = "400"/>
  <br/>
  <i>Forest plot for empirical logits</i>
</p>

A Bayesian hierarchical model was implemented for this purpose, which allows to  simultaneously model both individual study-level variability, and the variability between the different studies. This provides the benefit of allowing the **borrowing of information** between the studies, which leads to a more comprehensive modelling. Naturally, Bayesian methodology allows to incorporate prior uncertainty in the model, and it provides a coherent framework where posterior distributions quantify the uncertainty in model parameters. In the analysis, the **hierarchical** model specification and inference were followed by **shrinkage** investigation and **sensitivity** analysis. Additionally, the resulting hierarchical model was compared to simpler **non-hierarchical** structures.

<sub><i> Project completed in collaboration with Corrà Sara </i></sub>

# Statistical Network Analysis

><b>Structural and Resilience Analysis of the German Transmission Network</b>

The analysis provides insights into the structure of the German **power transmission network**, and attempts to investigate potential **vulnerability** points that might lead to disruptions of the electricity flow in cases of targeted or random attacks on the network. The project was inspired by the [**SciGRID**](https://www.power.scigrid.de/) project, which was created for the purpose of developing automated generation of models of power grids for the purposes of research and practical applications. 

<p align="center">
  <img src="https://github.com/dontkillourjoy/stat_analytics/blob/main/network_analysis/aux_files/targeted.png" alt="Germany population density overlaid by targeted nodes" width="300" height = "400"/>
  <br/>
  <i>Germany population density overlaid by targeted nodes</i>
</p>

The **structure** of the network was analysed, with the main centralities investigated and the results compared. Clustering was performed using a **fast and greedy** approach. Finally, **resilience analysis** was performed by using various approaches, which evidenced that the most efficient **attack strategy** node removal is coherent with population density levels, indicating the importance of robust network planning.

<sub><i>Project completed in collaboration with Poetto Patrick </i></sub>

# Adaptive Rejection Metropolis Samping

This is a **research** project investigating the **Adaptive Rejection Metropolis Sampling** approach, which is an advanced **Markov Chain Monte Carlo** technique that is used in Bayesian modelling where the posterior densities admit a **non-log-concave shape**. 
<p align="center">
  <img src="https://github.com/dontkillourjoy/stat_analytics/blob/main/arms_computational/aux_files/envelope.png" alt="An example of the envelope for the ARMS sampling" width="700" height = "400"/>
  <br/>
  <i>An example of the envelope for the ARMS sampling</i>
</p>

The project provides a full **theoretical description** of the simpler building blocks, such as rejection sampling, squeezing function and adative rejection sampling. Afterwards, the full algorithm for the ARMS is explained, with the practical implementation provided in order to demonstrate the gain in efficiency of the **sampling procedure**. 


<sub><i>Project completed in collaboration with Corrà Sara </i></sub>

# Linear Regression Modelling

><b>Statistical Analysis of Honey Production in the Environmental Framework</b>

The aim of the project is to investigate whether the rapid decline in the <b>honey bee population</b> can be attributed to certain envionmental pollution factors, among which are a number of widely used neonicotinoid pesticides and air pollution proxy variables. The idea for the project was inspired by the [Kaggle dataset](https://www.kaggle.com/datasets/kevinzmith/honey-with-neonic-pesticide), and the dataset was finalised by accessing data from US governmental sources. 

<p align="center">
  <img src="https://github.com/dontkillourjoy/stat_analytics/blob/main/linear_modelling/data/trend.png" alt="Number of beehives in the United states, 1961-2017. "  width="700" height = "400"/>
  <br/>
  <i>Number of beehives in the United states, 1961-2017. <a href="https://www.fao.org/faostat/en/" target="_blank">Data Source</a></i>
</p>

The analysis was conducted for 34 US states for the year 2016, with the **multiple regression model** specified used for inference and prediction purposes, with variable selection and model diagnostic steps of the analysis adhered to.
