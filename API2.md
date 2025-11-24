
#### Em 2024-1 - 2ª Semestre Curso 📚

**Empresa**: _FATEC São José dos Campos - SP_
<br>
Profº Giuliano Bertoti

## 🚧 Problema  
A empresa parceira enfrentava dificuldades significativas no acesso e na consulta à sua base de dados corporativa. O processo de extração de dados do Banco de dados coorporativo era realizado de forma **manual**, **não padronizada** e pouco intuitiva, resultando em divergências nos dados utilizados pelos colaboradores. Essa falta de consistência gerava **retrabalho**, **atrasos operacionais** e comprometia a confiabilidade das análises internas, impactando diretamente a **tomada de decisões estratégicas**.

## 💡 Solução  
Para superar essas limitações, foi desenvolvida uma **aplicação desktop** integrada a um **modelo de linguagem (LLM)**, permitindo que o usuário consulte o banco de dados utilizando **comandos em linguagem natural**, sem necessidade de conhecimento técnico específico.  
A ferramenta foi projetada para ser **flexível**, suportando diferentes modelos de linguagem e adaptando-se a diversos cenários operacionais.Dessa forma o processo se torna mais rápido e flexivel ao padrão do ser humano,mesmo não reduzindo a inconsistência (Não padroniza).

🔗 **Repositório:** [Phoenix Team – DataEase](https://github.com/Phoenix-Team-Fatec/DataEase?tab=readme-ov-file)

### 🛠️ Tecnologias Utilizadas 📚

| **Tecnologia** | **Funcionalidade / Utilização**                                                                                 |
|----------------|------------------------------------------------------------------------------------------------------------------|
| **MySQL**       | Banco de dados para armazenamento de informações do usuário                                                                              |
| **Java**       | Linguagem responsável pelo desenvolvimento de todo o sistema, conexão com modelo de linguagem e até interface. |
| **LangChain4j** | Biblioteca do java utilizada para conexão dos modelos (comunicação entre aplicação e modelos).                                                               |
| **LM Studio**   | Plataforma utilizada para execução e testes de modelos.                                                                      |
| **Git**         | Controle de versionamento utilizado para gerenciar e versionar o código-fonte e coordenação de trabalho em grupo.   



## 🚀 Contribuições Pessoais
Atuei como desenvolvedor com foco no **front-end em Java Swing**, integração básica com o back-end e melhorias pontuais na camada de conexão com o banco e no suporte ao modelo de linguagem. Minhas entregas concretas incluem:

- **Interface / UX (TelaChat, TelaLogin):** ajustes na UI (botões, ícones, sidebar), remoção de bordas, configuração de `JButton`/`JComboBox`, posicionamento com `setBounds` e pequenas correções de comportamento (ex.: toggle do botão Start/Stop do servidor local).  
- **Integração com LMs (LmConnection):** inclusão/ajustes de métodos para ligar/desligar modelos locais via `ProcessBuilder` (comandos `lms start/stop/load/unload`) e leitura da saída do processo, facilitando o controle do ambiente de inferência local.  
- **Conexão com BD / SQL (Cadastros):**  correções em queries e mapeamento de colunas (`instance_name` → `nome_instances`, `usuario` → `name_users`), e tratamento básico de exceções para melhorar a robustez nas consultas.  
- **População dinâmica de componentes:** implementação de método para preencher `JComboBox` com instâncias, usuários e bancos recuperados do banco (método `preencherJComboBox()` em `TelaChat`), tornando a UI reativa aos dados do usuário.  
- **Refatorações e manutenção:** correções ,padronizações e remoção/ajuste de duplicações em código gerado; apoio em merges e manutenção de consistência do projeto.


---

## 🧠💪 Hard Skills

| Tecnologia | Nível               | Descrição                                                                 |
|-----------|----------------------|---------------------------------------------------------------------------|
| **Java (Swing)**               | Com apoio    | Implementação de telas, botões, `JComboBox`, posicionamento e eventos.     |
| **MySQL / SQL**                | Ouvi falar   | Conhecimento básico das queries; ajustes e mapeamento de colunas.          |
| **Integração LLM (LangChain4j / ProcessBuilder)** | Com apoio | Scripts para iniciar/desligar modelo local, captura de saída e comandos.   |
| **GUI Layout (setBounds / Layouts)** | Com apoio | Ajustes de posicionamento, ícones, remoção de bordas e refinamentos visuais.|
| **Git / GitHub**               | Autônomo     | Versionamento, commits e suporte na resolução de conflitos.                |



---

## 🤝 Soft Skills


- **Comunicação:** mantive alinhamento direto com os colegas responsáveis pelo back-end sempre que modifiquei a interface (por exemplo em `TelaChat.java` e `TelaLogin.java`). Antes de alterar componentes como `JButton`/`JComboBox` ou o fluxo de início/parada do servidor local, confirmei com quem desenvolvia as rotas e as queries para evitar rupturas funcionais — isso reduziu retrabalho e conflitos de integração.

- **Colaboração:** dei suporte prático em correções pontuais no front-end e no acesso ao banco (ex.: `Cadastros.java`), revisando trechos de código, testando formulários e ajudando colegas a aplicar correções. Mesmo com participação reduzida em alguns períodos, mantive disponibilidade para code review e para validar merges, o que ajudou a manter o progresso do time.

- **Organização:** trabalhei com cuidado nas classes onde atuei, extraindo lógica repetida e mantendo padrões de nomeação (por exemplo, ajustes no mapeamento de colunas como `instance_name` → `nome_instances`). Minimizei impactos no repositório com commits claros, o que facilitou a manutenção e a retomada do trabalho por outros membros.

- **Adaptabilidade:** Devido uso de banco de dados no projeto e devida disciplina de Banco de Dados estar presente apenas no 4° semestre ampliei meu conhecimento sobre banco de dados e integração quando o projeto exigiu (estudei conceitos de SQL para entender `Cadastros.java`), e apliquei esse aprendizado em correções e validações. Também assumi tarefas técnicas de interface (posicionamento via `setBounds`, preenchimento dinâmico com `preencherJComboBox()`), mesmo sendo fora da grade curricular no momento — demonstrando rapidez de aprendizagem e aplicação prática.

- **Resolução de Problemas:** enfrentei problemas concretos como queries com mapeamento incorreto, comportamento de botões e controle de processos locais. Para isso, implementei soluções diretas (tratamento de exceções em acesso a BD, leitura de saída de `ProcessBuilder` em `LmConnection.java`, toggles de Start/Stop), priorizando estabilidade e retorno visual imediato ao usuário.

