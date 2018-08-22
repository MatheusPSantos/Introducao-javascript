# Trabalhando com tipos de dados

Assim como todas as linguagens de programação, javascript possui tipos de daos:
* numéricos
* booleanos
* texto

## Numérico

Tipos de dados numéricos incluem, inteiros, de ponto flutuante, números negativos, hexadecimais.
> 5.0 <br> 0x1289fa <br> -0.4

## String

São dados de texto em Javascript, elas sao indicadas por um conjunto de caracteres entre aspas "" e aspas simples ''.

Caso você queira usar aspas duplas dentro da frase, então é indicado o uso de aspas simples para a string. Por exemplo:

Código:
> 'Esse café está meio "frouxo".'

Saída:
> Esse café está meio "frouxo"

## Booleano

Os valores booleanos, ou boolean, só podem ser dois. Verdadeiro, indicado pela palavra reservada <b>true</b>, e Falso, indicado pela palavra reservada <b>false</b>.

```
var presencaDoAluno = false;
var verbaParaPesquisa = false;
var promessasDeCampanha = true;
```

São bastante necessários para instruções que precisam disparar eventos que só podem ocorrer após determinada condição ser satisfeita, seja ela como TRUE ou FALSE.


## NaN - Not a Number

A palavra reservada NaN do javascript indica que um valor não é um número.
Por Exemplo, qual o resultado da divisão entre a idade do usuário e o seu nome?

```
var idade = 21;
var nome = "Hercules";
var resultado = idade/nome;
alert(resultado);
```

## Null

<b>Null</b> significa <b>Nulo</b>, ou nada. Null é diferente de uma variável vazia.
Exemplo de variável Null:
> var teste = null;

Exemplo de variável vazia:
> var teste = "";

<img src="https://brunocapuano.files.wordpress.com/2017/11/0-vs-null.jpg?w=685" alt="diferença de NULL e um valor zero">



## Undefined

Uma variável é <b>undefined</b> quando ela é declarada, mas não é inicializada.
Exemplo:
> var teste;

## Propriedades dos tipos numéricos

Os tipos numéricos em javascript possuem algumas propriedades. Elas só podem ser acessadas através do objeto Number.
<table>
    <tr>
        <th>Propriedade</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>MAX_VALUE</td>
        <td>Exibe o maior número</td>
    </tr>
    <tr>
        <td>MIN_VALUE</td>
        <td>Exibe o menor número</td>
    </tr>
    <tr>
        <td>NEGATIVE_INFINITY</td>
        <td>Exibe o infinito negativo</td>
    </tr><tr>
        <td>POSITIVE_INFINITY</td>
        <td>Exibe o infinito positivo</td>
    </tr>
<table>

Exemplo:
```
var x = Number.MAX_VALUE;
var y = Number.MIN_VALUE;
var z = Number.POSITIVE_INFINITY;
var w = Number.NEGATIVE_INFINITY;

```

## A propriedade Length

A propriedade <b>length</b> retorna o tamanho de uma string. Por exemplo:

```
var algumaString = "Olá Mundo!";
var n = algumaString.length;

alert(n);
```

Saída:
> 10

## Methods

<b>Methods</b> são funções que estão ligadas ao objeto. Podemos criar uma variável string e acessar os methods do objeto string.

Alguns exemplos de methods do objeto string:

#### charAt()

Retorna o caractere presente na posição passada por parâmetro.
```
var txt = "Olá Mundo!";
var resultado = txt.charAt(2);
```
Saída:
> á

#### indexOf()

Retorna a posição da primeira aparição da string passada por parâmetro.
```
var txt = "Olá Mundo";
var saida = txt.indexOf("Olá");
```
Saída:
> 0

#### replace()

Substitui uma string passada por parâmetro por outra, também passada por parâmetro.
```
var txt = "Olá Mundo";
var result = txt.replace("Mundo", "Javascript");
alert(result);
```
Saída:
> Olá Javascript

#### slice()

Extrai uma parte de uma string, a partir de um ponto até outro. O range da extração é definido pelos parâmetros passados para o método.

```
var txt = "Eu sou a lenda";
var resul = txt.slice(3,6);

alert(resul);
```
Saída:
> sou

#### substr()

Extrai uma string de outra string, informando a posição de início e o tamanho da string.

```
var txt = "Olá Mundo";
var res = txt.substr(1, 3);

alert(res);
```
Saída:
> lá

#### split()

Separa a string em uma matriz de substrings.

```
var txt = "O que faz você feliz?";
var res = txt.split('');

```
Saída:
> ["O", " ", "q", "u", "e", " ", "f", "a", "z", " ", "v", "o", "c", "ê", " ", "f", "e", "l", "i", "z", "?"]

#### toLowerCase() e toUpperCase()

<b>toLowerCase()</b> transforma muda a caixa da string para caixa baixa. <b>toUpperCase()</b> transforma todas os caracteres da string em maiúsculos.

#### trim()

Remove espaços vazios, antes e depois da string.

```
var t = "       oi         oi      oi";
alert(t.trim());
```
Saída:
> "oi         oi      oi"


## Conversões

#### Númerico ---> Sttring

Para converter um tipo numérico em string, pode-se usar a função global <b>String()</b> ou o método <b>toString()</b>.

* String()

```
var num = 41.58;
var res = String(num);
```

* toString()

```
var num = 123.12;
var res = num.toString();
```

#### String ----> Numérico

Para converter uma string em um tipo numérico, pode ser usado o método


