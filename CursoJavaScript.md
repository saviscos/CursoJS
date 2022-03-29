# Front-End
Arquivos que rodam no Navegador

**Como rodar script em javaScript:**

```       
node script.js
```

O tipos de informação que podem ser salvos em variáveis são:

Primitivos:

- undefined -> Não há tipo nem valor

- boolean -> verdadeiro ou falso

- string -> textos

- number -> números

**Complexos:**

- function -> funções

- object -> objetos


**Boleanos**
- var a = true;
- var b = false;

**Number**
- var c = 10;
- var d = 11.5;

**String**
- var e = "teste";

**Undefined**
- var f;
- var g = undefined;

**Function**
- var a = function(){};
- var b = () => {};

**object**
- var c = {};
- var d = []; //array
- var e = null;



## Comentários 

let pra assumir uma variavel assume que ela nao sera reescrita fora da função (do seu escopo)*

let c = 10;
let d = 11.5;

; (ponto e virgula ) --> termina a função

let e = null #variavel nao guarda nenhuma informação

const pi = 3.1415; #assume uma constante que nao muda

#


# Condicionais

Operadores Lógicos

Em programação, condicionais são esturtura de decisões. O código executo de uma maneiro ou de outra a depender de uma condição, 
que por sua vez será interpretada como verdadeiro ou falso. Esse tipo de dado é chamado de booleano e possui valor true ou false. 
Uma condição é uma operação lógica que tem como resultado um valor booleano. Os operadores de comparação em JavaScript são:

![](../Imagem01.png)

If/Else

A estrutura condicional em JavaScript é da seguinte maneira:

```let condicao = x > 0;

if(condicao){
    console.log("X é maior do que zero");
}

else{
    console.log("X é menor ou igual a que zero");
}
```

A condição deve estar entre parêntesis. Para fim de ilustração o resultado condição foi guardada em uma variável (linha 1), porém é prática escrever diretamente dentro dos parêntesis. Caso a condição seja true o código dentro do if é executado, senão o do else é executado.

Ainda é possível fazer estruturas que verifiquem mais de uma condição usando o else if:

```
if(x > 0){
    console.log("X é positivo");
}

else if(x == 0){
    console.log("X é zero");
}

else{
    console.log("X é negativo");
}
```

Caso a condição do if for false, é verificado a condição do else if, se esta por sua vez for falsa é verificado a condição do próximo else if, se houver, senão é executado o else, também se houver.


#Back-End
Servidor