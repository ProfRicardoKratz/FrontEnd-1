# 🌐 Aula de HTML Básico – Manual de Consulta

Bem-vindo(a)!  
Este repositório contém um **guia rápido de HTML básico**, com as principais tags usadas na criação de páginas web.  
O objetivo é servir como **manual de apoio e consulta** durante os estudos ou práticas da disciplina de **Desenvolvimento Web**.

---

## 📘 O que é HTML?

**HTML (HyperText Markup Language)** é a linguagem usada para estruturar o conteúdo de páginas web.  
Ela utiliza **tags** (marcadores) para indicar ao navegador como cada elemento deve ser exibido.

Um exemplo simples:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Minha Primeira Página</title>
  </head>
  <body>
    <h1>Olá, mundo!</h1>
    <p>Essa é minha primeira página HTML.</p>
  </body>
</html>
````

---

## 🧱 Estrutura básica de uma página HTML

| Seção                           | Tag               | Função                                                                 |
| ------------------------------- | ----------------- | ---------------------------------------------------------------------- |
| Declaração do tipo de documento | `<!DOCTYPE html>` | Informa ao navegador que é um documento HTML5                          |
| Elemento raiz                   | `<html>`          | Contém todo o conteúdo da página                                       |
| Cabeçalho                       | `<head>`          | Inclui metadados, título, links de estilo, scripts etc.                |
| Corpo                           | `<body>`          | Contém todo o conteúdo visível da página (textos, imagens, links etc.) |

---

## 🏷️ Principais Tags HTML

### 🧭 Estrutura e texto

| Tag                | Descrição                    | Exemplo                             |
| ------------------ | ---------------------------- | ----------------------------------- |
| `<h1>` a `<h6>`    | Títulos e subtítulos         | `<h1>Título Principal</h1>`         |
| `<p>`              | Parágrafo de texto           | `<p>Um texto qualquer.</p>`         |
| `<br>`             | Quebra de linha              | `Primeira linha <br> Segunda linha` |
| `<hr>`             | Linha horizontal (separador) | `<hr>`                              |
| `<b>` / `<strong>` | Negrito / Ênfase forte       | `<strong>Importante!</strong>`      |
| `<i>` / `<em>`     | Itálico / Ênfase leve        | `<em>Palavra</em>`                  |
| `<u>`              | Sublinhado                   | `<u>Destaque</u>`                   |
| `<mark>`           | Texto marcado                | `<mark>Marcado</mark>`              |

---

### 🔗 Links e navegação

| Tag               | Descrição        | Exemplo                                       |
| ----------------- | ---------------- | --------------------------------------------- |
| `<a>`             | Cria um link     | `<a href="https://www.google.com">Google</a>` |
| `target="_blank"` | Abre em nova aba | `<a href="..." target="_blank">Abrir</a>`     |

---

### 🖼️ Imagens e mídias

| Tag       | Descrição     | Exemplo                                            |
| --------- | ------------- | -------------------------------------------------- |
| `<img>`   | Insere imagem | `<img src="imagem.jpg" alt="Descrição da imagem">` |
| `<video>` | Insere vídeo  | `<video controls src="video.mp4"></video>`         |
| `<audio>` | Insere áudio  | `<audio controls src="musica.mp3"></audio>`        |

---

### 📋 Listas

| Tipo               | Tag    | Exemplo                                   |
| ------------------ | ------ | ----------------------------------------- |
| Lista ordenada     | `<ol>` | `<ol><li>Item 1</li><li>Item 2</li></ol>` |
| Lista não ordenada | `<ul>` | `<ul><li>Item A</li><li>Item B</li></ul>` |
| Item da lista      | `<li>` | `<li>Item</li>`                           |

---

### 🧩 Tabelas

```html
<table border="1">
  <tr>
    <th>Nome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Maria</td>
    <td>22</td>
  </tr>
</table>
```

| Tag       | Função                             |
| --------- | ---------------------------------- |
| `<table>` | Define a tabela                    |
| `<tr>`    | Linha da tabela                    |
| `<th>`    | Cabeçalho (negrito e centralizado) |
| `<td>`    | Célula de dados                    |

---

### 🪪 Formulários

```html
<form action="/enviar" method="post">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome">
  
  <label for="email">Email:</label>
  <input type="email" id="email" name="email">

  <input type="submit" value="Enviar">
</form>
```

| Tag                     | Descrição            |
| ----------------------- | -------------------- |
| `<form>`                | Define um formulário |
| `<input>`               | Campo de entrada     |
| `<label>`               | Rótulo do campo      |
| `<textarea>`            | Caixa de texto maior |
| `<select>` e `<option>` | Lista suspensa       |
| `<button>`              | Botão personalizado  |

---

## 🎨 Outras tags úteis

| Tag        | Descrição                                    |
| ---------- | -------------------------------------------- |
| `<div>`    | Agrupa blocos de conteúdo                    |
| `<span>`   | Agrupa elementos em linha                    |
| `<meta>`   | Define metadados da página                   |
| `<link>`   | Importa arquivos externos (CSS, ícones etc.) |
| `<script>` | Inclui código JavaScript                     |

---

## 💡 Dica

Use sempre **indentação** e **comentários** para manter seu código legível:

```html
<!-- Cabeçalho da página -->
<header>
  <h1>Meu Site</h1>
</header>
```

---

## 🧠 Recursos de estudo

* [MDN Web Docs – HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
* [W3Schools – HTML Tutorial](https://www.w3schools.com/html/)
* [HTML Validator](https://validator.w3.org/) — valide seu código

---

📚 **Autor:** Prof. Ricardo de Andrade Kratz
🧩 **Disciplina:** Desenvolvimento FrontEnd 1 / HTML Básico
🏫 **IPOG EAD**
