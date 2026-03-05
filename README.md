# Previsão de Renda

Este projeto foi desenvolvido como parte dos exercícios do curso de Ciência de Dados. A ideia é analisar um conjunto de dados de clientes de uma instituição financeira para entender melhor o perfil de renda dessas pessoas.

O objetivo é explorar os dados e verificar se algumas variáveis disponíveis no banco de dados podem ajudar a prever a renda dos clientes, sem precisar solicitar documentos como comprovantes de renda.

## Etapas do projeto

Primeiro foi feita a leitura do arquivo `previsao_de_renda.csv` utilizando pandas.

Depois disso foram realizadas algumas análises exploratórias:

* análise da estrutura dos dados
* avaliação das correlações entre as variáveis numéricas
* criação de matriz de dispersão (pairplot)
* análise gráfica da matriz de correlação
* gráfico de dispersão entre as variáveis mais correlacionadas com a renda
* identificação de possíveis outliers na variável renda

Na sequência foi aplicado o **logaritmo da variável renda** para observar se a transformação melhora a visualização e a interpretação dos dados.

## Conclusão

A variável renda apresenta alguns valores muito altos que acabam influenciando bastante os gráficos. Ao aplicar o logaritmo, a distribuição dos dados fica mais equilibrada, o que facilita a visualização das relações entre as variáveis e pode ajudar em análises e modelos futuros.

## Ferramentas utilizadas

* Python
* Pandas
* Seaborn
* Matplotlib
