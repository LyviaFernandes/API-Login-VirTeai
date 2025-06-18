# 🧠 VirTEAI - API (Spring Boot)

Esta é a API do projeto **VirTEAI**, uma aplicação Spring Boot desenvolvida para gerenciar autenticação e usuários de uma plataforma de vendas de óculos de realidade virtual voltada a pessoas autistas. A proposta da API é fornecer suporte seguro, escalável e eficiente para o back-end do sistema.

---

## 📌 Visão Geral

A API realiza operações básicas de autenticação, criação e listagem de usuários, sendo a base do sistema que futuramente incluirá produtos, pedidos e integração com realidade virtual.

---

## 🚀 Tecnologias Utilizadas

- **Java 21**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **Spring Security**
- **Banco de Dados Relacional (MySQL)**
- **Maven**

---

## 📂 Estrutura Base do Projeto


---

## 🧪 Funcionalidades Implementadas

- ✅ Cadastro de usuários (`/auth/register`)
- ✅ Login de usuários (`/auth/login`)
- ✅ Ponto de entrada Spring Boot funcionando (`ApiLoginApplication.java`)
- ⏳ Futuras implementações:
  - Gerenciamento de produtos
  - Sistema de pedidos
  - Integração com módulo VR
  - Spring Security com JWT

---

## 🛠️ Como Rodar o Projeto

### ✅ Pré-requisitos

- Java 17 ou superior
- Maven
- Banco de dados MySQL em funcionamento

### 📦 Passos

1. Clone o projeto:

```bash
  git clone https://github.com/seu-usuario/virteai-api.git
  cd virteai-api
```
2. Configure o application.properties (exemplo):
spring.datasource.url=jdbc:mysql://localhost:3306/virteai
spring.datasource.username=root
spring.datasource.password=suasenha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=8080

3. Compile e rode:
./mvnw spring-boot:run

  4.Acesse no navegador ou Insomnia/Postman:
http://localhost:8080/

## 👨‍💻 Equipe

| Nome               | Função                                  |
|--------------------|------------------------------------------|
| **Lyvia Fernandes** | Desenvolvedora Front-End                 |
| **Ana Picoli**      | Web Designer                             |
| **Yuri Onishi**     | Desenvolvedor de IA e Back-End |
| **Ester Brasil**    | Desenvolvedora de Banco de Dados         |
| **Valdir Pereira**  | Marketing e Divulgação                   |
