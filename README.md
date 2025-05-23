<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Projeto Fábrica de Projetos</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="font-sans bg-gray-50 text-gray-800">


  <header class="bg-gray-800 shadow sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center text-white">
      <img src="./assets/image/logo-eficaz.svg">
      <h1 class="text-xl  font-bold">Fábrica de Projetos</h1>
      <nav class="space-x-6">
        <a href="#disciplina" class="hover:text-blue-600">Disciplina</a>
        <a href="#empresa" class="hover:text-blue-600">Empresa</a>
        <a href="#projeto" class="hover:text-blue-600">Projeto</a>
        <a href="#membros" class="hover:text-blue-600">Membros</a>
      </nav>
    </div>
  </header>

  <section id="disciplina" class="py-16 px-6 max-w-4xl mx-auto  bg-white mb-6">
    <h2 class="text-3xl font-semibold mb-4">Sobre a Disciplina</h2>
    <p>A Fábrica de Projetos busca integrar as demais disciplinas por meio da criação de projetos funcionais de acordo com a necessidade da empresa escolhida por sala.</p>
  </section>

  <section id="empresa" class="py-16 px-6 max-w-4xl mx-auto bg-white mb-6">
    <h2 class="text-3xl font-semibold mb-4">Sobre a Empresa</h2>
    <p>A Eficaz Marketing e Tecnologia esta há 10 anos no mercado, possui o mais alto nível de parceria com a Google, sendo reconhecidos nacionalmente como Agência Google Partner Premier, Meta Business Partner e Yango Partner, com prêmio internacional. Suas especialidades são E-Commerce e Publicidade Online.</p>
  </section>

  <section id="projeto" class="py-16 px-6 max-w-4xl mx-auto  bg-white mb-6">
    <h2 class="text-3xl font-semibold mb-4">Tema do Projeto</h2>
    <p>A empresa demanda um grande recurso de tempo para a inserção de novos clientes no sistema da empresa e envio de e-mails de boas-vindas e apresentação dos serviços por ela prestados. Dessa forma o sistema tem o objetivo de automatizar o cadastro dos novos clientes, desde a entrada dos mesmos por meio de um formulário, a validação dos dados inseridos, a sua inserção no banco de dados e o disparo, também automático. de e-mails de boas-vindas e oferta de serviços.</p>
  </section>

  <section id="membros" class="py-16 px-6 max-w-4xl mx-auto bg-white">
    <h2 class="text-3xl font-semibold mb-10 text-center">Membros do Grupo</h2>
    <div class="grid md:grid-cols-2 lg:grid-cols-2 gap-8">
      
      <div class="bg-gray-100 p-4 rounded-lg shadow ml-12 text-center">
        <img src="./assets/image/felipe.jpeg" alt="Foto Membro" class="w-32 h-32 rounded-full mx-auto mb-4">
        <h3 class="text-xl font-medium">Felipe Meireles</h3>
        <p class="text-sm text-gray-600">Responsável pela criação do banco de dados do sistema e a parte de Back-End.</p>
      </div>

      <div class="bg-gray-100 p-4 rounded-lg shadow ml-12 text-center">
        <img src="./assets/image/larissa.jpeg" alt="Foto Membro" class="w-32 h-32 rounded-full mx-auto mb-4">
        <h3 class="text-xl font-medium">Larissa Custódio</h3>
        <p class="text-sm text-gray-600">Responsável pela criação do Front-End do projeto e a inserção da API Verificadora de Dados.</p>
        </div>

      <div class="bg-gray-100 p-4 rounded-lg shadow ml-12 text-center">
        <img src="./assets/image/marcela.jpeg" alt="Foto Membro" class="w-32 h-32 rounded-full mx-auto mb-4">
        <h3 class="text-xl font-medium">Marcela Buzzo</h3>
        <p class="text-sm text-gray-600">Responsável pela criação do Front-End do projeto e a inserção da API Verificadora de Dados.</p>
      </div>

      <div class="bg-gray-100 p-4 rounded-lg shadow ml-12 text-center">
        <img src="./assets/image/matheus.jpeg" alt="Foto Membro" class="w-32 h-32 rounded-full mx-auto mb-4">
        <h3 class="text-xl font-medium">Matheus Salvador</h3>
        <p class="text-sm text-gray-600">Responsável pela criação do banco de dados do sistema e a parte de back-end.</p>
      </div>

    </div>
  </section>

  <footer class="text-center py-6 text-sm text-gray-500">
    Grupo Fábrica de Projetos Ágeis
  </footer>
</body>
</html>
