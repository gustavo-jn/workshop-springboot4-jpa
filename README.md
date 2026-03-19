#  API REST com Spring Boot

Projeto de API backend desenvolvido com Java e Spring Boot, com foco em operações CRUD e integração com banco de dados.

---

##  Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- H2 Database (testes)
- PostgreSQL
- Maven

---

##  Estrutura do projeto

O projeto segue arquitetura em camadas:

- **Resource (Controller)** → Recebe requisições HTTP  
- **Service** → Regras de negócio  
- **Repository** → Acesso ao banco de dados  
- **Entities** → Modelos de dados  

---

##  Funcionalidades

- Cadastro de usuários
- Cadastro de produtos
- Registro de pedidos
- Associação entre entidades
- Persistência em banco de dados

---

##  Endpoints principais

### Usuários
- `GET /users`
- `GET /users/{id}`
- `POST /users`
- `DELETE /users/{id}`

### Produtos
- `GET /products`
- `POST /products`

### Pedidos
- `GET /orders`
- `POST /orders`

---

##  Como executar o projeto

```bash
# Clonar repositório
git clone https://github.com/gustavo-jn/workshop-springboot4-jpa

# Entrar na pasta
cd workshop-springboot4-jpa

# Rodar o projeto
./mvnw spring-boot:run
