# GoStack-Desafios-Conceitos

## 🚀  Sobre o desafio Node Js


Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no Node.js!

Essa será uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

## 📙 Rotas da aplicação



-   **`POST /repositories`**: A rota deve receber  `title`,  `url`  e  `techs`  dentro do corpo da requisição, sendo a URL o link para o github desse repositório. Ao cadastrar um novo projeto, ele deve ser armazenado dentro de um objeto no seguinte formato:  `{ id: "uuid", title: 'Desafio Node.js', url: 'http://github.com/...', techs: ["Node.js", "..."], likes: 0 }`; Certifique-se que o ID seja um UUID, e de sempre iniciar os likes como 0.
    
-   **`GET /repositories`**: Rota que lista todos os repositórios;
    
-   **`PUT /repositories/:id`**: A rota deve alterar apenas o  `título`, a  `url`  e as  `techs`  do repositório que possua o  `id`  igual ao  `id`  presente nos parâmetros da rota;
    
-   **`DELETE /repositories/:id`**: A rota deve deletar o repositório com o  `id`  presente nos parâmetros da rota;
    
-   **`POST /repositories/:id/like`**: A rota deve aumentar o número de likes do repositório específico escolhido através do  `id`  presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes deve ser aumentado em 1;

## 🚀  Sobre o desafio React Js

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no ReactJS!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend no último desafio utilizando o Node.js.

### Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo  **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

-   **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo  **title**  de todos os repositórios que estão cadastrados na sua API.
    
-   **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto  **Adicionar**  e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.
    
-   **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto  **Remover**  que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.


## 🚀  Sobre o desafio React Native

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no React Native!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend utilizando o Node.js, e no último desafio em ReactJS.

### Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo  **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

-   **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos  **title**,  **techs**  e número de curtidas seguindo o padrão  `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.
    
-   **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto  **Curtir**  e deve atualizar o número de likes na listagem no mobile.
