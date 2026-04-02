# 🚀 Guia Completo de JavaScript e Node.js

## 📌 1. O que é JavaScript?

JavaScript é uma linguagem de programação interpretada, de alto nível e orientada a eventos, amplamente utilizada para desenvolvimento web.

### Principais características:

* Linguagem interpretada (não precisa compilar)
* Baseada em protótipos
* Suporte a programação assíncrona
* Executa no navegador

---

## 📌 2. Como o JavaScript funciona?

### 🔹 Engine JavaScript

Cada navegador possui uma engine que interpreta o código JS.

Exemplo:

```js
console.log("Olá, mundo!");
```

### 🔹 Event Loop

Responsável por gerenciar tarefas assíncronas.

---

## 📌 3. Variáveis

```js
var nome = "João"; // antigo
let idade = 20;     // recomendado
const PI = 3.14;    // constante
```

---

## 📌 4. Tipos de Dados

* String
* Number
* Boolean
* Null
* Undefined
* Object
* Array

```js
let nome = "Rubens";
let idade = 26;
let ativo = true;
```

---

## 📌 5. Operadores

### Aritméticos

```js
+ - * / %
```

### Comparação

```js
== === != !== > < >= <=
```

### Lógicos

```js
&& || !
```

---

## 📌 6. Estruturas de Controle

### Condicional

```js
if (idade >= 18) {
  console.log("Maior de idade");
} else {
  console.log("Menor de idade");
}
```

### Switch

```js
switch (dia) {
  case 1:
    console.log("Domingo");
    break;
}
```

---

## 📌 7. Laços de Repetição

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}

while (condicao) {}

do {} while (condicao);
```

---

## 📌 8. Funções

```js
function soma(a, b) {
  return a + b;
}

const soma2 = (a, b) => a + b;
```

---

## 📌 9. Arrays e Objetos

### Array

```js
let numeros = [1, 2, 3];
```

### Objeto

```js
let pessoa = {
  nome: "Rubens",
  idade: 26
};
```

---

## 📌 10. DOM (Document Object Model)

Manipula elementos HTML.

```js
document.getElementById("titulo").innerText = "Novo título";
```

---

## 📌 11. JavaScript Assíncrono

### Callback

```js
setTimeout(() => {
  console.log("Executado depois");
}, 1000);
```

### Promise

```js
new Promise((resolve, reject) => {
  resolve("Sucesso");
});
```

### Async/Await

```js
async function carregar() {
  const dados = await fetch(url);
}
```

---

## 📌 12. O que é Node.js?

Node.js é um ambiente de execução JavaScript fora do navegador.

Permite:

* Criar APIs
* Trabalhar com arquivos
* Criar servidores

---

## 📌 13. Módulos no Node.js

### CommonJS

```js
module.exports = {};
```

### Importação

```js
const modulo = require('./modulo');
```

---

## 📌 14. Criando um Servidor

```js
const http = require('http');

const server = http.createServer((req, res) => {
  res.end('Olá mundo');
});

server.listen(3000);
```

---

## 📌 15. NPM (Node Package Manager)

Comandos:

```bash
npm init
npm install express
```

---

## 📌 16. Express (Framework)

```js
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Olá');
});

app.listen(3000);
```

---

## 📌 17. Banco de Dados

Pode usar:

* MongoDB
* MySQL
* PostgreSQL

---

## 📌 18. JSON

Formato de troca de dados.

```json
{
  "nome": "Rubens"
}
```

---

## 📌 19. Boas Práticas

* Usar const e let
* Evitar var
* Escrever código limpo
* Modularizar
* Tratar erros

---

## 📌 20. Estrutura de Projeto

```
/meu-projeto
  /src
  /routes
  /controllers
  /models
  app.js
```

---

## 📌 21. Conclusão

JavaScript + Node.js permitem criar aplicações completas (frontend + backend).

Você pode evoluir para:

* APIs REST
* Sistemas completos
* Aplicações em tempo real

---

🔥 Fim do guia
