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

Uma variável pode ser declarada em qualquer parte do código. Porém, uma variável criada dentro de uma função somente pode ser acessada dentro da função (escopo local). Para declarar uma variável usa-se a palavra reservada <b>var</b>.

Exemplos:
```
var valorDoSalario = 1000;
var nomeDoFuncionario = "José";
var dataDeNascimento = "01-02-98";
var num1, num2, num3;

```

### var e let
> var define um escopo local, a variável somente é acessada dentro da função ou bloco de comando
> let tem um escopo mais restrito que var, não pode ser acessada por um bloco superior ao que ela foi declarada.

Exemplo de como uma variável x pode ser acessada com var e com let:
```
function exemplo() {
    //x poderia ser acessado aqui
    for(var x = 0; x < 5; x++) {
        //x existe aqui
    };
    //x está visível aqui novamente
};
function exemplo() {
    //x não existe aqui
    for(let x = 0; x < 5; x++ ) {
        //x existe aqui
    };
    //x não está visível aqui novamente
};
```

### Console.log()

A função console.log() permite que possamos ver uma saída no console do navegador web. Esse console geralmente pode ser consultado pressionando a tecla "F12" com seu navegador aberto.
Uma das principais aplicações do console.log() é a de depuração do código, o programador pode verificar se os comandos estão seguindo um fluxo de interpretação esperado.

```
console.log('recebe uma string');
console.log(oValorDeUmaVariavel);
console.log(aSaidaDeUmaFuncao());

... etc
```

## Janelas de Diálogo

Servem para que o usuário possa interagir com a página web, inserindo informações.

### Alert()

A função <b>alert()</b> mostra um alerta na tela do usuário. Ela recebe uma string, que será exibida assim que a janela for carregada, atualizada, um botão for pressionado ou qualquer outro evento planejado.

Exemplo de um <b>alert()</b> com uma mensagem:

<img src="http://ptgmedia.pearsoncmg.com/imprint_downloads/informit/learninglabs/9780134173719/graphics/01fig02.jpg">

### Confirm() e Prompt()

A função de diálogo <b>confirm()</b> espera uma interação com usuário. Ela espera que o usuário aperte "OK" ou "Cancelar". Caso seja pressionado o botão "OK" é retornado um valor booleano true, caso contrário, é retornado false.

Isso significa que a função <b>confirm()</b> precisa ter seu valor guardado em uma variável.
Exemplo:

```
var resposta = window.confirm("Você gostaria de tomar um sorvete?");

if(resposta == true) {
    window.alert("Ótimo, então vamos!");
} else {
    window.alert("Que pena! Podemos ir em uma outra ocasião.");
}
```

Exemplo de confirm():
<img src="https://dbushell.com/images/2012/02/macosx-confirm1.png">

Já a função <b>prompt()</b> espera uma resposta, porém ela não é limitada à valores booleanos. Ou seja, o usuário pode inserir um valor numérico, uma string, ou qualquer outra informação.

Isso significa que <b>prompt()</b> também retorna um valor e esse valor pode ser guardado em uma variável. Como no exemplo a seguir:

```
var nome = window.prompt("Qual o seu nome? ");
var cidade = window.prompt("Onde você mora? ");

window.alert("Prazer, " + nome + ", de " + cidade);
```
Exemplo:

<img src="https://www.codeproject.com/KB/scripting/JavaScriptConsole/Window.prompt.jpg">






