# Fase 4 - Capítulo 4: Ciência de Dados ao Alcance das Mãos com Streamlit

Repositório de estudos e testes práticos do Capítulo 4 da Fase 4, referente ao 1º semestre do curso de Tecnólogo em Inteligência Artificial da FIAP.

O objetivo deste projeto é praticar o uso do Streamlit para criar aplicações web interativas com Python, incluindo testes básicos, uso de widgets, criação de um quiz interativo, análise exploratória de dados, modelagem preditiva com Machine Learning e publicação da aplicação no Streamlit Cloud.

## Conteúdo do repositório

* `hello_fiap_app.py`: primeiro teste básico com Streamlit.
* `quiz_app.py`: mini projeto de quiz interativo com perguntas, alternativas, conferência de respostas e pontuação.
* `widgets_entrada.py`: testes com widgets de entrada de dados.
* `widgets_iteratividade.py`: testes com widgets de interação.
* `widgets_experiencia.py`: testes com widgets de feedback visual.
* `app.py`: aplicação principal do projeto agrícola.
* `data_generation.py`: geração de dataset simulado de produção agrícola.
* `pages/1_exploracao_de_dados.py`: página de análise exploratória interativa.
* `pages/2_modelagem_preditiva.py`: página de treinamento, avaliação e previsão com modelo de Machine Learning.
* `requirements.txt`: lista de bibliotecas necessárias para execução da aplicação.
* `.gitignore`: arquivo para evitar o envio de pastas e arquivos locais desnecessários ao GitHub.
* `README.md`: documentação do repositório.

## Tecnologias utilizadas

* Python
* Streamlit
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn

## Projeto principal

A aplicação principal simula um cenário agrícola e permite:

* carregar dados simulados de produção agrícola;
* visualizar informações gerais do dataset;
* analisar estatísticas descritivas;
* gerar gráficos interativos;
* observar relações entre variáveis;
* treinar um modelo preditivo;
* avaliar o modelo com métrica de desempenho;
* realizar previsões de produção agrícola;
* publicar a aplicação na nuvem com Streamlit Cloud.

## Estrutura do projeto

```text
fase4-cap4-streamlit/
├── app.py
├── data_generation.py
├── hello_fiap_app.py
├── quiz_app.py
├── widgets_entrada.py
├── widgets_iteratividade.py
├── widgets_experiencia.py
├── requirements.txt
├── .gitignore
├── README.md
└── pages/
    ├── 1_exploracao_de_dados.py
    └── 2_modelagem_preditiva.py
```

## Como executar localmente

1. Clone o repositório.
2. Crie e ative um ambiente virtual.
3. Instale as dependências listadas em `requirements.txt`.
4. Execute a aplicação principal com Streamlit.

Comando para instalar as dependências:

```bash
pip install -r requirements.txt
```

Comando para executar a aplicação principal:

```bash
streamlit run app.py
```

Para executar os arquivos de teste separadamente:

```bash
streamlit run hello_fiap_app.py
streamlit run quiz_app.py
streamlit run widgets_entrada.py
streamlit run widgets_iteratividade.py
streamlit run widgets_experiencia.py
```

## Deploy

A aplicação foi publicada no Streamlit Cloud a partir do repositório GitHub, usando:

* branch principal: `main`;
* arquivo principal: `app.py`;
* dependências: `requirements.txt`.

Link da aplicação publicada:

https://fase4-cap4-fiap.streamlit.app

## Observação acadêmica

Este repositório foi desenvolvido como prática de estudo do Capítulo 4 da Fase 4, no 1º semestre do curso de Tecnólogo em Inteligência Artificial da FIAP.

O foco do capítulo é compreender como o Streamlit pode ser usado para transformar scripts Python em aplicações web interativas voltadas à Ciência de Dados e Machine Learning.

Além da aplicação principal, o repositório mantém arquivos de teste utilizados durante o estudo do capítulo, incluindo exemplos básicos, widgets e quiz interativo.
