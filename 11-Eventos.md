# Eventos

Os eventos são ações realizadas pelo usuário. Exemplos de eventos são: clicar em um botão, por o mouse em cima de algum elemento da página HTML, clicar e arrastar algum objeto na tela, dentro de outros.

## Eventos de nível 0

São os eventos mais facéis de usar, podendo ser informados dentro do próprio HTML.

<table>
    <tr>
        <th>Evento</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>onblur()</td>
        <td>Quando o elemento perde o foco</td>
    </tr>
    <tr>
        <td>onclick()</td>
        <td>Quando o elemento é clicado</td>
    </tr>
    <tr>
        <td>onchange()</td>
        <td>Quando o elemento é alteredo</td>
    </tr>
    <tr>
        <td>ondblclick()</td>
        <td>O duplo clique do mouse no elemento</td>
    </tr>
    <tr>
        <td>onfocus()</td>
        <td>Quando o elemento está com o mouse em cima</td>
    </tr>
    <tr>
        <td>onkeydown()</td>
        <td>Quando o usuário está pressionando uma tecla</td>
    </tr>
    <tr>
        <td>onkeypress()</td>
        <td>Quando o usuário pressiona uma tecla do teclado</td>
    </tr>
    <tr>
        <td>onkeyup()</td>
        <td>Quando o usuário solta a tecla</td>
    </tr>
    <tr>
        <td>onload()</td>
        <td>Ocorre quando o documento é carregado</td>
    </tr>
    <tr>
        <td>onmousedown()</td>
        <td>Quando o botão do mouse é pressionado</td>
    </tr>
    <tr>
        <td>onmousemove()</td>
        <td>Quando o mouse é movido sobre o elemento</td>
    </tr>
    <tr>
        <td>onmouseover()</td>
        <td>Quando o mouse está sobre o elemento</td>
    </tr>
    <tr>
        <td>onmouseup()</td>
        <td>Quando o botão do mouse é liberado</td>
    </tr>
    <tr>
        <td>onreset()</td>
        <td>Quando o formulário é resetado, os campos do formulário são limpos</td>
    </tr>
    <tr>
        <td>onresize()</td>
        <td>O tamanho da janela é alterado</td>
    </tr>
    <tr>
        <td>onselect()</td>
        <td>Quando é necessário selecionar o texto de um elemento do formulário</td>
    </tr>
    <tr>
        <td>onsubmit()</td>
        <td>Quando o formulário é enviado</td>
    </tr>
    <tr>
        <td>onunload()</td>
        <td>Quando a página é descarregada</td>
    </tr>

</table>


## Eventos de nível 2

Utiliza o método addEventListener() para capturar os eventos. Com esse método é possível capturar mais de um evento ao mesmo tempo.
A sintaxe é:
> objeto.addEventListener("evento", funcao, true ou false);

Primeiro parâmetro: O Evento a ser capturado
Segundo parâmetro: A função a ser chamada pelo evento
