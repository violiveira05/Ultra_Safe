# UltraSafe

## Monitoramento Inteligente de Segurança Industrial

O **UltraSafe** é uma solução acadêmica desenvolvida para o projeto **Metaindústria**, com o objetivo de representar uma plataforma inteligente voltada ao monitoramento, identificação, tratamento e acompanhamento de situações de risco em ambientes industriais.

A proposta utiliza conceitos de **visão computacional, inteligência artificial e monitoramento inteligente** para representar como um sistema poderia auxiliar na identificação de situações potencialmente inseguras, como ausência ou uso incorreto de Equipamentos de Proteção Individual (EPIs), vazamentos, falhas em equipamentos e outras condições de risco.

Ao longo das quatro Sprints, o projeto evoluiu de uma ideia inicial de monitoramento para um protótipo navegável mais completo, contemplando identificação, análise, tratamento e histórico das ocorrências.

---

# Integrantes

* Milena Queiroz — RM: 558825
* Gabriel Yeshua — RM: 558273
* Nicolas Alvares — RM: 557271
* Pedro Henrique Garcia — RM: 558867
* Victor Augusto — RM: 558338

---

# Sprint 4 — Entrega Final da Solução

## Objetivo

A Sprint 4 teve como objetivo consolidar toda a evolução realizada ao longo do projeto UltraSafe.

Nesta etapa, foram reunidos em uma única entrega:

* protótipo final navegável;
* fluxos principais da solução;
* simulação de dados relacionados ao contexto da Metaindústria;
* arquitetura conceitual final;
* definição de uma stack tecnológica proposta;
* documentação consolidada;
* histórico de evolução das quatro Sprints;
* artefatos Scrum;
* Sprint Backlog da Sprint 4;
* Sprint Review final;
* instruções de utilização;
* apresentação final do projeto.

A Sprint 4 representa a consolidação da proposta desenvolvida pelo grupo.

---

# Natureza da Entrega

A entrega final do UltraSafe consiste em um **protótipo navegável de alta fidelidade desenvolvido no Figma**, com apoio dos recursos de Inteligência Artificial disponibilizados pela própria plataforma.

O grupo **não realizou o desenvolvimento de código da aplicação** nesta etapa.

O objetivo do protótipo é representar visualmente e de forma navegável como funcionaria uma aplicação real de segurança industrial.

As funcionalidades, ocorrências, alertas, indicadores, colaboradores, setores e demais informações apresentadas são simuladas para fins acadêmicos.

A Inteligência Artificial do Figma foi utilizada como ferramenta de apoio para:

* criação e evolução das telas;
* organização visual da interface;
* criação de componentes;
* construção dos fluxos de navegação;
* representação de estados da aplicação;
* melhoria da experiência do usuário;
* simulação das funcionalidades propostas.

O grupo ficou responsável pela definição da solução, análise do problema, requisitos, funcionalidades, validação dos fluxos, organização das entregas, decisões conceituais e documentação do projeto.

---

# Problema

Ambientes industriais apresentam diferentes riscos relacionados à segurança dos colaboradores, utilização de equipamentos, funcionamento de máquinas e execução de processos.

A identificação tardia de uma situação de risco pode resultar em:

* acidentes;
* interrupções;
* perda de eficiência operacional;
* danos a equipamentos;
* exposição de colaboradores a situações inseguras.

Além da identificação de uma situação de risco, também existe a necessidade de registrar, classificar, tratar e acompanhar cada ocorrência.

O UltraSafe foi proposto para representar uma solução capaz de centralizar esse processo.

---

# Solução Proposta

O UltraSafe representa uma plataforma web voltada ao acompanhamento de situações de segurança industrial.

A solução foi concebida para permitir que um operador:

* acompanhe indicadores de segurança;
* visualize áreas monitoradas;
* identifique alertas;
* analise ocorrências;
* confirme ou rejeite uma detecção;
* classifique sua severidade;
* registre observações;
* acione responsáveis;
* acompanhe o tratamento;
* encerre ocorrências;
* consulte registros anteriores.

O fluxo geral proposto é:

**Monitoramento → Identificação → Alerta → Análise → Tratamento → Encerramento → Histórico**

---

# Protótipo Final

O protótipo final foi desenvolvido no **Figma** e representa uma aplicação web de alta fidelidade.

