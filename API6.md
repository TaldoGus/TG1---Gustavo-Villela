
#### Em 2026-1 - 6ª Semestre Curso 📚

**Empresa**: DomRock
Área de atuação - Inteligência Artificial

## 🚧 Problema

Empresas enfrentam dificuldades significativas no gerenciamento de regras de negócio dinâmicas, especialmente quando essas regras sofrem alterações frequentes por fatores como lançamento de produtos, mudanças de precificação, acordos comerciais e políticas de vendas. Na prática, essa base de conhecimento raramente está registrada e organizada de forma adequada, gerando inconsistências operacionais, conflitos entre regras aplicadas por diferentes colaboradores e perda de rastreabilidade dos processos.

No contexto específico do cálculo de comissionamento mensal, os desafios se intensificam: aplicação incorreta de percentuais por cargo, dificuldade em gerenciar exceções e particularidades, falta de transparência nas decisões de cálculo e inconsistência das regras em diferentes cenários de venda.

## 💡 Solução

Foi desenvolvida uma aplicação web chamada **RuleAI**, que aplica técnicas de IA Generativa para criação, gerenciamento e controle de regras de negócio. A solução é composta por três camadas integradas:

- **Backend (Spring Boot):** API REST responsável pelo cálculo de comissões, gerenciamento das regras de negócio, persistência em MongoDB e importação de dados via Excel.
- **Frontend Web (Vue.js 3):** Aplicação SPA com interface intuitiva para criação, visualização e gerenciamento de regras, com autenticação de usuários.
- **Agente de IA (LLMs):** Sistema baseado em modelos de linguagem generativos capaz de interpretar regras em linguagem natural, gerar código automaticamente a partir de requisitos, indexar e recuperar regras via RAG (Retrieval-Augmented Generation) e processar PDFs e código-fonte para construção de base de conhecimento.

Gestores podem interagir com o sistema por linguagem natural e acompanhar os resultados por meio de indicadores e gráficos, promovendo maior explicabilidade e eficiência nas decisões.

---




🔗 **Repositório:** [Phoenix Team – API6](https://github.com/Phoenix-Team-Fatec/API_6)
___________________________________________________________________________________________

### 🛠️ Tecnologias Utilizadas 📚

| **Tecnologia** | **Funcionalidade / Utilização**                                                                                 |
|----------------|-----------------------------------------------------------------------------------------------------------
| FastAPI                 | Framework Python para criação da API de comunicação com o agente IA                            |
| Python 3.10+            | Linguagem utilizada no desenvolvimento do agente de IA                                          |
| LangChain               | Framework para orquestração de agentes IA e gerenciamento de prompts                           |
| LangGraph               | Orquestração do fluxo de execução do agente em formato de grafo                                 |
| LangChain Groq          | Integração com modelos Groq                                                                     |
| Google Vertex AI/Gemini | Integração com modelos de linguagem do Google                                                   |
| HuggingFace             | Acesso a modelos de IA abertos                                                                  |
| LanceDB                 | Banco de dados vetorial para RAG (Retrieval-Augmented Generation)                              |
| MLflow                  | Observabilidade do agente: rastreamento de tokens, métricas, versionamento de prompts          |
| Ollama                  | Execução local de modelos LLM                                                                   |
| Java 17                 | Linguagem de programação utilizada no backend                                                   |
| Spring Boot             | Framework para construção da API REST com features avançadas                                    |
| MongoDB                 | Banco de dados NoSQL para armazenamento de regras, comissões e dados de funcionários            |
| Maven                   | Gerenciador de dependências e build do backend Java                                             |
| PyMUPDF                 | Processamento de PDFs para indexação de regras na base de conhecimento                         |
| Vue.js 3                | Framework JavaScript para construção do frontend SPA                                           |
| Vue Router              | Roteamento da aplicação web                                                                     |
| Node.js                 | Ambiente de execução JavaScript para suporte à aplicação web                                   |
| Docker                  | Conteinerização e padronização do ambiente de execução                                          |
| Pandas                  | Manipulação e análise de dados                                                                  |


## 🚀 Contribuições Pessoais

No API6, atuei como **Scrum Master** do time, sendo responsável pela organização e condução do processo ágil ao longo do semestre. Utilizei o **Jira** como ferramenta central de gestão, traduzindo o backlog definido pelo Product Owner em tarefas detalhadas com descrições claras, atribuindo responsáveis conforme perfil de cada membro e acompanhando o andamento via **burndown chart** para garantir que as entregas ocorressem dentro do prazo planejado.

A comunicação do time foi mantida de forma contínua pelo **WhatsApp**, onde acompanhei o andamento das tarefas, verifiquei o status de cada membro e sinalizei pontos de atenção entre os encontros presenciais. Em aula, incentivei e organizei reuniões com o grupo que se tornaram essenciais para alinhar dúvidas, definir a direção de uso do sistema e estruturar a lógica de cálculo dos comissionamentos junto ao cliente — garantindo que o time chegasse às reuniões com perguntas objetivas e saísse com decisões claras.

Utilizei ferramentas de **IA generativa** para apoiar meu próprio entendimento do projeto, facilitando a leitura de requisitos mais técnicos e ajudando a comunicar melhor as tarefas para os membros do time.

---

## 🧠💪 Hard Skills

| Tecnologia / Ferramenta | Nível              | Descrição                                                                                      |
|-------------------------|--------------------|------------------------------------------------------------------------------------------------|
| Jira                    | Uso com autonomia  | Tradução do backlog em tarefas no Jira, atribuição de responsáveis e acompanhamento de burndown |
| Metodologia Scrum       | Uso com autonomia  | Condução de cerimônias ágeis, apoio ao PO e facilitação do fluxo de trabalho do time           |
| Gestão de tempo         | Uso com autonomia  | Monitoramento de ritmo de entrega e antecipação de impedimentos via burndown chart             |
| IA Generativa           | Uso com autonomia  | Apoio à compreensão de requisitos técnicos e auxilio na elaboração de descrições de tarefas               |

---

## 🤝 Soft Skills

- **Liderança situacional:** incitei reuniões presenciais e por meio do Grupo WhasApp que se mostraram decisivas para alinhar o time e definir rumos importantes do projeto junto ao cliente.
- **Comunicação:** mantive contato ativo com o grupo via WhatsApp, acompanhando o andamento entre sprints e garantindo que ninguém ficasse bloqueado sem suporte.
- **Organização:** estruturei as tarefas no Jira de forma clara e descritiva, facilitando a execução por parte dos membros mesmo sem minha presença imediata, atribuindo cada membro para com tarefas de.
- **Facilitação:** conduzi reuniões com foco em decisões objetivas, transformando dúvidas do time em perguntas em conjunto com o Product Owner, direcionadas ao cliente sobre a lógica de comissionamento.
- **Proatividade:** busquei compreender aspectos técnicos do projeto com auxílio de ferramentas de IA, para poder apoiar o time com mais embasamento mesmo atuando na gestão.

---
