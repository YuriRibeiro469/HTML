# 🔹 HTML

## O QUE É HTML?

HTML é a sigla para **HyperText Markup Language** (Linguagem de Marcação de Hipertexto).  
Ele **não é uma linguagem de programação**, pois não possui lógica (como estruturas condicionais ou loops).  
Seu objetivo principal é **estruturar e organizar o conteúdo** das páginas web.

---

## 🔹 CRIAÇÃO DO ARQUIVO HTML

- Não requer servidor para funcionar  
- Executado diretamente no navegador  
- O arquivo `index.html` é geralmente a página inicial  
- Usa a extensão `.html`

---

## 🔹 ESTRUTURA BÁSICA DE UMA PÁGINA HTML

Atalho para criar a estrutura base em editores como VS Code:
! (Enter)

```html
<html>
  <head> 
    <title>Título da Página</title>
  </head>

  <body>
    <h1>Título do conteúdo</h1>
    <p>Parágrafo</p>
    <p>Outro parágrafo</p>
  </body>
</html>
```

### `<head>`
- Define o título da aba  
- Inclui links para arquivos externos (CSS, JS, etc.)  
- Contém metadados  

### `<body>`

- Contém tudo que aparece na página  
- Onde usamos tags HTML como cabeçalhos, parágrafos, imagens, etc.

---

## Abertura e Fechamento de Tags

```html
<tag>    => abertura
</tag>   => fechamento
```

As **tags HTML** geralmente vêm em pares:
```html
<tag>Conteúdo</tag>
```

---

## 🔹 ELEMENTOS INLINE E BLOCK

### Elementos Inline

- Não iniciam uma nova linha  
- Ocupam apenas a largura necessária
 
**Exemplos:** `<span>`, `<img>`, `<a>`

### Elementos Block

- Iniciam em uma nova linha  
- Ocupam toda a largura disponível  

**Exemplos:** `<div>`, `<h1>`, `<form>`

---

## 🔹 ATRIBUTOS DAS TAGS HTML

- Todas as tags podem ter atributos  
- Atributos fornecem informações adicionais sobre o elemento  
- São definidos na tag de abertura  

### Exemplo:

```html
<div class="container"> 
```

Formato padrão: class="valor"
Exemplo: id="dicasparadevs"

---

## 🔹 TAGS SEMÂNTICAS NO HTML5

<header> <nav> <section> <aside> <article> <footer>

- Um elemento semântico descreve claramente seu significado para navegadores e desenvolvedores
- Ajuda na organização e acessibilidade do conteúdo

---

## 🔹 ESTRUTURA DE TABELAS

```HTML
<table>
  <thead>
    <tr>
      <th>Nome</th>
      <th>Email</th>
      <th>Idade</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Teste</td>
      <td>teste@email.com</td>
      <td>23</td>
    </tr>
  </tbody>
</table>
```

Tags usadas:
 
-  `<table>`: tabela
- `<thead>`: cabeçalho da tabela
- `<tbody>`: corpo da tabela
- `<tr>`: linha da tabela
- `<th>`: célula de cabeçalho
- `<td>`: célula de dados

---

## 🔹 TAGS DE FORMATAÇÃO DE TEXTO

`<strong>`  => Deixa o texto em negrito
`<em>`      => Deixa o texto em itálico

Exemplo:
`<p>`Esse é um `<strong>`destaque`</strong>` e um `<em>`italico`</em>`.`</p>`

---

## 🔹 ATALHOS ÚTEIS (VS Code)

```
! + Enter          => Cria a estrutura base do HTML
Ctrl + ;           => Comenta a linha selecionada
lorem              => Gera um texto fictício
lorem10            => Gera um texto com 10 palavras fictícias
```
---
