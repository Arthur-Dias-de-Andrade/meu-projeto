# Exemplo — Site HTML

<!DOCTYPE html>

<!-- =========================================================
     EXEMPLO DIDÁTICO — MINI-CURSO DE HTML

     Este arquivo foi criado exclusivamente para demonstrar
     conceitos básicos de HTML.

     NÃO é um site real.
     ========================================================= -->

<html lang="pt-BR">

<head>

    <!-- EXEMPLO: configuração de caracteres -->
    <meta charset="UTF-8">

    <!-- EXEMPLO: adaptação para dispositivos móveis -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- EXEMPLO: título exibido na aba do navegador -->
    <title>Meu Primeiro Site</title>

</head>

<body>

    <!-- =====================================================
         EXEMPLO DE CABEÇALHO
         ===================================================== -->

    <header>

        <h1>Meu Primeiro Site</h1>

        <p>
            Este site é um exemplo criado para o mini-curso
            introdutório de HTML.
        </p>

    </header>


    <!-- =====================================================
         EXEMPLO DE NAVEGAÇÃO
         ===================================================== -->

    <nav>

        <a href="#inicio">Início</a> |
        <a href="#sobre">Sobre</a> |
        <a href="#conhecimentos">Conhecimentos</a> |
        <a href="#contato">Contato</a>

    </nav>


    <!-- =====================================================
         CONTEÚDO PRINCIPAL
         ===================================================== -->

    <main>

        <!-- EXEMPLO DE SECTION -->

        <section id="inicio">

            <h2>Bem-vindo!</h2>

            <p>
                Esta página demonstra como diferentes elementos
                HTML podem ser combinados para construir a
                estrutura de um site.
            </p>

            <p>
                O HTML é responsável pela estrutura e pelo
                significado do conteúdo de uma página.
            </p>

        </section>


        <!-- =================================================
             EXEMPLO DE ARTICLE
             ================================================= -->

        <article>

            <h2>O que estou aprendendo?</h2>

            <p>
                Durante este curso estou aprendendo os
                fundamentos da linguagem HTML.
            </p>

            <p>
                Entre os conceitos estudados estão elementos,
                atributos, links, imagens, listas e HTML
                semântico.
            </p>

        </article>


        <!-- =================================================
             EXEMPLO DE IMAGEM

             Neste exemplo usamos uma imagem externa apenas
             para fins didáticos.
             ================================================= -->

        <section id="sobre">

            <h2>Sobre o projeto</h2>

            <img
                src="https://picsum.photos/600/300"
                alt="Imagem aleatória utilizada como exemplo"
            >

            <p>
                A imagem acima demonstra a utilização do
                elemento <code>&lt;img&gt;</code>.
            </p>

        </section>


        <!-- =================================================
             EXEMPLO DE LISTA NÃO ORDENADA
             ================================================= -->

        <section id="conhecimentos">

            <h2>O que estou aprendendo</h2>

            <ul>

                <li>Estrutura básica do HTML</li>

                <li>Elementos e tags</li>

                <li>Atributos</li>

                <li>Links</li>

                <li>Imagens</li>

                <li>Listas</li>

                <li>HTML semântico</li>

            </ul>

        </section>


        <!-- =================================================
             EXEMPLO DE LISTA ORDENADA
             ================================================= -->

        <section>

            <h2>Minha ordem de estudo</h2>

            <ol>

                <li>Aprender HTML</li>

                <li>Aprender CSS</li>

                <li>Aprender JavaScript</li>

                <li>Criar projetos</li>

            </ol>

        </section>


        <!-- =================================================
             EXEMPLO DE LINKS
             ================================================= -->

        <section id="contato">

            <h2>Links</h2>

            <p>
                Consulte a documentação para continuar
                estudando:
            </p>

            <a
                href="https://developer.mozilla.org/pt-BR/docs/Web/HTML"
                target="_blank"
            >
                Documentação HTML da MDN
            </a>

        </section>

    </main>


    <!-- =====================================================
         EXEMPLO DE RODAPÉ
         ===================================================== -->

    <footer>

        <p>
            Exemplo didático de HTML — Mini-curso de HTML
        </p>

        <p>
            Este site foi criado exclusivamente para fins
            educacionais.
        </p>

    </footer>

</body>

</html>