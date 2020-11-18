# Testes Unitários - Digital Innovation One

##### Objetivos da Aula:
1. Apresentar a pirâmide de testes de software e detalhar cada nível.
2. Destacar a importância dos testes unitários durante o desenvolvimento.
3. Apresentar frameworks referência para testes: JUnit, Mockito e Hamcrest.
4. Codificar, compartilhar e aprender todos juntos.

##### O que vamos utilzar:
- Java 14
- Maven 3.6.2
- Spring Boot (última versão estável lançada)
- GIT/GITHUB para versionamento de código
- Frameworks JUnit, Mockito e Hamcrest

##### @Data 
- Gera os getters e setters automaticamente.

##### DAO
- Data Access Object
- Comunicação com o banco de dados.

##### Optional 
- Introduzido no Java 8.

##### @Service 
- De dentro para fora.

##### @RestController
- Uma controller passandos os dados sem parte gráfica.

##### Typical HTTP Verbs:
- GET -> Read from Database.
- PUT -> Update/Replace row in Database.
- PATCH -> Update/Modify row in Database.
- POST -> Create a new recorde in the database.
- DELETE -> Delete from the database.

##### API RESTful - Richardson

###### Glory Of Rest
- Level 3 - Hypermedia Controls
- Level 2 - HTTP Verbs
- Level 1 - Resources
- Level 0 - The Swamp Of Pox

##### Pirâmide de Testes
- UI Tests -> appium
- Integrations Tests -> UI Automator, espresso e AndroidJUnit4
- Unit Tests -> Mock, JUnit e mockito

##### Vantagens
- Sistema testado de ponta a ponta.
- Evolução segura: sem quebrar funcionalidades.
- Teste também é forma de documentação.
- Integração contínua (CI)
- Deploy contínuo (CD)

##### Nível 1: testes unitários
- Maior número de testes, menor custo e tempo
- Testes feito pelo próprio desenvolvedor
- Rápidos, com base em linhas de código
- Cobertura de vários cenários para as linhas
- Integração com outros códigos: através de mocks

##### Principais frameworks
- JUnit
- Mockito
- Hamcrest
- Spring Boot Starter Test: acesso a todos os frameworks!

##### Builder 
- Auxilia nos testes porque traz tudo preenchido.

##### Maven
- Adiciona qualidade ao teste e deixa mais poderoso.

##### Inglês
- Maioria dos testes da empresas e comunidades são em inglês.

##### Terminal IDE
- git diff -> Lista todos os testes realizados.

##### TDD 
- Testar e simplificar o código.
