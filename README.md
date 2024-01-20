<h1>Rentx - Sistema de Aluguel de Carros</h1>
<p>
  O Rentx é uma API para gestão de aluguel de carros, desenvolvida pela Rocketseat. Utilizando tecnologias como Node.js,
  TypeScript, TypeORM, PostgreSQL e Docker, a aplicação oferece funcionalidades como cadastro de carros, listagem, especificações,
  imagens, aluguel, devolução, e recuperação de senha.
</p>

<h2>Tecnologias</h2>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nodejs" title="NodeJS" height="60" width="60" />
    <img src="https://skillicons.dev/icons?i=ts" title="Typescript" height="60" width="60" />
    <img src="https://skillicons.dev/icons?i=postgres" title="Postgresql" height="60" width="60" />
    <img src="https://skillicons.dev/icons?i=docker" title="Docker" height="60" width="60" />
    <img src="https://raw.githubusercontent.com/typeorm/typeorm/master/resources/logo_big.png" title="TypeORM" height="60" width="150" />
  </a>
</p>

<h2>Funcionalidades</h2>

<ul>
    <li><strong>Cadastro de Carro:</strong> Cadastrar novos carros com placa única. Carros são registrados com disponibilidade por padrão. Apenas usuários administradores podem realizar o cadastro.</li>
    <li><strong>Listagem de Carros:</strong> Listar todos os carros disponíveis. Filtrar carros por nome da categoria, marca e modelo.</li>
    <li><strong>Cadastro de Especificação no Carro:</strong> Cadastrar especificações para um carro existente. Restrições aplicadas para garantir integridade dos dados.</li>
    <li><strong>Cadastro de Imagens do Carro:</strong> Cadastrar imagens para um carro utilizando o multer para upload.</li>
    <li><strong>Aluguel de Carro:</strong> Cadastrar aluguel com duração mínima de 24 horas. Restrições para evitar múltiplos aluguéis para o mesmo usuário ou carro. Alteração do status do carro para indisponível durante o aluguel.</li>
    <li><strong>Devolução de Carro:</strong> Realizar a devolução de um carro. Cálculo automático do valor total do aluguel. Aplicação de multa proporcional ao atraso, se houver.</li>
    <li><strong>Listagem de Alugueis para Usuário:</strong> Buscar todos os alugueis associados a um usuário logado.</li>
    <li><strong>Recuperar Senha:</strong> Recuperar a senha através do e-mail. Link de recuperação com expiração de 3 horas.</li>
</ul>

<h2>Especificações</h2>

<div class="badge badge-green">Node.js v14.17.5</div>
<div class="badge badge-blue">TypeScript v4.4.2</div>
<div class="badge badge-red">TypeORM v0.2.37</div>
<div class="badge badge-blue">PostgreSQL v13.3</div>
<div class="badge badge-lightgrey">Docker v20.10.8</div>

<p>
