# 🏥 Clínica Médica - Projeto Integrador

Este projeto tem como objetivo o desenvolvimento de um sistema para gerenciamento de uma clínica médica, permitindo o cadastro de pacientes, médicos e agendamentos de consultas. Desenvolvido como parte do Projeto Integrador do curso de Análise e Desenvolvimento de Sistemas.

---

## 🚀 Tecnologias Utilizadas

- Java 17
- Spring Boot 3.x
- Spring Data JPA
- MySQL
- HTML5, CSS3 e JavaScript
- Lombok
- Postman (para testes de API)

---

## 📁 Estrutura do Projeto

```
/src
 └── main
     ├── java
     │   └── com.clinica.clinicamedica
     │       ├── model
     │       ├── repository
     │       └── controller
     └── resources
         ├── static
         │   ├── index.html
         │   ├── agendamento.html
         │   ├── especialidades.html
         │   ├── contato.html
         │   ├── css/
         │   └── js/
         └── application.properties
```

---

## 🔧 Como executar o projeto

1. Clone este repositório:
```bash
git clone https://github.com/seuusuario/clinicamedica.git
```

2. Importe o projeto em sua IDE (IntelliJ, VS Code ou Eclipse)

3. Configure o `application.properties` com os dados do seu banco MySQL:
```properties
spring.datasource.url=jdbc:mysql://localhost:3306/clinica
spring.datasource.username=root
spring.datasource.password=suasenha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

4. Execute a classe principal do Spring Boot (`ClinicamedicaApplication.java`)

---

## 📌 Funcionalidades

- Cadastro de pacientes
- Cadastro de médicos
- Agendamento de consultas
- Listagem de registros via API
- Interface web com integração com o back-end

---

## 🧪 Testes

Os testes das rotas podem ser feitos via Postman utilizando os endpoints:

- `GET /pacientes`
- `POST /pacientes`
- `GET /medicos`
- `POST /medicos`
- `GET /agendamentos`
- `POST /agendamentos`

---

## 🧠 Integrantes

- Wendy (Organização geral, integração e front-end)
- [Inserir os outros nomes e funções aqui]

---

## 📅 Prazo

- **Entrega do Back-End:** 21/05/2025
- **Entrega do Front-End + Apresentação:** 07/06/2025

---

## 📄 Licença

Projeto acadêmico sem fins lucrativos.
