# Previsão do PLD do Subsistema Nordeste
### Uma Abordagem Utilizando Técnicas de Machine Learning

Esse repositório apresenta o processo de criação do modelo preditivo utilizado no artigo: "Previsão do PLD do Subsistema Nordeste: Uma Abordagem Utilizando Técnicas de Machine Learning".

Nesse artigo, foi realizado um estudo sobre a aplicação das técnicas de Machine Learning na previsão do Preço de Liquidação das Diferenças (PLD) do submercado Nordeste (preço spot). O objetivo foi encontrar uma técnica de Machine Learning que melhor pudesse descrever o comportamento do sistema, utilizando os atributos escolhidos, e prever o PLD médio semanal com a maior taxa de acerto possível, com base em dados históricos de junho/2020 a junho/2023. Os dados utilizados foram extraídos do Operador Nacional do Sistema Elétrico (ONS). Os atributos considerados incluem a geração térmica, solar, eólica, carga total e energia bruta proveniente de fontes renováveis. A análise visa contribuir para a tomada de decisões eficientes no setor elétrico, permitindo a antecipação e a comercialização eficiente da energia elétrica por parte das empresas de geração e comercialização.

#### Estrutura do Projeto:
- O arquivo "Dados_ONS.xlsx" contém os conjuntos de dados utilizados no projeto.
- O arquivo "Análise Preditiva em Base Semanal.ipynb" contém o Jupyter Notebook com análises exploratórias, visualizações e modelagem.
- O arquivo "MLPRegressor-PLD.pkl" contém o modelo treinado, salvo em formato .pkl.

#### Instalação e Execução do Projeto:
- Certifique-se de que o Python está instalado em sua máquina, assim como um ambiente capaz de executar o Jupyter Notebook, como o Visual Studio Code, por exemplo.
- Clone este repositório em seu ambiente local.
- Instale as dependências utilizadas:
  - Pandas
  - Seaborn
  - Matplotlib
  - scikit-learn

#### Ambientes testados:
- Python: 3.11.8
- Visual Studio Code via extensão Jupyter
