# Acessando o Objeto de Processo

Na ciência da computação, um _processo_ é a instância de um programa de computador que está sendo executado. Você pode abrir o Gerenciador de Tarefas se estiver em uma máquina Windows ou o Monitor de Atividades de um Mac para ver informações sobre os vários processos em execução no seu computador agora. O Node possui um `process`objeto global com métodos úteis e informações sobre o processo atual.

A `process.env`propriedade é um objeto que armazena e controla informações sobre o ambiente no qual o processo está sendo executado. Por exemplo, o `process.env`objeto contém uma `PWD`propriedade que contém uma string com o diretório no qual o processo atual está localizado. Pode ser útil ter alguma `if/else`lógica em um programa, dependendo do ambiente atual - um aplicativo da web em uma fase de desenvolvimento pode executar tarefas diferentes do que quando está ao vivo para os usuários. Poderíamos armazenar essas informações no `process.env`. Uma convenção é adicionar uma propriedade a `process.env`com a chave `NODE_ENV`e um valor de `production`ou `development`.

```text
if (process.env.NODE_ENV === 'development'){
  console.log('Testing! Testing! Does everything work?');
}
```

O `process.memoryUsage()`retorna informações sobre as demandas de CPU do processo atual. Ele retorna uma propriedade semelhante a esta:

```text
{ rss: 26247168,
  heapTotal: 5767168,
  heapUsed: 3573032,
  external: 8772 }
```

_Heap_ pode significar coisas diferentes em contextos diferentes: um heap pode se referir a [uma estrutura de dados específica](https://en.wikipedia.org/wiki/Heap_%28data_structure%29) , mas também pode se referir a um bloco de [memória](https://en.wikipedia.org/wiki/Memory_management) do [computador](https://en.wikipedia.org/wiki/Memory_management) . `process.memoryUsage().heapUsed`retornará um número que representa quantos bytes de memória o processo atual está usando.

A `process.argv`propriedade contém uma matriz de valores de linha de comando fornecidos quando o processo atual foi iniciado. O primeiro elemento na matriz é o caminho absoluto para o Node, que executou o processo. O segundo elemento da matriz é o caminho para o arquivo em execução. Os seguintes elementos serão quaisquer argumentos de linha de comando fornecidos quando o processo foi iniciado. Os argumentos da linha de comando são separados uns dos outros por espaços.

```text
node myProgram.js testing several features
```

```text
console.log(process.argv[3]); // Prints 'several'
```

Cobrimos apenas algumas das propriedades do `process`objeto, portanto, certifique-se de verificar a [documentação do `process`objeto](https://nodejs.org/api/process.html) para aprender mais sobre ele e explorar alguns de seus outros métodos e propriedades.

Vamos praticar o uso do `process`objeto!

