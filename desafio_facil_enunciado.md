# Desafio SQL: Países Grandes

## Tabela: World

| Column Name | Type    |
|-------------|---------|
| name        | varchar |
| continent   | varchar |
| area        | int     |
| population  | int     |
| gdp         | bigint  |

- `name` é a chave primária da tabela, com valores únicos.
- Cada linha desta tabela fornece informações sobre o nome de um país, o continente ao qual pertence, sua área, população e valor do PIB.

## Definição de País Grande

Um país é considerado grande se:

- Tem uma área de pelo menos três milhões (ou seja, 3000000 km²), ou
- Tem uma população de pelo menos vinte e cinco milhões (ou seja, 25000000).

## Objetivo

Escreva uma solução para encontrar o nome, a população e a área dos países grandes.

Retorne a tabela de resultados em qualquer ordem.

O formato do resultado está no exemplo a seguir.

## Exemplo

### Exemplo 1:

**Input:** 
Tabela World:
| name        | continent | area    | population | gdp          |
|-------------|-----------|---------|------------|--------------|
| Afghanistan | Asia      | 652230  | 25500100   | 20343000000  |
| Albania     | Europe    | 28748   | 2831741    | 12960000000  |
| Algeria     | Africa    | 2381741 | 37100000   | 188681000000 |
| Andorra     | Europe    | 468     | 78115      | 3712000000   |
| Angola      | Africa    | 1246700 | 20609294   | 100990000000 |

**Output:** 
| name        | population | area    |
|-------------|------------|---------|
| Afghanistan | 25500100   | 652230  |
| Algeria     | 37100000   | 2381741 |
