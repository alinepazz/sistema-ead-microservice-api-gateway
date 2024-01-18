# EAD - API GATEWAY

## Sobre o projeto
Projeto Decoder EAD - Arquitetura de microservices, tem como maior
objetivo colocar em prática todos os conceitos abordados.

Cada funcionalidade da plataforma é abordada como um serviço independente, promovendo flexibilidade e isolamento de responsabilidades.

### Alguns dos conceitos abordados ao longo do projeto
`Shared Database Pattern`
`Event Driven Pattern`
`Comunicação por Coreografia`
`Authentication e Authorization com JWT`
`Observability`
`SAGA Pattern`
`Cross
Cutting`
`Event Carried State Transfer Pattern`

### Desenho da solução
![Desenho da solucao ead](imagens/projeto.png)

### Desenho da solução
![Desenho da solucao ead](imagens/projeto.png)

## Sobre a API
Implementação do padrão API Gateway, tem como objetivo gerenciar e direcionar as solicitações de entrada para os microservices subjacentes. 
Funcionando como um ponto de entrada único para a arquitetura.

## Tecnologias utilizadas
- Java 11
- Spring boot
- Maven
- Eureka Client
- Spring Cloud Gateway

## Como executar o projeto
- Pré-requisitos: Java 11
- Ter os seguinte projetos em execução:
    - Service Registry
    - Config Server

```bash
# clonar repositório
git clone https://github.com/alinepazz/sistema-ead-microservice-api-gateway.git

# entrar na pasta raiz do projeto

# executar o projeto
mvn spring-boot:run
```
### Autor
Aline Soares da Paz

https://www.linkedin.com/in/alinepazz/

### Repositórios do projeto

- https://github.com/alinepazz/sistema-ead-microservice-configserver
- https://github.com/alinepazz/sistema-ead-microservice-api-configserver
- https://github.com/alinepazz/sistema-ead-microservice-api-registry
- https://github.com/alinepazz/sistema-ead-microservice-api-notification
- https://github.com/alinepazz/sistema-ead-microservice-api-course
- https://github.com/alinepazz/sistema-ead-microservice-api-authuser