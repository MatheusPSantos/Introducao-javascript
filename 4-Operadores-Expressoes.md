# Operadores e expressões

Javascript possui os seguintes operadores:
* Operadores de atribuição
* Operadores de comparação
* Operadores aritméticos
* Operadores bit a bit
* Operadores lógicos
* Operadores unários
  
## Operadores de atribuição

Atribuem valores a uma variável, por exemplo var n = 19. Existem os seguintes operadores na linguagem.

<table>
    <tr>
        <th>Operador</th>
        <th>Significado</th>
    </tr>
    <tr>
        <td>x*= y</td>
        <td>Multiplica o operando da esquerda pelo operando da direita</td>
    </tr>
    <tr>
        <td>x/=y</td>
        <td>Divide o operando da esquerda pelo operando da direita</td>
    </tr><tr>
        <td>x += y</td>
        <td>Soma o operando da esquerda pelo operando da direita</td>
    </tr><tr>
        <td>x-=y</td>
        <td>Subtrai o operando da esquerda pelo operando da direira</td>
    </tr><tr>
        <td>x %= y</td>
        <td>O resultado é o resto da divisão do operando da esquerda pelo operando da direita</td>
    </tr><tr>
        <td>x <<= y</td>
        <td>Deslocamento bit a bit à esquerda</td>
    </tr><tr>
        <td>x >>= y</td>
        <td>Deslocamento bit a bit à direita</td>
    </tr><tr>
        <td>x >>>= y</td>
        <td>Deslocamento bit a bit sem sinal</td>
    </tr><tr>
        <td>x &= y</td>
        <td>AND bit a bit</td>
    </tr><tr>
        <td>x ^= y</td>
        <td>XOR bit a bit</td>
    </tr><tr>
        <td>x |= y</td>
        <td>OR bit a bit</td>
    </tr>
</table>

## Operadores de comparação

Esses operadores retornam valores booleanos, true ou false. São operadores binários.

<table>
    <tr>
        <th>Operador</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>==</td>
        <td>Igual: retorna true se os operandos forem iguais</td>
    </tr>
    <tr>
        <td>!=</td>
        <td>Diferente: retorna false se os operandos forem diferentes</td>
    </tr>
    <tr>
        <td>===</td>
        <td>Estritamente igual: retorna true se os operandos são iguais em valores e tipo</td>
    </tr>
    <tr>
        <td>!==</td>
        <td>Estritamente diferente: retorna false se os operandos são diferentes, em valores e tipos</td>
    </tr>
    <tr>
        <td>></td>
        <td>Maior que: retorna true se o operando da esquerda for maior que o da direita</td>
    </tr>
    <tr>
        <td><</td>
        <td>Menor que: retorna true se o operando da esquerda for menor que o da direita</td>
    </tr>
    <tr>
        <td>>=</td>
        <td>Maior ou igual: retorna true se o operando da esquerda for maior ou igual ao da direita</td>
    </tr>
    <tr>
        <td><=</td>
        <td>Menor ou igual: retorna true se o operando da esquerda for menor ou igual ao da direita</td>
    </tr>
</table>

## Operadores aritméticos

São os famosos operadores da matemática:
* adição (+)
* subtração (-)
* multiplicação (*)
* divisão (/)

## Operadores Bit a Bit

Tratam seus operandos como bit (32 bits)

<table>
    <tr>
        <th>Operador</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>a & b</td>
        <td>AND bit a bit</td>
    </tr>
    <tr>
        <td>|</td>
        <td>OR bit a bit</td>
    </tr>
    <tr>
        <td>^</td>
        <td>XOR bit a bit</td>
    </tr>
    <tr>
        <td>~</td>
        <td>NOT bit a bit</td>
    </tr>
    <tr>
        <td><<</td>
        <td>Deslocamento à esquerda</td>
    </tr>
    <tr>
        <td>>></td>
        <td>Deslocamento à direita</td>
    </tr>
</table>


## Operadores Lógicos

<table>
    <tr>
        <th>Operador</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>&&</td>
        <td>AND - retorna true se ambas expressões forem verdadeiras</td>
    </tr>
    <tr>
        <td>||</td>
        <td>OR - retorna false somente quando as duas expressões são falsas</td>
    </tr>
    <tr>
        <td>!</td>
        <td>NOT - inverte o valor booleano</td>
    </tr>
</table>

## Operadores Unários

São unários pois atuam em cima de um operando.

<table>
    <tr>
        <th>Operador</th>
        <th>Descrição</th>
    </tr>
    <tr>
        <td>++</td>
        <td>Incrementa 1 ao operando</td>
    </tr>    
    <tr>
        <td>--</td>
        <td>Decrementa 1 ao operando</td>
    </tr>    
    <tr>
        <td>-</td>
        <td>Altera o valor do operando para um valor negativo</td>
    </tr></table>