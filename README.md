# Computational Statistics & Applied Analytics

1. [Bayesian](#introduction)
2. [Networks](#installation)
3. [Linear](#usage)
4. [Computational](#contributing)
5. [Time Series](#timeseries)

# Bayesian Hierarchical Meta-Analysis

## Quantifying the Effect of Beta Blockers on Mortality

<i>Project completed in collaboration with Corrà Sara </i>

The aim of the analysis is to investigate the efficacy of beta-blockers in reducing mortality rates after a cardiac event. A meta-analysis of 15 clinical studies was implemented, which showed a significant reduction in long-term mortality but inconclusive short-term effects, highlighting the complexity of treatment efficacy and the potential influence of publication bias.

![Forest plot for empirical logits](https://i.imgur.com/yourimage.jpg)

A Bayesian hierarchical model was implemented for this purpose, which allows to model simultaneously incorporate both individual study-level variability, and the variability between the different studies incorporated in the analysis. This provides the benefit of allowing the borrowing of information between the studies, which leads to a more comprehensive modelling. Naturally, Bayesian methodology allows to incorporate prior uncertainty in the model, and it provides a coherent framework where posterior distributions quantify the uncertainty in model parameters. In the analysis, the hierarchical model specification and inference were followed by shrinkage investigation and sensitivity analysis. Additionally, the resulting hierarchical model was compared to a simple non-hierarchical structures.

<i> The course [Bayesian Modelling](https://www.unicatt.it/upl/proguc/MI/2023/ENG/interfac_eco_mate/2I4A_Bayesian_modelling_Castelletti_Consonni.docx) covered comprehensively the foundational concepts of Bayesian Methodology, including posterior update, approaches to prior specifications, hierarchical modelling, Bayesian generalised regression modelling, with model inference and variable selection, elements of graphical modelling, and computational approaches: MCMC Gibbs and Metropolis-Hastings sampling methods. (III trimester, 2022-2023 a.y.)</i>

# Structural and Resilience Analysis of the German Transmission Network

<i>Project completed in collaboration with Poetto Patrick </i>

The analysis provides insights into the structure of the German power transmission network, and attempts to investigate potential vulnerability points that might lead to disruptions of the electricity flow in cases of targeted or random attacks on the network. The project was inspired by the [SciGRID](https://www.power.scigrid.de/) project, which was created for the purpose of developing automated generation of models of power grids for the purposes of research and practical applications. The structure of the network was analysed, with the main centralities investigated and the results compared. Clustering was performed using a fast and greedy approach. finally, resilience analysis was performed by using various approaches, which evidenced that the most efficient attack strategy node removal is coherent with population density levels, indicating the importance of robust network planning.

![Germany population density overlaid by targeted nodes](https://imgur.com/v3csQGQ)

<i> The statistical networks course provides a gentle introduction into the concepts of statistical network analysis, including descriptive statistics and centralities, sampling approaches for networks, common network models and community detection approaches. (III trimester, 2023-2024 a.y.)</i>

# Linear

## Statistical Analysis of Honey Production in the Environmental Framework

The aim of the project is to investigate whether the rapid decline in the <b>honey bee population</b> can be attributed to certain envionmental pollution factors, among which are a number of widely used neonicotinoid pesticides and air pollution proxy variables. The idea for the project was inspired by the [Kaggle dataset](https://www.kaggle.com/datasets/kevinzmith/honey-with-neonic-pesticide), and the dataset was finalised by accessing data from US governmental sources. The analysis was conducted for 34 US states for the year 2016, with the multiple regression model specified used for inference and prediction purposes, with variable selection and model diagnostic steps of the analysis adhered to.

![Number of beehives in the United states, 1961-2017. [Source](https://www.fao.org/faostat/en/)](https://imgur.com/a/szmOmgh)

The project was completed as part of the final examination for the [Applied Linear Models](https://www.unicatt.eu/courses/data-analytics-for-business-milan-23-24-curriculum) course, which introduces the basic linear regression concepts, putting an emphasis on understanding the theoretical assumptions of the models, the variable selection and model diagnostics process, and expands to the generalised linear models, providing methodology to model with in a wider range of situations. <i> (II trimester, 2022-2023 a.y.)</i>


# Adaptive Rejection Metropolis Sampling

<i>Project completed in collaboration with Corrà Sara </i>

This is a research project investigating the Adaptive Rejection Metropolis Sampling approach, which is an advanced Markov Chain Monte Carlo technique that is used in Bayesian modelling where the posterior densities admit a non-log-concave shape. The project provides a full theoretical description of the simpler building blocks, such as rejection sampling, squeezing function and adative rejection sampling. Afterwards, the full algorithm for the ARMS is explained, with the practical implementation provided in order to demonstrate the gain in efficiency of the sampling procedure. 

![An example of the envelope for the ARMS sampling](https://imgur.com/a/QAvnfG5)

<i> The Computational Statistics course gave a comprehensive and detailed overview of the cruicial concepts, such as random number generation, Monte Carlo simulations, bootstrap and jacknife, numerical approximation methods and expectation and maximisation algorithm. Both theoretical and computational aspects of the concepts were covered exhaustively. (III trimester, 2022-2023 a.y.)</i> 
