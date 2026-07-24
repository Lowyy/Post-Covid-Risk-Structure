# Post-COVID Risk Structure in US Financial Markets

Empirical Methods in Finance — HEC Lausanne, May 2026

## Question
Has the structure of risk in US financial markets changed since COVID-19?

## Data
S&P 500, Gold, US IG Bonds — daily, 2010–2026 (~4,100 obs)

## Methods
GARCH / EGARCH (QML + Bollerslev–Wooldridge SEs) → DCC-(E)GARCH mixed
spec → Bai-Perron structural breaks → Chow-style Wald tests

<img width="1389" height="1189" alt="image" src="https://github.com/user-attachments/assets/b59fa79c-312c-4229-b7f3-961f31bfe2a9" />

## Headline result
Equity–bond correlation flipped from −0.33 to +0.18 across the COVID break;
60/40 Sharpe collapsed from 1.04 to 0.54, max drawdown more than doubled.

## Contributors
Léo, Frédéric, Alan, Corentin, André
