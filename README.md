---
description: >-
  Esse gitbook é o meu caderno de estudos, resumo de conteúdo de cursos,
  tutoriais, livros e artigos referente a linguagem JavaScript.
---

# JavaScript

### **O que é JavaScript**

JavaScript é uma linguagem de programação interpretada, isso significa que você escreve o seu programa em um arquivo .js e abre esse arquivo em um navegador ou no node.js, ele automaticamente vai ser interpretado, diferente de uma linguagem compilada que primeiro tem que compilar o código para depois executar.\(exemplo developer tools\).  
  
JavaScript está entre as linguagens de programação mais poderosas e flexíveis da web.  
  
_**Obs: JavaScript , não é Java.**_

**Sintaxe básica:**

```javascript
const nome: "karina";

function somar(a, b) {
    return a + b;
}

somar(2,4);

//resultado 6
```

### **O que podemos fazer com JavaScript?**

  
****O JavaScript foi criado para aplicações Front-End, onde faz a manipulação do DOM e comunicação assíncrona com o back-end.   
  
A linguagem permite que  você desenvolva vários tipos de projetos, desde os mais simples e complexos como:   
Games, Websites, Aplicações web 

### Tipos de Dados

O JavaScript tem seis tipos de dados primitivos:

* **Boolean:** armazena dois valores, true \(verdadeiro\) ou false \(falso\).
* **Number:** armazena números inteiros, decimais ou hexadecimais.
* **String:** armazena texto. Pode estar entre aspas simples \(’ '\), asplas duplas \("" “”\) ou backticks  \(\` \`\), ou seja os acentos graves.
* **Undefined:** quando não há nenhum valor atribuído.
* **Null:** armazena um valor vazio.
* **Symbol:** usado para realizar operações em objetos.

```javascript
var nome = 'Curso de JavaScript'; // String
var idade = 28; // Number
var alunoStart = true; // Boolean var time; // Undefined
var comida = null; // Null
var simbolo = Symbol() // Symbol
var novoObjeto = {} // Object
```

**\*Obs**: _Sobre  os backticks: Implementando esse tipo de dados, permite fazer interpolação de strings que permite colocar uma variável dentro do backticks._

```javascript
var nome = 'Amanda';
console.log( ` o nome da membro é: ${nome}`);
```

 Tipo de dado não primitivo:  tipo de dado imutável.

* **Object:** É um conjunto de chaves e valores

### **Variáveis**

Responsáveis por guardar dados na memória, onde podem ser armazenados valores de diferentes tipos que podem ser números inteiros, reais, strings, booleanos, entre outros.  
  
A diferença entre **var** e **let** tem a ver com escopo vou abordar mais na frente,  Já **const**, de constante, não pode ter o seu valor modificado depois que for atribuído uma vez, ao contrário do var e let que podem ser modificados a qualquer hora.

 Ex: Sintaxe para declarar uma variável, pode iniciar com a palavra **var, let ou const**. 

```javascript
var nome = 'Amanda';
let idade = 35;
const membroComunidade = true;
```

Você pode criar mais de uma variável, sem repetir a palavra chave var.

```javascript
var nome = 'Amanda',
    idade = 35,
    membroComunidade = true;
```

Vamos chamar essa variáveis no console do navegador para visualizar os valores.

![](.gitbook/assets/captura-de-tela-2020-04-10-a-s-09.48.44%20%281%29.png)

```javascript
console.log(nome, idade, membroComunidade);
```

### **Evita Repetições**

```javascript
var preco = 20;
var quantidade = 5;
var precoTotal = preco * quantidade;
```

### Sem Valor

Pode declarar sem atribuir nenhum valor.

```javascript
var precoCurso; // retorna undefined
```







