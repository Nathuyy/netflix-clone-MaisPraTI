# 🍿 Projeto Netflix Clone

Este projeto é uma reprodução da interface da Netflix usando React, com integração à API do `The Movie Database (TMDb)`. Nele, você pode visualizar uma seleção de filmes e séries, assistir trailers, e adicionar títulos à sua lista pessoal.

## 🛠️ Tecnologias Utilizadas

* **React**: Biblioteca JavaScript para construção de interfaces de usuário.

* **CSS**: Estilização dos componentes para uma interface atraente e responsiva.
* **TMDb API**: Integração com a API do TMDb para obtenção de informações sobre filmes e séries.
* **React Player**: Componente para reprodução de vídeos, utilizado para exibir trailers.
* **Fetch API**: Para realizar as requisições à API do TMDb.

## 📁 Estrutura do Projeto

O projeto está organizado da seguinte forma

```sh
src/
├── api/              
├── components/ 
├── App.js     
├── index.js    
├── Banner.css         
├── Nav.css    
├── Row.css          
└── App.css
```

🚀 Funcionalidades

* **Banner Aleatório**: Exibe um filme ou série aleatória em destaque.

* **Navegação Dinâmica**: Menu que altera a cor conforme a rolagem da página.
* **Listagem de Filmes e Séries**: Diferentes categorias de filmes e séries são exibidas em linhas.
* **Trailers**: Clique em um filme ou série para assistir ao trailer diretamente na página.

## 🔧 Como Executar o Projeto

Clone o repositório:
```sh
git clone https://github.com/Nathuyy/netflix-clone-MaisPraTI
```

Navegue até o diretório do projeto

```sh
cd netflix-clone-MaisPraTI
```

Instale as dependências

```sh
npm install
```

Obtenha sua API key no TMDb e adicione-a ao arquivo `api.js`:

```sh
const API_KEY = 'SUA_API_KEY_AQUI';
```

Execute o projeto:

```sh
npm start
```

Acesse o projeto em seu navegador

```sh
http://localhost:3000
```

## 📄 Licença
Este projeto está licenciado sob os termos da MIT License.

## 🤝 Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests.