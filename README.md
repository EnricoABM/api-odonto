# API Odonto

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4.1.0-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

API REST desenvolvida em Java com Spring Boot para gerenciamento de agendamentos odontológicos, com foco na implementação de endpoints para atendimentos e proteção das informações.

## Tecnologias utilizadas

- **Java 21**
- **Spring Boot**
- **Spring Security**
- **Spring Data JPA**
- **MySQL**
- **Flyway**
- **Docker**
- **Render**
- **Aiven**

## Como executar

### Pré-requisitos

- Java 21
- MySQL
- Docker

### Executando localmente

Clone o repositório:

```bash
git clone https://github.com/EnricoABM/api-odonto.git
cd api-odonto
```

Configure as variáveis de ambiente e a conexão com o banco de dados conforme as configurações da aplicação.

Execute o projeto:

```bash
./mvnw spring-boot:run
```

No Windows:

```bash
mvnw.cmd spring-boot:run
```

### Executando com Docker

Construa a imagem:

```bash
docker build -t api-odonto .
```

Execute o contêiner:

```bash
docker run -p 10000:10000 api-odonto
```

> É necessário configurar as variáveis de ambiente e garantir a conexão com o banco de dados.
