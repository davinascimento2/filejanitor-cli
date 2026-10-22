# 🚀 FileJanitor CLI

[![Java 21](https://img.shields.io/badge/Java-21%20LTS-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://openjdk.org/)
[![CI Build](https://img.shields.io/badge/CI-Passing-brightgreen?style=for-the-badge&logo=githubactions&logoColor=white)](.github/workflows/ci.yml)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero%20External-blue?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](LICENSE)

> SHA-256 duplicate file finder and heavy build artifacts (node_modules, target, .next) cleanup CLI.

---

## ⚡ Como Usar

### Compilação Rápida
```bash
# Compilar direto com javac
javac -d target/classes $(find src/main/java -name "*.java")
jar --create --file target/filejanitor-cli.jar --main-class com.allday.filejanitor.FileJanitor -C target/classes .

# Executar
java -jar target/filejanitor-cli.jar
```

---

## 🛠️ Tecnologias
- **Java 21 LTS** puro (Records, Pattern Matching, Streams, Lambdas)
- Zero dependências de terceiros no runtime
- GitHub Actions CI/CD automatizado

---

## 👤 Autor
Desenvolvido por **Davi Nascimento**
- GitHub: [@davinascimento2](https://github.com/davinascimento2)
