# 04 — Referências e Consulta Rápida

Esta aula funciona como uma pequena **folha de consulta** para os conceitos apresentados no curso.

---

# Estrutura básica

```html
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título da página</title>
</head>

<body>

    <h1>Olá, mundo!</h1>

</body>

</html>
```

---

# Estrutura do documento

| Elemento          | Função                 |
| ----------------- | ---------------------- |
| `<!DOCTYPE html>` | Declara HTML moderno   |
| `<html>`          | Elemento raiz          |
| `<head>`          | Metadados do documento |
| `<title>`         | Título da página       |
| `<body>`          | Conteúdo da página     |

---

# Texto

```html
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>

<p>Parágrafo.</p>

<strong>Texto importante</strong>

<em>Texto enfatizado</em>

<br>
```

---

# Links

```html
<a href="https://example.com">
    Visitar site
</a>
```

Para abrir em uma nova aba:

```html
<a href="https://example.com" target="_blank">
    Visitar site
</a>
```

---

# Imagens

```html
<img
    src="imagem.jpg"
    alt="Descrição da imagem"
>
```

---

# Listas

## Não ordenada

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

## Ordenada

```html
<ol>
    <li>Primeiro</li>
    <li>Segundo</li>
    <li>Terceiro</li>
</ol>
```

---

# Divisões e semântica

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
    Seção
</section>

<article>
    Artigo
</article>

<aside>
    Conteúdo complementar
</aside>

<footer>
    Rodapé
</footer>
```

---

# Elementos genéricos

```html
<div>
    Conteúdo em bloco
</div>

<span>
    Trecho de texto
</span>
```

---

# Comentários

```html
<!-- Este conteúdo não será exibido como texto na página. -->
```

---

# Atributos comuns

| Atributo | Utilizado principalmente para |
| -------- | ----------------------------- |
| `href`   | Destino de links              |
| `src`    | Localização de recursos       |
| `alt`    | Texto alternativo de imagens  |
| `id`     | Identificador único           |
| `class`  | Classificação de elementos    |
| `title`  | Informação complementar       |
| `lang`   | Idioma do documento           |

Exemplo:

```html
<p id="introducao" class="texto">
    Olá!
</p>
```

---

# Formulários — introdução

HTML também permite criar formulários:

```html
<form>

    <label for="nome">
        Nome:
    </label>

    <input
        type="text"
        id="nome"
        name="nome"
    >

    <button type="submit">
        Enviar
    </button>

</form>
```

Alguns elementos importantes:

```html
<form>
<label>
<input>
<textarea>
<select>
<option>
<button>
```

---

# Tabelas — introdução

```html
<table>

    <tr>
        <th>Nome</th>
        <th>Idade</th>
    </tr>

    <tr>
        <td>Arthur</td>
        <td>21</td>
    </tr>

</table>
```

Principais elementos:

| Elemento  | Função    |
| --------- | --------- |
| `<table>` | Tabela    |
| `<tr>`    | Linha     |
| `<th>`    | Cabeçalho |
| `<td>`    | Célula    |

---

# Meta tags importantes

Codificação:

```html
<meta charset="UTF-8">
```

Configuração para dispositivos móveis:

```html
<meta
    name="viewport"
    content="width=device-width, initial-scale=1.0"
>
```

---

# Boas práticas

### 1. Use HTML semântico

Prefira:

```html
<article>
```

quando o conteúdo realmente representa um artigo, em vez de usar:

```html
<div>
```

para tudo.

### 2. Mantenha o código organizado

Exemplo:

```html
<section>

    <h2>Sobre mim</h2>

    <p>
        Este é um parágrafo.
    </p>

</section>
```

### 3. Utilize `alt` em imagens

```html
<img src="gato.jpg" alt="Gato preto sentado">
```

### 4. Use títulos de maneira hierárquica

Normalmente:

```text
h1
 ├── h2
 │    ├── h3
 │    └── h3
 └── h2
```

### 5. Não use HTML apenas para aparência

HTML deve representar **estrutura e significado**.

A aparência deve ser controlada principalmente pelo CSS.

---

# Ferramentas úteis

Para estudar HTML, você pode utilizar:

* um navegador moderno;
* um editor de código;
* as ferramentas de desenvolvedor do navegador;
* a documentação oficial da Web;
* validadores de HTML.

---

# Próximos passos

Depois de dominar o conteúdo deste mini-curso, a progressão natural é:

```text
HTML
 │
 ├── CSS
 │    ├── seletores
 │    ├── box model
 │    ├── Flexbox
 │    ├── Grid
 │    └── responsividade
 │
 └── JavaScript
      ├── variáveis
      ├── funções
      ├── eventos
      ├── DOM
      └── APIs
```

O HTML fornece a estrutura. O CSS controla a apresentação. O JavaScript adiciona comportamento e interatividade.

---

# Referências recomendadas

## MDN Web Docs

A MDN é uma das principais referências técnicas para desenvolvimento Web.

https://developer.mozilla.org/

## WHATWG HTML Standard

Especificação oficial do HTML mantida pelo WHATWG.

https://html.spec.whatwg.org/

## W3C

Organização responsável por diversos padrões relacionados à Web.

https://www.w3.org/

---

# Resumo final

Se você lembrar apenas de alguns conceitos após a primeira aula, lembre-se destes:

```text
HTML = estrutura

Elemento = componente do documento

Tag = marca utilizada para representar um elemento

Atributo = informação adicional de um elemento

Semântica = significado estrutural do conteúdo
```

E, principalmente:

> **Não tente decorar HTML inteiro. Aprenda a entender a estrutura de um documento e consulte a documentação quando precisar de um elemento específico.**
