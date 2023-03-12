<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#sobre">Sobre</a></li>
          <li><a href="#servicos">Serviços</a></li>
          <li><a href="#contato">Contato</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="sobre">
        <h1>Sobre Nós</h1>
        <p>Somos uma empresa especializada em desenvolvimento de sites e aplicativos web. Oferecemos soluções personalizadas para atender às suas necessidades e objetivos de negócios.</p>
      </section>
      <section id="servicos">
        <h1>Nossos Serviços</h1>
        <ul>
          <li>Desenvolvimento de sites</li>
          <li>Otimização de sites para motores de busca</li>
          <li>Integração de mídias sociais</li>
          <li>Manutenção de sites</li>
        </ul>
      </section>
      <section id="contato">
        <h1>Entre em Contato</h1>
        <form action="enviar_mensagem.php" method="post">
          <label for="nome">Nome:</label>
          <input type="text" id="nome" name="nome">
          <label for="email">E-mail:</label>
          <input type="email" id="email" name="email">
          <label for="mensagem">Mensagem:</label>
          <textarea id="mensagem" name="mensagem"></textarea>
          <input type="submit" value="Enviar">
        </form>
      </section>
    </main>
    <footer>
      <p>Todos os direitos reservados</p>
    </footer>
  </body>