A navegação permite demonstrar os principais fluxos do UltraSafe de forma visual.

## Principais módulos representados

* Login;
* Dashboard;
* Monitoramento;
* Alertas;
* Ocorrências;
* Tratamento de Ocorrências;
* Histórico;
* Relatórios;
* Configurações.

Outros elementos relacionados à gestão de segurança e EPIs também podem ser representados por meio dos dados simulados utilizados no protótipo.

---

# Fluxo Principal da Aplicação

O principal fluxo apresentado no protótipo é:

Login  
↓  
Dashboard  
↓  
Monitoramento  
↓  
Identificação de situação de risco  
↓  
Alerta  
↓  
Detalhes da ocorrência  
↓  
Análise da confiança da detecção  
↓  
Confirmação ou rejeição  
↓  
Classificação de severidade  
↓  
Registro de observações  
↓  
Acionamento do responsável ou manutenção  
↓  
Tratamento  
↓  
Encerramento  
↓  
Histórico de Ocorrências

---

# Tratamento de Ocorrências

Um dos principais fluxos desenvolvidos no protótipo é o tratamento de ocorrências.

O fluxo representa as ações que poderiam ser realizadas após a identificação de um risco.

O operador pode:

* visualizar a ocorrência;
* consultar seus detalhes;
* visualizar data, horário e área;
* analisar o nível de confiança da detecção;
* confirmar ou rejeitar a ocorrência;
* classificar sua severidade;
* registrar observações;
* acionar a manutenção;
* acompanhar o andamento;
* visualizar uma linha do tempo;
* marcar a ocorrência como resolvida;
* consultar posteriormente o registro no histórico.

Essa funcionalidade foi criada para resolver uma limitação identificada nas etapas anteriores, nas quais a solução estava mais concentrada apenas na identificação do risco.

---

# Histórico de Ocorrências

A área de Histórico permite representar a consulta a registros anteriores.

Os filtros disponíveis podem incluir:

* período;
* área;
* tipo de ocorrência;
* severidade;
* nível de risco;
* status.

A proposta dessa funcionalidade é aumentar a rastreabilidade das informações e facilitar a análise de situações recorrentes.

---

# Monitoramento de EPIs

O UltraSafe também considera situações relacionadas à utilização de Equipamentos de Proteção Individual.

Entre os eventos que podem ser representados estão:

* colaborador sem EPI obrigatório;
* utilização incorreta;
* ausência de capacete;
* ausência de luvas;
* ausência de óculos de proteção;
* ausência de protetor auricular;
* irregularidade identificada durante o monitoramento.

Exemplos de EPIs considerados:

* capacete;
* óculos de proteção;
* luvas;
* protetor auricular;
* botas;
* máscaras;
* coletes.

---

# Dados Simulados

O protótipo utiliza dados simulados para representar situações compatíveis com o contexto industrial da Metaindústria.

Entre os dados representados estão:

* colaboradores;
* áreas industriais;
* ocorrências;
* alertas;
* tipos de risco;
* níveis de severidade;
* datas e horários;
* responsáveis;
* status;
* EPIs;
* registros históricos.

Exemplos de áreas industriais utilizadas:

* Produção;
* Manutenção;
* Logística;
* Expedição;
* Almoxarifado;
* Qualidade.

---

# Dashboard

O Dashboard representa uma visão geral das condições de segurança.

Entre os elementos apresentados ou propostos estão:

* quantidade de ocorrências;
* ocorrências abertas;
* ocorrências críticas;
* alertas recentes;
* níveis de risco;
* indicadores de segurança;
* ocorrências por setor;
* ocorrências por período;
* status das ocorrências.

O objetivo é permitir que o operador visualize rapidamente o cenário geral da operação.

---

# Melhorias de Experiência do Usuário

Durante a evolução do projeto foram incorporadas melhorias relacionadas à experiência de uso.

Entre elas:

* indicadores visuais de severidade;
* diferenciação de status;
* feedback após ações;
* modais de confirmação;
* filtros;
* linha do tempo das ocorrências;
* padronização visual;
* organização das informações;
* melhoria da navegação;
* representação de diferentes estados da aplicação.

Entre os estados utilizados estão:

* Normal;
* Atenção;
* Crítico;
* Pendente;
* Em análise;
* Em tratamento;
* Resolvido.

