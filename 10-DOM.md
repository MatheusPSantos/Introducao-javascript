# Document Object Model

É uma estrutura de árvore, no qual podemos acessar os elementos de documentos HTML. O objeti <b>document</b> é o nó raiz e nó pai de todos os outros elementos do documento HTML.

Por meio de todas as propriedades e métodos do objeto document, é possível acessar todos os objetos de nó, de dentro do Javascript.

## getElementByIDd()

Captura um elemento pelo seu ID.

Exemplo de código:
```
function mudarConteudo() {
    document.getElementById("exemplo").innerHTML = "Olá Mundo";
}
```

## getElementsByClassName()

Captura todos os elementos que pertencem à alguma classe específica. É retornado um array com o conteúdo de todos os elementos com a classe especificada.

Exemplo:
HTML:
```
<p class="exemplo">Primeiro elemento com a classe exemplo</p>
<p class="exemplo">Segundo elemento com a classe exemplo</p>
```

Javascript:
```
function mudaConteudo() {
    var txt = document.getElementsByClassName("exemplo");
    var x;

    for(x = 0; x < txt.length; x++) {
        if(x==0) {
            txt[0].innerHTML = "Olá Mundo";
        } else {
            txt[1].innerHTML = "Segundo Olá Mundo";
        }
    }
}
```

## getElementsByName()

Captura todos os elementos com o atributo <b>name</b> especificado.

## getElementsByTagName()

Captura os elementos com a tag especificada.


## Criando Elementos

É possível criar e acessar elementos do DOM dinamicamente.

## Método appendChild()

Serve para criar elementos.

* createElemet()
Cria um novo elemento

* createTextNode()
Para criar um texto html para a tag criada por createElement()

* appendChield()
Adicionar o novo elemento no DOM

## Removendo Elementos

* removeChild()
Remover um elemento do DOM
