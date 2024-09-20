# Projeto academia Uninove

## Configurando o banco de dados 

Usar o banco de dados MySQL do XAMPP;

Criar um banco de dados com o nome academia;

Crie a tabela cliente

    CREATE TABLE cliente ( 
	    id SERIAL PRIMARY KEY,
	    nome VARCHAR(255) NOT NULL,
	    email VARCHAR(255) NOT NULL,
	    data_nascimento DATE,
	    cpf VARCHAR(14) NOT NULL UNIQUE
    );


## Como abrir o projeto

 1.   Abra o projeto no IntelliJ IDEA.
 2.   Baixe as dependências do Maven (clicando no ícone de sincronização ou utilizando o comando `mvn install`).
 3.   Certifique-se de que o banco de dados está ativo e rodando.
 4.   Execute o arquivo `Main.java` que está no caminho `src/main/java/com/example/Academia`.
 5.   Após iniciar a aplicação, acesse `localhost:8080` no seu navegador.

