---
description: >-
  Esse gitbook é o meu caderno de estudos, resumo de conteúdo de cursos,
  tutoriais, livros e artigos referente a linguagem JavaScript.
---

# JavaScript

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

### **Evita Repetições**

```javascript
var preco = 20;
var quantidade = 5;
var precoTotal = preco * quantidade;
```

## Sem Valor

Pode declarar ela e não atribuir valor inicialmente.

```javascript
var precoCurso; // retorna undefined
```







