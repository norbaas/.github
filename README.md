# Norbaas Tecnologias

Este é um desafio de login via pull requests no GitHub. Este documento tem a responsabilidade de alinhar as contribuições de acordo com os padrões estabelecidos no mesmo. Em caso de dúvidas, [nossa página no github](https://github.com/norbaas).

## Objetivo do desafio
Conhecer como cada candidato organiza a lógica de registro de um usuário, os cuidados que na hora de adicionar middleware, descrição de schema de banco de dados e a sequência de commits.

## Regras do desafio

1. Crie um fork deste repositório.
2. Envie seus commits em português.
3. Insira um pequeno resumo sobre o que foi adicionado.
4. Solicite um pull request no repositório.
5. Utilize o ORM Prisma
6. O Banco de dados deve ser PostgreSQL

## Ferramentas do Desafio

1. A base de framework será o [Next.js](https://nextjs.org/)
2. Frameworks de autenticação [Auth.js](https://authjs.dev/)
3. Banco de dados PostgreSQL [Neon PostgreSQL](https://neon.tech/)

## Passos do desafio
1. Crie um fork deste repositório
2. Instale o Auth.js como framework de login
3. Organize suas pastas
4. Cria uma rota autenticada chamada /dash
5. Gerar uma lógica de OTP de 6 dígitos antes de enviar para a rota autenticada.
6. Envie um e-mail de boas-vindas para seus usuários cadastrados

## Detalhamento do desafio

Uma vez realizado o fork do repositório e instalado o Auth.js, você precisa criar 3 campos.
* Nome completo
* Email
* Senha

Criar a rota de autenticação de login e a lógica de OTP que será necessário quando o seu usuário criar seu cadastro você deve enviar via e-mail os códigos de 6 dígitos para validar o cadastro.

Assim que o usuário validar seu cadastro via OTP de 6 dígitos, fazer um push para a rota autenticada /dash

* Serviço para envio de e-mail é escolha do candidato
* Dúvidas enviar e-mail para ola@norbaas.com.br
* O prazo de entrega são 7 dias

## Ajuda
* Fluxo de autenticação em [Next.js](https://nextjs.org/docs/app/building-your-application/authentication)
* Documentação de integração do [Auth.js](https://authjs.dev/getting-started/installation)
* Documentação de conexão do Banco de dados [Neon](https://neon.tech/docs/get-started-with-neon/connect-neon)

Post de ajuda para suporte de OTP: [Guia do OTP](https://www.linkedin.com/pulse/ditching-magic-links-otp-tutorial-nextjs-nextauth-will-olson-smo3c/)