---

# Arquitetura Conceitual Final

A arquitetura apresentada no UltraSafe representa uma **proposta conceitual de como a solução poderia ser implementada futuramente**.

As tecnologias apresentadas nesta seção **não foram implementadas na Sprint 4**.

Elas foram selecionadas para representar uma possível arquitetura técnica compatível com as necessidades da solução.

---

## 1. Captura de Imagens

Em uma implementação real, câmeras instaladas nas áreas industriais poderiam realizar a captura contínua de imagens.

Essas imagens seriam encaminhadas para um módulo responsável pela análise visual.

---

## 2. Visão Computacional

### Tecnologias propostas

* Python;
* YOLO;
* OpenCV.

O módulo de visão computacional teria como objetivo identificar possíveis situações de risco.

Exemplos:

* colaborador sem EPI;
* utilização inadequada de proteção;
* acesso a área insegura;
* anomalias visuais;
* vazamentos;
* situações próximas a equipamentos.

O **YOLO** poderia ser utilizado para detecção de objetos e pessoas.

O **OpenCV** poderia apoiar o processamento e tratamento das imagens.

---

## 3. Backend

### Tecnologias propostas

* Node.js;
* Express;
* TypeScript.

O backend teria como responsabilidade controlar as regras de negócio da aplicação.

Entre as funções propostas estão:

* receber eventos;
* registrar ocorrências;
* controlar status;
* registrar severidade;
* relacionar ocorrências a áreas;
* registrar ações do operador;
* gerenciar usuários;
* fornecer informações ao Dashboard;
* manter o histórico.

---

## 4. Banco de Dados

### Tecnologia proposta

* PostgreSQL.

O banco de dados poderia armazenar informações como:

* usuários;
* colaboradores;
* áreas;
* câmeras;
* EPIs;
* ocorrências;
* tipos de risco;
* severidade;
* responsáveis;
* ações;
* histórico;
* status.

---

## 5. Interface Web

### Tecnologias propostas

* React;
* TypeScript;
* HTML;
* CSS.

A interface web permitiria a interação entre o usuário e o sistema.

Os principais módulos seriam:

* Login;
* Dashboard;
* Monitoramento;
* Alertas;
* Ocorrências;
* Histórico;
* Relatórios;
* Configurações.

Nesta entrega acadêmica, essa interface é representada pelo protótipo desenvolvido no Figma.

---

## 6. Comunicação em Tempo Real

### Tecnologias propostas

* WebSocket;
* Socket.IO.

Em uma implementação real, a comunicação em tempo real poderia ser utilizada para enviar alertas imediatamente ao Dashboard após a identificação de uma situação de risco.

---

## 7. API

A comunicação entre frontend e backend poderia ser realizada por meio de uma **API REST**.

Exemplos de operações:

* consultar ocorrências;
* registrar ocorrência;
* alterar status;
* consultar histórico;
* registrar ações;
* consultar alertas;
* consultar indicadores;
* gerar dados para relatórios.

---

## 8. Autenticação

### Tecnologia proposta

* JWT — JSON Web Token.

O JWT poderia ser utilizado para controlar sessões e restringir o acesso aos usuários autorizados.

---

# Fluxo Técnico Proposto

Uma possível arquitetura de funcionamento seria:

Câmeras  
↓  
Python + OpenCV  
↓  
YOLO  
↓  
Backend Node.js + Express  
↓  
PostgreSQL  
↓  
API REST / WebSocket  
↓  
Frontend React  
↓  
Operador UltraSafe

Esse fluxo representa apenas uma proposta de implementação futura.

---

# Stack Tecnológica Proposta

| Área | Tecnologia proposta |
|---|---|
| Prototipação | Figma |
| Apoio à criação do protótipo | Inteligência Artificial do Figma |
| Frontend futuro | React + TypeScript |
| Backend futuro | Node.js + Express |
| Visão Computacional futura | Python + YOLO |
| Processamento de imagens futuro | OpenCV |
| Banco de Dados futuro | PostgreSQL |
| API futura | REST |
| Comunicação em tempo real futura | WebSocket / Socket.IO |
| Autenticação futura | JWT |
| Versionamento e documentação | GitHub |
| Gestão Ágil | Scrum |
| Gestão Visual | Trello |

---

# Justificativas da Stack Proposta

