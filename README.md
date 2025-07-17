
# 📘 README - API de Lista de Tarefas em Java Puro

## 📌 Nome do projeto:
**API de Lista de Tarefas em Java Puro**

## 🎯 Objetivo / Resumo:
Construir uma API RESTful utilizando apenas **Java SE puro**, sem frameworks externos, para reforçar fundamentos de backend, arquitetura em camadas, princípios REST e manipulação de requisições HTTP.  
A API permite operações **CRUD** (Criar, Ler, Atualizar, Deletar) sobre tarefas.

## 🛠 Tecnologias utilizadas:
- **Java 17+**
- **Servidor HTTP Nativo**: `com.sun.net.httpserver.HttpServer`
- **Coleções Java**: `Map`, `List`
- **JSON manual** ou via biblioteca leve (`org.json`)
- **IntelliJ IDEA** (IDE recomendada)

## ▶️ Como rodar localmente:

### 1. Clone o repositório:
```bash
git clone https://github.com/Fpsn26/tarefa-api-java-puro.git
cd tarefa-api-java-puro
```

### 2. Abra o projeto no **IntelliJ IDEA**

### 3. Compile e execute a classe `Main.java`

### 4. Teste os endpoints com seu navegador, Postman ou Insomnia:

- `GET` → [http://localhost:8000/tarefas](http://localhost:8000/tarefas)
- `POST` → [http://localhost:8000/tarefas](http://localhost:8000/tarefas)
- `PUT` → [http://localhost:8000/tarefas/{id}](http://localhost:8000/tarefas/{id})
- `DELETE` → [http://localhost:8000/tarefas/{id}](http://localhost:8000/tarefas/{id})

## 🚀 Como fazer deploy (opcional):

Este projeto tem fins **educacionais e uso local**. Para fazer deploy:

- Gere um `.jar` com `java -jar`
- Execute em um servidor com Java instalado
- Ou use um VPS leve (Ubuntu na AWS, DigitalOcean, Oracle Cloud)

## 📝 Licença:
Distribuído sob a Licença **MIT**. Consulte o arquivo `LICENSE.md` para mais detalhes.

## 🙋‍♂️ Créditos:
Desenvolvido por **Felipe Sanches**  
Projeto de aprendizado e portfólio.
