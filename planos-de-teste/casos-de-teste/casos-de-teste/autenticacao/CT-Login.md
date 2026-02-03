Estou utilizando um site público para testes funcionais:

Nome: Book Cart
Link: https://lnkd.in/dWx5YzWZ

A funcionalidade testada é a tela de Login, conforme imagem enviada, que contém:
Campo Username;
Campo Password;
Botão Login.

Caso de Teste – Login (Credenciais válidas e inválidas)

Objetivo:
- Validar o comportamento da funcionalidade de login ao inserir credenciais válidas e inválidas, garantindo:
- Acesso correto do usuário autenticado;
- Exibição de mensagens de erro apropriadas em tentativas inválidas.

Pré-requisitos:
- Usuário com cadastro válido no site Book Cart;
- Acesso à página de login;
- Navegador ativo e com conexão à internet.

Funcionalidade: Login de usuário no Book Cart

Cenário: Login com credenciais válidas.
    - Dado que o usuário esteja na página de login do Book Cart
    - Quando o usuário preencher o campo Username com um usuário válido
    - E o usuário preencher o campo Password com uma senha válida
    - E o usuário clicar no botão Login
    - Então o sistema deve autenticar o usuário com sucesso
    - E o usuário deve ser redirecionado para a página inicial

Cenário: Login com credenciais inválidas
    - Dado que o usuário esteja na página de login do Book Cart
    - Quando o usuário preencher o campo Username ou Password com dados inválidos
    - E o usuário clicar no botão Login
    - Então o sistema não deve autenticar o usuário
    - E o sistema deve exibir uma mensagem de erro informando credenciais inválidas

<img width="1914" height="478" alt="image" src="https://github.com/user-attachments/assets/15cfcc90-9d56-444a-8fba-f42bb54fd3e7" />

