# Resumo do Projeto

Crie uma aplicação capaz de receber o nome e as notas de um atleta, calcular a média e apresentar ao usuário.

## Introdução

Em uma competição de ginástica artística, atletas são avaliados por cinco jurados. Cada um fornece notas de 1 a 10, e a média é calculada considerando apenas as três notas do meio, desconsiderando a maior e a menor.

### Regras de Avaliação:

- Cada jurado dá notas de 1 a 10.
- A média é calculada a partir das três notas intermediárias.

O organizador contratou sua equipe para desenvolver uma aplicação em JavaScript que atenda a esses requisitos.

## Especificações

Crie uma função que receba uma matriz de objetos com o nome do atleta e suas cinco notas. A função deve calcular a média e apresentar os resultados.

### Exemplo de Entrada:

```javascript
let atletas = [
  { nome: "Cesar Abascal", notas: [10, 9.34, 8.42, 10, 7.88] },
  { nome: "Fernando Puntel", notas: [8, 10, 10, 7, 9.33] },
  { nome: "Daiane Jelinsky", notas: [7, 10, 9.5, 9.5, 8] },
  { nome: "Bruno Castro", notas: [10, 10, 10, 9, 9.5] }
];
```
##Saída Esperada:
Atleta: Cesar Abascal
Notas Obtidas: 10, 9.34, 8.42, 10, 7.88
Média Válida: 9.25

Atleta: Fernando Puntel
Notas Obtidas: 8, 10, 10, 7, 9.33
Média Válida: 9.11

Atleta: Daiane Jelinsky
Notas Obtidas: 7, 10, 9.5, 9.5, 8
Média Válida: 9.00

Atleta: Bruno Castro
Notas Obtidas: 10, 10, 10, 9, 9.5
Média Válida: 9.83

## Dicas
- Utilize um laço `for` para percorrer a matriz.
- Use o método `.sort()` para ordenar as notas.
- Use `if/else` para eliminar as notas extremas.
- Utilize `.slice(1, 4)` para selecionar as notas intermediárias.
- Use `.forEach()` para somar as notas.
- Utilize `.length` para calcular a média.
- Use `console.log()` para mostrar os resultados.
