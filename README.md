# Desafio de Ciência de Dados - Análise de Filmes IMDB para PProductions

## Descrição do Projeto

Este projeto foi desenvolvido como solução para o desafio de Ciência de Dados da Indicium. O objetivo é realizar uma análise detalhada sobre uma base de dados de filmes do IMDB para orientar o estúdio de Hollywood "PProductions" sobre qual tipo de filme deve ser o próximo a ser desenvolvido.

A análise inclui:
-   **Análise Exploratória de Dados (EDA)** para identificar tendências e padrões no mercado cinematográfico.
-   Respostas a **perguntas de negócio** chave sobre recomendação de filmes e fatores de sucesso.
-   O desenvolvimento de um **modelo de Machine Learning** para prever a nota do IMDB de um filme com base em suas características.

## Requisitos

Para executar este projeto, você precisará ter o Python 3 instalado, além das seguintes bibliotecas:

-   `pandas`
-   `numpy`
-   `matplotlib`
-   `seaborn`
-   `scikit-learn`
-   `joblib`
-   `jupyter`

Todas as dependências e suas versões estão listadas no arquivo `requirements.txt`.

## Como Instalar e Configurar o Ambiente

Siga os passos abaixo para preparar seu ambiente e executar a análise.

**Passo 1: Clonar o Repositório**

Clone este repositório para a sua máquina local usando o seguinte comando:
```bash
git clone https://github.com/Carolsfig/LH_CD_CAROLINAFIGUEIREDO.git
cd LH_CD_CAROLINAFIGUEIREDO
```

**Passo 2: Criar um Ambiente Virtual (Recomendado)**

É uma boa prática criar um ambiente virtual para isolar as dependências do projeto:
```bash
python -m venv venv
```
Para ativar o ambiente:
- No Windows: `.\venv\Scripts\activate`
- No macOS/Linux: `source venv/bin/activate`

**Passo 3: Instalar as Dependências**

Com o ambiente virtual ativado, instale todas as bibliotecas necessárias com um único comando:
```bash
pip install -r requirements.txt
```

## Como Executar o Projeto

Com o ambiente configurado e as dependências instaladas, você pode executar a análise.

**Passo 1: Iniciar o Jupyter Notebook**

No seu terminal, execute o seguinte comando para iniciar o servidor Jupyter:
```bash
jupyter notebook
```
Isso abrirá uma nova aba no seu navegador.

**Passo 2: Executar a Análise**

Na interface do Jupyter, clique no arquivo `analise_filmes.ipynb` para abri-lo.

Dentro do notebook, você pode executar cada célula de código sequencialmente clicando em "Run" no menu superior ou usando o atalho `Shift + Enter`. O notebook está dividido nas seguintes seções:
1.  **Carregamento e Limpeza dos Dados**: Importação do dataset e tratamento inicial.
2.  **Análise Exploratória de Dados (EDA)**: Geração de gráficos e estatísticas para entender os dados.
3.  **Respostas às Perguntas de Negócio**: Análise direcionada para as questões do desafio.
4.  **Pré-processamento para Modelagem**: Preparação das features para o modelo.
5.  **Treinamento e Avaliação do Modelo**: Construção do `RandomForestRegressor` e verificação de sua performance.
6.  **Previsão e Salvamento**: Uso do modelo para prever a nota do filme de exemplo e salvamento do artefato final (`.pkl`).

O notebook irá gerar todas as visualizações e, ao final, salvará o modelo treinado como `modelo_imdb_rating.pkl`.

## Autor

* **Carolina Silva Figueiredo**