## Figma

Foi utilizado para criação, evolução e navegação do protótipo final.

Os recursos de IA da plataforma auxiliaram na geração das telas, componentes e fluxos.

## YOLO

Foi selecionado conceitualmente por ser uma tecnologia voltada à detecção de objetos em imagens e vídeos, sendo compatível com uma futura solução de monitoramento visual.

## OpenCV

Foi proposto para apoiar captura, manipulação e processamento de imagens.

## React

Foi considerado como uma opção futura para desenvolvimento de uma interface web baseada em componentes.

## Node.js

Foi proposto como tecnologia para uma possível camada de backend e integração com eventos em tempo real.

## PostgreSQL

Foi considerado como banco de dados relacional para armazenamento estruturado das informações do sistema.

## WebSocket

Foi proposto para permitir o envio de alertas e atualizações em tempo real.

---

# Evolução do Projeto

O UltraSafe evoluiu de forma incremental ao longo das quatro Sprints.

---

# Sprint 1 — Definição Inicial

Na Sprint 1 foram realizadas as definições iniciais do projeto.

Principais atividades:

* entendimento do problema;
* levantamento inicial de requisitos;
* definição da proposta;
* análise do contexto de segurança industrial;
* estruturação inicial da solução;
* definição inicial dos principais fluxos.

Essa etapa estabeleceu a base conceitual do UltraSafe.

---

# Sprint 2 — Protótipo Inicial

Na Sprint 2 foi desenvolvida uma primeira versão do protótipo.

O foco estava principalmente em:

* interface inicial;
* Dashboard;
* monitoramento;
* alertas;
* representação visual da identificação de riscos;
* primeiros fluxos da aplicação.

Uma limitação identificada nessa etapa foi que o sistema representava principalmente a detecção de um risco, mas ainda não contemplava de forma completa o processo posterior.

---

# Sprint 3 — Evolução do Protótipo

Na Sprint 3, o protótipo foi evoluído para representar melhor o ciclo de tratamento das ocorrências.

Foram adicionados:

* detalhes da ocorrência;
* análise da confiança da detecção;
* confirmação ou rejeição;
* classificação de severidade;
* registro de observações;
* acionamento da manutenção;
* acompanhamento do atendimento;
* encerramento;
* histórico;
* filtros;
* melhorias de UX;
* modais;
* linha do tempo;
* organização Scrum.

A Sprint 3 tornou o fluxo da aplicação mais completo e aproximou o protótipo de uma experiência de produto real.

---

# Sprint 4 — Consolidação Final

A Sprint 4 teve como foco consolidar o trabalho realizado anteriormente.

As principais atividades foram:

* revisão do protótipo;
* validação dos fluxos;
* refinamento da navegação;
* consolidação dos dados simulados;
* definição da arquitetura conceitual final;
* definição de uma stack técnica proposta;
* consolidação do histórico das quatro Sprints;
* organização dos artefatos Scrum;
* criação do Sprint Backlog final;
* registro da Review;
* atualização do README;
* preparação da apresentação final.

---

# Gestão Ágil

O projeto utilizou conceitos do framework Scrum para organização das atividades.

O board do Trello foi estruturado com as seguintes etapas:

* Product Backlog;
* Sprint Backlog;
* Em andamento;
* Em revisão;
* Concluído.

---

# Product Backlog

O Product Backlog reúne as principais funcionalidades identificadas durante o projeto.

Entre elas:

* Login;
* Dashboard;
* Monitoramento;
* Detecção de riscos;
* Alertas;
* Tratamento de ocorrências;
* Histórico;
* Relatórios;
* Configurações;
* Monitoramento de EPIs.

---

# Sprint Backlog — Sprint 4

Entre as principais atividades da Sprint 4 estão:

* revisar o protótipo;
* validar os fluxos principais;
* corrigir inconsistências de navegação;
* consolidar os dados simulados;
* revisar o tratamento de ocorrências;
* revisar o histórico;
* consolidar a arquitetura;
* definir a stack conceitual;
* atualizar a documentação;
* atualizar o Trello;
* documentar a Review final;
* preparar o vídeo de apresentação.

---

# Definition of Done

Uma atividade é considerada concluída quando:

