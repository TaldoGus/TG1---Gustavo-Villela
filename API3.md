
#### Em 2024-2 - 3ª Semestre Curso 📚

**Empresa**: _Youtan - (PIT)_
Representante - Fátima.
<br>
Área de Atuação : Desenvolvimento de Software

## 🚧 Problema  
A empresa parceira enfrentava dificuldades significativas para acompanhar o clima organizacional e compreender, de forma estruturada, como os colaboradores percebiam aspectos como autonomia, liderança e relacionamento com suas equipes. A ausência de um processo padronizado de coleta de informações gerava dados inconsistentes, pouca confiabilidade e a impossibilidade de analisar a evolução dos colaboradores ao longo do tempo. Essas limitações prejudicavam diretamente a tomada de decisões do RH, dificultavam a identificação de problemas reais dentro da empresa e comprometiam a comunicação entre líderes, liderados e gestores.


## 💡 Solução  
Para resolver esses desafios, foi desenvolvida uma aplicação web capaz de centralizar, organizar e interpretar avaliações internas de maneira clara e acessível. O sistema permite a criação e o gerenciamento de diferentes tipos de formulários — incluindo autoavaliação, avaliação de líder e avaliação de liderado — além de oferecer dashboards dinâmicos que apresentam métricas, gráficos comparativos e histórico temporal. Essa solução possibilita que colaboradores, líderes e administradores acompanhem suas informações de forma personalizada, enquanto o RH obtém análises globais e comparações precisas entre diferentes perspectivas. A aplicação também conta com filtros por período e suporte para geração de relatórios, garantindo que a evolução individual e coletiva possa ser acompanhada ao longo do tempo.

---
<details>
<summary><strong>👥 Níveis de acesso e gráficos comparativos</strong></summary>
<br>

### 🔐 Modos de Acesso

**Administrador (RH):**  
- Acesso completo ao sistema  
- Criação de equipes, usuários e formulários  
- Visualização global de autoavaliações, avaliações de líder e de liderado  
- Dashboard com sobreposição dos três conjuntos de dados  

**Líderes:**  
- Visualizam o próprio dashboard pessoal  
- Têm acesso às autoavaliações dos liderados  
- Podem comparar suas avaliações (Líder → Liderado) com a visão dos próprios colaboradores  

**Liderados (colaboradores):**  
- Têm acesso apenas ao seu **Dashboard Pessoal**  
- Podem acompanhar sua evolução ao longo do tempo  
- Visualizam categorias e indicadores definidos pelo RH  

---

### 📊 Gráficos e Comparações

O sistema apresenta gráficos interativos que permitem:

- Comparar **autoavaliação × avaliação do líder**  
- Comparar **autoavaliação × avaliação do liderado**  
- Analisar evolução temporal por categoria (ex.: comunicação, autonomia, desempenho)  
- Visualizar discrepâncias entre percepções internas da equipe  
- Baixar relatórios completos em **PDF**

Essas comparações dão ao RH e aos líderes uma visão objetiva, histórica e fundamentada das relações internas de trabalho.

</details>

---


