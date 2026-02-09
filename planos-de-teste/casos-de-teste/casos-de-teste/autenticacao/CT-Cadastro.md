Estou utilizando um site público para testes funcionais:

Nome: Book Cart Link: https://lnkd.in/dWx5YzWZ

A funcionalidade testada é a tela de Cadastro, conforme imagem enviada, que contém: Campo First name; Campo Last name; Campo User name; Campo Password; Campo Confirm Password; Genêro; Botão de Registro.

Caso de Teste – Cadastro (Credenciais válidas e inválidas)

Objetivo:
- Validar o comportamento da funcionalidade de cadastro de usuário, garantindo:
- Criação de conta com sucesso quando todos os campos obrigatórios são preenchidos corretamente
- Exibição de mensagens de erro apropriadas quando houver dados inválidos ou campos obrigatórios não preenchidos

Pré-requisitos:
- Acesso ao site Book Cart
- Usuário não cadastrado previamente com o mesmo username
- Acesso à página de Login
- Navegador ativo e com conexão à internet

Funcionalidade: Cadastro de usuário no Book Cart

Cenário: Cadastro de usuário com dados válidos
- Dado que o usuário esteja na página de login do Book Cart
- Quando o usuário clicar no botão Register
- E o sistema exibir a tela de cadastro
- E o usuário preencher o campo First name com um valor válido
- E o usuário preencher o campo Last name com um valor válido
- E o usuário preencher o campo User name com um valor válido e não cadastrado
- E o usuário preencher o campo Password com uma senha válida
- E o usuário preencher o campo Confirm Password com a mesma senha informada
- E o usuário selecionar uma opção válida no campo Gender
- E o usuário clicar no botão Register
- Então o sistema deve realizar o cadastro do usuário com sucesso
- E o usuário deve ser redirecionado para a tela de login ou página inicial

Cenário: Cadastro de usuário com dados inválidos ou campos obrigatórios não preenchidos
- Dado que o usuário esteja na página de login do Book Cart
- Quando o usuário clicar no botão Register
- E o sistema exibir a tela de cadastro
- E o usuário deixar de preencher um ou mais campos obrigatórios
- Ou o usuário informar senhas diferentes nos campos Password e Confirm Password
- Ou o usuário informar um User name já cadastrado
- E o usuário clicar no botão Register
- Então o sistema não deve realizar o cadastro do usuário
- E o sistema deve exibir mensagens de erro indicando os campos inválidos ou obrigatórios

<img width="670" height="331" alt="image" src="https://github.com/user-attachments/assets/0532291e-0758-4d89-b61d-16438331762b" />

<img width="670" height="592" alt="image" src="https://github.com/user-attachments/assets/d54edd8f-b975-4785-a911-f9cbebfc936e" />


