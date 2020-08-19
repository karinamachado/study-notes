# The Node REPL

LEARN NODE.JS

**The Node REPL**

[REPL](https://en.wikipedia.org/wiki/Read%E2%80%93eval%E2%80%93print_loop) is an abbreviation for **r**ead–**e**val–**p**rint **l**oop. It’s a program that **l**oops, or repeatedly cycles, through three different states: a **r**ead state where the program **r**eads input from a user, the **e**val state where the program **e**valuates the user’s input, and the **p**rint state where the program **p**rints out its evaluation to a console. Then it **l**oops through these states again.

When you install Node, it comes with a built-in JavaScript REPL. You can access the REPL by typing the command `node` \(with nothing after it\) into the terminal and hitting enter. A `>` character will show up in the terminal indicating the REPL is running and prompting your input. The Node REPL will evaluate your input line by line.

By default, you indicate the input is ready for eval when you hit enter. If you’d like to type multiple lines and then have them evaluated at once you can type `.editor` while in the REPL. Once in “editor” mode, you can type CONTROLD when you’re ready for the input to be evaluated. Each session of the REPL has a single shared memory; you can access any variables or functions you define until you exit the REPL.

A REPL can be extremely useful for performing calculations, learning a language, and developing code. It’s a place where you can explore language features and try things out while receiving immediate feedback. Figuring out how to do this outside of the browser or a website can be really empowering.

The Node environment contains a number of Node-specific global elements in addition to those [built into the JavaScript language](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects). Every Node-specific global property sits inside the [the Node `global` object](https://nodejs.org/api/globals.html). This object contains a number of useful properties and methods that are available anywhere in the Node environment.

Let’s try out the Node REPL. This will be a good way for you to explore the Node `global` object!

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

