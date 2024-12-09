# Piloto-SeducON
https://gersonsantiago95.github.io/Piloto-SeducON/

**Projeto: Sistema de Gestão de Unidades Escolares**

**Objetivo**:
Desenvolver uma aplicação web para gerenciar planilhas piloto das unidades escolares, com funcionalidades para cadastro, inserção, atualização e remoção de alunos, salas de aula, professores, funcionários e escolas. A aplicação deve permitir uma gestão centralizada e organizada de todas as informações educacionais de uma rede escolar, incluindo relatórios e atualizações mensais.

### Funcionalidades Principais:

1. **Cadastro de Escolas**:
   - Interface para adicionar, remover e editar escolas.
   - Informações: nome, endereço, contato e diretoria responsável.

2. **Cadastro de Salas de Aula**:
   - Adicionar e remover salas de aula.
   - Associar salas com séries, turnos e escolas.

3. **Cadastro de Professores**:
   - Registrar e atualizar dados dos professores (nome, disciplina, e-mail, telefone).
   - Associar professores às salas de aula e escolas.

4. **Cadastro de Funcionários**:
   - Adicionar e gerenciar funcionários administrativos e de apoio para cada escola.

5. **Inserir e Remover Alunos**:
   - Formulário para adicionar alunos com informações completas (nome, idade, série, etc.).
   - Associar alunos a uma sala de aula específica em uma escola.
   - Opção para remover alunos ou atualizar seus dados.

6. **Relatórios**:
   - Gerar relatórios de alunos por escola, professores por sala de aula, etc.
   - Relatórios personalizados por filtros (escola, série, professor).

7. **Tela de Atualizações Mensais**:
   - Exibir um resumo mensal de todas as alterações no sistema (inserções, remoções, atualizações).
   - Filtros por tipo de alteração e escola específica.
   - Histórico de alterações com data, tipo de mudança e responsável.
   - Notificações para visualização de mudanças recentes.
   - Relatórios exportáveis (PDF, Excel).

8. **Painel Administrativo**:
   - Dashboard para visualizar o status geral das escolas, com contagem de alunos, professores e funcionários.
   - Interface intuitiva para navegação e gerenciamento de recursos.

### Perfis de Acesso:

1. **Administrador Geral**:
   - Acesso total a todas as funcionalidades do sistema.
   - Gerenciamento de todos os usuários e permissões.
   - Criação, edição e exclusão de escolas, salas, professores, funcionários e alunos.
   - Acesso completo aos relatórios e tela de atualizações mensais.
   - Configuração de backups e controle de usuários.

2. **Gestor Municipal**:
   - Acesso total a todas as escolas sob sua jurisdição.
   - Gerenciamento de escolas, relatórios e atualizações mensais.
   - Acesso aos dados gerais das escolas, sem capacidade para alterar dados individuais de professores ou funcionários.
   - Visualização de relatórios consolidados e estatísticas.

3. **Gestor Escolar**:
   - Gerenciamento completo de uma ou mais escolas específicas.
   - Adicionar, editar e remover alunos, professores, funcionários e salas dentro de sua escola.
   - Acesso a relatórios e atualizações mensais da sua escola.
   - Gerenciamento de informações relacionadas a sua escola.

4. **Secretário de Escola**:
   - Inserção e atualização de dados de alunos, professores e funcionários.
   - Acesso para visualizar e atualizar informações da escola, incluindo relatórios e estatísticas específicas da escola.
   - Gerenciamento de dados administrativos, mas não possui permissões para alterar configurações gerais ou de outros usuários.

5. **Funcionário em Geral**:
   - Acesso restrito a funções administrativas específicas, como atualização de dados pessoais e registros.
   - Visualização limitada a dados e relatórios relevantes para suas funções.
   - Não tem acesso a relatórios ou dados fora do escopo de suas tarefas.

6. **Professor**:
   - Acesso para visualizar e atualizar suas próprias informações e dados relacionados às suas turmas.
   - Acesso a relatórios de desempenho e registros dos alunos que estão sob sua responsabilidade.
   - Não tem permissão para alterar dados administrativos ou de outros professores.

### Tecnologias Sugeridas:

- **Front-end**: HTML, CSS, JavaScript.
- **Back-end**: Google Apps Script ou Node.js (dependendo da complexidade e do banco de dados necessário).
- **Banco de Dados**: Planilhas Google ou Firebase/NoSQL (para uma solução mais robusta).
- **Hospedagem**: GitHub Pages (para a parte estática) ou Google Apps Script (para a lógica do backend).

### Fluxo da Aplicação:

1. **Tela de Login**:
   - Autenticação para diferentes tipos de usuários (administradores, gestores, etc.).

2. **Painel Principal**:
   - Exibe gráficos e resumos das principais informações (número de alunos, professores, salas, funcionários).
   - Link para a **tela de atualizações mensais**.

3. **Tela de Atualizações Mensais**:
   - Resumo das mudanças mais recentes.
   - Filtros por mês, tipo de alteração e escola.
   - Opção para exportar relatórios e baixar backup.

4. **Seção de Relatórios e Gestão**:
   - Gerenciamento de alunos, professores, salas, funcionários e escolas com inserção, remoção e atualização de dados.

5. **Funcionalidades Adicionais**:
   - **Controle de Usuários**: Sistema de permissões e registro de atividades.
   - **Backup Automático**: Sistema de backup mensal dos dados.
   - **Design Responsivo**: Interface acessível em dispositivos móveis e tablets.
   - **Dashboard Personalizado**: Gráficos e estatísticas sobre o número de novos alunos, professores e funcionários.
