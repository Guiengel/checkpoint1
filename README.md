# Projeto Checkpoint1

Este projeto é uma aplicação baseada no Spring Boot.

## Tecnologias Utilizadas

- Java
- Spring Boot
- Maven

## Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:

- [Java 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven](https://maven.apache.org/download.cgi)

## Instalação e Execução

1. Clone o repositório:
   sh
   https://github.com/Gabriel-Dias-Santiago/Checkpoint1.git
   ou
   git clone https://github.com/Guiengel/checkpoint1
   
2. Acesse a pasta do projeto:
   sh
   cd checkpoint1
   
3. Compile o projeto:
   sh
   mvn clean install
   
4. Execute a aplicação:
   sh
   mvn spring-boot:run
   

## Estrutura do Projeto


checkpoint1/
├── src/
│   ├── main/
│   │   ├── java/br/com/seuapp/
│   │   ├── resources/
│   │   │   ├── application.properties
│   ├── test/
│   │   ├── java/br/com/seuapp/
├── pom.xml
└── README.md


## Endpoints Disponíveis

A aplicação expõe os seguintes endpoints:

- GET /api/exemplo - Retorna uma lista de exemplos.
- POST /api/exemplo - Cria um novo exemplo.

## Contribuição

1. Fork este repositório
2. Crie uma branch para sua feature (git checkout -b feature/nova-feature)
3. Faça commit das suas alterações (git commit -m 'Adiciona nova feature')
4. Envie para o repositório remoto (git push origin feature/nova-feature)
5. Abra um Pull Request

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
