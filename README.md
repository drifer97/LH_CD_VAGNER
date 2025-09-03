# LH_CD_VAGNER
# Projeto de Análise de Filmes IMDB e Predição de Notas

## 🎬 Sobre o Projeto

Este projeto foi desenvolvido como um desafio para a Indicium. O objetivo é analisar um banco de dados de filmes do IMDB para ajudar um estúdio de Hollywood fictício a decidir qual tipo de filme produzir.

A análise inclui:
* Limpeza e tratamento dos dados.
* Análise Exploratória de Dados (EDA) para encontrar padrões interessantes.
* Um modelo de Machine Learning que prevê a nota do IMDB de um filme com base em suas características.

Este repositório foi organizado de forma didática, para que mesmo quem está começando na área de dados possa entender o passo a passo.

## ⚙️ Como Executar o Projeto

Siga os passos abaixo para rodar a análise no seu computador.

### Pré-requisitos

* Python 3.8 ou superior
* Pip (gerenciador de pacotes do Python)

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/drifer97/LH_CD_VAGNER.git
    cd LH_CD_VAGNER
    ```

2.  **(Opcional, mas recomendado) Crie um ambiente virtual:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    Use o arquivo `requirements.txt` para instalar todos os pacotes necessários.
    ```bash
    pip install -r requirements.txt
    ```

### Executando a Análise

1.  **Abra o Jupyter Notebook:**
    O arquivo `analise_filmes_imdb.ipynb` contém todo o código e as explicações. Para abri-lo, execute o seguinte comando no seu terminal:
    ```bash
    jupyter notebook
    ```
2.  **Execute as células:**
    Dentro do Jupyter, você pode executar cada célula de código para ver os resultados passo a passo.

## 📂 Estrutura do Repositório

* `desafio_indicium_imdb.csv`: O conjunto de dados original.
* `analise_filmes_imdb.ipynb`: O notebook Jupyter com toda a análise e o código de modelagem.
* `imdb_rating_predictor.pkl`: O modelo de machine learning treinado e salvo.
* `requirements.txt`: Lista de pacotes Python para instalar.
* `README.md`: Este arquivo que você está lendo :)
* `/imagens/`: Pasta contendo as imagens geradas durante a análise.
