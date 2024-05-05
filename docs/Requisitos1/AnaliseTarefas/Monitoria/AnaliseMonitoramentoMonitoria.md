# Análise de Tarefas: Monitoramento da Monitoria

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Análise Hierárquica de Tarefas](Análise-Hierárquica-de-Tarefas)
    * [Análise Contextual](#Análise-Contextual)
    * [Diagrama de Atividades](#Diagrama-de-Atividades)
    * [Tabela de Análise](#Tabela-de-Análise)
* [GOMS](#GOMS)
    * [Definição dos objetivos(Goals)](#Definição-dos-objetivos)
    * [Definição dos operadores(Operators)](#Definição-dos-operadores(Operators))
    * [Definição dos Métodos](#Definição-dos-Métodos )
    * [Definição das Regras de Seleção](#Definição-das-Regras-de-Seleção)
    * [Execução do GOMS](#Execução-do-GOMS)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

A funcionalidade de monitoramento proporcionará aos estudantes uma visão abrangente de sua participação em programas de monitoria ao longo dos semestres e permitirá que a monitoria atual tenha seus dados atualizados e incrementados. Sendo
assim, este documento tem o objetivo de realizar uma análise detalhada das tarefas envolvidas nessa funcionalidade, visando compreender os processos subjacentes e identificar áreas de foco. Além disso, como essa funcionalidade também terá o objetivo de promover um conjunto de dados sobre o formato que a monitoria será dada, a análise terá o objetivo de verificar a complexidade de aprendizado do seu uso.

## Objetivos
A funcionalidade de monitoramento visa atender a uma série de objetivos essenciais para aumentar a eficácia de acesso a dados e melhorar a organização. Alguns dos principais objetivos incluem:

- Permitir acesso a informações detalhadas sobre a participação em programas de monitoria ao longo de vários semestres, anteriores e atuais.
- Possibilitar que os estudantes monitores documentem e disponibilizem uma grade horária de atendimento.
- Permitir que seja realizado o aluguel de salas para aula de monitoria atual.
- Permitir que o monitor envie mensagens para a turma ou para o docente no privado.

## Análise Hierárquica de Tarefas

A análise de tarefas consiste em desmembrar as atividades dos usuários em elementos menores, denominados tarefas, que estão inseridas em um sistema ou interface. Essa abordagem visa simplificar tarefas complexas, dividindo-as em objetivos, subobjetivos e operações, e estabelecendo um plano para determinar a sequência adequada de realização desses subobjetivos. Abaixo, serão fornecidos detalhes sobre a análise contextual, o diagrama e a tabela que ilustram esse processo.

### Análise Contextual

Como há um conjunto de tarefas a serem realizadas, há baixo há a análise contextual e hierárquica utilizada.

<details>
  <summary size="20"><b> Análise Contextual </b></summary> 
  
    0. Visualização de Monitoria (1/2)
      1. Verificar Monitoria Atual (1/2)
         1.1 Estabelecer Forma e Grade de Atendimento (1+2)
            1.1.1 Configurar Forma de Atendimento (1+2)
               1.1.1.1 Selecionar Forma de Atendimento (WhatsApp, Telegram, Presencial)
               1.1.1.2 Personalizar Configurações de Atendimento (Notificações, Disponibilidade)
            1.1.2 Estabelecer Grade de Atendimento (1+2)
               1.1.2.1 Selecionar Horários Disponíveis e Duração das Monitorias
               1.1.2.2 Priorizar Horários de Pico de Dificuldade nas Disciplinas
               1.1.2.3 Reservar Horários para Atendimento Extra (Sessões de Dúvidas)
         1.2 Solicitar Aluguel de Salas para Aulas de Monitorias (1>2)
            1.2.1 Inserir Data, Horário Desejado e Duração da Monitoria
            1.2.2 Verificar Disponibilidade de Salas (1>2)
               1.2.2.1 Consultar Sistema de Reservas de Salas
               1.2.2.2 Avaliar Opções de Salas Disponíveis (Localização, Capacidade)
            1.2.2 .3 Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis (1>2)
               1.2.2.3.1 Notificar Usuário sobre Indisponibilidade de Salas
               1.2.2.3.2 Sugerir Alternativas (Outras Salas, Outros Horários)
         1.3 Trocar Mensagens Privadas com Professores e Alunos (1>2)
               1.3.1 Selecionar Professor ou Aluno
               1.3.2 Enviar e Receber Mensagens
               1.3.3 Agendar Reunião Presencial (Se Necessário)
      2. Verificar Monitorias Anteriores (1>2)
            2.1 Escolha entre os Registros de Monitorias Anteriores
            2.2 Visualização dos Dados Anteriores sem Possibilidade de Modificação
            2.3 Consultar Relatórios, Avaliações e Feedback de Monitorias Passadas

</details>

### Diagrama de Atividades

Para facilitar a visualização de tarefas, a imagem 1 mostra o diagrama:

### Tabela de Análise

A tabela 1 mostra a tabela da análise hierárquica de tarefas sobre a funcionalidade de pedido de monitoria.

<details>
  <summary size="20"><b> Tabela de Análise </b></summary> 

| Objetivos/Operações | Relações | Problemas e Recomendações |
|---------------------|----------|--------------------------|
| 0. Visualização de Monitoria | (1/2) | **Input:** Solicitação de visualização do status de monitorias. <br> **Feedback:** Apresentação das informações de monitorias atuais e anteriores. <br> **Plano:** Desenvolver uma interface intuitiva para a visualização dos dados. <br> **Recomendação:** Incluir filtros e opções de ordenação para facilitar a navegação. |
| 1. Verificar Monitoria Atual | (1/2) | **Input:** Requisição para ver o status da monitoria atual. <br> **Feedback:** Apresentação do status atual da monitoria. <br> **Plano:** Acessar os dados do sistema de monitoramento. <br> **Recomendação:** Garantir que as informações sejam atualizadas em tempo real. |
| 1.1 Estabelecer Forma e Grade de Atendimento | (1+2) | **Input:** Preferências do usuário, disponibilidade de horários. <br> **Feedback:** Confirmação de seleções. <br> **Plano:** Personalizar configurações conforme preferências do usuário. <br> **Recomendação:** Facilitar a seleção de horários com uma interface intuitiva. |
| 1.1.1 Configurar Forma de Atendimento | (1+2) | **Input:** Opções de formas de atendimento. <br> **Feedback:** Confirmação da seleção. <br> **Plano:** Facilitar o acesso às configurações. <br> **Recomendação:** Oferecer opções adicionais de comunicação, como videoconferência. |
| 1.1.1.1 Selecionar Forma de Atendimento (WhatsApp, Telegram, Presencial) | | **Plano:** Integrar sistemas de comunicação selecionados para garantir a compatibilidade. <br> **Recomendação:** Fornecer guias ou tutoriais sobre o uso das formas de comunicação selecionadas. |
| 1.1.1.2 Personalizar Configurações de Atendimento (Notificações, Disponibilidade) | | |
| 1.1.2 Estabelecer Grade de Atendimento | (1+2) | **Input:** Disponibilidade de horários, preferências do usuário. <br> **Feedback:** Confirmação das seleções. <br> **Plano:** Organizar horários de acordo com preferências do usuário. <br> **Recomendação:** Permitir a seleção de múltiplos horários simultaneamente. |
| 1.1.2.1 Selecionar Horários Disponíveis e Duração das Monitorias |  | **Plano:** Organizar horários conforme preferências do usuário. <br> **Recomendação:** Oferecer opções de duração de monitorias pré-definidas. |
| 1.1.2.2 Priorizar Horários de Pico de Dificuldade nas Disciplinas | | **Plano:** Priorizar horários mais requisitados. <br> **Recomendação:** Oferecer sugestões com base nas estatísticas de dificuldade. |
| 1.1.2.3 Reservar Horários para Atendimento Extra (Sessões de Dúvidas) |  | **Plano:** Reservar horários conforme demanda. <br> **Recomendação:** Disponibilizar horários extras em períodos de pico de dificuldade. |
| 1.2 Solicitar Aluguel de Salas para Aulas de Monitorias | (1>2) | **Input:** Data, horário e duração desejados. <br> **Feedback:** Confirmação da solicitação. <br> **Plano:** Verificar a disponibilidade de salas. <br> **Recomendação:** Facilitar o acesso às informações sobre disponibilidade de salas. |
| 1.2.1 Inserir Data, Horário Desejado e Duração da Monitoria |  |  **Plano:** Verificar a disponibilidade de salas. <br> **Recomendação:** Oferecer opções de duração de monitoria pré-definidas. |
| 1.2.2 Verificar Disponibilidade de Salas | (1>2) | **Input:** Requisição de reserva de sala. <br> **Feedback:** Informação sobre disponibilidade de salas. <br> **Plano:** Oferecer alternativas em caso de indisponibilidade. <br> **Recomendação:** Notificar o usuário sobre as opções disponíveis. |
| 1.2.2.1 Consultar Sistema de Reservas de Salas |  | **Plano:** Integrar-se ao sistema de reservas. <br> **Recomendação:** Facilitar a pesquisa e reserva de salas. |
| 1.2.2.2 Avaliar Opções de Salas Disponíveis (Localização, Capacidade) | | **Plano:** Apresentar detalhes sobre as salas disponíveis. <br> **Recomendação:** Incluir informações sobre localização e capacidade das salas. |
| 1.2.2.3 Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis | (1>2) | **Input:** Indisponibilidade de salas. <br> **Feedback:** Informação sobre alternativas. <br> **Plano:** Sugerir alternativas de salas ou horários. <br> **Recomendação:** Oferecer opções de horários flexíveis para a monitoria. |
| 1.2.2.3.1 Notificar Usuário sobre Indisponibilidade de Salas | | **Plano:** Informar ao usuário sobre a indisponibilidade. <br> **Recomendação:** Oferecer soluções alternativas para a realização da monitoria. |
| 1.2.2.3.2 Sugerir Alternativas (Outras Salas, Outros Horários) | |**Plano:** Apresentar opções alternativas de salas ou horários. <br> **Recomendação:** Facilitar o acesso às opções alternativas. |
| 1.3 Trocar Mensagens Privadas com Professores e Alunos | (1>2) | **Input:** Interação com professores e alunos. <br> **Feedback:** Respostas às mensagens. <br> **Plano:** Facilitar a comunicação privada. <br> **Recomendação:** Garantir a privacidade das mensagens. |
| 1.3.1 Selecionar Professor ou Aluno | | **Plano:** Integrar sistema de seleção com banco de dados de usuários. <br> **Recomendação:** Facilitar a busca e seleção de contatos. |
| 1.3.2 Enviar e Receber Mensagens | | **Plano:** Implementar sistema de mensagens seguro e eficiente. <br> **Recomendação:** Criptografar mensagens para garantir privacidade. |
| 1.3.3 Agendar Reunião Presencial (Se Necessário) | | **Plano:** Integrar sistema de mensagens com calendário. <br> **Recomendação:** Disponibilizar opções de agendamento com base na disponibilidade de professores e alunos. |
| 2. Verificar Monitorias Anteriores | (1>2) | **Input:** Solicitação para visualizar monitorias anteriores. <br> **Feedback:** Apresentação das monitorias anteriores. <br> **Plano:** Acessar o histórico de monitorias. <br> **Recomendação:** Organizar e apresentar as informações de forma clara e concisa. |
| 2.1 Escolha entre os Registros de Monitorias Anteriores | | **Plano:** Desenvolver interface intuitiva para seleção de registros. <br> **Recomendação:** Incluir opções de filtro e busca para facilitar a seleção. |
| 2.2 Visualização dos Dados Anteriores sem Possibilidade de Modificação | | **Plano:** Implementar sistema de visualização de dados seguro e eficiente. <br> **Recomendação:** Garantir acesso apenas a usuários autorizados. |
| 2.3 Consultar Relatórios, Avaliações e Feedback de Monitorias Passadas | | **Plano:** Integrar relatórios, avaliações e feedback ao sistema de visualização de dados. <br> **Recomendação:** Disponibilizar ferramentas de análise para extrair insights dos dados anteriores. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>
