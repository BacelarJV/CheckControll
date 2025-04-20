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

 Funcionalidades Adicionais (futuras)

- [ ] Relatórios de gastos por categoria  
- [ ] Gráficos de análise financeira  
- [ ] Exportação de relatórios  

---

## Protótipos de Tela

Os protótipos das telas foram desenvolvidos no Figma com um layout simplificado, limpo e funcional, incluindo interações entre as telas para simulação da navegação.

 [Clique aqui para visualizar os protótipos no Figma](https://www.figma.com/link-do-prototipo-aqui)

---

## Modelagem do Banco

A modelagem do banco de dados foi projetada para armazenar de forma eficiente os dados financeiros do usuário.

###  Diagrama Entidade-Relacionamento

 ![Diagrama](https://drive.google.com/file/d/1Mk-2uRMCTZpyHQpeIMOTZ0TygR6Kudkg/view?usp=sharing)

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

###  Sprint 1 — até Checkpoint 2  
**Objetivo:** Implementar o esqueleto do app e navegação básica  

- [ ] Criar estrutura inicial do projeto  
- [ ] Criar telas de login, dashboard e navegação  
- [ ] Estilização básica  

###  Sprint 2 — até Checkpoint 3  
**Objetivo:** Funcionalidades principais e banco de dados  

- [ ] Implementar banco de dados local e/ou remoto (Supabase)  
- [ ] Habilitar cadastro, login e registro de transações  
- [ ] Criar visualização do saldo e gastos  

###  Sprint 3 — até Checkpoint 4  
**Objetivo:** Finalizar e publicar o app  

- [ ] Refatorar e testar todas as funcionalidades  
- [ ] Implementar recursos extras (gráficos e relatórios)  
- [ ] Gerar e testar o APK  

---

## Ambiente de Desenvolvimento e Ferramentas

- **Front-end:** React Native (Expo)  
- **Back-end:** Supabase  
- **Design:** Figma  
- **Gerenciador de Pacotes:** Yarn  

---

## Executando o Projeto em Ambiente de Desenvolvimento

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/CheckControll.git

# Acesse a pasta
cd CheckControll

# Instale as dependências
yarn

# (Opcional) Instale o TypeScript, se necessário
yarn add typescript@5.3.3 --dev
