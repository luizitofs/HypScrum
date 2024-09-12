# HypScrum

## Descrição

Este projeto é um sistema web desenvolvido para guiar os usuários no aprendizado do Scrum. O sistema inclui seções de instrução com avaliações e um mecanismo para emissão de certificados de conclusão do curso. Ele é construído utilizando HTML, CSS, JavaScript e PostgreSQL, e as telas foram prototipadas no Figma.

## Tecnologias Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** JavaScript (Node.js)
- **Banco de Dados:** PostgreSQL
- **Prototipação:** Figma
<!-- - **Hospedagem:** [Nome do serviço de nuvem utilizado] -->
- **Controle de Versão e Documentação:** GitHub

## Funcionalidades

### Requisitos Funcionais

- **RF.01** Navegação por menu comum para acesso às seções.
- **RF.02** Auto-cadastro com nome, e-mail e senha.
- **RF.03** Autenticação com e-mail e senha.
- **RF.04** Cadastro de questões no SGBD PostgreSQL.
- **RF.05** Exibição de 3 questões por tópico para usuários logados.
- **RF.06** Acesso ao conteúdo do curso para usuários não logados, sem visualização das questões.
- **RF.07** Respostas ilimitadas às questões até a aprovação.
- **RF.08** Exibição de questões apenas nos tópicos não aprovados.
- **RF.09** Emissão de certificados para usuários aprovados em todos os tópicos.
- **RF.10** Cadastro de questões pelo administrador diretamente no PostgreSQL.

### Requisitos Não Funcionais

- **RNF.01** Distribuição de conteúdo em páginas com princípios de arquitetura de informação.
- **RNF.02** Sequência lógica nas páginas com navegação entre páginas.
- **RNF.03** Curso cobrindo conhecimentos necessários para o aprendizado do Scrum.
- **RNF.04** Sequência lógica de aprendizado do Scrum.
- **RNF.05** Questões compatíveis com o conteúdo do tópico.
- **RNF.06** Visual responsivo.

## Estrutura do Projeto

- **Frontend:** 
  - `index.html` - Página inicial e navegação.
  - `styles.css` - Estilos do projeto.
  - `script.js` - Lógica de interação do usuário.

- **Backend:**
<!--  - `server.js` - Servidor Node.js.
  - `routes/` - Rotas da API.
  - `controllers/` - Lógica de controle.
  - `models/` - Modelos de dados.
  - `config/` - Configurações de banco de dados e outras. -->

- **Banco de Dados:**
 <!-- - `schema.sql` - Estrutura do banco de dados PostgreSQL.
  - `seed.sql` - Dados iniciais para desenvolvimento e testes. -->

- **Prototipação:**
  - `figma/` - Arquivos de prototipação no Figma.

## Configuração do Projeto

### Pré-requisitos

- Node.js
- PostgreSQL

### Instalação

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Hypogram-Technologies/HypScrum]
   cd [HypScrum]
