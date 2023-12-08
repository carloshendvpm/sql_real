# Desafio SQL: Segundo Maior Salário

## Tabela: Employee

| Column Name | Type |
|-------------|------|
| id          | int  |
| salary      | int  |

- `id` é a chave primária da tabela, contendo valores únicos.
- Cada linha desta tabela contém informações sobre o salário de um funcionário.

## Objetivo

Escreva uma solução para encontrar o segundo maior salário na tabela Employee. Se não houver um segundo maior salário, retorne null (ou None em Pandas).

O formato do resultado está no exemplo a seguir.

## Exemplos

### Exemplo 1:

**Input:** 
Tabela Employee:
| id | salary |
|----|--------|
| 1  | 100    |
| 2  | 200    |
| 3  | 300    |

**Output:** 
| SecondHighestSalary |
|---------------------|
| 200                 |

### Exemplo 2:

**Input:** 
Tabela Employee:
| id | salary |
|----|--------|
| 1  | 100    |

**Output:** 
| SecondHighestSalary |
|---------------------|
| null                |
