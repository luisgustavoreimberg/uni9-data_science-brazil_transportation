# Projeto de Ciência de Dados
- Universidade Nove de Julho
- Ciência da Computação - 2021/02
- Visualização Online [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/luisgustavoreimberg/uni9-data_science-brazil_transportation/main?labpath=BrazilTransportation%5B2019-2020%5D.ipynb)

## Sobre o Projeto
- **Tema:** Análise do fluxo do transporte interestadual de ônibus entre os anos de 2019 e 2020
- **Integrantes**:
  - Daniel Dos Santos Pierre
  - Estevão Souza dos Santos
  - Gustavo Henrique Barcellos Jaques
  - James Lima Moreira da Cruz
  - Luis Gustavo Gonçalves Reimberg
  - Matheus Ferreira da Silva
  - Thiago da Cruz Lino
- **Professor**:
  - Prof. Dr. José Eduardo Storopoli
  ```
  https://storopoli.io/
  ```

--------------------------------------
## Descrição
### **Introdução**
O projeto em questão envolve o uso dos conceitos apresentados na aula de **Ciência de Dados** para análise de um *DataSet*. Os conceitos da aula envolvem:
- Leitura de dados com *pandas*
- Manipulação e limpeza de dados com *pandas*
- Descritivo e exploração de dados com *pandas* (*groupbys*)
- Geração de insights sobre os dados com *pandas* e *matplotlib*
- Quebra de dados em conjunto de treino e conjunto de teste
- Treino de estimador do *scikit-learn* de aprendizagem supervisionada (regressor ou classificador) no conjunto de treino
- Verificação de desempenho do estimador do *scikit-learn* no conjunto de teste

### **Desenvolvimento do projeto**
O *DataSet* escolhido para realizar a análise e manipulação dos dados foi o **Road transport dataset in Brazil**: um levantamento de dados de viagens interestaduais de ônibus realizadas no Brasil entre os anos de 2019 e 2020. A partir deste dataset, foram realizadas as atividades de análise e manipulação de dados seguindo os conceitos da matéria de Ciência de Dados 2021/02.  
Todas as informações e resultados do processamento de dados estão descritos e demonstrados no arquivo **BrazilTransportation[2019-2020].ipynb**.

--------------------------------------
## Referências e Links importantes

> ### **DataSet: Road transport dataset in Brazil**
> Base de dados utilizada no projeto  
> ```
> GOMES, Fellipe. Road transport dataset in brazil: Data from a year of road trips in Brazil (+ COVID19 data). Kaggle, 2020. Disponível em: https://www.kaggle.com/gomes555/road-transport-brazil
> ```


> ### **Ciência de Dados**
> Orientações do trabalho e conceitos das aulas utilizados para realização do trabalho
> ```
> Storopoli (2020, March 2). Ciência de Dados com Python: pandas, matplotlib, scikit-learn e tensorflow: Ciência de Dados. Disponível em: https://github.com/storopoli/ciencia-de-dados
> ```

--------------------------------------
## Como iniciar a aplicação

1 - Descompactar o dataset
> O dataset do projeto está em formato zip(por questões de espaço no repositório).  
> Antes de iniciar a aplicação, deve-se descompactar o arquivo **data/road-transport-brazil.zip**

2 - Abrir o arquivo **BrazilTransportation[2019-2020].ipynb**
> Este arquivo é um Jupiter Notebook que contém todas as operações de análize e tratamento de dados

### **Importante:**
Para o projeto funcionar corretamente, deve-se ter instalados os seguintes softwares:
- Python 3.9.9
- Pip 21.3.1+
- Pandas
- Matplotlib
- Scikitlearn

Extensões para serem usadas no Visual Studio Code(caso necessário):
- Jypyter
- Jupyter Keymap
- Jupyter Notebook Renders
- Python
- Pylance