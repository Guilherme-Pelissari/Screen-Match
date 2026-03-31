# 📺 ScreenMatch

**Projeto para treinar Spring Boot** — Catálogo de filmes e séries

---

## 📌 Sobre o Projeto

O **ScreenMatch** é uma aplicação desenvolvida em **Spring Boot** com o objetivo de praticar os principais conceitos do framework.

A ideia é criar um catálogo simples de filmes e séries, permitindo cadastrar, listar, buscar e gerenciar títulos, simulando um pequeno sistema de streaming.

Projeto ideal para quem está aprendendo Spring Boot, REST API, JPA, DTOs e boas práticas de desenvolvimento backend.

---

## ✨ Funcionalidades

- Cadastro de séries e filmes  
- Listagem de todos os títulos cadastrados  
- Busca de séries por nome  
- Busca por ator  
- Visualização de detalhes  
- Integração futura com API externa (OMDB)  

---

## 🛠️ Tecnologias Utilizadas

- **Java 17**  
- **Spring Boot**  
- **Spring Web (REST)**  
- **Spring Data JPA**  
- **H2 Database (banco em memória)**  
- **Maven**  
- **Lombok (opcional)**  

---

## 🚀 Como Executar o Projeto

### 📋 Pré-requisitos

- JDK 17 ou superior  
- Maven instalado (ou usar o wrapper `./mvnw`)  

### ▶️ Passos

1. Clone o repositório:
```
    git clone https://github.com/Guilherme-Pelissari/Screen-Match.git  
    cd Screen-Match
```

2. Execute a aplicação:
```
    ./mvnw spring-boot:run
```
Ou rode diretamente pela classe `ScreenMatchApplication` no IntelliJ IDEA.

3. A API estará disponível em:
```
    http://localhost:8080
```
---

## 📌 Endpoints Principais

| Método | Endpoint             | Descrição               |
|--------|---------------------|-------------------------|
| GET    | /series             | Lista todas as séries   |
| GET    | /series/{id}        | Busca série por ID      |
| GET    | /series/nome/{nome} | Busca série por nome    |
| POST   | /series             | Cadastra uma nova série |

⚠️ Os endpoints podem variar conforme o desenvolvimento do projeto.

---

## 📂 Estrutura do Projeto

    src/main/java/com/guilhermepelissari/screenmatch/
    ├── ScreenMatchApplication.java
    ├── controller/
    ├── model/
    ├── repository/
    ├── service/
    └── dto/

---

## 🚧 Próximos Passos

- [ ] Integração com a API do OMDB  
- [ ] Tratamento de exceções e responses padronizados  
- [ ] Paginação e filtros avançados  
- [ ] Testes unitários e de integração  
- [ ] Documentação com Swagger  
- [ ] Deploy em plataforma na nuvem  

---

## 🤝 Contribuição

Este é um projeto de estudo. Contribuições são bem-vindas!

1. Faça um fork do projeto  
2. Crie uma branch:
```
    git checkout -b feature/nova-funcionalidade
```
3. Commit:
```
    git commit -m "Adiciona nova funcionalidade"
```
4. Push:
```
    git push origin feature/nova-funcionalidade
```
5. Abra um Pull Request  

---

## 📄 Licença

Este projeto é apenas para fins educacionais.

---

## 👨‍💻 Autor

Desenvolvido por **Guilherme Pelissari**  

☕ Aprendendo Spring Boot com dedicação e café
