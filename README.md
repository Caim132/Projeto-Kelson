# 📱 Projeto Mobile - Gerenciador de Cursos

Este é um aplicativo mobile desenvolvido com **React Native** que permite o gerenciamento de cursos, incluindo autenticação de usuários, visualização de cursos e perfil pessoal. O projeto utiliza **Firebase** como backend para autenticação e banco de dados.

## 🚀 Funcionalidades

- ✅ Cadastro e login de usuários
- ✅ Listagem de cursos
- ✅ Visualização de detalhes de cada curso
- ✅ Criação e edição de cursos
- ✅ Perfil do usuário
- ✅ Logout

## 🧭 Telas do Aplicativo

### 🔐 Login (`LoginScreen.js`)
- Tela de autenticação com e-mail e senha.
- Link para criação de nova conta.

### 📝 Cadastro (`RegisterScreen.js`)
- Formulário para registrar novos usuários.
- Campos: nome, e-mail, senha e confirmação.

### 🏠 Home (`HomeScreen.js`)
- Exibe uma lista de cursos disponíveis.
- Acesso aos detalhes dos cursos.

### 📄 Detalhes do Curso (`DetailsScreen.js`)
- Mostra informações completas de um curso selecionado.

### ➕ Formulário de Curso (`CursoFormScreen.js`)
- Adiciona ou edita informações de um curso.
- Campos para título, descrição, entre outros.

### 👤 Perfil (`ProfileScreen.js`)
- Mostra os dados do usuário logado.
- Opção para logout.

## 🔧 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Firebase Authentication](https://firebase.google.com/products/auth)
- [Firebase Firestore](https://firebase.google.com/products/firestore)
- [React Navigation](https://reactnavigation.org/)
- Context API

## ▶️ Como Executar o Projeto

1. Clone este repositório:
   ```
   git clone https://github.com/seu-usuario/projetomobile-main.git
Instale as dependências:

npm install
Configure o Firebase:

Altere o arquivo src/config/firebaseConfig.js com suas credenciais do Firebase.

Execute o app:

npx expo start
💡 Este projeto foi criado com Expo. Certifique-se de ter o Expo CLI instalado globalmente (npm install -g expo-cli).

📄 Licença
Este projeto está licenciado sob a MIT License.
