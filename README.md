# 📊 TelecomX - Parte 2

Este projeto tem como objetivo prever o abandono de clientes (**Abandono**) em uma empresa fictícia de telecomunicações — a **TelecomX** — utilizando análise exploratória de dados e modelos de Machine Learning. O foco é identificar os principais fatores que influenciam a saída de clientes e criar estratégias para aumentar a retenção. 🚀

---

## 📁 Sobre o Projeto

- 🔍 **Desafio**: Explorar, tratar e modelar dados para prever quais clientes têm maior probabilidade de abandonar o serviço.
- 🎯 **Objetivo Principal**: Criar um modelo de previsão de Abandono e extrair insights estratégicos para reduzir a evasão.

---

## 🧰 Tecnologias Utilizadas

- **Python** 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📜 Etapas do Projeto

### 🛠️ Preparação dos Dados
- **Remoção de Colunas Irrelevantes**: Exclusão de informações que não contribuem para a previsão.
- **Encoding**: Conversão de variáveis categóricas em variáveis numéricas.
- **Verificação da Proporção de Evasão**: Análise inicial para entender a taxa de abandono.

### 🎯 Correlação e Seleção de Variáveis
- **Análise de Correlação**: Identificação de variáveis mais associadas à evasão.
- **Análises Direcionadas**: Estudo detalhado de variáveis-chave.

### 🤖 Modelagem Preditiva
- **Separação de Dados**: Divisão em conjuntos de treino e teste.
- **Criação de Modelos**: Teste de algoritmos como Regressão Logística, KNN, Random Forest e SVM.
- **Avaliação dos Modelos**: Comparação de métricas de desempenho.

### 📋 Interpretação e Conclusões
- **Análise de Importância das Variáveis**: Identificação dos fatores mais relevantes para a previsão de evasão.
- **Insights para Negócio**: Sugestões estratégicas para retenção de clientes.

---

## 📄 Relatório Final

## 1. Principais Pontos Achados

### 1.1 Experiência Inicial
- **Clientes no primeiro mês de contrato** apresentam a maior taxa de abandono.
- Este resultado sugere **possíveis falhas na experiência inicial** do cliente, como problemas na instalação, atendimento ou adaptação ao serviço.
- Estratégias de **onboarding** e suporte ativo nesse período podem reduzir significativamente a evasão.
  
### 1.2 Perfil Demográfico
- **Idosos** e **clientes com dependentes** têm **menor taxa de abandono**.
- Esse grupo tende a buscar estabilidade e apresenta maior fidelidade.
- Estratégias de retenção podem priorizar outros segmentos com maior risco.

### 1.3 Tempo de Permanência
- Quanto **maior o tempo de permanência**, **menor a chance de abandono**.
- Após o **primeiro ano**, o risco de evasão cai consideravelmente.
- Isso reforça a importância de estratégias para **garantir que o cliente permaneça além dos primeiros meses**.

### 1.4 Variáveis Financeiras
- **Mensalidade**, **Total Cobrado** e **Custo Diário** apresentam **pouca variação** entre clientes que abandonam e os que permanecem.
- **Conclusão:** o **preço por si só** não é o principal motivador de abandono.

### 1.5 Tipo de Contrato
- **Contrato Mensal** → **maior taxa de abandono**.
- **Contratos de longo prazo (1 ou 2 anos)** → **maior retenção**, especialmente **2 anos**.
- A flexibilidade do contrato mensal facilita a saída, enquanto contratos longos incentivam a fidelidade.

### 1.6 Forma de Pagamento
- **Pagamentos automáticos** (Transferência Bancária Automática, Cartão de Crédito) → **menor evasão**.
- **Pagamentos manuais** (Boleto, Cheque Eletrônico) → **maior evasão**.
- A automação de pagamentos reduz a chance de cancelamentos por esquecimento ou dificuldade no pagamento.

## 2. Conclusão Geral

A evasão de clientes está fortemente ligada à **fase inicial do relacionamento**, ao **tipo de contrato** e à **forma de pagamento**.  
O preço, isoladamente, **não é um fator determinante**, mas o **Total Cobrado** baixo entre clientes que abandonam sugere cancelamentos precoces.  
Focar em **melhorar a experiência no primeiro mês**, incentivar **contratos de longo prazo** e promover **pagamentos automáticos** pode reduzir significativamente a taxa de abandono.

---

## 📎 Link do Projeto 

🔗 Acesse o Desafio: [TelecomX-Parte-2-Challege](https://github.com/SousaPHP/Telecom-X-Parte-2-Challenge-Data-Science-Alura/blob/main/TelecomX_Parte_2.ipynb)

---

## 🙋‍♂️ Autor

**Paulo Henrique Sousa**  
📧 [LinkedIn](https://www.linkedin.com/in/sousaphp) | 💻 [GitHub](https://github.com/SousaPHP)

---

## 📌 Observação

Este projeto foi desenvolvido como parte de um **desafio de Data Science da Alura** com o projeto **Oracle One**, simulando um caso real de aplicação de análise de dados e aprendizado de máquina para retenção de clientes.
