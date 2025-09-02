# Screenmatch Study

> Study project to learn the fundamentals of **Spring Boot**, focused on basic concepts **without a web layer**.

---

## 📚 Table of Contents
- [About](#-about)
- [Tech Stack](#-tech-stack)
- [Prerequisites](#-prerequisites)
- [How to Run](#-how-to-run)
- [How to Code (Quick Guide)](#-how-to-code-quick-guide)
- [How to Test](#-how-to-test)
- [Project Structure](#-project-structure)
- [Useful Commands](#-useful-commands)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📖 About

This repository contains exercises and experiments with **Spring Boot**, practicing concepts like dependency injection, layered organization, service creation, and collection handling.  
The goal is to build a solid foundation before moving to web APIs.

---

## 🧰 Tech Stack

- **Java (JDK 17+)**
- **Spring Boot**
- **Maven** (with **Maven Wrapper** included)
- Suggested IDE: IntelliJ IDEA, VS Code or Eclipse

---

## ✅ Prerequisites

- **Java JDK 17+** installed and in `PATH`:
  ```bash
  java -version
  ```
- Maven (optional) — you can use the Maven Wrapper `(./mvnw or mvnw.cmd)`.

## 🚀 How to Run

- Clone the repository:
```bash
  git clone https://github.com/secio014/screenmatch-study.git
  cd screenmatch-study
  ```
- Run with Maven Wrapper:
```bash
  ./mvnw spring-boot:run   # Linux/macOS
  mvnw.cmd spring-boot:run # Windows
  ```
- Build JAR and run:
```bash
  ./mvnw clean package
  java -jar target/*.jar
  ```

## 🛠️ How to Code (Quick Guide)

1. Models `(model/)`: classes that represent entities (e.g., Movie, Series). 
2. Services `(service/)`: encapsulate business rules. 
3. Entry point `(principal/)`: runs the app via console. 
4. Best practices: keep classes cohesive, methods small, and low coupling.

## 🧪 How to Test

- Run all tests:
```bash
  ./mvnw test   # Linux/macOS
  mvnw.cmd test # Windows
  ```
## 🗂️ Project Structure
```
src/
├── main/java/br/com/alura/screenmatch/
│   ├── principal/
│   ├── model/
│   ├── service/
│   └── ScreenmatchApplication.java
└── test/
```

## 🧾 Useful Commands
| Task      | Command                  |
| --------- | ------------------------ |
| Compile   | `./mvnw compile`         |
| Run app   | `./mvnw spring-boot:run` |
| Run tests | `./mvnw test`            |
| Build JAR | `./mvnw clean package`   |

## 🤝 Contributing

1. Fork the project 
2. Create your branch: `git checkout -b feature/name` 
3. Commit: `git commit -m "feat: describe your change"`
4. Push: `git push origin feature/name `
5. Open a Pull Request

## 📄 License

MIT License (c)