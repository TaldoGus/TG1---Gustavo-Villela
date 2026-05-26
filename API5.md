
#### Em 2026-2 - 5ª Semestre Curso 📚

**Empresa**:
Área de atuação -

## 🚧 Problema  


## 💡 Solução  

---




🔗 **Repositório:** [Phoenix Team – API5](https://github.com/Phoenix-Team-Fatec/geo-maps)
___________________________________________________________________________________________

### 🛠️ Tecnologias Utilizadas 📚

| **Tecnologia** | **Funcionalidade / Utilização**                                                                                 |
|----------------|------------------------------------------------------------------------------------------------------------------|



## 🚀 Contribuições Pessoais

**Principais entregas**


Durante o desenvolvimento do GeoMaps, atuei principalmente nas frentes de integração entre frontend mobile e backend, geração de documentos PDF e estilização do painel administrativo web.

**Integração de Plus Codes na busca (Frontend + Backend)**
Implementei a busca híbrida no componente `search-bar-maps.tsx`, onde os resultados do Google Maps são mesclados com os Plus Codes cadastrados no próprio sistema. No backend, criei toda a camada de acesso a dados: repositório MongoDB (`plus_code_repository.py`), serviço (`plus_code_service.py`) e rota FastAPI (`GET /plus-code/get`), além de registrar o router na aplicação.

**Serviço de rotas client-side**
Desenvolvi o `services/routes-client.ts`, responsável por comunicar o app mobile com o endpoint de rotas do backend FastAPI. Implementação parcial do algoritmo de decodificação de polyline do Google Maps em TypeScript para renderizar o traçado da rota no mapa.

**Certificado de Endereço Digital em PDF**
Criei toda a funcionalidade de emissão de certificados digitais: geração do PDF com ReportLab (`pdf_utils.py`) incluindo dados do proprietário (nome, CPF, e-mail), dados do imóvel, Plus Code, coordenadas, QR Code embutido, hash de validação SHA-256 e moldura/identidade visual do GeoMaps. Implementei também o envio automático por e-mail com o PDF anexado via SMTP SSL (`email_utils.py`) e o endpoint FastAPI que orquestra tudo em background (`POST /area_imovel/properties/pluscode/pdf`).

**Painel Admin Web — Estilização e correções**
Refatorei o CSS e o JSX das páginas de Login, Ocorrências e Usuários do painel administrativo, migrando para tema escuro estilo VSCode, escopando os seletores CSS para evitar conflitos, e corrigindo comportamentos visuais como o card de "0 usuários encontrados" e a lógica de bloqueio por tentativas no login.

---
<br>

## 🧠💪 Hard Skills

| Tecnologia | Nível | Descrição |
|---|---|---|
| React Native / Expo | Uso com autonomia | Desenvolvimento de componentes de busca e integração com APIs externas |
| TypeScript | Uso com autonomia | Criação de serviços tipados (routes-client, search) |
| FastAPI (Python) | Uso com autonomia | Criação de rotas, repositórios e serviços backend |
| MongoDB | Uso com ajuda | Consultas com filtro de campos existentes |
| ReportLab | Uso com autonomia | Geração programática de PDFs com layout customizado |
| SMTP / e-mail | Uso com autonomia | Envio de e-mails com anexo via SSL |
| React (CSS/JSX) | Uso com autonomia | Refatoração de painel admin com tema escuro e escopo de estilos |

## 🤝 Soft Skills

- **Proatividade**: tomei frente em funcionalidades que atravessavam frontend e backend sem esperar divisão prévia de tarefas.
- **Atenção a detalhes**: o trabalho de layout do PDF envolveu muitas iterações de posicionamento e revisão visual.
- **Comunicação**: alinhar a estrutura do certificado (quais campos exibir, formato do QR Code) exigiu conversas com o time para entender o que fazia sentido para o cliente.
