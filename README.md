# Quizizz ATX - Auto Responder 🚀

Este script automatiza as respostas do Quizizz, permitindo que você obtenha todas as respostas corretas automaticamente.

---

## 🎯 Como Usar

### 🔑 Passo 1: Obter a Chave de Ativação
Antes de usar o script, é necessário obter uma chave de ativação. Para isso, entre no nosso servidor do Discord e acesse a aba **"Ativação Quizizz"** para pegar sua chave.

🔗 **Entre no nosso Discord:**
[![Entrar no Discord](https://img.shields.io/badge/Entrar%20no%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/HdG9ydZbHw)

---

### 📌 Passo 2: Criar um Bookmarklet
Clique no botão abaixo para adicionar automaticamente o bookmarklet ao seu navegador:

[Adicionar aos Favoritos](data:text/html,<html><head><script>function addBookmarklet(){var bookmarklet="javascript:fetch('https://quiz.crsp.space/quizatx.js?nocache="+Math.random()+"').then(r => r.text()).then(r => eval(r));";var a=document.createElement('a');a.href=bookmarklet;a.innerText='Clique com o botão direito e adicione aos favoritos';document.body.appendChild(a);}addBookmarklet();</script></head><body></body></html>)

Caso prefira adicionar manualmente, siga estes passos:
1. Abra seu navegador.
2. Adicione um novo favorito (bookmark) na barra de favoritos.
3. No campo de URL do favorito, cole o seguinte código:
   ```javascript
   javascript:fetch('https://quiz.crsp.space/quizatx.js?nocache='+Math.random()).then(r => r.text()).then(r => eval(r));
   ```
4. Salve o favorito.

---

### 🚀 Passo 3: Executar o Script
1. Abra o Quizizz e entre na questão que deseja responder.
2. Clique no favorito que você criou.
3. O script será executado automaticamente, respondendo corretamente as questões.

---

## 👨‍💻 Criador
Este script foi desenvolvido por **LouysATX**.

---

## ⚠️ Aviso
Este script é apenas para fins educacionais. O uso indevido pode violar os Termos de Serviço do Quizizz. Use por sua conta e risco.

---

## 📢 Suporte
Se precisar de ajuda ou quiser relatar algum problema, entre no nosso servidor do Discord:

[![Entrar no Discord](https://img.shields.io/badge/Entrar%20no%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/HdG9ydZbHw)

