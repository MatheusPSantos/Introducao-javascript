# Funções

As funções são meios para deixar o código mais enxuto, reutilizável, manutenível e modulado.
Elas evitam que haja repetições e perca de tempo no momento de desenvolver projetos mais amplos, não só emmm javascript mas em qualquer outra linguagem.

## Sintaxe

As funções podem ser escritas da seguinte maneira:

```
function NomeDaFuncao(parametro, parametro, ..., parametro) {
    // instruções
}
```

Existe funções que precisam de parâmetros e outras que não, algumas retornam valores e outras não. Tudo isso vai depender da finalidade que você vai dar para a função que escrever.

## Função que retorna valor

Uma função que retorna valor é aquela que tem seu final na palavra reservada <b>return</b>.
Essa palavra que indica que algo será retornado. O retorno pode ser armazenado em uma variável, em outra função, ou ser exibido.

Sintaxe
```
function nomeDaFuncao(...) {
    // codigo
    ...
    return retornoDaFuncao;
}
```

## Função que recebe parâmetro

As funções podem receber parâmetros ou não, caso ela não receba parâmetros então sua sintaxe básica é:
```
function nomeDafuncao() {
    // codigo
}
```

Se ela recebe parâmetros, então os parâmetros devem ser declarados no escopo da função.
```
function nomeDaFuncao(parametro1, parametro2, parametro3) {
    // codigo
}
```

## Função anônima

A função anônima é atribuída a uma variável.

Sintaxe:
```
var mensagem = function() {
    alert("Mensagem");
}

// chamando a função mensagem

mensagem();

```

## Arow Functions

Arrow function é uma outra forma de escrever e declarar funções. Apresenta uma sintaxe mais enxuta.

```
// para somente um parametro
parametro => {
    // código
}

// se não houver parametro
() => {
    // código
}

// uma declaração ou expressão
parametro => expressao => {
    // codigo
}

// multiplas declarações
parametro => {expressoes, declaracoes} => {
    // codigo
}

```
