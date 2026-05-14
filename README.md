# Análise de Saúde Mental e Burnout no Setor de Tech 🧠💼

Este projeto realiza a extração, tratamento e análise exploratória visual de um dataset focado em saúde mental e burnout de profissionais da área de tecnologia. O script automatiza o download dos dados via KaggleHub, traduz as variáveis para o português e gera gráficos estatísticos.

## 📋 Sumário

* [Sobre os Dados](https://www.google.com/search?q=%23-sobre-os-dados)
* [Tecnologias Utilizadas](https://www.google.com/search?q=%23-tecnologias-utilizadas)
* [Funcionalidades]()
* [Como Executar]()
* [Visualizações Geradas]()

---

## 📊 Sobre os Dados

O dataset original é o **Employee Mental Health and Burnout**, disponível no Kaggle. Ele contém informações críticas como:

* Níveis de estresse, ansiedade e depressão.
* Hábitos de sono e atividade física.
* Fatores profissionais (horas extras, suporte do gerente, carga horária).
* Pontuação de burnout e satisfação no trabalho.

## 🛠 Tecnologias Utilizadas

* **Python 3.x**
* **KaggleHub**: Para integração e download direto do dataset.
* **Pandas**: Para manipulação e limpeza dos dados.
* **Matplotlib & Seaborn**: Para visualização de dados e criação de gráficos.

## ✨ Funcionalidades

1. **Download Automático**: Busca a versão mais recente do dataset diretamente do Kaggle.
2. **Dicionário de Tradução**: Renomeia todas as colunas originais (em inglês) para termos em português, facilitando a análise local.
3. **Tratamento de Categorias**: Traduz os valores das colunas `sexo`, `modo_de_trabalho` e `nivel_de_burnout`.
4. **Análise Estatística**: Gera a distribuição percentual de gênero dos entrevistados através de gráficos de barras.

## 🚀 Como Executar

### 1. Pré-requisitos

Instale as bibliotecas necessárias via terminal:

```bash
pip install kagglehub pandas matplotlib seaborn

```

### 2. Execução

Basta rodar o script principal. Ele irá baixar o arquivo `.csv` para o cache local do seu sistema e realizar o processamento:

```bash
python seu_script.py

```

## 📈 Visualizações Geradas

O script inclui, por padrão, uma visualização da **Distribuição Percentual por Sexo**, utilizando a paleta de cores `viridis`, que ajuda a entender a demografia do estudo de forma rápida.

---

> **Nota:** Certifique-se de ter conexão com a internet para o primeiro download via `kagglehub`. As execuções subsequentes utilizarão o cache local.
