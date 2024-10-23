# arvoreDecisao

## Leitura e visualização dos dados
Primeiramente realizamos a leitura do dataset, e em sequencia é feito a vizualização do dataset para entender como são os dados

## separação de treino e teste
Na vizualização percebemos que não tem nada que precise de tratamento no dataset, então partimos para a separação de treino e teste, nesse dataset separamos 70% para treino e 30% para teste

## Treinamento do modelo
Para este dataset utilizamos um modelo de arvore de decisão, testando ele com diferentes valores para descobrir qual a melhor configuração para o modelo

# Conclusão
Pelo que vimos no modelo, basta adicionar alguns graus de profundidade na arvore e ela apresenta resultados maiores no teste de acuracia, pelo codigo, a partir da profundidade 3 da arvore, a acuracia ja estava em 100%, porem o dataset é bem pequeno e com bem poucas colunas, então acredito que esteja dentro do padrão. Não ouve muitas diferenças entre o criterion gini e entropy, acredito que seja necessário um dataset bem maior para que possamos começar a ver alguma diferença.
