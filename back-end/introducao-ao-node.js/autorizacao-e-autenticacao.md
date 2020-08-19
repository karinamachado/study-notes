# Autorização e Autenticação

**Autorização e Autenticação**

Dois outros conceitos que queremos que nossa lógica do lado do servidor trate são _autenticação_ e _autorização_ .

_A autenticação_ é o processo de validação da identidade de um usuário. Uma técnica de autenticação é usar logins com nomes de usuário e senhas. Essas credenciais precisam ser armazenadas com segurança no back-end em um banco de dados e verificadas a cada visita. Os aplicativos da Web também podem usar recursos externos para autenticação. Provavelmente, você se conectou a um site ou aplicativo usando suas credenciais do Facebook, Google ou Github; isso também é um processo de autenticação.

_A autorização_ controla quais usuários têm acesso a quais recursos e ações. Determinadas visualizações do aplicativo, como a página para editar um perfil pessoal de mídia social, são acessíveis apenas para esse usuário. Outras atividades, como excluir uma postagem, costumam ser restritas da mesma forma.

Ao construir um back-end de aplicativo da web robusto, precisamos incorporar autenticação \(quem é esse usuário? Ele é quem afirma ser?\) E autorização \(quem tem permissão para fazer e ver o quê?\) Em nossa lógica do lado do servidor para garantir que estamos criando conteúdo seguro, personalizado e dinâmico.

![](../../.gitbook/assets/nodeanimation_6.gif)

