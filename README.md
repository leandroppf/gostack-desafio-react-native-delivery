<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 11: GoRestaurant Mobile
</h3>

<blockquote align="center">“Nada no mundo supera a persistência.”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/leandroppf/gostack-desafio-react-native-delivery?color=%2304D361">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Leandro Pedroso" src="https://img.shields.io/badge/made%20by-Leandroppf-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">

  <a href="https://github.com/leandroppf/gostack-desafio-react-native-delivery/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/leandroppf/gostack-desafio-react-native-delivery?style=social">
  </a>
</p>

## :rocket: Sobre o desafio

Nesse desafio o objetivo era desenvolver uma nova aplicação, a GoRestaurant, só que dessa vez a versão mobile para o cliente. Para esse desafio, foi utilizado React Native junto com TypeScript, para criar um pequeno app para pedidos de comida.

Essa aplicação deve exibir e filtrar os pratos de comida da API e permitir a criação de novos pedidos.

### Layout da aplicação

Essa aplicação possui um layout desenvolvido pela equipe da Rocketseat.

O layout pode ser acessado através da página do Figma, no [seguinte link](https://www.figma.com/file/cHzfYrUBgdzp1XrRuUpggk/GoRestaurant-Mobile?node-id=1603%3A448).

### Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `name`, `value` e  `description` de todos os pratos de comida que estão cadastrados na sua API.

- **`Listar as categorias da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `title` e `image_url` de todas as categorias que estão cadastrados na sua API.

- **`Filtrar pratos de comida por busca ou por categorias`**: Em sua página Dashboard permitir que o input de pesquisa e os botões de categoria façam uma busca na API de acordo com o que estiver selecionado ou escrito no input.

- **`Listar os pedidos da sua API`**: Sua página `Orders` deve ser capaz de exibir uma listagem, com o campo as informações do produto pedido, com `name` e `description` de todos os pedidos que estão cadastrados na sua API.

- **`Listar os pratos favoritos da sua API`**: Sua página `Favorites` deve ser capaz de exibir uma listagem, com o campo as informações do produto favorito, com `name` e `description` de todos os pedidos que estão cadastrados na sua API.

- **`Realizar um pedido`**: Na sua página `Dashboard`, ao clicar em um item, você deve redirecionar o usuário para a página `FoodDetails`, onde será possível realizar um novo pedido, podendo controlar a quantidade desse item pedido, ou adicionar ingredientes extras. Todo o valor deve ser calculado de acordo com a quantidade pedida.

### Específicação dos testes

O template também possui testes automatizados e um dos objetivos é que o código criado passe em todos os testes listados abaixo:

- **`should be able to list the food plates`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua `Dashboard`, todos os pratos de comidas que são retornados da sua fake API.

- **`should be able to list the food plates filtered by category`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua `Dashboard`, os pratos de comidas filtrados por categoria da sua fake API.

- **`should be able to list the food plates filtered by name search`**:  Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua `Dashboard`, os pratos de comidas filtrados por nome da sua fake API.

- **`should be able to navigate to the food details page`**: Para que esse teste passe, em sua `Dashboard`, você deve permitir que ao clicar em um item, seja navegado para a página `FoodDetails` passando por parâmetro da navegação o id do item clicado.

- **`should be able to list the favorite food plates`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua página `Favorites`, todos os pratos de comidas que estão salvos na rota `favorites`.

- **`should be able to list the orders`**: Para que esse teste passe, sua aplicação deve permitir que sejam listados na sua página `Orders`, todos os pratos de comidas que estão salvos na rota `orders`.

- **`should be able to list the food`**: Para que esse teste passe, sua aplicação deve permitir que seja listado todos os dados de uma comída específica na página `FoodDetails`, baseado no id recuperado pelos parametros da rota.

- **`should be able to increment food quantity`**: Para que esse teste passe, você deve permitir que seja incrementada em 1 a quantidade do item na página `FoodDetails`.

- **`should be able to decrement food quantity`**: Para que esse teste passe, você deve permitir que seja decrementada em 1 a quantidade do item na página `FoodDetails`.

- **`should not be able to decrement food quantity below than 1`**: Para que esse teste passe, você deve impedir que seja decrementado a quantidade de itens até um número menor que 1, assim o número mínimo de itens no pedido é 1.

- **`should be able to increment an extra item quantity`**: Para que esse teste passe, você deve permitir que seja incrementada em 1 a quantidade de um ingrediente extra na página `FoodDetails` baseado no seu id.

- **`should be able to decrement an extra item quantity`**: Para que esse teste passe, você deve permitir que seja decrementado em 1 a quantidade de um ingrediente extra na página `FoodDetails` baseado no seu id.

---

Desafio concluído no dia 21/08/2020 por Leandro Pinto Pedroso Filho
