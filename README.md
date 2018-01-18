# Chat com Firebase Realtime Database

Exemplo muito simples  de como fazer um chat com Firebase e Vanilla Javascript


## Instruções

- abra o [site do Firebase](firebase.google.com)
- cadastre-se/faça o login
- no painel de controle do Firebase crie um novo projeto
- clique em "Add Firebase to your web app" para visualizar as chaves de configuração do seu projeto
- copie e cole as propriedades do objeto `config` (apiKey, authDomain, etc) referentes ao seu projeto na index.html

## Para emular um usuário autenticado

- Abra o console do Developer Tools do seu navegador `ctrl` + `shift` + `i` (no Chrome)
- Adicione o registro `user_id` no Local Storage rodando o comando localStorage.setItem('user_id', 'nome_do_usuário')
- Teste em 2 navegadores diferentes (Chrome e Firefox, por exemplo)
