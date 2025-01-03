# Rossmann Sales Prediction 

## Projeto de Previsão de Vendas 
Este projeto visa prever as vendas das lojas da rede de farmácias Rossmann para as próximas 6 semanas. O objetivo é fornecer ao CFO uma previsão precisa dos lucros, ajudando na tomada de decisões estratégicas. 

## Problema de Negócio 
O CFO da Rossmann precisa de uma previsão confiável das vendas para as próximas 6 semanas para estimar os lucros das lojas. A solução apresentada aqui utiliza técnicas de aprendizado de máquina para prever as vendas futuras com base em dados históricos. 

## Estrutura do Projeto  
**0.0 Imports**: Importação das bibliotecas e pacotes necessários.  
**1.0 Descrição dos Dados**: Detalhamento dos dados utilizados, incluindo origem e descrição das variáveis.  
**2.0 Featuring Engineering**: Criação de novas variáveis que podem ajudar a melhorar o desempenho do modelo.  
**3.0 Filtragem das Variáveis**: Seleção das variáveis mais relevantes para a modelagem.  
**4.0 Análise Exploratória de Dados**: Análises univariadas, bivariadas e multivariadas para entender melhor os dados.  
**5.0 Data Preparation**: Preparação dos dados para a modelagem, incluindo tratamento de valores ausentes e normalização.  
**6.0 Feature Selection**: Seleção das variáveis mais importantes para a modelagem.  
**7.0 Machine Learning Modelling**: Desenvolvimento e treinamento dos modelos de aprendizado de máquina.  
**8.0 Hyperparameter Fine Tuning**: Ajuste fino dos hiperparâmetros dos modelos para otimizar o desempenho.  
**9.0 Tradução e Interpretação do Erro**: Interpretação dos erros dos modelos e avaliação da performance.  
**10.0 Deploy Model To Production**: Implementação do modelo em produção utilizando Flask e Heroku.  

## Tecnologias Utilizadas 
- **Python**
- **Pandas**
- **Scikit-learn**
- **Flask**
- **Heroku**
- **Telegram Bot API**
- 
## Principais Hipóteses 
1. Lojas com competidores mais próximos deveriam vender menos.
  - **Resultado**: Falso, lojas com competidores mais próximos vendem mais.
  - **Análise**: Foi analisada a distância de competidores mais próximos em relação às vendas. Utilizando o método de correlação de Pearson, foi obtido um valor de -0.23, indicando uma correlação negativa entre a proximidade de competidores e as vendas. No entanto, esta correlação não é forte o suficiente para confirmar a hipótese inicial.

## O Produto Final 
Painel online, hospedado na nuvem e disponível para acesso em qualquer dispositivo conectado à Internet. O painel pode ser acessado através do [link da API](https://rossmann-model-hg-7d38cfc390fb.herokuapp.com/rossmann/predict).

## Conclusão 
O objetivo deste projeto é criar um conjunto de gráficos e tabelas que exibam as métricas da melhor forma possível para o CFO. A partir das análises, podemos concluir que as vendas tendem a aumentar em determinados períodos, o que pode ser utilizado para estratégias de Marketing.

## Próximos Passos 
1. Refine o número de métricas apresentadas.
2. Crie novos filtros para análise mais detalhada.
3. Adicione novas visões de negócio para uma análise mais completa.
4. Melhorias no Bot do Telegram
   - o Bot atualmente trás informações das previsões de vendas nas próximas 6 semanas.

## Autores 
- **Hugo Gabriel** - Desenvolvimento do projeto

## Licença 
Este projeto está licenciado sob os termos da licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
