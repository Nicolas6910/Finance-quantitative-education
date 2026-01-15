# Cours de Finance Quantitative

Structure basee sur les programmes de reference mondiaux:
- Princeton MFin (Bendheim Center for Finance)
- MIT Sloan Master of Finance
- UC Berkeley Haas MFE
- Carnegie Mellon MSCF
- Oxford MSc Mathematical and Computational Finance
- CQF (Certificate in Quantitative Finance) de Paul Wilmott

---

## PARTIE I - HISTOIRE ET CONTEXTE (Semaines 1-4)

### Module 1: Origines de la Finance et des Marches
- Des marchands de Venise aux premieres bourses
- Bourse d'Amsterdam (1602) - VOC et premieres actions
- Naissance des obligations d'Etat
- Tulipomanie (1637) - premiere bulle speculative documentee

### Module 2: Fondations Mathematiques de la Finance (1654-1900)
- Pascal et Fermat: naissance des probabilites (1654)
- Bernoulli et l'utilite esperee (1738)
- Laplace et la theorie des probabilites
- Louis Bachelier: "Theorie de la Speculation" (1900) - these revolutionnaire

### Module 3: Revolution Quantitative (1952-1973)
- Harry Markowitz: theorie moderne du portefeuille (1952)
- William Sharpe: CAPM (1964)
- Eugene Fama: hypothese des marches efficients (1965)
- Black-Scholes-Merton: revolution des options (1973)
- Robert Merton: calcul stochastique en finance

### Module 4: Ere Moderne et Crises (1980-Present)
- Emergence des hedge funds quantitatifs (Renaissance Technologies, DE Shaw)
- Crise LTCM (1998) - limites des modeles
- Crise financiere de 2008 - remise en question
- Trading haute frequence (HFT)
- Machine Learning et Big Data en finance
- Crypto-actifs et DeFi

---

## PARTIE II - FONDEMENTS MATHEMATIQUES (Semaines 5-12)

*Base sur: Princeton FIN 501, MIT 15.S05, Berkeley MFE 230Q, CMU Math Prep*

### Module 5: Algebre Lineaire pour la Finance
- Vecteurs et matrices
- Systemes d'equations lineaires
- Valeurs propres et vecteurs propres
- Decomposition matricielle (SVD, Cholesky)
- Applications: optimisation de portefeuille, PCA

### Module 6: Calcul Differentiel et Integral
- Derivees et integrales
- Fonctions de plusieurs variables
- Derivees partielles et gradient
- Optimisation: conditions du premier et second ordre
- Multiplicateurs de Lagrange
- Conditions KKT (Karush-Kuhn-Tucker)

### Module 7: Probabilites
- Espaces de probabilite et axiomes
- Variables aleatoires discretes et continues
- Distributions: Normale, Log-normale, Student-t, Chi-carre
- Esperance, variance, moments
- Distributions jointes et marginales
- Independance et correlation
- Theoreme de Bayes

### Module 8: Statistiques et Econometrie
*Base sur: Princeton FIN 505, Berkeley MFE 230E*
- Estimation: maximum de vraisemblance (MLE), methode des moments (GMM)
- Tests d'hypotheses
- Regression lineaire simple et multiple
- Regression non-parametrique
- Heteroscedasticite et autocorrelation
- Introduction aux series temporelles

---

## PARTIE III - PROCESSUS STOCHASTIQUES (Semaines 13-20)

*Base sur: Princeton FIN 503/ORF 515, Berkeley MFE 230Q, Oxford core curriculum*

### Module 9: Marches Aleatoires et Mouvement Brownien
- Marche aleatoire discrete
- Passage a la limite: mouvement brownien
- Proprietes du mouvement brownien
- Mouvement brownien geometrique
- Simulation de trajectoires

### Module 10: Calcul Stochastique - Fondements
- Integrale d'Ito
- Lemme d'Ito (formule centrale)
- Equations differentielles stochastiques (EDS)
- Solution des EDS lineaires
- Theoreme de Girsanov

### Module 11: Martingales et Mesures de Probabilite
- Definition et proprietes des martingales
- Theoreme de representation des martingales
- Mesure risque-neutre
- Theoreme fondamental de l'evaluation des actifs
- Changement de mesure

