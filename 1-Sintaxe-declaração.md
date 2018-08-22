# Sintaxe e Declaração

Em uma página web é possível declarar um trecho de código em Javascript através das tags <script></script>.

Exemplo de como inserir código Javascript em um documento html:
```
<!Doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Título da Página</title>
    </head>
    <body>
        <script type="text/javascript"> 
            // escrever aqui o código javascript
        </script>
    <body>
</html>
```

## Case Sensitive

<p>Javascript é uma linguagem case sensite, ou seja, os nomes de variáveis, funções ou qualquer outra coisa que está escrito dentro de um arquivo javascript, somente pode ser identificado de uma maneira.</p>

<p>As letras maiúsculas e minusculas são diferenciadas pelo interpretador do javascript presente no navegador web.</p>

O que significa que:
<b>essetexto</b> é diferente de <b>Essetexto</b>, que por sua vez é diferente de <b>ESSETEXTO</b> e <b>esseTexto</b>.


## Espaços em branco e recuos

O javascript ignora espaços em branco e tabulações, o que permite deixar o código mais organizado. O recomendado é que seja usado com sabedoria os espaços em branco.

Uma boa forma de uso: separar nomes das funções, instruções e nomes de objetos.

Exemplo de mal uso de espaços e recuos:
```
var divisao=function(num1,num2){
if(num2!="0"){ var resultado=num1/num2;
alert(resultado);}
else alert("Impossível dividir por zero!");
};
```

Exemplo de bom uso de espaços e recuos:
```
var divisao = function(num1, num2) {
    if(num2 != "0") {
        var resultado = num1/num2;
        alert(resultado);
    } else {
        alert("Impossível dividir por zero!");
    }
};
```

## Comentários

Para realizar comentários no código existe duas maneira:

Comentário de linha, que pode usar <b>//</b>.
Comentário de múltiplas linhas, usando <b>/* */</b>.

Como na maioria das linguagens de programação.

## Palavras reservadas

São palavras que você não pode usar para nomear funções, variáveis, objetos e etc. São nomes de instruções inerentes a linguagem. Caso sejam usados de forma errada, podem dar piriri na hora da interpretação pelo navegador.

São elas:
<img src="http://www.codewordjs.com/wp-content/uploads/2016/10/JS-Reserved-Keywords.png" alt="palavras reservadas do Javascript">

## Modo Estrito (Strict Mode)

É um modo mais rigoroso de execução da linguagem. O Javascript gera um erro <b>exception</b> caso ao tentar executar algo que é considerado uma má prática de códificação. Usar variáveis não declaradas, recursos obsoletos, palavras reservadas, etc.

Para usar o modo estrito deve-se declarar <b>"use strict"</b> antes de todo o código. Caso haja código antes, o modo estrito não será habilitado. Por exemplo:

> modo estrito habilitado
```
"use strict";
var algumavariavel = "algumvalor";
// código
```
> modo estrito desabilitado
```
var algumacoisa = "algumvalor";
// código
"use strict";
```

