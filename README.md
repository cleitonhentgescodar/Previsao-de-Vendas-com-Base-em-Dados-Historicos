# Previsão de Vendas com Base em Dados Históricos

Projeto de análise de dados e modelagem preditiva para **previsão de vendas em e-commerce**, usando **Python**, **Pandas**, **Matplotlib** e **Scikit-learn**.

O notebook explora o comportamento histórico das vendas, identifica padrões de sazonalidade, mede o impacto de **promoções**, **feriados**, **marketing** e **preço médio**, e treina um modelo de **Regressão Linear** para estimar vendas futuras.

---

## 🎯 Objetivo

Responder, com base em dados, perguntas como:

- As vendas estão crescendo ao longo do tempo?
- Existe sazonalidade no negócio?
- Promoções e feriados realmente impulsionam as vendas?
- Qual é a relação entre investimento em marketing e volume vendido?
- O preço médio afeta a demanda?
- É possível prever vendas futuras com um modelo simples e interpretável?

---

## 🛠 Tecnologias utilizadas

- Python 3  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 📊 Base de dados

O dataset contém informações históricas de vendas.

### Principais colunas:

- `data`  
- `vendas`  
- `promocao`  
- `investimento_marketing`  
- `feriado`  
- `preco_medio`  

### Tratamento realizado:

- Conversão da coluna `data` para datetime  
- Criação de variáveis temporais (`ano`, `mes`, `trimestre`, `nome_mes`)  
- Tratamento de valores ausentes com mediana  

---

## 🔎 Etapas da análise

### 1. Preparação dos dados
Leitura, limpeza e transformação das variáveis.

### 2. Análise Exploratória (EDA)
- Estatísticas descritivas  
- Crescimento anual  
- Sazonalidade  
- Impacto de promoções e feriados  
- Correlações  

### 3. Visualizações
- Heatmap de correlação  
- Evolução temporal das vendas  
- Comparações mensais  
- Relação marketing × vendas  
- ROI de marketing  
- Elasticidade-preço  
- Vendas reais vs previstas  

### 4. Análise de negócio
- Identificação de meses fortes e fracos  
- Impacto de campanhas  
- Influência de feriados  
- Retorno de marketing  
- Sensibilidade ao preço  

### 5. Modelagem preditiva

Modelo: **Regressão Linear**

Variáveis:
- `promocao`  
- `investimento_marketing`  
- `preco_medio`  

Target:
- `vendas`  

Split:
- 80% treino  
- 20% teste  

---

## 📈 Métricas do modelo

- MAE  
- MSE  
- RMSE  
- R²  

📌 **R² ≈ 0.84** → o modelo explica cerca de 84% da variação das vendas.

---

## 💡 Principais insights

- Crescimento consistente ao longo do tempo  
- Forte sazonalidade (picos em nov/dez)  
- Marketing impacta diretamente as vendas  
- Promoções e feriados aumentam vendas  
- Preço médio tem relação negativa com demanda  
- Modelo simples com boa performance  

---

📚 Aprendizados
- Data cleaning
- EDA
- Visualização
- Análise de negócio
- Machine Learning
- Avaliação de modelos
- Comunicação de insights

---

👤 Autor

cleiton Hentges
