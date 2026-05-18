# Sistema Acadêmico 🎓

Este é um sistema de gerenciamento acadêmico desenvolvido em Java Swing com persistência de dados em banco de dados MySQL.

## 🛠️ Pré-requisitos para Rodar o Projeto

Antes de iniciar, você precisará ter instalado em sua máquina:
* **Java JDK** (versão 8 ou superior).
* **MySQL Server** (rodando na porta padrão `3306`).
* Driver JDBC do MySQL (`mysql-connector-java`).

## 💾 Configuração do Banco de Dados

1. Abra o seu gerenciador MySQL (Workbench, prompt, etc).
2. Execute o script SQL contido na pasta `/banco/script.sql` para criar a database `sistema_academico` e as tabelas necessárias.
3. Caso necessite alterar as credenciais de acesso, os dados configurados por padrão no código são:
   * **URL:** `jdbc:mysql://localhost:3306/sistema_academico`
   * **Usuário:** `root`
   * **Senha:** `admin1004`

## 🚀 Como Executar a Aplicação

1. Clone este repositório ou baixe o código-fonte em formato ZIP.
2. Abra o projeto na sua IDE de preferência (Eclipse, IntelliJ ou NetBeans).
3. Certifique-se de adicionar o arquivo `.jar` do **MySQL Connector** às bibliotecas/Build Path do projeto.
4. Execute a classe principal localizada em `src/academico/Sistema.java`.
