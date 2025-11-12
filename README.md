## 🧮 Time Series Econometrics Labs

Repositório com exercícios práticos e laboratórios da disciplina **Econometria II**, com foco em **Análise e Modelagem de Séries Temporais (Univariadas e Multivariadas)**.

Cada questão proposta está implementada em um **notebook Jupyter** independente, desenvolvido em **Python**, utilizando bibliotecas como `pandas`, `numpy`, `statsmodels`, `matplotlib` e `scikit-learn`.

---

### 📁 Estrutura do Repositório

| Arquivo                             | Descrição                                                                                                                                                                                                                                                                                                             |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `01_missing_data_imputation.ipynb`  | **Questão 1** — Seleção de uma série temporal (real ou simulada), eliminação proposital de períodos e estimação dos dados faltantes usando diferentes técnicas de imputação (Interpolação Linear, Média Móvel, Regressão, KNN, etc.). Comparação entre valores reais e estimados.                                     |
| `02_outliers_treatment.ipynb`       | **Questão 2** — Detecção e tratamento de *outliers* em séries temporais. Discussão e aplicação de métodos como: remoção de observações, suavização da variância e transformações robustas (Winsorização, Box-Cox, etc.).                                                                                              |
| `03_montecarlo_ar_simulation.ipynb` | **Questão 3** — Simulação de séries temporais via **Monte Carlo** para processos do tipo **AR(1)** e **AR(2)**. Geração de diversas trajetórias simuladas, análise de comportamento e representação gráfica dos resultados.                                                                                           |
| `04_forecasting_methods.ipynb`      | **Questão 4** — Aplicação de três métodos clássicos de previsão: <br> - **Simples (VIX)** – Suavização exponencial simples <br> - **Holt (PIB EUA)** – Tendência linear dupla <br> - **Holt-Winters (Commodities)** – Sazonalidade + tendência. <br> Comparação dos desempenhos e visualização gráfica das previsões. |

---

### 🧰 Tecnologias Utilizadas

* **Linguagem:** Python 3.x
* **Bibliotecas Principais:**

  * `pandas`, `numpy` – Manipulação e geração de dados
  * `matplotlib`, `seaborn` – Visualização
  * `statsmodels`, `scikit-learn` – Modelagem estatística
  * `random`, `scipy` – Simulações e geração de ruído aleatório

---

### 🚀 Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/SEU_USUARIO/timeseries-econometrics-labs.git
   cd timeseries-econometrics-labs
   ```
2. Crie um ambiente virtual e instale as dependências:

   ```bash
   python -m venv venv
   source venv/bin/activate  # ou venv\Scripts\activate no Windows
   pip install -r requirements.txt
   ```
3. Abra os notebooks:

   ```bash
   jupyter notebook
   ```

---

### 📊 Objetivo

O objetivo geral é aplicar técnicas fundamentais de **Econometria de Séries Temporais** em cenários práticos, explorando:

* Manipulação de dados faltantes e outliers
* Modelagem AR(p) e simulação via Monte Carlo
* Aplicação de métodos de previsão clássicos