### Module 12: Applications du Calcul Stochastique
- Equation de Black-Scholes (derivation rigoureuse)
- Equations de Fokker-Planck et Kolmogorov
- Formule de Feynman-Kac
- Processus de Poisson et sauts
- Modeles a volatilite stochastique (Heston, SABR)

---

## PARTIE IV - THEORIE DU PORTEFEUILLE (Semaines 21-26)

*Base sur: Princeton FIN 501, CMU Investments, Berkeley MFE 230A*

### Module 13: Rendement et Risque
- Mesures de rendement (arithmetique, geometrique, log)
- Volatilite et ecart-type
- Distributions des rendements financiers
- Queues epaisses (fat tails) et asymetrie
- VaR et Expected Shortfall

### Module 14: Theorie de Markowitz
- Frontiere efficiente
- Portefeuille a variance minimale
- Portefeuille tangent
- Droite du marche des capitaux (CML)
- Limites de l'approche moyenne-variance

### Module 15: Modeles d'Evaluation d'Actifs
- CAPM (Capital Asset Pricing Model)
- Beta et prime de risque
- Security Market Line (SML)
- APT (Arbitrage Pricing Theory)
- Modeles multi-facteurs de Fama-French (3 et 5 facteurs)
- Facteur momentum (Carhart)

### Module 16: Mesures de Performance
- Ratio de Sharpe
- Ratio de Sortino
- Ratio de Treynor
- Alpha de Jensen
- Information Ratio
- Maximum Drawdown

---

## PARTIE V - PRODUITS DERIVES (Semaines 27-36)

*Base sur: CMU Options, Princeton FIN 503, Berkeley MFE 230D, Hull textbook*

### Module 17: Options - Fondamentaux
- Call et Put europeens et americains
- Parite Put-Call
- Bornes sur les prix d'options
- Determinants du prix: sous-jacent, strike, temps, volatilite, taux
- Strategies de base: spreads, straddles, strangles

### Module 18: Modele Binomial
- Arbre binomial a une periode
- Evaluation risque-neutre
- Extension multi-periodes
- Convergence vers Black-Scholes
- Options americaines et exercice anticipe

### Module 19: Modele de Black-Scholes
- Hypotheses du modele
- Derivation de l'equation
- Formules pour calls et puts europeens
- Limites et extensions du modele

### Module 20: Les Grecques
- Delta: sensibilite au prix du sous-jacent
- Gamma: convexite
- Theta: decay temporel
- Vega: sensibilite a la volatilite
- Rho: sensibilite aux taux
- Gestion dynamique (delta hedging)

### Module 21: Volatilite
- Volatilite historique vs implicite
- Surface de volatilite
- Smile et skew de volatilite
- Modeles de volatilite locale (Dupire)
- Modeles a volatilite stochastique (Heston, SABR)

### Module 22: Options Exotiques
- Options barrieres (knock-in, knock-out)
- Options asiatiques (moyenne)
- Options lookback
- Options digitales/binaires
- Methodes de pricing: analytique, Monte Carlo, PDE

---

## PARTIE VI - TAUX D'INTERET ET CREDIT (Semaines 37-42)

*Base sur: Princeton FIN 521, Berkeley MFE 230I, CMU Fixed Income*

### Module 23: Marches de Taux
- Obligations et conventions de marche
- Prix, rendement, duration, convexite
- Courbe des taux et structure par terme
- Bootstrapping de la courbe zero-coupon
- Forward rates

### Module 24: Modeles de Taux d'Interet
- Modeles d'equilibre: Vasicek, CIR
- Modeles sans arbitrage: Ho-Lee, Hull-White, HJM
- Calibration aux prix de marche
- Pricing des caps, floors, swaptions

### Module 25: Derives de Taux
- Swaps de taux d'interet (IRS)
- Basis swaps
- Caps et floors
- Swaptions
- Evaluation et risques

### Module 26: Risque de Credit
- Probabilite de defaut et taux de recouvrement
- Modeles structurels (Merton)
- Modeles a forme reduite (intensite)
- Credit Default Swaps (CDS)
- Spread de credit et pricing

---

## PARTIE VII - GESTION DES RISQUES (Semaines 43-46)

*Base sur: Berkeley MFE 230H, CMU Risk Management, CQF Module 2*

### Module 27: Value at Risk (VaR)
- VaR parametrique (variance-covariance)
- VaR historique
- VaR Monte Carlo
- Backtesting du VaR
- Limites du VaR

