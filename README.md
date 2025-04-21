# CheckControll

O **CheckControll** é um aplicativo de controle financeiro pessoal desenvolvido para facilitar a gestão de despesas e ganhos do usuário de forma prática e intuitiva. Este projeto foi criado como parte da disciplina de Desenvolvimento de Projetos para Dispositivos Móveis.

## Sobre o App

O CheckControll tem como objetivo principal auxiliar o usuário no acompanhamento de sua vida financeira, permitindo o registro, visualização e análise de gastos e ganhos.

### Funcionalidades Básicas

- [ ] Cadastro e login de usuários com autenticação segura  
- [ ] Exibição do saldo atual  
- [ ] Registro de despesas mensais (ex.: contas fixas como água e luz)  
- [ ] Registro de gastos de crédito (ex.: compras esporádicas como delivery)  
- [ ] Visualização e edição de transações  

### Funcionalidades Adicionais (Futuras)

- [ ] Relatórios de gastos por categoria  
- [ ] Gráficos de análise financeira  
- [ ] Exportação de relatórios  

---

## Protótipos de Tela

Os protótipos foram desenvolvidos no Figma, com layout simplificado e interações configuradas para simular a navegação.

[Visualizar protótipos no Figma](https://www.figma.com/design/znDL8Yh8zt1lTZ8h8npwlO/Untitled?node-id=0-1&t=WTlSB0BuR6QSVpDz-1)

---

## Modelagem do Banco

A modelagem do banco de dados foi projetada para organizar e armazenar de forma eficiente os dados financeiros do usuário.

[Visualizar Diagrama no Google Drive](https://drive.google.com/file/d/1I73mhr_iGKOLQrDgm9EqLU0REFDAoEvv/view?usp=sharing)

### Estrutura das Tabelas

- **Usuario**  
  `id`, `primeiro_nome`, `ultimo_nome`, `apelido`, `senha`

- **Gastos_Mensais**  
  `id`, `usuario_id`, `nome`, `valor`, `data_hora_gasto`

- **Gastos_Credito**  
  `id`, `usuario_id`, `nome`, `valor`, `data_hora_gasto`

- **Ganhos_Mensais**  
  `id`, `usuario_id`, `nome`, `valor`, `data_hora_ganho`

---

## Planejamento de Sprints

### Sprint 1 — até Checkpoint 2  
**Objetivo:** Implementar o esqueleto do app e navegação básica  

- [ ] Criar estrutura inicial do projeto  
- [ ] Criar telas de login, dashboard e navegação  
- [ ] Estilização básica  

### Sprint 2 — até Checkpoint 3  
**Objetivo:** Funcionalidades principais e banco de dados  

- [ ] Implementar banco de dados local e/ou remoto (Supabase)  
- [ ] Habilitar cadastro, login e registro de transações  
- [ ] Criar visualização do saldo e gastos  

### Sprint 3 — até Checkpoint 4  
**Objetivo:** Finalizar e publicar o app  

- [ ] Refatorar e testar todas as funcionalidades  
- [ ] Implementar recursos extras (gráficos e relatórios)  
- [ ] Gerar e testar o APK  

---

## Ambiente de Desenvolvimento e Ferramentas

- **Front-end:** React Native (Expo)  
- **Back-end:** MySQL  
- **Design:** Figma  
- **Gerenciador de Pacotes:** Yarn  
