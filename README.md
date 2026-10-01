# PaoLab Admin — Painel Web

> Painel administrativo web para o ecossistema **PaoLab**, desenvolvido para a disciplina de Desenvolvimento de Aplicações Backend com Framework (TSI35D-EAD — UTFPR), utilizando Laravel.

## Sobre o projeto

O PaoLab é um app mobile (React Native + Expo) voltado para padeiros artesanais, desenvolvido na disciplina de Projeto/Prototipação de Apps Móveis. Ele funciona como um diário de fermentação, com cálculo de hidratação, consulta de clima, avaliação sensorial de receitas e armazenamento offline.

Este projeto nasce como o **backoffice web** desse mesmo domínio: uma aplicação Laravel, renderizada no servidor (Blade), para administrar os dados que hoje vivem apenas no app — farinhas, fermentações, avaliações e usuários (padeiros) — de forma centralizada.

> Repositório separado do mobile: o código deste projeto é uma implementação nova, feita especificamente para esta disciplina, ainda que compartilhe o domínio e a modelagem conceitual do PaoLab mobile ([repositório do app](https://github.com/erickserpe/pao-lab-mobile)).

## Motivação

Padeiros artesanais controlam receitas, tempos de fermentação e avaliações de forma dispersa (cadernos, planilhas, memória). O app mobile resolve o registro individual; este painel resolve a **gestão centralizada**: permite visualizar e administrar dados de múltiplos padeiros, cadastrar farinhas de referência e acompanhar avaliações sensoriais em um único lugar.

## Objetivos

- Aplicar na prática os conceitos da disciplina (Blade, TailwindCSS, Forms e Validação, Autenticação, Migrations/Eloquent, Policies) em um projeto com domínio real e já validado.
- Construir um painel web funcional que complementa o ecossistema PaoLab.

## Funcionalidades planejadas

- [ ] Autenticação de administrador (login)
- [ ] CRUD de farinhas (cadastro, edição, listagem, exclusão)
- [ ] Listagem e visualização de fermentações registradas pelos padeiros
- [ ] Listagem e visualização de avaliações sensoriais
- [ ] Gestão de usuários (padeiros) cadastrados
- [ ] Regras de autorização (Policies): cada padeiro só edita seus próprios registros; administrador tem acesso amplo
- [ ] Validação de formulários (ex: cadastro/edição de farinha)

## Stack

- Laravel (PHP)
- Blade (views renderizadas no servidor)
- TailwindCSS
- Eloquent ORM / Migrations

## Artefatos de engenharia de software

Ver pasta [`docs/`](./docs) — contém modelagem do banco de dados (DER), levantamento e priorização de requisitos (MoSCoW) e protótipos de tela.

- Protótipos de tela (referência do domínio, feitos originalmente para o app mobile): [Figma — PaoLab Mobile](https://www.figma.com/design/cpvoitQcVrBi2hYD4pNeCO/pao-lab-moblie)

## Vídeo de apresentação

_(link a ser adicionado)_
