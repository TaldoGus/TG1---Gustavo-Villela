
#### Em 2024-1 - 2ª Semestre Curso 📚

**Empresa**: _FATEC São José dos Campos - SP_
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

- **Comunicação:** Mantive alinhamento constante com os colegas responsáveis pelas partes principais do back-end, garantindo que minhas alterações na interface (como componentes, botões e campos de seleção) não interferissem no fluxo da aplicação. Sempre que precisava modificar algo no fluxo visual, buscava confirmar com a equipe para evitar conflitos.

- **Colaboração:** Dei suporte em pequenas correções de código e ajustes de interface, contribuindo para que o restante da equipe avançasse sem bloqueios. Mesmo com participação reduzida naquele período, mantive disponibilidade para revisar trechos de código, testar funcionalidades e auxiliar em dúvidas do grupo.

- **Organização:** Trabalhei de forma cuidadosa nas classes em que atuei — realizando adaptações específicas, evitando gerar inconsistências e mantendo as telas funcionais. Também colaborei para manter o repositório estável, garantindo commits claros e evitando atrapalhar o desenvolvimento dos demais membros.

- **Adaptabilidade:** Apesar das dificuldades pessoais no período, contribuí onde era possível, como exemplo o projeto necessitava de conhecimento sobre banco de dados, entretanto tal disciplina seria parte da grade disciplinar apenas no 4° semestre, (acabei por pesquisar e estudar sobre para entender) e também assumindo tarefas menores e técnicas que precisavam ser feitas no projeto, principalmente relacionadas à interface como implementeação de Jbutton/JComboBox.

- **Resolução de Problemas:** Ao lidar com ajustes de queries SQL, comportamentos de botões e inicialização de modelos locais via `ProcessBuilder`, busquei alternativas simples e diretas para solucionar os erros apresentados, ajudando a manter a aplicação funcionando corretamente.
