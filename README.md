# challenge-telecomx-parte2
### **📊 Análise de Evasão de Clientes (Churn) – TelecomX**

---

### **🎯 Objetivo**

Este projeto tem como objetivo principal prever a evasão de clientes (Customer Churn) em uma empresa de telecomunicações. A evasão de clientes é um dos maiores desafios para as empresas de serviços, e a capacidade de prever quais clientes estão em risco de cancelar seu serviço é crucial para o planejamento de estratégias de retenção.

Utilizamos uma abordagem de aprendizado de máquina, combinando análise de dados exploratória com a criação e avaliação de modelos preditivos, para identificar os principais fatores que influenciam o churn e propor ações estratégicas.
### **🔍 Indicadores Analisados**

* **Distribuição de Churn:** Proporção de clientes que cancelaram o serviço versus os que permaneceram.
* **Churn por Perfil:** Análise da evasão por tipo de contrato, tempo de serviço (`tenure`) e método de pagamento.
* **Churn por Serviço:** Relação da evasão com serviços de internet (fibra óptica, DSL), segurança online, streaming, etc.
* **Análise Numérica:** Relação da evasão com o tempo de contrato (`tenure`), gastos mensais (`MonthlyCharges`) e gastos totais (`TotalCharges`).

### **📌 Principais Conclusões**

* A taxa de evasão está fortemente associada a clientes com **contratos mensais**.
* Clientes com **pouco tempo de serviço (`tenure` baixo)** são o grupo mais vulnerável ao `churn`.
* O uso de **cheques eletrônicos** como método de pagamento tem uma alta correlação com a evasão de clientes.
* O serviço de **fibra óptica** apresenta maior risco de evasão em comparação com outras opções de internet.
* A análise mostrou que a taxa de `churn` **não apresenta diferença significativa entre gêneros**.

**Recomendação:** A empresa deve focar seus esforços de retenção em clientes novos e com planos mensais, incentivando a migração para contratos de longo prazo e otimizando a experiência de serviços como a fibra óptica.

### **🛠️ Como Utilizar o Projeto**

* Acesse o notebook do projeto no GitHub para explorar o código completo.
* Abra o arquivo `.ipynb` no **Google Colab** ou **Jupyter Notebook**.
* Execute as células para visualizar:
    * Gráficos comparativos de `churn` por diferentes perfis de clientes.
    * Análises detalhadas da distribuição de variáveis numéricas.
    * Matrizes de correlação e *heatmaps* das variáveis mais relevantes.
    * Conclusões e recomendações estratégicas.

### **💡 Insights Obtidos**

* Como identificar os principais *drivers* de `churn` em uma base de clientes por meio da Análise Exploratória de Dados (EDA).
* Quais métricas são mais relevantes para entender o comportamento de evasão e a performance dos modelos preditivos.
* Como transformar análises de dados em ações estratégicas de retenção, visando a redução do `churn`.

### **👨‍💻 Tecnologias Utilizadas**

* **Linguagem:** `Python`
* **Bibliotecas:** `Pandas`, `Matplotlib`, `Seaborn`, `Scikit-learn`
* **Ferramentas:** `Google Colab`
* **Metodologia:** Análise de Dados Exploratória (EDA) e Visualização de Dados

---

**Autor:** [Vitor Oliveira]
