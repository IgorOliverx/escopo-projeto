### Gerenciamento de Plataforma para Cursos Online

#### 1. Escopo

**Definição do Escopo:**

**Incluído no Projeto:**

- **Interface do Usuário:**
    - Página para inscrição em cursos.
    - Página para visualização e participação em aulas.
    - Página para visualização e realização de atividades.

- **Interface do Professor:**
    - Página para criação e gerenciamento de cursos.
    - Página para gerenciamento de conteúdo de curso (aulas e atividades).

- **Funcionalidades:**
    - Sistema de autenticação para professores e alunos.
    - CRUD (Create, Read, Update, Delete) para cursos.
    - Inscrição de alunos em cursos.
    - Gerenciamento de cursos pelos professores.

- **Tecnologias Utilizadas:**
    - PHP com framework Laravel.
    - PostgreSQL.
    - CSS para estilização.

- **Funcionalidades Avançadas:**
    - Painel de controle para professores e alunos.
    - Notificações e atualizações em tempo real.

#### 2. Revisão dos Objetivos

**Objetivos SMART:**

- **Específicos:**
    - Criar um sistema onde professores possam criar e gerenciar cursos e alunos possam se matricular e acessar o conteúdo dos cursos.
    - Desenvolver páginas e funcionalidades para inscrição, visualização de aulas e gerenciamento de atividades.

- **Mensuráveis:**
    - O sistema deve passar em pelo menos 85% dos testes de usabilidade e funcionalidade.

- **Atingíveis:**
    - Alocar uma equipe de desenvolvedores, com marcos semanais para revisão de progresso e garantir a integração dos módulos conforme o cronograma.

- **Relevantes:**
    - Facilita a gestão de cursos online e melhora a experiência de aprendizado para alunos e de ensino para professores.

- **Temporais:**
    - Concluir a implementação e testes da versão beta até o final da sexta semana do projeto.

#### 3. Gestão de Riscos

**3.1 Identificação de Riscos Potenciais:**

- Problemas com a disponibilização de conteúdos.
- Desafios na implementação da interface de usuário.
- Segurança de dados e controle de acesso.

**3.2 Estratégias de Mitigação:**

- **Problemas com Disponibilização de Conteúdos:**
    - Implementar um sistema de upload e gerenciamento de conteúdo robusto e realizar testes exaustivos.

- **Desafios na Implementação da Interface de Usuário:**
    - Desenvolver protótipos e realizar testes de usabilidade regulares com feedback de usuários reais.

- **Segurança de Dados e Controle de Acesso:**
    - Utilizar boas práticas de segurança, como criptografia e controle de acesso baseado em roles, e realizar auditorias de segurança.

#### 4. Cronograma

**Semana 1: Análise de Requisitos e Definição do Escopo**
- Atividades:
    - Reuniões com stakeholders para levantamento de requisitos detalhados.
    - Definir e documentar o escopo do projeto e criar uma arquitetura preliminar.

**Semana 2-3: Implementação do CRUD para Cursos**
- Atividades:
    - Desenvolver as funcionalidades de CRUD (Create, Read, Update, Delete) para cursos.
    - Testar a criação, visualização, edição e exclusão de cursos.

**Semana 4: Implementação do Sistema de Autenticação**
- Atividades:
    - Desenvolver o sistema de autenticação para professores e alunos.
    - Implementar login, registro e recuperação de senha.

**Semana 5: Gerenciamento de Cursos**
- Atividades:
    - Desenvolver funcionalidades para que os professores possam gerenciar o conteúdo dos cursos.
    - Implementar painéis para professores e alunos.

**Semana 6: Documentação e Entrega**
- Atividades:
    - Documentar o sistema e as funcionalidades desenvolvidas.
    - Conduzir uma revisão final, realizar ajustes com base no feedback da versão beta e preparar a entrega do projeto.

#### Diagramas

- **Diagrama de Classe:**
    - **Cursos:** Atributos e métodos relacionados a cursos.
    - **Professores:** Atributos e métodos relacionados a professores.
    - **Alunos:** Atributos e métodos relacionados a alunos.

- **Diagrama de Uso:**
    - **Professor:** Gerencia cursos (cria, edita, exclui cursos).
    - **Aluno:** Acessa conteúdo dos cursos, realiza atividades e visualiza progresso.

- **Diagrama de Fluxo:**
    - **Login → Dashboard do Curso → Gestão de Atividades → Avaliações → Logout.**

Este escopo visa garantir que a plataforma para cursos online atenda às necessidades dos usuários, proporcionando uma experiência eficiente e segura tanto para professores quanto para alunos.


