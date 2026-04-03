# M4 Time Series Forecasting — Quarterly

Comparaison de 7 modèles de prévision sur le sous-ensemble 
Quarterly du Challenge M4 (100 séries trimestrielles).

## Résultats obtenus

| Modèle | sMAPE (%) |
|---|---|
| Transformer | 31.68 |
| SARIMA | 34.87 |
| MLP | 35.17 |
| ARIMA | 35.26 |
| LSTM | 36.10 |
| Gradient Boosting | 43.31 |
| Random Forest | 47.66 |
| Naive2 (benchmark M4) | 10.91 |

## Modèles implémentés
- Statistique : ARIMA, SARIMA (pmdarima)
- Machine Learning : Random Forest, Gradient Boosting (scikit-learn)
- Deep Learning : MLP, LSTM (TensorFlow/Keras), Transformer (PyTorch)

## Technologies
Python · Pandas · NumPy · Scikit-learn · TensorFlow · PyTorch · Statsmodels

## Données
Données M4 Quarterly disponibles ici :
https://github.com/Mcompetitions/M4-methods/tree/master/Dataset
