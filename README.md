# 📈 Projeto: Modelagem Preditiva com Regressão Linear | G8 ONE - Alura & Oracle

Este projeto foi desenvolvido como parte do curso **"Regressão Linear: Técnicas Avançadas de Modelagem"**, integrante do programa **G8 ONE** (Alura + Oracle). O foco foi aplicar **modelos de regressão linear simples e múltipla** para análise e previsão em **duas bases de dados reais**: uma relacionada ao setor **hoteleiro** e outra ao setor **energético**.

---

## 🎯 Objetivos do Projeto

- Analisar a relação entre variáveis numéricas e precificação de estadias hoteleiras
- Treinar e comparar modelos de **regressão linear simples e múltipla**
- Investigar fenômenos estatísticos como **multicolinearidade** e **homocedasticidade**
- Utilizar técnicas de **modelagem estatística e machine learning** com Python

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.x**
- **Google Colab**
- **Pandas** – manipulação e limpeza de dados
- **Seaborn & Matplotlib** – visualização gráfica
- **Scikit-learn** – modelagem e métricas de regressão
- **Statsmodels** – análise estatística dos modelos

---

## 📁 Bases de Dados

### 1. 🏨 Dataset de Hotéis
- Variáveis: número de estrelas, distância de atrações turísticas e capacidade.
- Objetivo: prever o **preço da estadia** com base nas variáveis.

### 2. ⚡ Dataset de Usina de Energia
- Objetivo: analisar a existência de **multicolinearidade** e **homocedasticidade**.

---

## 🧪 Modelos Aplicados

### 🔹 Regressão Linear Simples
- Utilizado inicialmente na base de hotéis.
- Resultado: modelo com boa interpretação, mas performance limitada.

### 🔹 Regressão Linear Múltipla
- Aplicado na base de dados incluindo todas as variáveis.
- Resultado: melhor performance na previsão de preços dos hotéis.
- Permitiu analisar o impacto simultâneo de várias variáveis preditoras.

---

## 🔍 Análises Estatísticas

- **Multicolinearidade**:
  - Avaliada usando o **VIF (Variance Inflation Factor)**
  - Aplicada principalmente na base da usina

- **Homocedasticidade**:
  - Investigada com análise de resíduos e gráficos de dispersão
  - Contribuiu para validar a robustez do modelo

---

## 📊 Visualizações Criadas

- Pairplots e heatmaps para correlação
- Gráficos de dispersão com linha de regressão
- Análise de resíduos para diagnóstico dos modelos

---

## 🧠 Conclusões

- A **regressão linear múltipla** foi o modelo com melhor desempenho na base de hotéis, oferecendo previsões mais realistas.
- A análise de **multicolinearidade e homocedasticidade** reforçou a necessidade de diagnosticar modelos antes de aplicá-los a dados reais.
- A importância de escolher **modelos adequados ao contexto e às variáveis** ficou evidente.


---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone git@github.com:pedrohalarcao/projeto_regressao_linear.git
   cd projeto_regressao_linear
   

---

## 👤 Autor

Pedro Alarcão

Apaixonado por Ciência de Dados, IA e pela busca de respostas através de análises práticas, estatísticas e preditivas.


---

## 📝 Licença

Este projeto é de caráter educacional, baseado em dados fictícios ou públicos. Licença livre para fins acadêmicos e não comerciais.

