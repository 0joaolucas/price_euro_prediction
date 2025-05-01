# Previsão de Preços de Casas (Regressão)

Este projeto aplica técnicas de Machine Learning para prever o preço de imóveis em euros, usando dados reais da cidade de Cluj-Napoca.

## 🔍 Objetivo

Construir um modelo de regressão capaz de prever o valor de um imóvel com base em características como tamanho, bairro, número de cômodos e outros atributos relevantes.

## 🧪 Técnicas Utilizadas

- Pré-processamento de dados
- Engenharia de atributos (Feature Engineering)
- Normalização
- Treinamento com Random Forest Regressor
- Avaliação com MAE, RMSE e R² Score

## ⚙️ Métricas do Modelo

- **MAE**: ~16.464  
- **RMSE**: ~21.443  
- **R² Score**: ~0.868

Esses valores indicam uma boa performance do modelo após aplicação de feature engineering.

## 📁 Estrutura

- `cluj_prices.ipynb` – Notebook com todo o código e explicações
- `cluj_prices_lm.pkl` – Modelo salvo com pickle
- `output.png` – Boxplot exploratório
- (Opcional) `cluj_prices.csv` – Dataset utilizado *(não incluído no repositório)*

## 📦 Como usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   cd seu-repo
