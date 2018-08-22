# Trabalhando com variáveis em Javascript

Um dos principais papéis das variáveis é permitir que nós possamos trabalhar com dados. Permitir que sejam armazenados informações, mostrar dados na tela do usuários, enviar, através de formulários, valores para armazenamento em bancos de dados. Permitir que dados sejam manipulados. Dentre outras finalidades.

## Nomeclatura 
A restrição na nomeclatura de variáveis se resume a iniciar seus nomes com caracteres, cifrão ou sublinhado. Não é permitido usar acentos.
Geralmente é usado a técnica CamelCase, que define que se a variável possuir um nome composto, a separação entre esses nomes deve ser feito através da alternância das caixas dos caracteres. Por exemplo:
```
_nomeVariavel   (com camel case)
_nomevariavel   (sem camel case)
$NomeVariavel   (com camel case)
$nomevariavel   (sem camel case)
$_nome-variavel (sem camel case)
```

## Declarando Variáveis

Uma variável pode ser declarada em qualquer parte do código. Porém, uma variável criada dentro de uma função somente pode ser acessada dentro da função. Para declarar uma variável usa-se a palavra reservada <b>var</b>.

Exemplos:
```
var valorDoSalario = 1000;
var nomeDoFuncionario = "José";
var dataDeNascimento = "01-02-98";
var num1, num2, num3;

```


