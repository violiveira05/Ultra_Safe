

# UltraSafe

## Monitoramento Inteligente de Segurança Industrial

O UltraSafe é uma solução desenvolvida para o projeto Metaindústria com o objetivo de auxiliar na prevenção e identificação de riscos em ambientes industriais por meio de visão computacional.

A aplicação foi projetada para monitorar áreas industriais e identificar situações que possam representar riscos para trabalhadores, equipamentos ou processos, como vazamentos em tubulações, falhas em equipamentos e outras condições inseguras.

---

## Integrantes

* Milena Queiroz — RM: 558825
* Gabriel Yeshua — RM: 558273
* Nicolas Alvares — RM: 557271
* Pedro Henrique Garcia — RM: 558867
* Victor Augusto — RM: 558338

---

# Sprint 3

## Objetivo

A Sprint 3 teve como objetivo evoluir o protótipo do UltraSafe, incorporando novos fluxos, melhorias de experiência do usuário e organização do projeto por meio da metodologia Scrum.

Além da evolução visual, o objetivo foi representar todo o processo realizado após uma situação de risco ser identificada pelo sistema.

---

# Evolução do protótipo

Na Sprint anterior, o sistema estava concentrado principalmente no monitoramento e identificação de situações de risco.

Na Sprint 3 foram desenvolvidos novos fluxos para tornar o protótipo mais completo.

## 1. Tratamento de ocorrências

Foi criado um fluxo completo que permite:

* identificar uma ocorrência;
* visualizar seus detalhes;
* analisar a confiança da detecção;
* confirmar ou rejeitar a ocorrência;
* classificar sua severidade;
* registrar observações;
* acionar a equipe de manutenção;
* acompanhar o atendimento;
* marcar a ocorrência como resolvida.

### Justificativa

A mudança foi realizada porque apenas detectar uma situação de risco não representa todo o processo necessário em uma aplicação de segurança industrial.

Após uma detecção, o operador precisa tomar uma decisão e acompanhar as ações realizadas para solucionar o problema.

---

## 2. Histórico de ocorrências

Foi criada uma nova tela de Histórico de Ocorrências.

A funcionalidade permite consultar eventos anteriores utilizando filtros como:

* período;
* área;
* tipo;
* severidade;
* status.

### Justificativa

A criação do histórico permite maior rastreabilidade e facilita a análise de problemas recorrentes.

Também possibilita acompanhar quais ações foram tomadas em cada situação.

---

# Outras melhorias

Além dos novos fluxos, foram adicionadas melhorias de experiência do usuário:

* indicadores visuais de severidade;
* feedback após ações;
* filtros de monitoramento;
* modais de confirmação;
* linha do tempo das ocorrências;
* padronização de componentes;
* melhoria da navegação;
* estados Normal, Atenção, Crítico, Pendente e Resolvido;
* organização das informações do dashboard.

---

# Fluxo principal

O principal fluxo da aplicação é:

Login
↓
Dashboard
↓
Monitoramento em Tempo Real
↓
Detecção de risco
↓
Detalhe da Ocorrência
↓
Confirmação pelo operador
↓
Acionamento da manutenção
↓
Tratamento da ocorrência
↓
Encerramento
↓
Histórico de Ocorrências

---

# Arquitetura Técnica

A arquitetura proposta para o UltraSafe foi dividida em camadas.

## 1. Captura de imagens

Câmeras instaladas nas áreas industriais fornecem imagens em tempo real para o sistema.

## 2. Visão computacional

As imagens são processadas por um modelo de visão computacional responsável pela identificação de possíveis situações de risco.

O modelo pode identificar eventos como:

* vazamentos;
* ausência de equipamentos de proteção;
* situações anormais em equipamentos;
* riscos em áreas monitoradas.

## 3. Backend

O backend é responsável por receber os eventos identificados pela visão computacional e realizar o gerenciamento das ocorrências.

Principais responsabilidades:

* registrar ocorrências;
* armazenar data e horário;
* controlar status;
* registrar severidade;
* relacionar ocorrência e câmera;
* registrar ações realizadas pelo operador;
* atualizar histórico.

## 4. Banco de dados

O banco de dados mantém informações relacionadas a:

* usuários;
* câmeras;
* áreas monitoradas;
* ocorrências;
* tipos de risco;
* ações realizadas;
* responsáveis;
* histórico de alterações.

## 5. Interface Web

A interface do UltraSafe apresenta as informações ao operador.

Principais módulos:

* Login;
* Dashboard;
* Monitoramento;
* Ocorrências;
* Histórico;
* Relatórios;
* Configurações.

## 6. Fluxo de dados

Câmeras → Modelo de Visão Computacional → Backend → Banco de Dados → Dashboard UltraSafe → Operador.

Quando uma situação de risco é encontrada, o sistema cria um alerta que é exibido ao operador.

O operador pode analisar, confirmar, encaminhar para manutenção e posteriormente encerrar a ocorrência.

---

# Gestão Ágil

O desenvolvimento da Sprint 3 foi organizado utilizando Scrum.

O board do Trello possui as seguintes etapas:

* Product Backlog
* Sprint Backlog
* Em andamento
* Em revisão
* Concluído

Também foram documentadas as seguintes cerimônias:

* Sprint Planning;
* Daily Scrum;
* Sprint Review.

Foi criada uma Definition of Done para estabelecer os critérios necessários para considerar uma atividade finalizada.

---

# Links do Projeto

## Protótipo Figma

(https://www.figma.com/make/6VWjMimHk2LFU6RbxjxJX4/Base-UI-for-UltraSafe?t=a05YFSaF5zfiWmPM-1)

## Board Scrum — Trello

https://trello.com/invite/b/6aa2e9837d0ec908b92b051d/ATTIdf32f6994ad6d3fd5172ae6f700f8dc96F6FFA92/ultra-safe

## Documento de Cerimônias Scrum

https://datacriticalticombr-my.sharepoint.com/:w:/r/personal/victor_oliveira_datacriticalti_com_br/Documents/Documentos/Cerim%C3%B4nias%20Scrum.docx?d=w322e5c27c0ed451380b7622ea06adba0&csf=1&web=1&e=lZvQLg
---

# Tecnologias e conceitos utilizados

* Figma
* Scrum
* Trello
* Visão Computacional
* Inteligência Artificial
* Interface Web
* Segurança Industrial
* GitHub

---

# Status do projeto

Sprint 3 concluída.

As principais evoluções do protótipo e a organização Scrum foram implementadas e documentadas.
