
#### Em 2025-1 - 4ª Semestre Curso 📚

**Empresa**: _FAPG(FUndação de Apoio á Pesquisa e Gestão)_
Área de atuação - Pesquisa de pós graduação

## 🚧 Problema  


## 💡 Solução  

---



---


🔗 **Repositório:** [Phoenix Team – API4](https://github.com/Phoenix-Team-Fatec/API-4)

### 🛠️ Tecnologias Utilizadas 📚

| **Tecnologia** | **Funcionalidade / Utilização**                                                                                 |
|----------------|------------------------------------------------------------------------------------------------------------------|
| **React**      | Base para construção do frontend, criando componentes reutilizáveis e telas interativas. |
| **Node.js**    | Ambiente responsável pela execução do backend e processamento das regras de negócio. |
| **JavaScript** | Linguagem utilizada para implementar a lógica da interface e o comportamento dos componentes. |
| **TypeScript** | Utilizado para adicionar tipagem e garantir maior segurança e organização na estrutura do código. |
| **PostgreSQL** | Banco de dados relacional adotado para armazenar e gerenciar as informações da aplicação. |
| **Firebase**   | Serviço usado para autenticação de usuários e gerenciamento de credenciais. |
| **Ollama**     | Ambiente local utilizado para executar os modelos de linguagem integrados ao chatbot. |
| **Git**        | Ferramenta fundamental para versionamento, controle de alterações e colaboração entre os desenvolvedores. |



## 🚀 Contribuições Pessoais
Atuei como **Dev** do projeto API4,n focando na construção de componentes reutilizáveis, integração de formulários com backend e na experiência de gerenciamento de projetos/tarefas. Implementei o modal de cadastro de projetos (`ProjectRegistration`) usando componentes do *shadcn/ui* e estilização dedicada (`ProjectRegistration.css`), criei a página de **Tarefas/Etapas** (`/tasks`) com lógica cliente para adicionar etapas e tarefas e desenvolvi modais auxiliares (`StageModal`, `TaskModal`) para criação/edição. Trabalhei na modularização dos templates e no uso de estados e efeitos (React hooks) para controlar formulários, validações básicas e fluxo de submissão (simulação / integração com endpoints). No back-end participei indiretamente ao validar a necessidade da coluna de exclusão temporal (`proj_data_exclusao`) (migration) e alinhei o front com o formato de dados esperado. Também resolvi pequenos conflitos de merge, padronizei importações/dependências (adição de libs e componentes UI) e apliquei ajustes de CSS/Tailwind para manter coerência visual e responsividade.

**Principais entregas**
- Implementação do componente **ProjectRegistration** (modal de cadastro) com estados controlados, validação básica e estilização em arquivo CSS.  
- Criação da **página de Tarefas/Etapas** (`ProjectTasks`) com UI para listar etapas, adicionar etapas/tarefas dinamicamente e modais de inserção.  
- Desenvolvimento dos componentes **StageModal** e **TaskModal** (dialogs controlados) e seus estilos.  
- Ajustes de layout/global (rota `/tasks` adicionada ao menu, sidebar integrada) e criação de `tasks.css` com regras para cards, listas e responsividade.  
- Suporte na integração com o backend (simulação de fetch, preparação do payload de `projectData`) e alinhamento com a migration `AddProjDataExclusao` para tratamento de exclusões lógicas.  
- Manutenção do repositório: adição/ajuste de dependências (UI libs), resolução de conflitos de merge e organização de arquivos de componente.
 

---

## 🧠💪 Hard Skills

| Tecnologia | Nível               | Descrição                                                                 |
|-----------|----------------------|---------------------------------------------------------------------------|
| **React**        | Com apoio    | Desenvolvimento de componentes funcionais, hooks (`useState`, `useEffect`) e roteamento. |
| **TypeScript**   | Com apoio    | Tipagem aplicada em componentes e organização estrutural.                |
| **JavaScript**   | Autônomo     | Lógica de UI, manipulação de estado e criação de fluxos de formulário.   |
| **Node.js**      | Ouvi falar   | Noção do ambiente servidor e comunicação com endpoints.                   |
| **PostgreSQL**   | Ouvi falar   | Compreensão básica de modelos relacionais e migrations.                   |
| **Firebase**     | Ouvi falar   | Conhecimento conceitual de autenticação e armazenamento NoSQL.            |
| **Ollama**       | Ouvi falar   | Entendimento conceitual do uso de modelos LLM no ambiente local.         |
| **Git/GitHub**   | Autônomo     | Versionamento, resolução de conflitos e trabalho em branches.             |
| **CSS/Tailwind** | Com apoio    | Estilização de componentes, responsividade e criação de arquivos CSS dedicados. |
| **shadcn/ui**    | Com apoio    | Utilização de componentes baseados em Radix para construção de modais e formulários. |




---

## 🤝 Soft Skills


- ### 🤝 Soft Skills (contextualizadas) — API 4 (Gestão de Projetos)

**Comunicação Técnica:** Durante a definição da arquitetura do front-end, dialoguei com o time para evitar que repetíssemos erros da API 3, que havia se tornado extensa por possuir páginas demais. Propus substituir novas rotas por **modais configuráveis** — como no `ProjectRegistration`, `StageModal` e `TaskModal` — e apresentei a vantagem de centralizar fluxos, reduzir navegação e tornar o uso mais intuitivo. Essa comunicação ajudou o grupo a adotar um padrão mais enxuto e consistente de interface.

**Colaboração com Front e Back-end:** Atuei em conjunto com o desenvolvedor responsável pelo backend para alinhar o payload do cadastro de projetos e a nova regra de exclusão lógica (`proj_data_exclusao`). Ajustei a estrutura do `projectData` no front com base nessas validações e auxiliei o time a integrar corretamente cada modal às rotas. Essa colaboração evitou incompatibilidades entre camadas e reduziu retrabalho.

**Resolução de Problemas (UI/UX):** Identifiquei que criar páginas separadas para edição, criação e visualização de entidades tornaria o sistema mais complexo e menos fluido. Como solução, implementei **modais autocontidos** com validação local e controle de estado (React hooks), permitindo criar etapas e tarefas sem sair da página principal. Essa decisão melhorou a experiência do usuário e simplificou a manutenção.

**Organização e Padrões:** Padronizei arquivos de estilo (`ProjectRegistration.css`, `tasks.css`), ajustei importações duplicadas e organizei componentes para torná-los reutilizáveis. Também mantive commits segmentados, evitando que alterações visuais interferissem em lógicas de outros membros. Essa organização ajudou o time a trabalhar com mais segurança no repositório.

**Adaptabilidade:** Por ser um projeto mais moderno (React + TypeScript + shadcn/ui + Tailwind), precisei aprender rapidamente novas bibliotecas e padrões de design system. Adaptei-me ao uso dos Radix Dialogs, responsividade via Tailwind e tipagens do TypeScript para formular componentes mais robustos, mesmo sem ter domínio prévio dessas ferramentas.

**Atenção a UX e detalhamento:** Durante o desenvolvimento das páginas de tarefas, prestei atenção a comportamentos que afetam o fluxo do usuário — como estados de carregamento, controle do fechamento de modais, clareza dos inputs e feedback visual. Essa preocupação garantiu telas mais estáveis e reduz a curva de aprendizado dos usuários do sistema.


