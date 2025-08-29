# PUC - Pontifícia Universidade Católica do Rio de Janeiro

<p align="center">
  <img src="https://images.squarespace-cdn.com/content/v1/59a8480fccc5c52fff14d38a/1529026153457-7W1EX1C6VUVUNIQN0CE1/image-asset.png" alt="PUC logo" border="0" width="100px">
</p>

# MVP desenvolvido para a Sprint: Machine Learning & Analytics do curso de Pós Graduação em Ciência de Dados e Analytics da PUC-RIO

### 🚀 Desenvolvedor
- <a href="https://www.linkedin.com/in/daniel-vcosta/">Daniel Vibranovski Costa</a> - daniel.vc7@gmail.com

## 🔍 Sumário

| Tópicos|
|---|
| [Definição do Problema](#-Definição do Problema)|
| [Etapas do Projeto](#-etapas-do-projeto)|
| [Estrutura do Repositório](#-estrutura-do-repositório)|
| [Tecnologias Utilizadas](#-tecnologias-utilizadas)|
| [Bibliotecas Utilizadas](#-bibliotecas-utilizadas)|
| [Licença/License](#-licençalicense)|
| [Referências](#-referências)|
| [Agradecimentos](#-agradecimentos)|


## 📜 Definição do Problema

O dataset [Global AI Job Market & Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025) é um conjunto de dados que oferece uma análise abrangente do mercado de trabalho em inteligência artificial, com mais de 15.000 vagas reais coletadas nas principais plataformas de emprego do mundo. Ele inclui informações detalhadas sobre salários, requisitos das vagas, insights sobre as empresas e tendências geográficas.

Este repositório refere-se ao Projeto MVP (Minimum Viable Product) desenvolvido para a Sprint: Machine Learning & Analytics, do curso de Pós-Graduação em Ciência de Dados e Analytics da PUC-RIO. O foco agora é, a partir de machine learning e seus principais modelos, prever os salários de empregos na área de inteligência artificial.


## 🪜 Etapas do Projeto

1) Definição do Problema.

2) Premissas ou hipóteses sobre o problema.

3) Hiperparametrização e Comparação de Modelos.

4) Aplicação em rede neural.

## 📁 Estrutura do Repositório

```
├── 📁 dataset
├── 📝 XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX.ipynb
├── 📝 README.md

```

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- <b>README.md</b>: Arquivo que serve como guia e explicação geral sobre o projeto (arquivo atual).
- <b>XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX.ipnyb</b>: Notebook com a análise exploratória e pipeline de processamento dos dados.
- <b>datasets</b>: Arquivos utilizados no projeto.
  - [Global AI Job Market & Salary Trends 2025](https://www.kaggle.com/datasets/bismasajjad/global-ai-job-market-and-salary-trends-2025).


## 👨‍💻 Tecnologias Utilizadas

- [Python 3.12.8 (Windows 64-bit)](https://www.python.org/ftp/python/3.12.8/python-3.12.8-amd64.exe): Linguagem de programação utilizada.

- [Google Colab](https://colab.research.google.com/): Ambiente de desenvolvimento utilizado para a execução do código.

- Habilitar Caminhos Longos no Windows

> 👉  Passo a Passo para habilitar o suporte a **longpath** (caminhos longos) no Windows.
> 
> 1. Pressione `Windows + R`
> 2. Digite `gpedit.msc` e pressione **Enter**
> 3. No **Editor de Política de Grupo Local**, navegue até:
> 
> Configuração do Computador
> → Modelos Administrativos
> → Sistema
> → Sistema de Arquivos
> → Habilitar caminhos Win32 longos
> 
> 4. Marque a opção como **Habilitado**
> 5. Reinicie o computador (se necessário)


## 📄 Bibliotecas utilizadas

**Análise de dados**
1. [Pandas](https://pandas.pydata.org/): Biblioteca de software criada para a linguagem Python para manipulação e análise de dados. Em particular, oferece estruturas e operações para manipular tabelas numéricas e séries temporais.

2. [NumPy](https://numpy.org/): Biblioteca para a linguagem de programação Python, que suporta o processamento de grandes, multi-dimensionais arranjos e matrizes, juntamente com uma grande coleção de funções matemáticas de alto nível para operar sobre estas matrizes.

**Visualização de Dados**
1. [Matplotlib](https://matplotlib.org/): Biblioteca abrangente para criar estático, animado, e visualizações interativas em Python. Matplotlib faz coisas fáceis coisas fáceis e difíceis possíveis. 
2. [Seaborn](https://seaborn.pydata.org/): Biblioteca de visualização de dados Python baseada em matplotlib. Ele fornece uma interface de alto nível para desenho gráficos estatísticos atrativos e informativos. 
3. [Squarify](https://pypi.org/project/squarify/): Biblioteca Python para a visualização de treemap.

**Pré-processamento de Dados**
1. [Scikit-learn](https://scikit-learn.org/stable/): Ferramenta eficientes para análise preditiva de dados, construído em NumPy, SciPy e matplotlib.

**Utilitários** 
1. [Tabulate](https://pypi.org/project/tabulate/): Dados tabulares impressos em Python em formatação mais agradável, para múltiplos formatos de saída adequados para edição ou transformação adicional.

**Atualizações e Utilitários** 
1. [Joblib](colocar o link): Biblioteca utilizada para serialização em Python, comumente usada para salvar modelos de Machine Learning treinados (por exemplo, objetos do Scikit-learn) em disco de forma eficiente. Também otimiza o uso de paralelismo e cache em pipelines.

**Machine Learning e AutoML** 
1. [XGBoost](colocar o link): Biblioteca otimizada para gradient boosting, muito eficiente para grandes volumes de dados. É conhecida por sua performance em competições de Machine Learning devido à sua rapidez e precisão.
2. [LightGBM](colocar o link): Framework de boosting desenvolvido pela Microsoft, que utiliza uma técnica chamada histogram-based learning para ser ainda mais rápido e com menor uso de memória do que o XGBoost.
3. [CatBoost](colocar o link): Biblioteca de boosting criada pela Yandex, projetada para lidar de forma nativa com variáveis categóricas, evitando a necessidade de one-hot encoding.
4. [FLAML](colocar o link): Framework leve de AutoML que busca automaticamente o melhor modelo e os melhores hiperparâmetros de forma eficiente, minimizando custos computacionais.

**Integração Scikit-Learn + Keras** 
1. [SciKeras](colocar o link): Um wrapper que permite usar modelos do Keras/TensorFlow dentro do ecossistema do Scikit-learn. Isso torna possível integrar redes neurais em pipelines, aplicar GridSearchCV e outros métodos de validação e otimização típicos do Scikit-learn.

**Deep Learning** 
1. [TensorFlow](colocar o link): Framework de código aberto mantido pelo Google para desenvolvimento e treinamento de modelos de aprendizado profundo. Suporta tanto CPU quanto GPU/TPU, permitindo escalabilidade em projetos complexos.
2. [Keras](colocar o link): API de alto nível para construção de redes neurais, integrada ao TensorFlow. Facilita a criação e experimentação de modelos de Deep Learning de maneira simples e rápida.

**Suporte a Datasets** 
1. [KaggleHub](colocar o link): Biblioteca para acessar datasets do Kaggle diretamente via Python, sem a necessidade de download manual pelo site. Facilita a integração de competições e bases de dados no fluxo de trabalho de ciência de dados.

Panorama completo de cada biblioteca instalada:

- Manipulação de dados: pandas, numpy

- Visualização: matplotlib, seaborn, squarify

- Pré-processamento e ML: scikit-learn, xgboost, lightgbm, catboost, flaml

- Integração DL + ML: scikeras

- Deep Learning: tensorflow, keras

- Utilitários e suporte: joblib, kagglehub, tabulate


## ⬇️ Instruções para execução do projeto

1. Clone este repositório em sua máquina local:

    ```
    git clone https://github.com/Vibranovski/XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX.git
    ```

3. Abra o arquivo no Google Colab ou em um ambiente local com suporte a Jupyter Notebooks.

4. Execute as células do notebook para reproduzir o trabalho de análise e pré-processamento.


## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="#">Global AI Job Market & Salary Trends 2025</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="#">Daniel Vibranovski Costa.
</a> is 
licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

## 🎓 Referências

BRUCE, A.; BRUCE, P. Estatística prática para cientistas de dados: 50 conceitos essenciais. Rio de Janeiro: Alta Books, 2019.

BROOKS JR., F. P. No silver bullet: essence and accidents of software engineering.

IEEE Computer, v. 20, n. 4, p. 10-19, 1987.

ESCOVEDO, T.; KOSHIYAMA, A. Introdução a data science: algoritmos de
machine learning e métodos de análise. São Paulo: Casa do Código, 2020.

FAWCETT, T.; PROVOST, F. Data science para negócios: o que você precisa saber sobre mineração de dados e pensamento analítico de dados. Rio de Janeiro: Alta Books, 2018.

KALINOWSKI, M.; ESCOVEDO, T.; VILLAMIZAR, H.; LOPES, H. Engenharia
de software para ciência de dados: um guia de boas práticas com ênfase na construção de sistemas de Machine Learning em Python. São Paulo: Casa do Código, 2023.

KNAFLIC, C. N. Storytelling with data: a data visualization guide for business professionals. Hoboken: Wiley, 2015.

LAURA, I.; SANTI, S. Introduction to data science: a Python approach to concepts, techniques and applications. Cham: Springer, 2017.

MCKINNEY, W. Python para análise de dados: tratamento de dados com Pandas, NumPy e IPython. São Paulo: Novatec, 2019.

MUNZNER, T. Visualization analysis and design. Boca Raton: CRC Press, 2014.

SOMMERVILLE, I. Engenharia de software. 10. ed. São Paulo: Pearson, 2019.

## 🙏 Agradecimentos

Agradeço à PUC-RIO e aos meus professores pela oportunidade de fazer esse MVP a partir da Sprint: Machine Learning & Analytics do curso de Pós Graduação em Ciência de Dados e Analytics da PUC-RIO.