### Module 28: Expected Shortfall et Mesures Coherentes
- Proprietes d'une mesure de risque coherente
- Expected Shortfall (CVaR)
- Comparaison VaR vs ES
- Allocation du capital

### Module 29: Stress Testing et Scenarios
- Scenarios historiques
- Scenarios hypothetiques
- Reverse stress testing
- Exigences reglementaires (Bale III/IV)

### Module 30: Risques Operationnels et de Modele
- Risque de modele
- Risque de liquidite
- Risque operationnel
- Gouvernance des modeles

---

## PARTIE VIII - PYTHON POUR LA FINANCE (Semaines 47-52)

*Base sur: Berkeley MFE 230P, CMU Financial Computing, CQF Python labs*

### Module 31: Fondamentaux Python
- Environnement (Jupyter, VSCode)
- Types de donnees et structures
- Fonctions et classes
- NumPy: operations vectorielles
- Pandas: manipulation de donnees

### Module 32: Donnees Financieres
- APIs: Yahoo Finance, Alpha Vantage, Bloomberg
- Nettoyage et preparation des donnees
- Rendements et transformations
- Visualisation: Matplotlib, Seaborn, Plotly

### Module 33: Series Temporelles
- Analyse exploratoire
- Stationnarite et tests (ADF, KPSS)
- Modeles ARMA/ARIMA
- Modeles GARCH pour la volatilite
- Bibliotheque statsmodels

### Module 34: Implementation Portefeuille
- Optimisation Markowitz avec scipy
- Contraintes et regularisation
- Backtesting de strategies
- Bibliotheques: cvxpy, PyPortfolioOpt

---

## PARTIE IX - METHODES NUMERIQUES (Semaines 53-58)

*Base sur: Oxford numerical methods, CMU Simulation, CQF computational finance*

### Module 35: Monte Carlo
- Generation de nombres aleatoires
- Simulation de trajectoires
- Pricing d'options par Monte Carlo
- Reduction de variance: variables antithetiques, controle
- Simulation de modeles multi-facteurs

### Module 36: Methodes de Differences Finies
- Discretisation de l'equation de Black-Scholes
- Schema explicite, implicite, Crank-Nicolson
- Stabilite et convergence
- Conditions aux bords
- Options americaines et exercice anticipe

### Module 37: Arbres et Lattices
- Arbres binomiaux et trinomiaux
- Calibration a la volatilite
- Options path-dependent
- Implementation efficace

### Module 38: Optimisation Numerique
- Methodes de gradient
- Newton-Raphson
- Programmation quadratique
- Optimisation convexe
- Applications: calibration, portefeuille

---

## PARTIE X - STRATEGIES QUANTITATIVES (Semaines 59-64)

*Base sur: CMU Studies in Financial Engineering, Berkeley electives*

### Module 39: Factor Investing
- Facteurs academiques: value, momentum, size, quality
- Construction de facteurs
- Backtesting rigoureux
- Biais de look-ahead et survivorship
- Smart beta et ETF factoriels

### Module 40: Trading Statistique
- Mean reversion et pairs trading
- Cointegration et test de Engle-Granger
- Statistical arbitrage
- Market making basics

### Module 41: Microstructure de Marche
*Base sur: Oxford market microstructure, Berkeley HFT elective*
- Carnets d'ordres (order books)
- Bid-ask spread et liquidite
- Impact de marche
- Execution optimale (Almgren-Chriss)

### Module 42: Backtesting et Evaluation
- Methodologie de backtesting
- Biais courants (look-ahead, survivorship, overfitting)
- Walk-forward analysis
- Validation out-of-sample

---

## PARTIE XI - MACHINE LEARNING EN FINANCE (Semaines 65-72)

*Base sur: MIT 15.C51, Oxford deep learning, Berkeley MFE 230P, CMU ML electives*

### Module 43: Apprentissage Supervise
- Regression: lineaire, Ridge, Lasso, ElasticNet
- Classification: logistique, SVM
- Arbres de decision et Random Forest
- Gradient Boosting (XGBoost, LightGBM)
- Cross-validation et hyperparametres

### Module 44: Apprentissage Non-Supervise
- Clustering: K-means, hierarchique, DBSCAN
- Reduction de dimension: PCA, t-SNE, UMAP
- Detection d'anomalies
- Applications: regime detection, asset clustering

