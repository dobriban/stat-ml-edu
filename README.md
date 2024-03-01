# Statistics and machine learning: from undergraduate to research

by [Edgar Dobriban, Associate Prof. of Statistics & Data Science, Wharton; w/ Secondary Appointment in Computer and Information Science, Univ. of Pennsylvania](https://statistics.wharton.upenn.edu/profile/dobriban/)

- This repository contains links to references (books, courses, etc) that are useful for **learning statistics and machine learning** (as well as some neighboring topics).
References for background materials such as linear algebra, calculus/analysis/measure theory, probability theory, etc, are usually not included.

- The level of the references starts from **advanced undergraduate stats/math/CS** and in some cases goes **up to the research** level. The books are often **standard references and textbooks, used at leading institutions**. In particular, several of the books are used in the standard curriculum of the PhD program in Statistics at Stanford University (where I learned from them as well), as well as at the University of Pennsylvania (where I work).
The goal is to benefit **students, researchers seeking to enter new areas, and lifelong learners**.

-  For each topic, materials are listed in a rough order of from **basic to advanced**.
  
- The list is highly **subjective and incomplete**, reflecting my own preferences, interests and biases. For instance, there is an emphasis on theoretical material. Most of the references included here are something that I have at least partially (and sometimes extensively) studied; and found helpful. Others are on my to-read list. **Several topics are omitted** due to lack of expertise (e.g., causal inference, Bayesian statistics, time series, sequential decision-making, functional data analysis, biostatistics, ...).

- The links are to freely available author copies if those are available, or to online marketplaces otherwise (you are encouraged to search for the best price).

- How to use these materials to learn: To be an efficient researcher, certain **core material must be mastered**. However, there is so much specialized knowledge that it can be overwhelming to know it all. Fortunately, it is often enough to **know what type of results/methods/tools are available, and where to find them**. Then, at any point during a research project when they are needed, they can be recalled and used.

- Please feel free to contact [me](https://statistics.wharton.upenn.edu/profile/dobriban/) with suggestions.



# Statistics
## Principles and overview
- [Casella & Berger: Statistical Inference (2nd Edition)](https://www.amazon.com/Statistical-Inference-George-Casella/dp/0534243126) - Possibly the best introduction to the principles of statistical inference at an advanced undergraduate level. Mathematically rigorous but not technical.
- [Wasserman: All of Statistics: A Concise Course in Statistical Inference](https://www.amazon.com/All-Statistics-Statistical-Inference-Springer/dp/1441923225) - A panoramic overview of statistics; mathematical but proofs are omitted. Covers material overlapping with ESL, TSH, TPE (abbreviations defined below), and other books in this list.
- [Cox: Principles of Statistical Inference](https://www.amazon.com/Principles-Statistical-Inference-D-Cox/dp/0521685672) - Covers a number of classical principles and ideas such as pivotal inference, ancillarity, conditioning, including famous paradoxes. Light on math, but containing deep thoughts.


## Statistical Methodology
- [Hastie, Tibshirani & Friedman: The Elements of Statistical Learning](https://hastie.su.domains/ElemStatLearn/printings/ESLII_print12_toc.pdf) - The bible of modern statistical methodology, comprehensive coverage from linear methods to kernels, basis expansions, trees/forests, model selection, high-dimensional methods, etc. Emphasizes ideas over math. Free on author's website. Known as "ESL".

## Statistical Theory
### Core Theory: First Year PhD Curriculum
- [Lehmann & Casella: Theory of Point Estimation, 2nd Edition](https://www.amazon.com/Theory-Point-Estimation-Springer-Statistics/dp/0387985026) - Solid mathematically rigoros overview of point estimation theory. Known as "TPE".
- [Lehmann & Casella: Testing Statistical Hypotheses, 4th Edition](https://www.amazon.com/Testing-Statistical-Hypotheses-Springer-Statistics-dp-3030705773/dp/3030705773) - A complement to TPE, covers the theory of inference (hypothesis tests and confidence intervals). Known as "TSH".
- [van der Vaart: Asymptotic Statistics](https://www.amazon.com/Asymptotic-Statistics-Statistical-Probabilistic-Mathematics/dp/0521784506) - Covers classical fixed-dimensional asymptotics.
- [Candes: Theory of Statistics, STAT 300C Lecture Notes](https://candes.su.domains/teaching/stats300c/) - Modern statistical theory: sparsity, detection thresholds, multiple testing, false discovery rate control, Benjamini-Hochberg procedure, model selection, conformal prediction, etc.

### Advanced Theory
This section is the most detailed one, as it is the closest to my research.
#### Non-parametrics, minimax lower bounds
- [Tsybakov: Introduction to Nonparametric Estimation](https://www.amazon.com/Introduction-Nonparametric-Estimation-Springer-Statistics/dp/0387790519) - The first two chapters contain many core results and techniques in nonparametric estimation, including lower bounds (Le Cam, Fano, Assouad).
- Weissman, Ozgur, Han: Stanford EE 378 Course Materials. [Lecture Notes](https://theinformaticists.com/category/blog/online-lectures/) - Possibly the most comprehensive set of materials on information theoretic lower bounds, including estimation and testing (Ingster's method) with examples given in high-dimensional problems, optimization, etc. 
- [Johnstone: Gaussian estimation: Sequence and wavelet models](https://imjohnstone.su.domains/GE_08_09_17.pdf) - Beautiful overview of estimation in Gaussian noise (shrinkage, wavelet thresholding, optimality). Rigorous and deep, has challenging exercises.


#### Overviews of statistical machine learning theory
- [Duchi: Lecture Notes on Statistics and Information Theory](https://web.stanford.edu/class/stats311/lecture-notes.pdf) - Eclectic modern topics in modern statistical learning, at the interface of stats and ML: intro to information theory tools, PAC-Bayes, minimax lower bounds (estimation and testing), probabilistic prediction, calibration, online game playing, online optimization, etc.
- [Bach: Learning Theory from First Principles](https://www.di.ens.fr/~fbach/ltfp_book.pdf)
- [RJ Tibshirani: Lecture Notes on Advanced Topics in Statistical Learning: Spring 2023](https://www.stat.berkeley.edu/~ryantibs/statlearn-s23/) - Overview of a variety of important dna modern topics in statistical machine learning.

#### Semiparametrics
- [van der Vaart: Semiparametric Statistics, Chapter III of Lectures at Ecole d'Ete de Probabilites de Saint-Flour XXIX, 1999](https://www.amazon.com/Lectures-Probability-Theory-Statistics-Bolthausen/dp/3540437363) - Concise and mathematically rigorous introduction to key ideas in semiparametrics.
- [Kosorok: Introduction to Empirical Processes and Semiparametric Inference](https://www.amazon.com/Introduction-Empirical-Processes-Semiparametric-Statistics/dp/0387749772) - Detailed and rigorous introduction to semiparametrics, also containing the required background from empirical process theory. A number of detailed examples are presented, which greatly aid appreciating the power of the theory.
- [Bickel, Klaassen, Ritov, Wellner: Efficient and Adaptive Estimation for Semiparametric Models](https://www.amazon.com/Efficient-Adaptive-Estimation-Semiparametric-Models/dp/0387984739/) - Thorough and rigorous, but also heavy, treatise on semi-parametrics; including some required background on local asymptotic normality. The first few chapters present the general theory and and can be focused on during a first reading.


#### Multivariate statistical analysis
- [Anderson: An Introduction to Multivariate Statistical Analysis](https://www.amazon.com/Introduction-Multivariate-Statistical-Analysis/dp/0471360910) - Standard reference on multivariate statistical analysis (OLS, LDA, PCA, factor analysis, MANOVA). Describes practical methods with mathematical rigor. Beautifully written.

#### Subsampling
- [Polits, Romano, Wolf: Subsampling](https://www.amazon.com/Subsampling-Springer-Statistics-Dimitris-Politis/dp/0387988548) - Canonical reference for the powerful  resampling methodology of subsampling. 

#### Empirical processes
- [van der Vaart, Wellner: Weak convergence and empirical processes](https://www.amazon.com/Weak-Convergence-Empirical-Processes-Applications/dp/0387946403) - Thorough and mathematically fully rigorous (sometimes technically heavy) book on empirical processes; key reference when working in the area.

#### High dimensional (mean field, proportional limit) asymptotics; random matrix theory (RMT) for stats+ML
- [Mei: Lecture Notes for Mean Field Asymptotics in Statistical Learning](https://www.stat.berkeley.edu/~songmei/Teaching/STAT260_Spring2021/index.html) - Good overview of various techniques in the area: replica methods, Gaussian comparison inequalities/Convex Gaussian Minimax Theorem, Stieltjes transforms for random matrices, and approximate message passing (AMP). Several applications to stats+ML are presented.
- [Couillet & Debbah: Random Matrix Methods for Wireless Communications](https://www.amazon.com/Random-Matrix-Methods-Wireless-Communications/dp/1107011639) - The first section is a good overview of the most commonly used RMT techniques and results for stats+ML. Strikes an ideal balance between rigor and clarity (Statements are rigorous, detailed proof sketches are presented, but some of the most technical proof components are omitted and references to papers are given).
- [Bai & Silverstein: Spectral Analysis of Large Dimensional Random Matrices](https://www.amazon.com/Spectral-Analysis-Dimensional-Matrices-Statistics/dp/1441906606) - A standard reference in the field, with citable results stated at full generality, and with proofs. Nonetheless, requires filling in details of calculations/arguments, which can take a lot of effort for students.

# Machine Learning

## ML Theory
- [Shalev-Shwartz & Ben-David: Understanding Machine Learning: From Theory to Algorithms](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf) - Good single reference source of core machine learning theory ideas and results.
- [Srebro: Computational and Statistical Learning Theory](https://home.ttic.edu/~nati/Teaching/TTIC31120/2016/) - Great course materials on Statistical/PAC  learning, online learning, crypto lower bounds.
- [Orabona: A Modern Introduction to Online Learning](https://arxiv.org/abs/1912.13213)

## Deep Learning
### DL Practice
- [Courses at Deeplearning.ai](https://www.deeplearning.ai/)

### DL Theory 
This is subject to active development and research. There is no complete reference.
- [Telgarsky: Deep learning theory lecture notes](https://mjt.cs.illinois.edu/dlt/)

## Uncertainty quantification
- [Dobriban's course materials for STAT 991](https://github.com/dobriban/Topics-In-Modern-Statistical-Learning) - Contains detailed references to materials on uncertainty quantification for ML, including conformal prediction/predictive inference and calibration.

# Complements
## Optimization

- [Boyd and Vandenberghe: Convex Optimization](https://web.stanford.edu/~boyd/cvxbook/) - Good user- and algorithm-focused book on convex optimization. Mathematically rigorous and clean, but does not go deep in the theory.
- [Nesterov: Introductory Lectures on Convex Optimization: A Basic Course](https://www.amazon.com/Introductory-Lectures-Convex-Optimization-Applied/dp/1402075537/) - A deep dive into convex optimization theory, including optimality results.
- [Bottou, Curtis, Nocedal: Optimization Methods for Large-Scale Machine Learning](https://arxiv.org/abs/1606.04838) - Good introductory review focusing on scalable first order methods, such as SGD and variance-reduced methods. Has some proofs.
- [Duchi: Introductory Lectures on Stochastic Optimization](https://stanford.edu/~jduchi/PCMIConvex/Duchi16.pdf)

## Probability
### Concentration inequalities
- [Boucheron, Lugosi, Massart: Concentration Inequalities: A Nonasymptotic Theory of Independence](https://www.amazon.com/Concentration-Inequalities-Nonasymptotic-Theory-Independence/dp/019876765X/) - Standard reference on concentration inequalities, used often in proofs in stats/ML.
- [Vershynin: High-Dimensional Probability: An Introduction with Applications in Data Science](https://www.math.uci.edu/~rvershyn/papers/HDP-book/HDP-book.html) - Another standard reference in the area, with citable and usable results. Also has some example applications to covariance estimation, graph estimation, etc.

### Chaining
- [Talagrand: Upper and Lower Bounds for Stochastic Processes](https://michel.talagrand.net/ULB.pdf) - Chaining is a theoretical tool invented by Talagrand, and can often give optimal bounds of the tail behavior of stochastic processes (even when standard concentration inequalities fail to do so). This is the a readable, but rigorous and complete reference by the inventor of the theory.












