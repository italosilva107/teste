<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Clientes Atendidos - Ítalo</title>
  <style>
    body { font-family: Arial, sans-serif; background-color: #f5f5f5; margin: 0; padding: 0; }
    header { background-color: #111; color: white; text-align: center; padding: 2rem 1rem; }
    h1 { margin: 0; font-size: 2rem; }
    .intro { text-align: center; margin: 2rem; font-size: 1.2rem; }
    .clientes { display: flex; flex-wrap: wrap; justify-content: center; gap: 1.5rem; padding: 2rem; }
    .card { background: white; border-radius: 10px; box-shadow: 0 4px 10px rgba(0,0,0,0.1); width: 300px; padding: 1rem; text-align: center; }
    .card img { width: 100px; height: 100px; border-radius: 50%; object-fit: cover; margin-bottom: 1rem; }
    footer { background-color: #111; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>

  <header>
    <h1>Clientes Atendidos</h1>
    <p>Confira algumas pessoas que confiaram no meu trabalho</p>
  </header>

  <div class="intro">
    <p>Esses são alguns dos clientes que tive o prazer de atender com transparência, qualidade e confiança.</p>
  </div>

  <section class="clientes">

    <!-- Cliente 1 -->
    <div class="card">
      <img src="cliente1.jpg" alt="Foto do cliente 1" />
      <h3>João Silva</h3>
      <p>Financiou um carro com a melhor taxa!</p>
    </div>

    <!-- Cliente 2 -->
    <div class="card">
      <img src="cliente2.jpg" alt="Foto do cliente 2" />
      <h3>Maria Oliveira</h3>
      <p>Conseguiu aprovação rápida no financiamento do imóvel.</p>
    </div>

    <!-- Cliente 3 -->
    <div class="card">
      <img src="cliente3.jpg" alt="Foto do cliente 3" />
      <h3>Lucas Pereira</h3>
      <p>Site personalizado para sua barbearia!</p>
    </div>

    <!-- Adicione mais clientes conforme quiser -->
  </section>

  <footer>
    <p>© 2025 Ítalo Saraiva - Todos os direitos reservados</p>
  </footer>

</body>
</html>