### Module 45: Reseaux de Neurones
- Perceptron et backpropagation
- Architectures: MLP, CNN pour series temporelles
- Reseaux recurrents: RNN, LSTM, GRU
- Transformers et attention mechanisms
- Frameworks: PyTorch, TensorFlow

### Module 46: Applications ML en Finance
- Prediction de rendements
- Scoring de credit
- NLP pour sentiment analysis
- Reinforcement learning pour trading
- Considerations ethiques et risque de modele

---

## PARTIE XII - PROJETS CAPSTONE (Semaines 73-78)

*Base sur: Berkeley Applied Finance Project, CMU capstone, CQF final project*

### Projet 1: Construction de Portefeuille Quantitatif
- Collecte et nettoyage de donnees
- Implementation multi-facteurs
- Optimisation et contraintes
- Backtesting complet
- Rapport et presentation

### Projet 2: Pricing de Derives
- Implementation complete d'un pricer
- Multiple methodes (analytique, Monte Carlo, PDE)
- Calibration a la volatilite implicite
- Greeks et risk management
- Documentation et tests

### Projet 3: Strategie de Trading
- Developpement d'une strategie complete
- Backtesting rigoureux
- Analyse de risque
- Execution simulee
- Evaluation de performance

---

## LIVRES DE REFERENCE

### Obligatoires
1. **John Hull** - "Options, Futures, and Other Derivatives" (11th ed.)
2. **Steven Shreve** - "Stochastic Calculus for Finance I & II"
3. **Paul Wilmott** - "Paul Wilmott on Quantitative Finance" (3 volumes)

### Recommandes
4. **Paul Glasserman** - "Monte Carlo Methods in Financial Engineering"
5. **Mark Joshi** - "The Concepts and Practice of Mathematical Finance"
6. **Ruey Tsay** - "Analysis of Financial Time Series"
7. **Marcos Lopez de Prado** - "Advances in Financial Machine Learning"
8. **Dan Stefanica** - "A Primer for the Mathematics of Financial Engineering"
9. **Martin Baxter & Andrew Rennie** - "Financial Calculus"
10. **Alex Kuznetsov** - "The Complete Guide to Capital Markets for Quantitative Professionals"

### Preparation Entretiens
11. **Xinfeng Zhou** - "A Practical Guide to Quantitative Finance Interviews"
12. **Timothy Crack** - "Heard on the Street"

---

## SOURCES ET PROGRAMMES DE REFERENCE

- [Princeton MFin - Bendheim Center](https://bcf.princeton.edu/academic-programs/master-in-finance/)
- [MIT Sloan MFin](https://mitsloan.mit.edu/mfin/explore-program/mfin-curriculum)
- [UC Berkeley Haas MFE](https://mfe.haas.berkeley.edu/academics/curriculum)
- [Carnegie Mellon MSCF](https://www.cmu.edu/mscf/academics/curriculum/index.html)
- [Oxford MSc Mathematical Finance](https://www.ox.ac.uk/admissions/graduate/courses/msc-mathematical-and-computational-finance)
- [Imperial College MSc Mathematics and Finance](https://www.imperial.ac.uk/study/courses/postgraduate-taught/mathematics-finance/)
- [CQF - Certificate in Quantitative Finance](https://www.cqf.com/about-cqf/program-structure/program-overview)
- [QuantNet Rankings](https://quantnet.com/mfe-programs-rankings/)
- [QuantNet Master Reading List](https://quantnet.com/threads/master-reading-list-for-quants-mfe-financial-engineering-students.535/)

---

## DUREE ESTIMEE

- **Total**: 78 semaines (~18 mois a temps partiel)
- **Histoire**: 4 semaines
- **Mathematiques fondamentales**: 8 semaines
- **Processus stochastiques**: 8 semaines
- **Portefeuille**: 6 semaines
- **Derives**: 10 semaines
- **Taux et credit**: 6 semaines
- **Gestion des risques**: 4 semaines
- **Python**: 6 semaines
- **Methodes numeriques**: 6 semaines
- **Strategies quantitatives**: 6 semaines
- **Machine Learning**: 8 semaines
- **Projets**: 6 semaines

---

*Structure creee le 2026-01-15*
*Basee sur les meilleurs programmes MFE/MQF mondiaux*
