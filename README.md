# Paul Vega

### Quantitative Research · Time Series Machine Learning · Research Systems

**CS & Mathematics @ University of Maryland** — Executive Board @ Maryland Quant Finance Club — Research Fellow @ Startup Shell

[![Email](https://img.shields.io/badge/Email-vega.paul.pfv%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vega.paul.pfv@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Paul%20Vega-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulfvega)

---

## About

I build research systems end to end: from hypothesis design and labeling methodology, through statistically validated ML experiments, to deployed software. My forte is quantitative research on sequential data, but the work spans open-source Python packages, desktop tooling, embedded machine learning in constrained runtimes, and cloud research infrastructure.

The thread connecting everything: **research that survives contact with reality.** A model that looks good in a notebook is a hypothesis, not a result. The interesting problems are honest validation, leakage control, and knowing when a system is learning signal versus memorizing noise.

---

## Research & Projects

### 📄 Classification on Triple-Barrier Problems Within a Convex Payoff Structure — 3-Part Paper

Original research on classification when the reward is a rule-constrained payout game rather than symmetric profit-and-loss. Shows why symmetric triple-barrier labels fail under convex payoff constraints, develops a label-health screening method that avoids economic overfitting, introduces an account-level bootstrap that treats the account itself as a second triple-barrier problem, and documents a forward-test failure that motivated a stricter eight-stage validation standard — same-count random baselines, probability of backtest overfitting, sealed quarantine holdouts, and sentiment/regime agreement gates.

[📥 Download PDF](https://github.com/4SIGHTalgo/4SIGHTalgo/raw/main/saber_classification_triple_barrier_parts_1_to_3.pdf)

### 🧪 finShell — Label & Backtest Validation Engine

Model-free Python validation framework born directly from the paper above. Audits whether a label beats same-count random paths, fits selectors inside purged combinatorial cross-validation with block bootstrap, scores sealed out-of-sample quarantine data, and stress-tests economics with barrier-based Monte Carlo account paths. Deterministic, seeded, and schema-agnostic via column role mapping. Published on PyPI.

[![PyPI](https://img.shields.io/pypi/v/finshell?style=flat-square&label=PyPI)](https://pypi.org/project/finshell/) [![Repo](https://img.shields.io/badge/GitHub-finShell-181717?style=flat-square&logo=github)](https://github.com/4SIGHTalgo/finShell)

### 📈 Mid-Frequency ML Research Pipeline

End-to-end research infrastructure for sequential prediction: event-driven candidate generation (CUSUM filters, information-driven bars), gradient-boosted classifiers tuned with Optuna, hidden Markov regime models trained walk-forward, decision-time sentiment scoring with leakage audits, purged cross-validation at scale, and live inference with regime routing and feature-freshness monitoring. Backed by PostgreSQL/Supabase storage and AWS compute.

### 🧠 MQL5 Neural Network Library

Deep learning implemented natively inside MetaTrader 5 — an environment with no ML support. Custom MLP, RNN, and LSTM architectures written from scratch in MQL5 behind a common model interface, trained with Adam, serialized to binary weight files, and deployed through Expert Advisors for real-time inference with zero external dependencies.

[![Repo](https://img.shields.io/badge/GitHub-MQL5--Neural--Network--Library-181717?style=flat-square&logo=github)](https://github.com/4SIGHTalgo/MQL5-Neural-Network-Library)

### 🔁 MLP Statistical Arbitrage

Neural-network enhancement of classical correlation-based statistical arbitrage. A multilayer perceptron scans every major currency-pair combination and scores candidate trades, benchmarked against a plain Pearson/Spearman correlation strategy, with genetic and forward optimization used to control overfitting.

[![Repo](https://img.shields.io/badge/GitHub-MQL5--Multi--Layer--Perception-181717?style=flat-square&logo=github)](https://github.com/4SIGHTalgo/MQL5-Mutli-Layer-Perception)

### 🖥️ Backtest & Optimization App

Desktop research tool (Python/Tkinter) that combines data loading, a modular auto-discovered strategy catalogue, discrete trade simulation, Monte Carlo risk analysis (VaR, CVaR, equity confidence bands), and grid-search parameter optimization in one interface. Engine validated against TradingView with near-identical equity curves and trade statistics.

[![Repo](https://img.shields.io/badge/GitHub-Back--test--and--Optimization--App-181717?style=flat-square&logo=github)](https://github.com/4SIGHTalgo/Back-test-and-Optimization-App)

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MQL5](https://img.shields.io/badge/MQL5-1B1F24?style=for-the-badge)

**Machine Learning & Data**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-00427E?style=for-the-badge)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)

Modeling toolkit: gradient boosting, feedforward/recurrent networks, hidden Markov models, bootstrap and Monte Carlo methods, purged combinatorial cross-validation, probability calibration, lexicon-based NLP sentiment.

**Infrastructure & Tools**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![MetaTrader 5](https://img.shields.io/badge/MetaTrader%205-0A66C2?style=for-the-badge)

---

## GitHub Stats

![Paul's GitHub Stats](https://github-readme-stats.vercel.app/api?username=4SIGHTalgo&show_icons=true&theme=tokyonight)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=4SIGHTalgo&layout=compact&theme=tokyonight)

---

## Contact

Open to conversations about quantitative research, time series machine learning, research tooling, and applied AI.

**[vega.paul.pfv@gmail.com](mailto:vega.paul.pfv@gmail.com)**
