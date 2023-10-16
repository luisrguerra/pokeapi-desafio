# Desafio Pokedex utilizando pokeapi.co

![screenshot](screenshot.png)

Neste desafio você irá terminar de implementar o funcionamento da Pokedex utilizando o serviço pokeapi.co para conseguir as informações e imagens do Pokémon.

### PokeApi

### [Link da documentação do pokeapi.co](https://pokeapi.co/docs/v2)

Você poderá utilizar a seguinte url da api para pegar a lista de todos os pokémons:
```
https://pokeapi.co/api/v2/pokemon/?offset=0&limit=1292
```
O parâmetro "offset" define a partir de qual pokémon começará a lista(array) de pokémons que deseja receber. Já o parâmetro "limit" define até qual número de pokémon você irá receber nessa lista. Esses parâmetros foram criados com o objetivo de reduzir o consumo de dados ao carregar uma grande quantidade de informações. Como a quantidade de pokemons máxima de 1292 é considerada pequena para quantidade de processamento do computador e velocidade da rede. Não é considerado um problema carregar todos os pokémons de uma vez nesse caso. No entanto, em uma situação em que houvesse um milhão de pokémons, isso poderia se tornar um problema. Se você não utilizar os parametros "offset" e "limit" a api "https://pokeapi.co/api/v2/pokemon/" irá retornar somente 20 pokémons por padrão, o que é uma quantidade muito pequena para esse desafio. Esse recurso de limitar o número de resultados em uma api se chama paginação ou pagination.

### [Exemplo de resultados da API](exemplo.md)

### Fetch

Para conseguir utilizar a api você pode utilizar a função fetch nativa do Javascript.

### [Link da documentação do Fetch API no w3schools](https://www.w3schools.com/jsref/api_fetch.asp)
### [Link da documentação do Fetch API da Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API)
### [Tutorial do Fetch API Devmedia](https://www.devmedia.com.br/javascript-fetch/41206)

Tambem será necessário utilizar o JSON.stringify() para converter os dados fornecido pela api para objeto javascript.

### [Link da documentação do JSON.stringify() no w3schools](https://www.w3schools.com/jsref/jsref_stringify.asp)
### [Link da documentação do JSON.stringify() da Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/stringify)


### Sugestões de extensões para o Visual Studio Code
- Live Server - permite visualizar o arquivo html atualizando automáticamente toda vez que uma alteração for salva