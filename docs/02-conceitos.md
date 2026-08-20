# 02 — Conceitos Fundamentais de HTML

## 1. Elementos e tags

Um documento HTML é construído através de **elementos**.

Exemplo:

```html
<h1>Meu título</h1>
```

A tag de abertura é:

```html
<h1>
```

A tag de fechamento é:

```html
</h1>
```

E o conteúdo está entre elas:

```text
Meu título
```

---

## 2. Elementos sem fechamento

Nem todos os elementos possuem uma tag de fechamento.

Um exemplo é:

```html
<img src="foto.jpg" alt="Uma fotografia">
```

Outro exemplo:

```html
<br>
```

Esses elementos são chamados de **void elements** (elementos vazios).

---

## 3. Aninhamento

Elementos HTML podem ficar dentro de outros elementos.

```html
<div>
    <h1>Meu site</h1>

    <p>
        Bem-vindo ao meu site.
    </p>
</div>
```

Nesse caso, o `<h1>` e o `<p>` estão dentro do `<div>`.

É importante fechar os elementos na ordem correta.

Correto:

```html
<p>
    <strong>Texto importante</strong>
</p>
```

Incorreto:

```html
<p>
    <strong>Texto importante
</p>
</strong>
```

---

## 4. Atributos

Elementos podem possuir **atributos**.

Exemplo:

```html
<a href="https://example.com">Visitar site</a>
```

O atributo é:

```html
href="https://example.com"
```

Outro exemplo:

```html
<img src="imagem.jpg" alt="Descrição da imagem">
```

Aqui temos dois atributos:

```text
src
alt
```

Atributos fornecem informações adicionais ou modificam o comportamento de um elemento.

---

## 5. Títulos

HTML possui seis níveis de títulos:

```html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Seção</h3>
<h4>Subseção</h4>
<h5>Nível 5</h5>
<h6>Nível 6</h6>
```

A hierarquia vai de `<h1>` até `<h6>`.

Não devemos escolher títulos apenas pelo tamanho visual. A hierarquia deve representar a **estrutura do conteúdo**.

---

## 6. Parágrafos

Parágrafos são representados por `<p>`:

```html
<p>
    HTML é utilizado para estruturar documentos da Web.
</p>
```

Podemos criar vários parágrafos:

```html
<p>Primeiro parágrafo.</p>

<p>Segundo parágrafo.</p>
```

---

## 7. Links

Links são criados com `<a>`:

```html
<a href="https://example.com">
    Acessar o site
</a>
```

O atributo `href` indica o destino do link.

Também podemos criar links para outras páginas do nosso próprio projeto:

```html
<a href="sobre.html">Sobre</a>
```

---

## 8. Imagens

Imagens utilizam `<img>`:

```html
<img src="foto.jpg" alt="Descrição da fotografia">
```

O atributo `src` indica onde está a imagem.

O atributo `alt` fornece uma descrição textual da imagem e é importante para **acessibilidade**.

---

## 9. Listas

### Lista não ordenada

```html
<ul>
    <li>Maçã</li>
    <li>Banana</li>
    <li>Laranja</li>
</ul>
```

Resultado conceitual:

* Maçã
* Banana
* Laranja

### Lista ordenada

```html
<ol>
    <li>Primeiro passo</li>
    <li>Segundo passo</li>
    <li>Terceiro passo</li>
</ol>
```

Resultado conceitual:

1. Primeiro passo
2. Segundo passo
3. Terceiro passo

---

## 10. Comentários

Comentários permitem deixar anotações no código que não são exibidas como conteúdo da página.

```html
<!-- Este é um comentário -->
```

Comentários são úteis para explicar partes do código.

---

## 11. Estrutura semântica

HTML moderno possui elementos que descrevem o significado de cada parte da página.

Alguns exemplos:

```html
<header>
    Cabeçalho
</header>

<nav>
    Navegação
</nav>

<main>
    Conteúdo principal
</main>

<section>
    Uma seção
</section>

<article>
    Um conteúdo independente
</article>

<footer>
    Rodapé
</footer>
```

Uma página pode ser organizada assim:

```text
<html>
│
├── <head>
│
└── <body>
    │
    ├── <header>
    │
    ├── <nav>
    │
    ├── <main>
    │   ├── <section>
    │   └── <article>
    │
    └── <footer>
```

Esse tipo de estrutura torna o documento mais compreensível para navegadores, mecanismos de busca e tecnologias assistivas.

---

## 12. `div` e `span`

Dois elementos genéricos muito comuns são:

```html
<div>
    Conteúdo
</div>
```

e:

```html
<span>Texto</span>
```

O `<div>` é geralmente utilizado para agrupar conteúdo em bloco.

O `<span>` é utilizado para agrupar pequenos trechos de conteúdo dentro de uma linha.

Eles não possuem significado semântico específico.

---

## Objetivo da aula

Ao terminar esta aula, você deve compreender:

* elementos;
* tags;
* atributos;
* aninhamento;
* títulos;
* parágrafos;
* links;
* imagens;
* listas;
* comentários;
* elementos semânticos;
* `div` e `span`.