# Screenmatch Study

> Projeto de estudo para aprender os fundamentos do **Spring Boot**, focado em conceitos básicos **sem camada web**.

---

## 📚 Sumário
- [Sobre o Projeto](#-sobre-o-projeto)
- [Tecnologias](#-tecnologias)
- [Pré-requisitos](#-pré-requisitos)
- [Como Executar](#-como-executar)
- [Como Desenvolver (Guia Rápido)](#-como-desenvolver-guia-rápido)
- [Como Testar](#-como-testar)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Comandos Úteis](#-comandos-úteis)
- [Contribuição](#-contribuição)
- [Licença](#-licença)

---

## 📖 Sobre o Projeto

Este repositório reúne exercícios e experimentos com **Spring Boot**, aplicando conceitos como injeção de dependências, organização em camadas, criação de serviços e manipulação de coleções.  
O objetivo é construir uma base sólida antes de evoluir para APIs web.

---

## 🧰 Tecnologias

- **Java (JDK 17+)**
- **Spring Boot**
- **Maven** (com **Maven Wrapper** incluído)
- IDE sugerida: IntelliJ IDEA, VS Code ou Eclipse

---

## ✅ Pré-requisitos

- **Java JDK 17+** instalado e no `PATH`:
  ```
  java -version
  ```

- Maven (opcional) — pode usar o Maven Wrapper (./mvnw ou mvnw.cmd).

## 🚀 Como Executar

- Clone o repositório:
 ```
  git clone https://github.com/secio014/screenmatch-study.git
  cd screenmatch-study

 ```
- Rodando com Maven Wrapper:
 ```
  ./mvnw spring-boot:run   # Linux/macOS
   mvnw.cmd spring-boot:run # Windows

 ```
- Gerando JAR e executando:
```
./mvnw clean package
java -jar target/*.jar
 ```

## 🛠️ Como Desenvolver (Guia Rápido)

1. Modelos `(model/)`: classes que representam entidades (ex.: Filme, Série).

2. Serviços `(service/)`: encapsulam regras de negócio.

3. Ponto de entrada `(principal/)`: executa a aplicação via console.

4. Boas práticas: mantenha coesão, métodos pequenos e pouco acoplamento.

## 🧪 Como Testar

- Rodar todos os testes:

 ```
./mvnw test   # Linux/macOS
mvnw.cmd test # Windows
 ```

## 🗂️ Estrutura do Projeto

```
src/
├── main/java/br/com/alura/screenmatch/
│   ├── principal/
│   ├── model/
│   ├── service/
│   └── ScreenmatchApplication.java
└── test/
```

## 🧾 Comandos Úteis

| Tarefa    | Comando                  |
| --------- | ------------------------ |
| Compilar  | `./mvnw compile`         |
| Rodar app | `./mvnw spring-boot:run` |
| Testar    | `./mvnw test`            |
| Gerar JAR | `./mvnw clean package`   |

## 🤝 Contribuição

1. Faça fork do projeto

2. Crie sua branch: `git checkout -b feature/nome`

3. Commit: `git commit -m "feat: descrição da mudança"`

4. Push: `git push origin feature/nome`

5. Abra um Pull Request

## 📄 Licença

MIT License (c)
