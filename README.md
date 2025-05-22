<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
  <link rel="stylesheet" href="style.css">
  <title>Portfólio de Luiz Zene</title>
</head>
<body>
  <header class="container text-center mt-4">
    <img src="https://via.placeholder.com/150?text=Avatar" alt="Avatar do Luiz Zene" class="rounded-circle" width="150" height="150">
    <p class="lead">Eu sou <strong>Luiz Zene</strong></p>
    <h1>Sou estudante do 3º Ano A</h1>
    <p>Sou jardineiro e cabo. Desenvolvo paisagismos e reformas de jardins.</p>
    <p><strong>Minhas habilidades:</strong></p>
    <div>
      <span class="badge bg-success">Plantio de plantas</span>
      <span class="badge bg-success">Paisagismo</span>
      <span class="badge bg-success">Informações de invasão</span>
      <span class="badge bg-success">HPPS</span>
      <span class="badge bg-success">CFC</span>
    </div>
  </header>

  <main class="container mt-5">
    <h2>Meus Projetos</h2>
    <div class="row">
      <!-- Projeto 1 -->
      <div class="col-md-4">
        <div class="card">
          <img src="img/projeto-1.png" class="card-img-top" alt="Imagem do projeto">
          <div class="card-body">
            <h5 class="card-title">Projeto de Jardinagem</h5>
            <p class="card-text">Reforma completa de um jardim residencial com foco em flores nativas e uso de irrigação automática.</p>
            <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal1">Veja o projeto</button>
          </div>
        </div>
      </div>

      <!-- Projeto 2 -->
      <div class="col-md-4">
        <div class="card">
          <img src="img/projeto-2.png" class="card-img-top" alt="Imagem do projeto">
          <div class="card-body">
            <h5 class="card-title">Paisagismo Sustentável</h5>
            <p class="card-text">Projeto voltado para sustentabilidade com reaproveitamento de água e iluminação solar.</p>
            <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal2">Veja o projeto</button>
          </div>
        </div>
      </div>

      <!-- Projeto 3 -->
      <div class="col-md-4">
        <div class="card">
          <img src="img/projeto-3.png" class="card-img-top" alt="Imagem do projeto">
          <div class="card-body">
            <h5 class="card-title">Horta Escolar</h5>
            <p class="card-text">Desenvolvimento de uma horta em escola pública com participação dos alunos.</p>
            <button type="button" class="btn btn-link" data-bs-toggle="modal" data-bs-target="#modal3">Veja o projeto</button>
          </div>
        </div>
      </div>
    </div>
  </main>

  <!-- Modais dos Projetos (mesma estrutura que você já tem) -->
  <!-- Modal 1, Modal 2, Modal 3 - pode reutilizar e editar os conteúdos como desejar -->

  <footer class="container py-5">
    <h2>Entre em contato</h2>
    <div>
      <i class="bi bi-github"></i>
      <a href="https://github.com/seu-usuario">GitHub</a>
    </div>
    <p class="my-5 text-center">© 2025. Desenvolvido por Luiz Zene</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