* atende ao objetivo definido;
* está representada corretamente no protótipo ou documentação;
* apresenta navegação coerente quando aplicável;
* não contém inconsistências visuais relevantes;
* foi revisada pelo grupo;
* está registrada no board;
* atende ao escopo definido para a Sprint.

---

# Sprint Planning

Durante o Sprint Planning, o grupo definiu os objetivos e as tarefas prioritárias.

Na Sprint 4, foram priorizados:

* consolidação do protótipo;
* revisão dos fluxos;
* arquitetura;
* documentação;
* Scrum;
* README;
* apresentação final.

---

# Daily Scrum

As reuniões de acompanhamento foram utilizadas para verificar:

* atividades concluídas;
* atividades em andamento;
* dificuldades;
* próximos passos;
* redistribuição de tarefas quando necessário.

---

# Sprint Review

Ao final da Sprint, o grupo realizou a revisão das entregas e analisou:

* aderência aos requisitos;
* evolução do protótipo;
* funcionalidades representadas;
* melhorias realizadas;
* documentação;
* arquitetura;
* organização Scrum;
* itens concluídos.

---

# Sprint Review Final

A Review Final consolida a evolução do UltraSafe ao longo das quatro Sprints.

Entre os resultados alcançados estão:

* definição do problema;
* criação da proposta de solução;
* evolução progressiva do protótipo;
* fluxo completo de tratamento de ocorrências;
* histórico;
* filtros;
* melhorias de UX;
* arquitetura conceitual;
* definição de stack futura;
* organização da documentação;
* utilização de Scrum;
* consolidação das entregas anteriores.

---

# Instruções de Uso

A solução final é apresentada por meio do protótipo navegável desenvolvido no Figma.

Para visualizar:

1. acessar o link do protótipo;
2. iniciar a visualização ou apresentação;
3. acessar a tela de Login;
4. seguir para o Dashboard;
5. acessar o Monitoramento;
6. selecionar uma ocorrência;
7. visualizar os detalhes;
8. analisar a confiança da detecção;
9. confirmar ou rejeitar;
10. definir a severidade;
11. registrar o tratamento;
12. encerrar a ocorrência;
13. consultar o registro no Histórico.

Os dados utilizados no protótipo são simulados para fins acadêmicos.

---

# Links do Projeto

## Protótipo Figma

https://www.figma.com/make/6VWjMimHk2LFU6RbxjxJX4/Base-UI-for-UltraSafe?t=OceOhSx7kWmqb021-20&fullscreen=1

---

## Board Scrum — Trello

https://trello.com/invite/b/6aa2e9837d0ec908b92b051d/ATTIdf32f6994ad6d3fd5172ae6f700f8dc96F6FFA92/ultra-safe

---

## Vídeo Final

()

---

# Limitações

A Sprint 4 apresenta um **protótipo navegável de alta fidelidade**.

Não foram implementados nesta entrega:

* frontend em código;
* backend;
* banco de dados;
* modelo YOLO;
* integração com câmeras;
* API REST;
* WebSocket;
* autenticação real;
* processamento real de imagens.

As tecnologias descritas na arquitetura representam possibilidades para uma implementação futura.

Os dados e comportamentos apresentados no protótipo são simulados.

---

# Próximos Passos

Caso o projeto fosse continuado para uma etapa de implementação, os próximos passos poderiam incluir:

* desenvolvimento do frontend;
* desenvolvimento do backend;
* implementação do banco de dados;
* criação da API;
* treinamento de modelo de visão computacional;
* integração com câmeras;
* detecção real de EPIs;
* autenticação;
* comunicação em tempo real;
* armazenamento de evidências;
* notificações;
* geração automática de relatórios;
* integração com sistemas industriais.

---

# Conclusão

O UltraSafe evoluiu ao longo de quatro Sprints a partir de uma proposta inicial de monitoramento de segurança industrial.

Durante o projeto foram definidos fluxos, funcionalidades, estados, requisitos e comportamentos esperados para uma solução voltada à identificação e tratamento de situações de risco.

A versão final apresenta um protótipo navegável desenvolvido no Figma com apoio de Inteligência Artificial, representando de forma visual como o sistema poderia funcionar em um ambiente real.

A Sprint 4 consolida o trabalho realizado anteriormente por meio da revisão do protótipo, documentação das decisões, definição da arquitetura conceitual, organização dos artefatos Scrum e registro da evolução completa do projeto.

---
