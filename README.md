# Utilizando Machine Learning para Previsão de Inadimplência Empresarial

## Introdução
Este projeto é parte do curso de Data Science da Awari e aborda o desafio enfrentado por pequenas empresas no Brasil durante a pandemia, com mais de 5 milhões delas endividadas e inadimplentes, buscando empréstimos para sobreviver. O foco é desenvolver um modelo de machine learning capaz de prever a inadimplência dessas empresas com base em dados fornecidos pelo Banco Central do Brasil.

## Premissas para Análise
O trabalho utiliza dados disponibilizados pelo Banco Central do Brasil, acessados através do [site do BACEN](https://dadosabertos.bcb.gov.br/dataset/scr_data), relacionados à inadimplência empresarial no contexto brasileiro.

## Estratégia de Solução
A abordagem adotada envolve o uso do método `predict` para classificar empresas como inadimplentes (1) ou não inadimplentes (0). Além disso, é empregado o método `predict_proba` para calcular a probabilidade de inadimplência. Essa probabilidade pode ser utilizada por instituições financeiras para ajustar os juros com base no risco percebido, personalizando de forma mais eficiente suas estratégias de crédito.

## Principais Insights de Dados
Após análise, o modelo XGBoost destacou-se como o mais adequado para o projeto, oferecendo resultados precisos na previsão de inadimplência. Dessa forma, recomenda-se sua implementação para identificar potenciais inadimplentes entre novos dados de consumidores, possibilitando a tomada de medidas proativas para minimizar perdas.

## Produto Final do Projeto
O resultado do projeto é apresentado em um [Notebook Python](https://github.com/oemeferreira/previsao-inadimplencia/blob/main/Projeto.ipynb), contendo o código, análises exploratórias, treinamento do modelo e avaliação de desempenho.

## Conclusão
Ao enfrentar o desafio de identificar o risco de crédito, este projeto desenvolveu um modelo de machine learning robusto. A implementação prática desse modelo permite à instituição cedente do crédito tomar decisões informadas, personalizando sua abordagem com base na probabilidade de inadimplência, proporcionando uma gestão mais eficiente e eficaz.

