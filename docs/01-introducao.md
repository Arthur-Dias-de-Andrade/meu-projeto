# 01 — Introdução ao HTML

## 1. O que é HTML?

HTML significa **HyperText Markup Language**, ou **Linguagem de Marcação de Hipertexto**.

Apesar de ser frequentemente chamado de "linguagem de programação", HTML não é uma linguagem de programação. Ele é uma **linguagem de marcação**, utilizada para estruturar o conteúdo de páginas da Web.

Com HTML podemos definir coisas como:

* títulos;
* parágrafos;
* imagens;
* links;
* listas;
* tabelas;
* formulários;
* vídeos;
* seções de uma página.

Uma página HTML pode ser entendida como a **estrutura** de um documento.

---

## 2. HTML, CSS e JavaScript

Uma página Web normalmente utiliza três tecnologias principais:

### HTML — estrutura

Define **o que existe** na página.

```html
<h1>Meu site</h1>
<p>Bem-vindo ao meu site!</p>
```

### CSS — aparência

Define **como a página será apresentada**.

```css
h1 {
    color: blue;
}
```

### JavaScript — comportamento

Define **o que a página faz**.

```javascript
alert("Olá!");
```

Uma analogia útil:

> **HTML é o esqueleto, CSS é a aparência e JavaScript é o comportamento.**

---

## 3. O que é uma página Web?

Quando acessamos um site, o navegador recebe documentos e outros recursos de um servidor.

De maneira simplificada:

```text
Servidor
   │
   │ envia arquivos
   ▼
Navegador
   │
   ├── HTML → estrutura
   ├── CSS → aparência
   └── JavaScript → comportamento
```

O navegador interpreta esses arquivos e transforma o código em uma interface visual.

---

## 4. Nosso primeiro documento HTML

Crie um arquivo chamado:

```text
index.html
```

Dentro dele, coloque:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Minha primeira página</title>
</head>
<body>

    <h1>Olá, mundo!</h1>

    <p>Esta é a minha primeira página HTML.</p>

</body>
</html>
```

Salve o arquivo e abra-o com um navegador.

---

## 5. O que acabamos de escrever?

### `<!DOCTYPE html>`

Informa ao navegador que o documento utiliza HTML moderno.

### `<html>`

É o elemento que contém todo o documento HTML.

### `<head>`

Contém informações sobre o documento que normalmente não aparecem diretamente na página.

### `<title>`

Define o título exibido na aba do navegador.

### `<body>`

Contém o conteúdo que será apresentado ao usuário.

### `<h1>`

Representa um título principal.

### `<p>`

Representa um parágrafo.

---

## 6. HTML é formado por elementos

Grande parte do HTML utiliza elementos escritos entre sinais de menor e maior:

```html
<p>Olá!</p>
```

Nesse exemplo:

```text
<p>       → tag de abertura
Olá!      → conteúdo
</p>      → tag de fechamento
```

O conjunto forma um **elemento HTML**.

---

## 7. A ideia principal

Ao aprender HTML, não é necessário decorar centenas de tags.

O mais importante inicialmente é compreender:

1. como um documento HTML é estruturado;
2. o que são elementos;
3. como elementos podem ser organizados;
4. como utilizar atributos;
5. como estruturar semanticamente uma página.

Depois disso, novas tags podem ser aprendidas conforme a necessidade.

---

## Objetivo da aula

Ao terminar esta aula, você deve ser capaz de:

* explicar o que é HTML;
* diferenciar HTML, CSS e JavaScript;
* criar um arquivo `.html`;
* abrir uma página HTML no navegador;
* reconhecer a estrutura básica de um documento HTML.
