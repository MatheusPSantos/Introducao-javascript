# Instruções Condicionais

São instruções que permite que a aplicação se comporte de forma mais inteligente, principalmente reagindo a ações do usuário.

## If e if...else

If significa "se". Else significa "se não". Se a condição dentro do IF for verdadeira as instruções dentro das chaves do mesmo serão executadas.

Estrutura básica do if:
```
if(condição) {
    // bloco de código
}
```
Estrutura básica do if ... else:
```
if(condição) {
    // bloco de código
} else {
    // código que será executado caso a condição no if não seja verdadeira
}
```
Estrutura com mais de um if e else:
```
if(condição) {
    // bloco de código
} else if(outra condição) {
    // outro bloco de  comando
} else {
    // se nenhuma das condições for satisfeitas
}
```

## Switch

Quando há a necessidade de usar vários if's e else's entao é muito provável que se pode usar switch no lugar. Por uma questão de melhoria na prática de codificação.
Switch significa "escolha". É altamente indicado que haja uma condição padrão dentro do switch, deve haver ao menos a execução de uma instrução, nem que seja a de saída "break". Por isso há um valor "default".

Exemplo de como usar o switch:
```
switch(expressao) {
    case n:
        // bloco de comando
        break;
    case n:
        // bloco de comando
        break;
    .
    .
    .
    default:
        // bloco de comando
}
```

## Operador Ternário

É um formato condicional implícito, que usa o ponto de interrogação após a condição a ser aceita.
Sintaxe:
> condição ? primeiro comando : segundo comando

Podemos ler o ternário da seguinte maneira: "Condicao é verdaderia? Sim. Então executa aqui: Não. Então executa aqui."
