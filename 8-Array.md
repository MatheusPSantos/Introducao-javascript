# Array

O Array é um tipo de variável que pode armazenar varias informações ao mesmo tempo, podendo ser acessadas atraves do índice.

## Sintaxe

> var nomeArray = [item1, item2, item3,...];

Pode-se usar a palavra reservada <b>new</b>.
> var nomeArray = new Array(item1, item2, ...);

Para consultar a informação que está dentro do array você usa o indice do array. O indice começa em 0 e vai até N - 1, onde N é o tamanho do array.

Exemplo:
```
var carros = new Array("Gol", "Uno", "Fiat");

alert(carros[2]);
```
Saída:
> Fiat

## Propriedade Length

A propriedade Length retorna o tamanho do array, ou seja, a quantidade de elementos no array.
```
var cidades = ["Curitiba", "Salvador", "Florianopolis", "São Paulo", "Rio de Janeiro"];

for (var i = 0; i < cidades.length; i++) {
    document.write("Cidade: " + cidades[i]);
}
```

Saída:
> Cidade: Curitiba
> Cidade: Salvador
> Cidade: Florianopolis
> Cidade: São Paulo
> Cidade: Rio de Janeiro

## Pop() e Push()

O método pop() remove o último elemento de um array. O push() adiciona um novo elemento no final do array.


## Método splice()

Informa que um elemento deve ser adicionado ou eliminado de acordo com a sua posição.
> array.splice(A, N, p, q, ..., k);

Podemos ler da seguinte maneira:
> Adicionar na posição A do array e romever N elementos os elementos p, q, ..., k

