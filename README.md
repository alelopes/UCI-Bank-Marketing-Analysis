# UCI-Bank-Marketing-Analysis
O objetivo deste projeto é responder de maneira clara 6 perguntas sobre o UCI Bank Marketing Data Set.

## Estrutura
 - data/  - Contém os dados utilizados pelo projeto e disponíveis [aqui](https://archive.ics.uci.edu/ml/datasets/bank+marketing#).
 - notebook/  - Contém o BankMarketingAnalysis.ipynb, responsável pela análise de dados.

## Bibliotecas
Esse projeto foi testado com Python 3.5 e as seguintes dependências:
 - Pandas (0.23.4)
 - Numpy (1.13.3)
 - Plotly (3.2.1)
 
 Plotly é uma ferramenta de visualização com versão gratuita até 25 gráficos gerados. 
 
 Para fazer esse acesso aos gráficos renderizados e ter controle da quantidade de gráficos por conta, ele pede o uso de uma linha de credenciais, como na linha abaixo:

 ```
 plotly.tools.set_credentials_file(username='USERNAME', api_key='KEY')
 ```
 No notebook deixei o meu username e api_key pessoais, o que não deverão gerar nenhum tipo de problema. Para mais informações sobre as credenciais, clique [aqui](https://plot.ly/python/getting-started/).
 
## Instalação

Para instalar o ambiente, sugiro utilizar o gerenciador de dependências [conda](https://conda.io/docs/index.html)

## Notebook

O github não renderiza os gráficos, então se desejar utilize o [nbviewer](http://nbviewer.jupyter.org/) para abrir o notebook com gráficos. **O link do Notebook deste projeto já foi carregado e pode ser acessado [aqui](http://nbviewer.jupyter.org/github/alelopes/UCI-Bank-Marketing-Analysis/blob/master/notebooks/.ipynb_checkpoints/BankMarketingAnalysis-checkpoint.ipynb)**
