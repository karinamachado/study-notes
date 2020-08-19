---
description: Front-End X Back-end
---

# Front-End x Back-End

Nesta lição, explicaremos o que constitui o back-end de um aplicativo da Web ou site. O back-end pode parecer muito abstrato, mas fica mais claro quando o explicamos em termos de front-end! Para simplificar um pouco, o front-end são as partes de uma página da Web com as quais um visitante pode interagir e ver.

Várias ferramentas e estruturas podem ser usadas para criar uma página da web, mas, em seu núcleo, o front-end é composto de JavaScript, CSS, HTML e outros _ativos estáticos_ , como imagens ou vídeos. Ativos estáticos são arquivos que não mudam. Quando um visitante navega para uma página da web, esses ativos são enviados ao navegador.

Visitar um site simples é como fazer um pedido de entrega em um restaurante: fazemos um pedido de nossa refeição e, uma vez entregue, a temos em total posse. Nessa analogia, podemos pensar no front-end como tudo o que é entregue com a entrega: os recipientes, os utensílios e a própria comida.

Às vezes, você ouvirá o desenvolvimento de front-end referido como desenvolvimento do _lado do cliente_ . Nosso instinto pode ser pensar no cliente como o visitante humano ou usuário de um site, mas quando nos referimos ao cliente no desenvolvimento da web, normalmente nos referimos ao solicitante não humano de conteúdo. No caso de uma visita a um site, o cliente é o navegador, mas em outras circunstâncias, um cliente pode ser outro aplicativo, um dispositivo móvel ou mesmo um aparelho “inteligente”!

Enquanto o front-end é a parte do site que chega ao navegador, o back-end consiste em todos os processos e dados nos bastidores que fazem um site funcionar e enviar recursos aos clientes.

![](../../.gitbook/assets/nodebackendfrontend_update_1-2-.gif)

**O servidor web**

Falamos sobre como o front-end consiste nas informações enviadas a um cliente para que um usuário possa ver e interagir com um site, mas de onde vêm as informações? A resposta é um _servidor web_ .

A palavra “servidor” pode significar muitas coisas na computação, mas vamos nos concentrar em servidores da web especificamente. Um _servidor da web_ é um processo executado em um computador que escuta as solicitações de informações recebidas pela Internet e envia respostas. Cada vez que um usuário navega para um site em seu navegador, o navegador faz uma solicitação ao servidor da web desse site. Cada site tem pelo menos um servidor web. Uma grande empresa como o Facebook tem milhares de computadores poderosos rodando servidores web em instalações localizadas em todo o mundo que estão ouvindo solicitações, mas também poderíamos operar um servidor web simples em nosso próprio computador!

O formato específico de uma solicitação \(e a resposta resultante\) é chamado de _protocolo_ . Você deve estar familiarizado com o protocolo usado para acessar sites: HTTP. Quando um visitante navega para um site em seu navegador, da mesma forma como alguém faz um pedido de entrega, ele faz [uma solicitação HTTP](https://www.codecademy.com/articles/http-requests) para os recursos que compõem esse site.

Para os sites mais simples, um cliente faz uma única solicitação. O servidor da web recebe essa solicitação e envia ao cliente uma resposta contendo tudo o que é necessário para visualizar o site. Isso é chamado de _site estático_ . Isso não significa que o site não seja interativo. Tal como acontece com os ativos estáticos individuais, um site é estático porque, uma vez que esses arquivos são recebidos, eles não mudam ou se movem. Um site estático pode ser uma boa escolha para um site pessoal simples com uma pequena biografia e fotos de família. Um usuário navegando no Twitter, no entanto, deseja acessar o novo conteúdo à medida que ele é criado, o que um site estático não poderia fornecer.

Um site estático é como pedir comida para viagem, mas os aplicativos da web modernos são como jantar pessoalmente em um restaurante. Um cliente de restaurante pode pedir bebidas, pratos diferentes, fazer substituições ou fazer perguntas ao garçom. Para atingir esse nível de complexidade, um back-end igualmente complexo é necessário.



