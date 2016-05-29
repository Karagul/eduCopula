# Intuitive Educational Examples from Copula Theory
This repository contains a few intuitive examples to illustrate core concepts from copula theory. Here's a short list of scripts and their respective purpose.
- `introToCopulas.R` demonstrates how a Gaussian copula can be used to simulate two correlated random variables with arbitrary marginal distributions. It accomplishes this with basic R code and thus without the use of the copula package in order to demystify the concept. ![alt text](http://i.imgur.com/KYZ3tkW.png "Gaussian Copula")
- `fhBounds.py` is a short Python script that generates a 3D visualization of three basic copulas (countermonotonicity, independence, and comonotonicity) in a bivariate setting. The countermonotonicity copula constitutes the lower Fréchet-Hoeffding bound, while the comonotonicity copula is the upper Fréchet-Hoeffding bound. The independence copula lies between the two.![alt text](http://i.imgur.com/x8CRhwL.png "Fréchet-Hoeffding")
- `copulaFamilies.R` is designed to enhance your understanding of copula classes and families. By using scatter-plots we emphasize differences between a Gaussian, t, Clayton, and Gumbel copula. ![alt text](http://i.imgur.com/TEtoSvZ.png "Copula Families")
- `historyOfCopulas.R` differs from the other scripts as it doesn't directly illustrate a concept. Instead it plots the usage of the term "copula" in mathematical publications over time. This script uses the file `copulaData.csv` (also part of this repo) as its data source to facilitate this brief bibliometric analysis. All data was sourced from [Scopus](https://www.scopus.com/). ![alt text](http://i.imgur.com/bCNNrtm.png "Bibliometric Analysis")
