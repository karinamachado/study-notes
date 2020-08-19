# The Node REPL

APRENDA NODE.JS O Nó REPL REPL é uma abreviatura de loop read – eval – print. É um programa que efetua loops, ou ciclos repetidos, através de três estados diferentes: um estado de leitura onde o programa lê a entrada de um usuário, o estado de avaliação onde o programa avalia a entrada do usuário e o estado de impressão onde o programa imprime sua avaliação para um console. Em seguida, ele percorre esses estados novamente.

Quando você instala o Node, ele vem com um REPL JavaScript integrado. Você pode acessar o REPL digitando o nó de comando \(sem nada depois dele\) no terminal e pressionando enter. Um caractere&gt; aparecerá no terminal indicando que o REPL está em execução e solicitando sua entrada. O Node REPL avaliará sua entrada linha por linha.

Por padrão, você indica que a entrada está pronta para avaliação quando você pressiona enter. Se desejar digitar várias linhas e, em seguida, avaliá-las de uma vez, você pode digitar .editor enquanto estiver no REPL. Uma vez no modo “editor”, você pode digitar CONTROLD quando estiver pronto para a entrada a ser avaliada. Cada sessão do REPL possui uma única memória compartilhada; você pode acessar quaisquer variáveis ​​ou funções que definir até sair do REPL.

Um REPL pode ser extremamente útil para realizar cálculos, aprender uma linguagem e desenvolver código. É um lugar onde você pode explorar os recursos da linguagem e experimentar coisas enquanto recebe feedback imediato. Descobrir como fazer isso fora do navegador ou de um site pode ser muito estimulante.

O ambiente do Node contém vários elementos globais específicos do Node, além daqueles integrados à linguagem JavaScript. Cada propriedade global específica do Node fica dentro do objeto global do Node. Este objeto contém várias propriedades e métodos úteis que estão disponíveis em qualquer lugar no ambiente do Node.

Vamos experimentar o Node REPL. Esta será uma boa maneira de explorar o objeto global Node!

#### Instructions

**1.**

Let’s enter the Node REPL. Type `node` in the terminal and press enter.**2.**

Experiment on your own within the REPL to get a better sense of it. Here are some suggestions for things to try:

* Access the `global` object. You can `console.log(global)` or, since the REPL displays the return of each evaluated line, simply type `global` and then enter.
* Woah… it looks huge. A lot of that is because of the `global.process` object. Check out an easier to read list of the properties on the `global` object with `Object.keys(global)`.
* The `global` object has a lot of useful properties and methods, and it’s not common to add any to it. However, it is just an object, so we can! Add a property to the `global` object, eg. `global.cat = 'meow!'`.
* Now print or return the property you just added:

  ```text
  > console.log(global.cat)
  'meow!'
  ```

* If you’re familiar with running JavaScript on the browser, you’ve likely encountered the `Window` object. Here’s one major way that Node differs: try to access the `Window` object \(this will throw an error\). The `Window` object is the JavaScript object in the browser that holds the DOM, since we don’t have a DOM here, there’s no `Window` object.

You’ll learn more about the `global` object as you explore Node, but remember that, at its core, it’s just a JavaScript object!

