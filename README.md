# Branch dev

## Explorando Delícias Globais: Revelando Receitas Culinárias Através da Inteligência Computacional

A gastronomia é uma das formas mais ricas de expressão cultural, e a diversidade de sabores ao redor do mundo é uma fonte inesgotável de prazer para os paladares curiosos. No decorrer deste projeto, mergulhamos nesse universo de sabores ao utilizar uma vasta base de dados contendo receitas culinárias de diversas regiões do globo. Nosso objetivo principal foi extrair insights valiosos e criar um sistema capaz de sugerir as melhores receitas aos entusiastas da culinária.

## Importação de Dados e Configuração do Ambiente

A primeira etapa consistiu na importação dos conjuntos de dados de receitas provenientes de diferentes culturas e tradições culinárias. Para alcançar nossos objetivos, aproveitamos as capacidades das bibliotecas Python, como Pandas, para manipulação de dados, e a biblioteca Surprise para construir e treinar modelos de recomendação.

## Análise e Limpeza de Dados

Após a importação, procedemos à análise detalhada dos dados, buscando inconsistências, valores ausentes e possíveis erros. A qualidade dos dados é fundamental para garantir resultados confiáveis. Realizamos limpezas, preenchimento de valores faltantes e tratamento de outliers, assegurando que os modelos fossem alimentados com informações coerentes e precisas.

## Explorando a Magia dos Modelos de Machine Learning

A parte central do projeto envolveu a aplicação de técnicas de aprendizado de máquina para a criação de um sistema de recomendação de receitas. Utilizando a biblioteca Surprise, que é dedicada a sistemas de recomendação, configuramos diferentes modelos e os treinamos usando os dados previamente preparados. Entre esses modelos, o KNNBaseline se destacou como a escolha mais adequada para os nossos objetivos, demonstrando um desempenho superior em relação a outros modelos testados.

## Criação da Função de Recomendação Personalizada

Com o KNNBaseline definido como o modelo principal, avançamos para a criação de uma função que permitisse aos usuários desfrutar das maravilhas culinárias do mundo. Essa função, com base no ID do usuário como entrada, é capaz de identificar os gostos e preferências do usuário com base em suas interações anteriores. Com esse entendimento, a função é capaz de fornecer recomendações altamente personalizadas, apresentando receitas que se alinham ao perfil gastronômico de cada indivíduo.

## Conclusão: Celebrando a Diversidade Culinária com Tecnologia

Ao finalizar este projeto, não apenas exploramos a riqueza da culinária global, mas também utilizamos técnicas avançadas de aprendizado de máquina para desvendar os segredos por trás das preferências culinárias individuais. O sistema de recomendação que desenvolvemos permite que os entusiastas da comida embarquem em uma jornada culinária única, descobrindo novos sabores e ampliando seus horizontes gastronômicos, tudo isso com a ajuda da inteligência computacional.

## Que a aventura de sabores continue, e que a tecnologia continue a nos conectar com o mundo através da comida.

Devido ao tamanho dos Datasets não conseguimos fazer o upload no Github. Segue abaixo link das bases utilizadas:
https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions
