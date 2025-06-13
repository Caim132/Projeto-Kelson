# Apresentação do Projeto
Este é um aplicativo mobile com funcionalidades de autenticação de usuários e gerenciamento de cursos. Ele permite aos usuários criarem contas, fazerem login, visualizarem cursos e detalhes, e gerenciarem seu perfil. A aplicação utiliza React Native e a navegação é feita com o React Navigation. O backend e a autenticação são providos pelo Firebase.

Funcionamento das Telas
1. LoginScreen.js
-Tela de login onde o usuário informa e-mail e senha.

Validações básicas.

-Botão para redirecionar para a tela de registro.

-Ao logar com sucesso, o usuário é redirecionado para a HomeScreen.

RegisterScreen.js

-Tela para criação de conta.
-Campos: nome, e-mail, senha e confirmação de senha.
-Criação do usuário via Firebase Authentication.
-Após cadastro, redireciona para a tela de login.

3. HomeScreen.js

-Tela inicial após login.
-Mostra lista de cursos (possivelmente com dados do Firebase Firestore).
-A partir daqui o usuário pode acessar a tela de detalhes do curso.

4. DetailsScreen.js

-Mostra os detalhes de um curso selecionado.
-Exibe informações como título, descrição e talvez uma imagem.

5. CursoFormScreen.js

-Tela para adicionar ou editar um curso.
-Formulário com campos para nome, descrição, etc.
-Utiliza Firebase para armazenar os dados.

6. ProfileScreen.js

-Exibe dados do usuário logado.
-Pode conter botão para logout e editar informações.

