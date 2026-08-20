# 03 — Exercícios Práticos

Nesta aula, vamos colocar em prática os conceitos apresentados anteriormente.

## Exercício 1 — Primeira página

Crie um arquivo chamado:

```text
index.html
```

Construa uma página contendo:

* um título principal;
* dois parágrafos;
* um subtítulo;
* uma lista com três itens.

### Desafio

Faça a página apresentar uma pequena descrição sobre você.

---

## Exercício 2 — Links

Crie uma página contendo três links para sites diferentes.

Exemplo:

```html
<a href="https://example.com">
    Example
</a>
```

### Desafio

Crie também um link que leve para uma segunda página do seu próprio projeto.

Estrutura:

```text
projeto/
│
├── index.html
└── sobre.html
```

---

## Exercício 3 — Imagens

Adicione uma imagem à página utilizando:

```html
<img src="imagem.jpg" alt="Descrição">
```

Crie uma pasta:

```text
imagens/
```

e coloque a imagem dentro dela.

Depois utilize:

```html
<img src="imagens/imagem.jpg" alt="Descrição da imagem">
```

### Pergunta

Por que é importante utilizar o atributo `alt`?

---

## Exercício 4 — Lista de conhecimentos

Crie uma página chamada `conhecimentos.html`.

Nela, faça uma lista dos assuntos que você gostaria de aprender.

Utilize:

```html
<ul>
    <li>...</li>
</ul>
```

Depois crie uma lista ordenada mostrando uma ordem de estudo:

```html
<ol>
    <li>...</li>
</ol>
```

---

## Exercício 5 — Página semântica

Crie uma página utilizando:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

Organize o conteúdo de maneira lógica.

Uma possível estrutura:

```html
<body>

    <header>
        <h1>Meu site</h1>
    </header>

    <nav>
        <a href="index.html">Início</a>
        <a href="sobre.html">Sobre</a>
    </nav>

    <main>

        <section>
            <h2>Sobre o projeto</h2>

            <p>
                Este é um projeto criado durante meu curso de HTML.
            </p>
        </section>

        <article>
            <h2>Meu primeiro artigo</h2>

            <p>
                Estou aprendendo a estruturar páginas utilizando HTML.
            </p>
        </article>

    </main>

    <footer>
        <p>Meu site — 2026</p>
    </footer>

</body>
```

---

# Projeto final

Agora vamos juntar tudo.

Crie um pequeno **site pessoal** contendo pelo menos três páginas:

```text
meu-site/
│
├── index.html
├── sobre.html
├── projetos.html
└── imagens/
```

## Página inicial

A página `index.html` deve possuir:

* título principal;
* apresentação;
* imagem;
* menu de navegação;
* pelo menos dois links.

## Página "Sobre"

A página `sobre.html` deve possuir:

* título;
* alguns parágrafos;
* uma lista de interesses;
* link para voltar à página inicial.

## Página "Projetos"

A página `projetos.html` deve possuir:

* título;
* pelo menos três projetos;
* uma descrição para cada projeto;
* links quando apropriado.

---

# Desafio extra

Tente criar o projeto **sem consultar exemplos prontos**.

Quando encontrar algo que não sabe fazer:

1. identifique o problema;
2. procure na documentação;
3. tente implementar;
4. abra a página no navegador;
5. observe o resultado;
6. corrija os erros.

O objetivo não é memorizar HTML.

O objetivo é aprender a **construir e investigar**.

---

# Checklist

* [ ] Criei um arquivo HTML.
* [ ] Utilizei `<!DOCTYPE html>`.
* [ ] Utilizei `<html>`.
* [ ] Utilizei `<head>`.
* [ ] Utilizei `<body>`.
* [ ] Criei títulos.
* [ ] Criei parágrafos.
* [ ] Criei links.
* [ ] Adicionei uma imagem.
* [ ] Criei uma lista.
* [ ] Utilizei elementos semânticos.
* [ ] Criei mais de uma página.
* [ ] Criei links entre as páginas.