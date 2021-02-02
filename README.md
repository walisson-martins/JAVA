Repositório referente ao projeto feito em JAVA

JPA - Java Persistence API é uma API padrão da linguagem Java que descreve uma interface comum para frameworks de persistência de dados. A JPA define um meio de mapeamento objeto-relacional para objetos Java simples e comuns, denominados beans de entidade


Como estamos utilizando Maven, clicaremos em "Maven Artifacts" para sermos redirecionados para o repositório de dependências JFrog Bintray. 


Maven -- gerenciador de dependência do JAVA --> https://mvnrepository.com/artifact/mysql/mysql-connector-java

Escrever SQL no código Java é trabalhoso e precisa de manutenção contínua

A JPA é um ORM (Object Relacional Mapper) Java

Um ORM mapeia as classes para tabelas e gera o SQL de forma automática. Para inicializar a JPA, é preciso definir um arquivo de configuração, chamado persistence.xml
Nele, colocamos as configurações mais importantes, como o driver e os dados da conexão.

A classe Persistence lê a configuração e cria uma EntityManagerFactory.

Podemos usar a JPA para gerar e atualizar as tabelas no banco de dados.

Uma entidade deve usar as anotações @Entity e @Id @GeneratedValue não é obrigatório, mas pode ser útil para definir uma chave auto-increment
