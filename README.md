# Sistema de Gestão MRP Shoes (Projeto Universitário)

## Visão Geral
Este projeto é um Sistema de Gestão baseado em Java - MRP Shoes, desenvolvido como parte de um projeto universitário. Ele utiliza o padrão de projeto DAO (Data Access Object) para separar a lógica de negócios da camada de acesso a dados, e faz uso do MySQL como banco de dados para armazenar informações. O sistema é projetado para facilitar a gestão de inventário, vendas e informações de clientes, fornecendo funcionalidades para adicionar, atualizar e excluir produtos, gerenciar pedidos de clientes e gerar relatórios para análise.

## Funcionalidades
- **Gestão de Produtos**: Adicionar, atualizar e excluir produtos do inventário.
- **Gestão de Pedidos**: Gerenciar pedidos de clientes, incluindo adicionar novos pedidos, atualizar o status do pedido e visualizar o histórico de pedidos.
- **Relatórios**: Gerar relatórios sobre o status do inventário, vendas e outras métricas relevantes.

## Instalação
1. Clone o repositório:
    ```
    git clone https://github.com/victorfaccioli/MRP_SHOES.git
    ```
2. Configure o MySQL e importe o banco de dados fornecido no diretório `database`.
3. Certifique-se de que o driver JDBC do MySQL está incluído no projeto.
4. Navegue até o diretório do projeto:
    ```
    cd MRP_SHOES
    ```
5. Compile os arquivos Java:
    ```
    javac *.java
    ```

## Utilização
1. Execute a classe Main:
    ```
    java Main
    ```
2. Navegue pelo menu para acessar diferentes funcionalidades, como gestão de produtos, gestão de pedidos e relatórios.

## Contribuições
Contribuições são bem-vindas! Se você tiver ideias para novas funcionalidades, melhorias ou encontrar algum problema, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a [Licença MIT](LICENSE).

## Reconhecimentos
Agradecimentos especiais a [Victor Faccioli](https://github.com/victorfaccioli) por criar a base deste projeto.
