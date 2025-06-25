<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">

</head>
<body>
  <h1>ProjetoAPI</h1>
  <section>
    <h2>Descrição</h2>
    <p>O <strong>ProjetoAPI</strong> é uma API RESTful simples desenvolvida para fornecer informações sobre produtos. Ela permite realizar operações de consulta, adição, atualização e remoção de produtos em um banco de dados fictício.</p>
  </section>
  <section>
    <h2>Como Usar</h2>
    <p>Para utilizar a API, basta enviar requisições HTTP para os endpoints especificados abaixo:</p>
    <ul>
      <li><strong>GET /produtos</strong> — Lista todos os produtos.</li>
      <li><strong>GET /produtos/{id}</strong> — Retorna informações de um produto específico.</li>
      <li><strong>POST /produtos</strong> — Adiciona um novo produto.</li>
      <li><strong>PUT /produtos/{id}</strong> — Atualiza um produto existente.</li>
      <li><strong>DELETE /produtos/{id}</strong> — Remove um produto.</li>
    </ul>
  </section>
  <section>
    <h2>Exemplo de Requisição</h2>
    <pre>
      <code>
POST /produtos
Content-Type: application/json

{
  "nome": "Produto Exemplo",
  "preco": 99.90
}
      </code>
    </pre>
  </section>
  <section>
    <h2>Autenticação</h2>
    <p>Esta API não requer autenticação para uso básico.</p>
  </section>
  <section>
    <h2>Contato</h2>
    <p>Para dúvidas ou sugestões, entre em contato pelo <a href="mailto:victor.gabriel63@aluno.ifce.edu.br">email</a>.</p>
  </section>
</body>
