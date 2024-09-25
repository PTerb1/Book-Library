# Aplicativo React Native Book Library

Este é um aplicativo móvel simples Book Library criado usando React Native. O aplicativo permite que os usuários naveguem por uma lista de livros, pesquisem livros por nome, visualizem detalhes do livro e gerenciem sua biblioteca. Ele também inclui autenticação de usuário com telas de login e registro.

## Introdução

### Pré-requisitos

Antes de começar, certifique-se de ter atendido aos seguintes requisitos:

- Node.js e npm instalados em sua máquina de desenvolvimento.
- Expo CLI instalado globalmente (`npm install -g expo-cli`).
- Um editor de código de sua escolha (por exemplo, Visual Studio Code).
- Um dispositivo móvel ou emulador para testar o aplicativo.

---
## Instalação

### 1. Crie um projeto no Expo

expo init BookLibrary
cd BookLibrary

### 2. Instale essas dependências dentro da pasta
in cmd>>>

npm install @react-navigation/native
npm install @react-navigation/stack
expo install react-native-gesture-handler
npm install @react-navigation/bottom-tabs
npm install @react-navigation/drawer
expo install react-native-gesture-handler react-native-reanimated
expo install react-native-reanimated
npm install react-native-elements --save --force
npm install react-native-vector-icons --save

### 3. Substitua todos os arquivos dentro da sua pasta

### 4. Execute o aplicativo com este comando
expo start --clear

---

## Estrutura do aplicativo

O aplicativo é organizado nas seguintes seções:

1. **Autenticação**: telas de registro e login do usuário.

2. **Página inicial**: exibe uma lista de categorias de livros e permite que os usuários selecionem uma categoria para visualizar os livros.

3. **Livros**: lista livros na categoria selecionada, e os usuários podem clicar em um livro para visualizar seus detalhes.

4. **Detalhes do livro**: mostra informações detalhadas sobre um livro selecionado, incluindo título, autor, descrição, foto da capa e preço.

5. **Pesquisa**: permite que os usuários pesquisem livros por nome.

---

## Tecnologias usadas

- **React Native**: uma estrutura JavaScript para criar aplicativos móveis nativos.

- **Expo**: uma plataforma para criar e implementar aplicativos React Native.

- **Navegação React**: usada para navegação entre telas.
