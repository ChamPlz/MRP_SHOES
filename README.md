# Sistema de Gestão MRP para MRP Shoes (Projeto Universitário)

## Visão Geral
Este projeto é um Sistema de Gestão baseado em Java para MRP Shoes, desenvolvido como parte de um projeto universitário. Utiliza o padrão DAO (Data Access Object) para facilitar o acesso aos dados do banco de dados, proporcionando uma arquitetura mais organizada e modular. O sistema foi projetado para facilitar a gestão de inventário, vendas e informações de clientes, fornecendo funcionalidades como adicionar, atualizar e excluir produtos, gerenciar pedidos de clientes e gerar relatórios para análise.

## Funcionalidades
- **Gestão de Produtos**: Adicionar, atualizar e excluir produtos do inventário.
- **Gestão de Pedidos**: Gerenciar pedidos de clientes, incluindo adicionar novos pedidos, atualizar o status do pedido e visualizar o histórico de pedidos.
- **Relatórios**: Gerar relatórios sobre o status do inventário, vendas e outras métricas relevantes.

## Padrão de Desenvolvimento DAO
O projeto segue o padrão DAO (Data Access Object) para separar a lógica de negócios da camada de acesso a dados. Isso permite uma melhor organização do código e facilita a manutenção e extensibilidade do sistema. As classes DAO são responsáveis por fornecer métodos para acessar e manipular os dados no banco de dados, enquanto as classes de negócios se concentram na lógica específica do domínio.

## Instalação
1. Clone o repositório:
    ```
    git clone https://github.com/victorfaccioli/MRP_SHOES.git
    ```
2. Navegue até o diretório do projeto:
    ```
    cd MRP_SHOES
    ```
3. Compile os arquivos Java:
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
