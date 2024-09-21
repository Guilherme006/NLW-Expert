## Sobre o Projeto

Este é um projeto de aplicativo de e-commerce desenvolvido em TypeScript e React Native, utilizando o Expo para a construção de interfaces responsivas. O objetivo deste projeto é fornecer uma experiência de compra fluida, com funcionalidades como seleção de produtos, gerenciamento de carrinho e navegação entre categorias de forma dinâmica.

Este projeto usa o NativeWind, uma implementação do Tailwind CSS para React Native, para fornecer classes utilitárias de estilos, facilitando o desenvolvimento responsivo e bem estruturado.

![nlw-expert-image]

### Construído com

![visual-studio-code]
![React Badge]
![React Router Badge]
![TypeScript Badge]
![Tailwind CSS Badge]
![Expo Badge]

### Funcionalidades

#### Carrinho de Compras

O aplicativo possui um carrinho de compras que pode ser gerenciado de duas maneiras:

- **cart-in-memory.tsx:** Armazena o estado do carrinho na memória temporária.
- **cart-store.tsx:** Gerencia o estado do carrinho de forma mais persistente, permitindo manipulação global do estado.

#### Roteamento Dinâmico

O arquivo [id].tsx permite que a aplicação lide com páginas dinâmicas, como exibir detalhes de um produto ou categoria específicos, com base no identificador (id) da URL.

#### Formatação de Moeda

A função format-currency.tsx é utilizada para formatar os preços dos produtos no formato brasileiro (BRL).

#### Dados dos Produtos

O arquivo products.ts contém uma lista de produtos organizados em categorias, com detalhes como preço, descrição, imagens, e ingredientes (no caso de alimentos).

### Como Executar

1. Clone o repositório:

   ```sh
   git clone https://github.com/Guilherme006/NLW-Expert.git
   ```

2. Instale as dependências.

3. Execute o projeto:

   ```sh
   npx expo start
   ```


<!-- Badges -->
[visual-studio-code]: https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visualstudiocode&logoColor=fff&style=for-the-badge
[React Badge]: https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=fff&style=for-the-badge
[React Router Badge]: https://img.shields.io/badge/React%20Router-CA4245?logo=reactrouter&logoColor=fff&style=for-the-badge
[TypeScript Badge]: https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=for-the-badge
[Tailwind CSS Badge]: https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=for-the-badge
[Expo Badge]: https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=fff&style=for-the-badge

<!-- Images -->
[nlw-expert-image]: /assets.NLW-expert.png
