# Sistema de Gestão MRP Shoes (Projeto Universitário)

## Visão Geral
Este projeto é um **Sistema de Gestão MRP Shoes**, desenvolvido como parte de um projeto universitário. Ele utiliza **Java** com o padrão **DAO (Data Access Object)** para separação da lógica de negócios e da camada de acesso a dados. O sistema usa **MySQL** como banco de dados e é projetado para facilitar a **gestão de inventário, vendas e informações de clientes**.

## Tecnologias Utilizadas
- **Java 11+**
- **Maven** para gerenciamento de dependências
- **MySQL** para persistência de dados
- **Padrão DAO** para separação de responsabilidades

## Estrutura do Projeto
```
MRP_SHOES-main
│── database/            # Scripts SQL para criação do banco de dados
│   ├── mrpshoes_materiais.sql
│   ├── mrpshoes_ordens.sql
│   ├── mrpshoes_produto.sql
│── mrp_shoes/
│   ├── pom.xml          # Configuração do Maven
│   ├── src/
│   │   ├── main/java/org/example/
│   │   │   ├── Main.java
│   │   │   ├── DAO/
│   │   │   │   ├── MaterialDao.java
│   │   │   │   ├── ProdutoDAO.java
│   │   │   ├── configuration/
│   │   │   │   ├── Conexao.java
│   ├── target/          # Diretório de build
│── LICENSE
│── README.md
```

## Configuração e Instalação
1. **Clonar o repositório**
   ```sh
   git clone https://github.com/seu-usuario/MRP_SHOES.git
   cd MRP_SHOES-main
   ```

2. **Configurar o banco de dados**
   - Criar um banco de dados no MySQL
   - Importar os arquivos SQL na pasta `database/`

3. **Configurar o projeto**
   - Verificar a conexão com o banco de dados no arquivo `configuration/Conexao.java`

4. **Compilar e executar**
   ```sh
   mvn clean install
   mvn exec:java -Dexec.mainClass="org.example.Main"
   ```

## Funcionalidades
- Cadastro e gerenciamento de produtos
- Controle de estoque
- Registro de pedidos
- Gerenciamento de clientes

## Contribuição
Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

