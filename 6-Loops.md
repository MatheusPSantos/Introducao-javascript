# Loops

Assim como na maioria das linguagens de programação, javascript possui instruções que servem para que haja repetições, os loops. Essas repetições podem ter uma condição de parada definida, assim, quando algo acontecer o loop é encerrado.
É preciso ter cuidado com os loops, caso eles não sejam tratados de uma forma decente eles podem acarretar um travamento no navegador do usuário. Isso é bem incoveniente.

## While

While significa "enquanto", ou seja, enquanto uma determinada condição é satisfeita haverá a execução de um trecho de código. Caso essa condição não seja mais satisfeita então o trecho de código para de funcionar.

Sintaxe do while:

```
while(condição) {
    // bloco de código
}
```
O trecho anterior pode ser lido da seguinte maneira:
```
enquanto a condição é satisfeita faça
    // instruções em js
fim enquanto
```

## do ... while

O do ... while é semelhante ao laço while. A diferença entre eles se econtra no início da execução. No while, se a condição ja começa não sendo satisfeita então o código dentro do laço não é executado. O while testa a condição de início, para depois executar o laço.

Por exemplo, o código de exibir a mensagem na tela não será executado.
```
var num = 1;

while(num > 10) {
    alert('mensagem');
}
```

No do...while a condição só é testada no final da execução do primeiro laço. Ele primeiro executa o código dentro das chaves (do), e depois testa a condição (while).
Por exemplo, a mensagem só aparece uma vez, pois a condição para o segundo laço não é satisfeita.
``` 
var num = 1;

do {
    alert('esse é o laço do...while');
} while(num > 10);

```

## for

O significado de for é "para". A sintaxe básica do laço é a seguinte:

```
for(var i = 0; i <= n; i++) {
    // instruções em js
}
```

Essa sintaxe pode apresentar algumas alterações. Podemos ler o comando da seguinte maneira:

``` 
para i começando com 0, enquanto i for menor ou igual a n, então execute as instruções e após incemente i.
fim paras
```