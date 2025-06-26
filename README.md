## 📦 Projeto Spring Boot - API REST para E-commerce

Este projeto é uma aplicação backend desenvolvida com **Spring Boot**, que simula uma API REST para um sistema de e-commerce. A aplicação oferece endpoints para gerenciar **usuários**, **produtos** e **categorias**, utilizando boas práticas como injeção de dependência, tratamento de exceções personalizadas e arquitetura em camadas (Resource, Service e Repository).

### 🚀 Tecnologias Utilizadas

* **Java 17+**
* **Spring Boot**
* **Spring Data JPA**
* **Hibernate**
* **Maven**
* **Banco de dados H2 (para testes)**
* **Postman (para testes de API)**

### 🔧 Funcionalidades

* Listagem e busca por ID de usuários, produtos e categorias.
* Cadastro e remoção de usuários.
* Atualização parcial de dados de usuários.
* Tratamento de exceções com mensagens amigáveis.

## ▶️ Como Executar Localmente

Siga os passos abaixo para rodar a aplicação em sua máquina:

### ✅ Pré-requisitos

* **Java 17** ou superior instalado
* **Maven** instalado (ou usar o wrapper `./mvnw`)
* **IDE** (recomendado: IntelliJ IDEA ou Eclipse)
* **Git** (opcional, para clonar o projeto)

---

### 📥 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

---

### 📦 2. Instale as dependências com Maven

```bash
./mvnw clean install
```

Ou, se tiver o Maven instalado globalmente:

```bash
mvn clean install
```

---

### ▶️ 3. Execute o projeto

#### Com Maven:

```bash
./mvnw spring-boot:run
```

#### Ou via sua IDE:

* Abra o projeto na IDE
* Vá até a classe `Application.java` (aquela com `@SpringBootApplication`)
* Clique com o botão direito e escolha "Run"

---

### 🌐 4. Teste a API

Com o servidor rodando (por padrão em `http://localhost:8080`), você pode acessar endpoints como:

* `GET /categories`
* `GET /products`
* `GET /users`

Use ferramentas como **Postman**, **Insomnia** ou apenas o navegador para testar.

---



