<h1>Digital Innovation One - Bootcamp GFT</h1>

<p>Desenvolvimento de testes unitários para cobertura de uma API em Spring Boot para o gerenciamento de estoques de cerveja.<p>

<h2>Tópicos abordados:</h2>

* Apresentação conceitual sobre testes: a pirâmide dos tipos de testes, e também a importância de cada tipo de teste durante o ciclo de desenvolvimento.
* Foco nos testes unitários: mostrar o porque é importante o desenvolvimento destes tipos de testes como parte do ciclo de desenvolvimento de software.
* Principais frameworks para testes unitários em Java:

  - JUnit 
  - Mockito 
  - Hamcrest
    
* Desenvolvimento de testes unitários para validação de funcionalides básicas:
  - criação
  - listagem 
  - consulta por nome 
  - exclusão de cervejas
* TDD: apresentação e exemplo prático em 2 funcionaliades importantes: incremento e decremento do número de cervejas no estoque.

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Para executar a suíte de testes desenvolvida durante a live coding, basta executar o seguinte comando:

```shell script
mvn clean test
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/beers
```

<h3>Pré-requisitos para a execução do projeto desenvolvido durante a aula:</h3>

* Java 11 ou versões superiores.
* Maven 3.6.3 ou versões superiores.
* Intellj IDEA Community Edition ou sua IDE favorita.
* Postman

<h3>Referências, sobre tópicos abordados durante a aula:</h3>

* [SDKMan! para gerenciamento e instalação do Java e Maven](https://sdkman.io/)
* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
* [Site oficial Mockito](https://site.mockito.org/)
* [Site oficial Hamcrest](http://hamcrest.org/JavaHamcrest/)
* [Referências - testes em geral com o Spring Boot](https://www.baeldung.com/spring-boot-testing)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Referência pirâmide de testes - Martin Fowler](https://martinfowler.com/articles/practical-test-pyramid.html#TheImportanceOftestAutomation)

<h3>Link da api hospedada no Heroku:</h3>
https://beerstockapi.herokuapp.com/swagger-ui.html

