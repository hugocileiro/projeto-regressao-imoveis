# 🏠 Precificação de Imóveis - King County (EUA)

**Projeto Final - Módulo 1 | Desenvolvimento de IA para Análise Preditiva**

---

## 🎯 Objetivo do Projeto

Este projeto desenvolve um modelo de **Regressão Linear** para estimar o valor de venda de imóveis no condado de **King County (EUA)**, com base em características físicas e de localização.

**Problema de negócio:** Uma imobiliária deseja precificar imóveis de forma rápida e baseada em dados, reduzindo a subjetividade e agilizando o processo de avaliação.

**Variável-alvo:** `price` (valor de venda em dólares - valor numérico contínuo)

---

## 📊 Dataset

**Opção A** - Dataset `kc_house_data.csv` com **21.613 registros** de vendas de imóveis.

Colunas principais:
- `price`: Preço de venda (variável-alvo)
- `bedrooms`, `bathrooms`: Número de quartos e banheiros
- `sqft_living`, `sqft_lot`: Área construída e do terreno
- `floors`, `waterfront`, `view`, `condition`, `grade`: Características do imóvel
- `yr_built`, `yr_renovated`: Ano de construção e reforma
- `lat`, `long`: Coordenadas geográficas

---

## 🚀 Tecnologias e Técnicas Utilizadas

| Etapa | Técnicas |
|-------|----------|
| **Linguagem** | Python 3 |
| **Manipulação de dados** | Pandas, NumPy |
| **Visualização** | Matplotlib, Seaborn |
| **Modelagem** | Scikit-learn (LinearRegression) |
| **Pré-processamento** | One-Hot Encoding, StandardScaler |
| **Métricas** | MAE, MSE, RMSE, R² |

---

## 📈 Resultados - Modelo v1

| Métrica | Valor |
|---------|-------|
| **R² (Teste)** | 0,6861 (68,61%) |
| **RMSE** | US$ 114.331,04 |
| **MAE** | US$ 86.101,61 |
| **Erro percentual médio** | 24,1% |
| **Preço médio (teste)** | US$ 473.893,42 |

### Interpretação de Negócio

O modelo explica **68,6%** da variação dos preços dos imóveis. Em média, o erro de previsão é de **±US$ 86 mil**, o que representa **24%** do preço médio.

- ✅ **Adequado para:** Pré-avaliação inicial e triagem de imóveis
- ⚠️ **Limitação:** Para decisões de financiamento, recomenda-se combinar com avaliação presencial de um corretor

---

## 📁 Estrutura do Projeto
