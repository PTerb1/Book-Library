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

## Captura de tela da IU
<div align="center">
<img src="https://github.com/rihamnazeer/Book-Library/assets/90144970/3298c7d5-0456-42b5-9181-51a73a144e3a" width="220" height="400" />
<img src="https://github.com/rihamnazeer/Book-Library/assets/90144970/c485f2a9-2a99-40a2-99f8-627fc9dfb46e" width="220" height="400" />
<img src="https://github.com/rihamnazeer/Biblioteca-de-livros/ativos/90144970/f3e0ed85-fc99-499e-bc50-8d9f00d9465f" width="220" height="400" />
</div>
<div align="center">
<img src="https://github.com/rihamnazeer/Biblioteca-de-livros/ativos/90144970/79da04cb-a278-4755-9db4-0c34e8d4c760" width="220" height="400" />
<img src="https://github.com/rihamnazeer/Book-Library/assets/90144970/4f5e10b8-cc1a-49c4-8fd1-49377cac9ce4" width="220" height="400" />
<img src="https://github.com/rihamnazeer/Book-Library/assets/90144970/1ca07cf2-8773-4689-8617-5b0f887770f6" width="220" height="400" />
</div>

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