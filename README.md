
---

## 🧰 **PASSO 3 — IMPLEMENTAR ACESSIBILIDADE NO HTML**

Adicione nas suas páginas:
```html
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Plataforma Social</title>
  <link rel="stylesheet" href="css/style.css">
  <link rel="stylesheet" href="css/responsive.css">
  <link rel="stylesheet" href="css/high-contrast.css">
</head>
<body>
  <header role="banner">
    <nav role="navigation" aria-label="Menu principal">
      <ul>
        <li><a href="index.html" data-link>Início</a></li>
        <li><a href="projetos.html" data-link>Projetos</a></li>
        <li><a href="cadastro.html" data-link>Cadastro</a></li>
      </ul>
    </nav>
  </header>
  <main id="content" role="main">
    <!-- conteúdo -->
  </main>
  <footer role="contentinfo">
    <p>© 2025 - Todos os direitos reservados</p>
  </footer>
</body>
</html>
