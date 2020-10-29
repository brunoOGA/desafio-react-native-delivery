<h1 align="center">Desafio: GoRestaurant Mobile</h1>

## Sobre 
A aplicação usa uma fake API, e exibe e filtra os pratos de comida da API e permite a criação de novos pedidos.

## Funcionalidades da aplicação

- Listar os pratos de comida da sua API: A página Dashboard exibe uma listagem, com o campo title, value, e description de todos os pratos de comida que estão cadastrados na API.

- Listar as categorias da sua API: A página Dashboard exibe uma listagem, com o campo title e image_url de todas as categorias que estão cadastrados na sua API.

- Filtrar pratos de comida por busca ou por categorias: A página Dashboard permite que o input de pesquisa e os botões de categoria façam uma busca na API de acordo com o que estiver selecionado ou escrito no input.

- Listar os pedidos da sua API: A página Orders exibe uma listagem, com o campo as informações do produto pedido, com name e description de todos os pedidos que estão cadastrados na sua API.

- Listar os pratos favoritos da sua API: A página Favorites deve ser capaz de exibir uma listagem, com o campo as informações do produto favorito, com name e description de todos os pedidos que estão cadastrados na sua API.

- Realizar um pedido: A página Dashboard, ao clicar em um item, redireciona o usuário para a página FoodDetails, onde é possível realizar um novo pedido, podendo controlar a quantidade desse item pedido, ou adicionar ingredientes extras. Todo o valor é calculado de acordo com a quantidade pedida.
---
## Tecnologias utilizadas
- [React Native](https://reactnative.dev/)
---
## Como baixar o projeto 

```bash
  
  # Clonar o repositório
  $ git clone https://github.com/brunoOGA/desafio-react-native-delivery
  
  # Entrar no diretório
  $ cd desafio-react-native-delivery
  
  # Instalar as dependências
  $ yarn
  
  # Realizar os testes
  $ yarn test
  
  # Iniciar API fake
  yarn json-server server.json -p 3333
  
  # Iniciar o prjeto
  $ yarn start
  
```