🔗 **Repositório:** [Phoenix Team – OAK-RH](https://github.com/Phoenix-Team-Fatec/OAK-RH)

### 🛠️ Tecnologias Utilizadas 📚

| **Tecnologia** | **Funcionalidade / Utilização**                                                                                 |
|----------------|------------------------------------------------------------------------------------------------------------------|
| **TypeScript** | Utilizado para garantir maior segurança na aplicação através de tipagem estática e código estruturado. |
| **React**      | Desenvolvimento da interface do usuário (frontend) com componentes reutilizáveis e comportamento dinâmico.       |
| **JavaScript** | Implementação da lógica de interação, manipulação do estado e integração entre os módulos do sistema.  |
| **Node.js**    | Ambiente de execução responsável por sustentar a aplicação no servidor e processar funcionalidades do backend. |
| **PostgreSQL** | Banco de dados relacional usado para organizar e armazenar informações estruturadas da plataforma.     |
| **Firebase**   | Suporte para autenticação e armazenamento adicional via banco NoSQL, ampliando as capacidades da aplicação. |
| **Git**        | Controle de versão e gerenciamento colaborativo das tarefas, garantindo histórico e organização do projeto. |


## 🚀 Contribuições Pessoais
Atuei como **Product Owner (PO)** do projeto OAK-RH, sendo o principal ponto de contato entre o time e a cliente (Fátima, da Youtan). Minhas atividades e entregas incluíram:

- **Levantamento e validação de requisitos com a cliente:** elaborei e enviei perguntas concretas sobre a distribuição dos formulários (autoavaliação, avaliação de líder, avaliação de liderado), solicitei esclarecimentos sobre cenários fora do padrão e consolidei as respostas da cliente em regras de negócio claras para o time.  
- **Definição da lógica de distribuição dos formulários:** padronizei o fluxo (quem recebe qual formulário em função de papel/estrutura hierárquica) e documentei exceções (e.g., equipes horizontais, grandes equipes, casos de líder que também é liderado).  
- **Especificação dos Dashboards:** desenhei os requisitos funcionais para os três dashboards principais — **Dashboard Pessoal**, **Dashboard dos Liderados** e **Dashboard Geral (Admin)** — incluindo métricas, comparações (autoavaliação × avaliação de líder × avaliação de liderado), filtros por período e necessidade de visualização histórica.  
- **Critérios de comparações e filtros:** defini regras de comparação (por tempo, por tipo de avaliação e por sobreposição de conjuntos de dados) e requisitos para filtros por data e exportação em PDF (requisitos aceitos como parte do MVP).  
- **Interface e prototipação:** trabalhei no protótipo das telas  (estrutura de informação, categorias, organização dos cards e fluxos de navegação) e alinhei com a cliente as prioridades visuais e funcionais a serem implementadas pelo time de frontend (React), um exemplo de tela que trabalhei, seria a de formulários pendentes e já respondidos.  
- **Comunicação e alinhamento entre time e cliente:** conduzi threads no Slack e mensagens por WhatsApp para agilizar decisões, registrar respostas e garantir que as definições da cliente fossem traduzidas em user stories e tarefas no backlog por exemplo o cadastro e login de usuários e seus níveis de acesso.  
- **Priorização e acompanhamento do backlog:** transformei definições em histórias de usuário e critérios de aceite, priorizei entregas para o MVP e acompanhei o progresso das implementações garantindo aderência aos requisitos acordados, como exemplo definindo o desenvolvimento e entrega dos dashboards apenas na 3 sprint no MVP.  

**Impacto:** as definições e validações que conduzi garantiram que os dashboards fossem projetados para oferecer comparações significativas, histórico temporal e níveis de acesso apropriados (usuário, líder, admin), reduzindo retrabalho e alinhando o produto ao objetivo de gerar insights úteis ao RH.

Além do papel de PO, contribui tecnicamente no front-end (React/TypeScript + MUI), com entregas práticas como:

- **FormsAdmin:** implementação de DataGrid com seleção por linha, selecionar-tudo, paginação e ações em lote (ex.: exclusão em massa via `axios.delete`), tratamento de estado e feedback ao usuário.  
- **ModalCreateCategory:** componente MUI Dialog para criação de categorias com formulário controlado e integração via `axios.post`.  
- **Criação/edição de formulários:** lógica para criação dinâmica de perguntas (tipos, opções, validações) e fluxo de submissão que persiste formulário e perguntas no backend.  
- **Modais de feedback e navegação:** `SalvarFormularioModal` com controle de fluxo (onOk → `useNavigate`) e distinção visual para sucesso/erro.  
- **Estilos administrativos:** ajustes de CSS para área admin (sidebar fixa, margens, coerência visual).  
- **Dashboards & visualização:** componentes de visualização (e.g., `SmallCardChart`) com Recharts e containers responsivos; implementação de comportamentos de UX (desabilitar ações durante operações, confirmações).  
- **Integração e robustez:** tratamento de erros em requisições, controle de estados (`isDeleting`, loaders) e pequenos refinamentos para estabilidade do produto.


---

## 🧠💪 Hard Skills

| Tecnologia | Nível               | Descrição                                                                 |
|-----------|----------------------|---------------------------------------------------------------------------|
| **React + TypeScript**               | Com apoio | Desenvolvimento de componentes funcionais, hooks (`useState`, `useEffect`), e tipagem. |
| **Material-UI (MUI)**                | Faço com autonomia | Uso de Dialog, Button, Paper, Box, DataGrid e componentes de formulário.        |
| **Axios / Requisições HTTP**         | Faço com autonomia | Integração com backend (POST/DELETE), tratamento de respostas e erros.          |
| **@mui/x-data-grid**                 | Faço com autonomia | Implementação de tabelas, seleção de linhas, paginação e colunas customizadas.  |
| **Recharts**                         | Com apoio     | Criação de gráficos e componentes de visualização (LineChart, ResponsiveContainer). |
| **CSS / Responsividade**             | Faço com autonomia | Estilização de páginas administrativas, sidebar fixa, margens e layout adaptativo. |
| **React Router (useNavigate)**       | Com apoio     | Navegação programática após ações (ex.: redirecionar após salvar).              |
| **Validação de formulários (front)** | Faço com autonomia | Regras de validação (tamanho, obrigatoriedade) e feedback via modal.            |
| **Git / GitHub**                     | Faço com autonomia | Commits, colaboração em equipe e manutenção de integridade do repositório.      |



---

## 🤝 Soft Skills

- **Comunicação com stakeholders:** conduzi a comunicação direta com a cliente Slack, esclarecendo dúvidas críticas e formalizando respostas que guiaram o desenvolvimento, trazendo essas informações para o grupo tanto por dailys quanto por mensagem no WhatsApp.
 
- **Mediação e tomada de decisão:** quando surgiam opções técnicas ou de escopo, sintetizei alternativas e recomendei soluções práticas para viabilizar entregas no prazo.
  
- **Organização e priorização:** transformei discussões em user stories claras, atribuí prioridades baseadas nas respostas da cliente sobre e gerei critérios de aceite para o time.
  
- **Visão analítica:** defini comparações relevantes (tempo, autoavaliação vs. avaliação de liderado/líder) para que os dashboards entregassem insights acionáveis ao RH.
  
- **Colaboração:** mantive o time alinhado com as validações da cliente, apoiando a implementação e reduzindo retrabalho.

- **Papel orientador para outros grupos:** Baseado na pergunta realizada para cliente lógica de formulários e dos acessos que deveriam existir, consegui definir bem os niveis/modos de acesso adm-lider-liderado e a solução de distribuição e a pergunta e resposta formulada junto à cliente serviram de modelo e foram adotadas como referência por outros grupos que desenvolveram abordagens semelhantes em seus niveis de acesso, dashboards, formulário de pesquisa de clima e cultura e até em situações de dualidade quando usuário poderia ser liderado em uma equipe mas lider em outra, guiando o fluxo da API.
