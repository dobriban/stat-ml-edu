# Statistics and machine learning: from undergraduate to research

by [Edgar Dobriban, Associate Prof. of Statistics & Data Science, Wharton, Univ. of Pennsylvania](https://statistics.wharton.upenn.edu/profile/dobriban/)

- This repository contains links to references (books, courses, etc) that are useful for learning statistics and machine learning (as well as some neighboring topics).
References for background materials such as linear algebra, calculus/analysis/measure theory, probability theory, etc, are usually not included.

- The level of the references starts from advanced undergraduate stats/math/CS and in some cases goes up to the research level.
It is hoped that the list benefits students, researchers seeking to enter new areas, and lifelong learners.

- The list is highly subjective and incomplete, reflecting my own preferences, interests and biases. For instance, there is an emphasis on theoretical material. Most of the references included here are something that I have at least partially (and sometimes extensively) studied; and found helpful. Several topics are omitted due to lack of expertise (e.g., causal inference, Bayesian statistics, functional data analysis, biostatistics, ...).

- The links are to freely available author copies if those are available, or to online marketplaces otherwise (you are encouraged to search for the best price).

- Please feel free to contact [me](https://statistics.wharton.upenn.edu/profile/dobriban/) with suggestions.



# Statistics
## Principles and overview
- [Casella & Berger: Statistical Inference (2nd Edition)](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126) - Possibly the best introduction to the principles of statistical inference at an advanced undergraduate level. Mathematically rigorous but not technical.
- [Wasserman: All of Statistics: A Concise Course in Statistical Inference](https://www.amazon.com/All-Statistics-Statistical-Inference-Springer/dp/1441923225) - A panoramic overview of statistics; mathematical but proofs are omitted. Covers material overlapping with ESL, TSH, TPE, and other books in this list.
- [Cox: Principles of Statistical Inference](https://www.amazon.com/Principles-Statistical-Inference-D-Cox/dp/0521685672) - Covers a number of classical principles and ideas such as pivotal inference, ancillarity, conditioning. Light on math, but containing deep thoughts.


## Statistical Methodology
- [Hastie, Tibshirani & Friedman: The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf) - The bible of modern statistical methodology, comprehensive coverage from linear methods to kernels, basis expansions, trees/forests, model selection, high-dimensional methods, etc. Emphasizes ideas over math. Free on author's website. Known as "ESL".

## Statistical Theory
### Core Theory: First Year PhD Curriculum
- [Lehmann & Casella: Theory of Point Estimation, 2nd Edition](https://www.amazon.com/Theory-Point-Estimation-Springer-Statistics/dp/0387985026) - Solid mathematically rigoros overview of point estimation theory. Known as "TPE".
- [Lehmann & Casella: Testing Statistical Hypotheses, 4th Edition](https://www.amazon.com/Testing-Statistical-Hypotheses-Springer-Statistics-dp-3030705773/dp/3030705773) - A complement to TPE, covers the theory of inference (hypothesis tests and confidence intervals). Known as "TSH".
- [van der Vaart: Asymptotic Statistics](https://www.amazon.com/Asymptotic-Statistics-Statistical-Probabilistic-Mathematics/dp/0521784506) - Covers classical fixed-dimensional asymptotics. 

### Advanced Theory
#### Non-parametrics, minimax lower bounds
- [Tsybakov: Introduction to Nonparametric Estimation](https://www.amazon.com/Introduction-Nonparametric-Estimation-Springer-Statistics/dp/0387790519) - The first two chapters contain many core results and techniques in nonparametric estimation, including lower bounds (Le Cam, Fano, Assouad).
- Weissman, Ozgur, Han: Stanford EE 378 Course Materials. [Lecture Notes](https://theinformaticists.com/category/blog/online-lectures/) - Possibly the most comprehensive set of materials on information theoretic lower bounds, including estimation and testing (Ingster's method) with examples given in high-dimensional problems, optimization, etc. 
- [Duchi: Lecture Notes on Statistics and Information Theory](https://web.stanford.edu/class/stats311/lecture-notes.pdf) - Section II is another good reference on lower bounds.
- [Johnstone: Gaussian estimation: Sequence and wavelet models](https://imjohnstone.su.domains/GE_08_09_17.pdf) - Beautiful overview of estimation in Gaussian noise (shrinkage, wavelet thresholding, optimality). Rigorous and has challenging exercises.

#### Semiparametrics
- [van der Vaart: Semiparametric Statistics, Chapter III of Lectures at Ecole d'Ete de Probabilites de Saint-Flour XXIX, 1999](https://www.amazon.com/Lectures-Probability-Theory-Statistics-Bolthausen/dp/3540437363) - Concise and mathematically rigorous introduction to key ideas in semiparametrics.
- [Kosorok: Introduction to Empirical Processes and Semiparametric Inference](https://www.amazon.com/Introduction-Empirical-Processes-Semiparametric-Statistics/dp/0387749772) - Detailed and rigorous introduction to semiparametrics, also containing the required background from empirical process theory. A number of detailed examples are presented, which greatly aid appreciating the power of the theory.
- [Bickel, Klaassen, Ritov, Wellner: Efficient and Adaptive Estimation for Semiparametric Models](https://www.amazon.com/Efficient-Adaptive-Estimation-Semiparametric-Models/dp/0387984739/) - Thorough and rigorous, but also heavy, treatise on semi-parametrics; including some required background on local asymptotic normality. The first few chapters present the general theory and and can be focused on during a first reading.

#### Multivariate Statistical Analysis
- [Anderson: An Introduction to Multivariate Statistical Analysis](https://www.amazon.com/Introduction-Multivariate-Statistical-Analysis/dp/0471360910) - Standard reference on multivariate statistical analysis (OLS, LDA, PCA, factor analysis, MANOVA). Describes practical methods with mathematical rigor. Beautifully written.

#### Subsampling
- [Polits, Romano, Wolf: Subsampling](https://www.amazon.com/Subsampling-Springer-Statistics-Dimitris-Politis/dp/0387988548) - Canonical reference for the powerful  resampling methodology of subsampling. 

#### Empirical processes
- [van der Vaart, Wellner: Weak convergence and empirical processes](https://www.amazon.com/Weak-Convergence-Empirical-Processes-Applications/dp/0387946403) - Thorough and mathematically fully rigorous (sometimes technically heavy) book on empirical processes; key reference when working in the area.

# Machine Learning

## ML Theory
- [Shalev-Shwartz & Ben-David: Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf) - Good single reference source of core machine learning theory ideas and results.
- [Srebro: Computational and Statistical Learning Theory](https://home.ttic.edu/~nati/Teaching/TTIC31120/2016/) - Great course materials on Statistical/PAC  learning, online learning, crypto lower bounds.

## Deep Learning
### DL Practice
- [Courses at Deeplearning.ai](https://www.deeplearning.ai/)

### DL Theory 
This is subject to active development and research. There is no complete reference.
- [Telgarsky: Deep learning theory lecture notes](https://mjt.cs.illinois.edu/dlt/)

## Uncertainty quantification
- [Dobriban's course materials for STAT 991](https://github.com/dobriban/Topics-In-Modern-Statistical-Learning)

# Complements
## Optimization

- [Boyd and Vandenberghe: Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/) - Good user and algorithm-focused book on convex optimization. Mathematically rigorous and clean, but does not go deep in the theory.
- [Nesterov: Introductory Lectures on Convex Optimization: A Basic Course](https://www.amazon.com/Introductory-Lectures-Convex-Optimization-Applied/dp/1402075537/) - A deep dive into convex optimization theory, including optimality results.













