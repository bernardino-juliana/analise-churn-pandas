# 📊 Análise de Churn com Pandas: Identificando Padrões e Estratégias

**Juliana Bernardino | JB Data Insights**

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** completa sobre o *Churn* (cancelamento) de clientes em um serviço de telecomunicações, utilizando as bibliotecas **Pandas**, **Matplotlib** e **Seaborn** em Python.

O objetivo principal é **identificar padrões de comportamento**, **entender as causas** que levam os clientes ao cancelamento e fornecer *insights* estratégicos para a retenção.

---

## 🚀 Tecnologias e Bibliotecas

| Categoria | Tecnologia/Biblioteca | Finalidade |
| :--- | :--- | :--- |
| Linguagem | Python 3 | Linguagem de programação principal. |
| Análise de Dados | Pandas | Manipulação e análise de dados estruturados. |
| Visualização | Matplotlib, Seaborn | Criação de gráficos estatísticos e visualizações de alta qualidade. |
| Ambiente | Google Colab / Jupyter Notebook | Ambiente interativo para desenvolvimento e documentação. |

---

## 📁 Estrutura do Projeto

O repositório está organizado da seguinte forma:
analise-churn-pandas/
│
├── assets/
│   ├── Gráfico 1 - Distribuição de Churn.png
│   ├── Gráfico 2 - Distribuição de Churn %.png
│   ├── Gráfico 3 - Churn por Nível de Satisfação.png
│   ├── Gráfico 4 - Estados com Maior Churn.png
│   └── Gráfico 5 - Churn por Quantidade de Tickets.png
│
├── Projeto_1_Analise_de_Churn.ipynb  # Notebook principal com toda a análise e código.
└── README.md

---
## 📊 Resultados Chave da Análise

A análise revelou importantes correlações entre variáveis comportamentais e a taxa de *churn*. Abaixo, destacamos os principais achados visuais:

### 1. Distribuição de Churn (Contagem)

Este gráfico ilustra a contagem absoluta de clientes que cancelaram (Churn) versus os que permaneceram (Não Churn).

<img src="assets/Gráfico 1 - Distribuição de Churn.png" width="600" alt="Gráfico de barras mostrando a contagem de clientes Churn e Não Churn.">

### 2. Distribuição de Churn (Percentual)

Este gráfico ilustra a proporção percentual de clientes que cancelaram (Churn) versus os que permaneceram (Não Churn).

<img src="assets/Gráfico 2 - Distribuição de Churn %.png" width="600" alt="Gráfico de pizza mostrando a porcentagem de clientes Churn e Não Churn.">

### 3. Churn por Nível de Satisfação

A satisfação do cliente é um fator crítico. Observamos uma clara tendência de aumento do *churn* em clientes com níveis de satisfação mais baixos.

<img src="assets/Gráfico 3 - Churn por Nível de Satisfação.png" width="600" alt="Gráfico de barras mostrando a taxa de Churn por diferentes níveis de satisfação do cliente.">

### 4. Análise Geográfica: Estados com Maior Churn

A distribuição geográfica do *churn* sugere que fatores regionais ou operacionais podem estar influenciando a retenção em certas áreas.

<img src="assets/Gráfico 4 - Estados com Maior Churn.png" width="600" alt="Gráfico de barras mostrando os estados com as maiores taxas de Churn.">

### 5. Churn por Quantidade de Tickets

Este gráfico demonstra a correlação entre o volume de tickets de suporte abertos e a probabilidade de Churn.

<img src="assets/Gráfico 5 - Churn por Quantidade de Tickets.png" width="600" alt="Gráfico mostrando a relação entre a quantidade de tickets de suporte e a taxa de Churn.">

---

## 🎯 Principais Insights Estratégicos

Com base na análise exploratória, os seguintes *insights* podem guiar as estratégias de retenção:

1.  **Foco na Satisfação Crítica:** Clientes com **níveis de satisfação mais baixos** (conforme demonstrado no Gráfico 3) representam o grupo de maior risco. Ações de engajamento e suporte proativo devem ser direcionadas prioritariamente a este segmento.
2.  **Otimização Regional:** A disparidade nas taxas de *churn* entre os estados (Gráfico 4) indica a necessidade de uma **investigação aprofundada em falhas operacionais ou de serviço** específicas dessas regiões.
3.  **Impacto do Suporte:** O **número de tickets abertos** (Gráfico 5, não exibido, mas presente na análise) está diretamente correlacionado com a probabilidade de *churn*. Reduzir a necessidade de contato com o suporte e aumentar a eficiência na resolução de problemas são cruciais.
4.  **Definição de Perfil de Risco:** A análise permite a criação de um **modelo preditivo de risco de *churn***, combinando satisfação, localização e histórico de suporte, para intervenções de retenção mais eficazes e personalizadas.

---

## ▶️ Como Executar o Projeto

Para replicar a análise, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/bernardino-juliana/analise-churn-pandas.git
    ```
2.  **Navegue até o diretório:**
    ```bash
    cd analise-churn-pandas
    ```
3.  **Instale as dependências:**
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  **Execute a análise:**
    Abra o arquivo `Projeto_1_Analise_de_Churn.ipynb` no Google Colab ou Jupyter Notebook e execute as células sequencialmente.

---

## 👩‍💻 Sobre a Autora

**Juliana Bernardino** é Analista Financeira com **Especialização em Análise de Dados**, focada em **transformar dados brutos em *insights* estratégicos** que impulsionam a tomada de decisão e o crescimento empresarial.

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela (Star ) no repositório!

