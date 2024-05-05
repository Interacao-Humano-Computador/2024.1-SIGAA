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

### Análise Contextual

<details>
  <summary size="20"><b> Análise Contextual </b></summary> 
  
    0. Visualização de Monitoria
      1. Verificar Monitoria Atual
         1.1 Estabelecer Forma e Grade de Atendimento
            1.1.1 Configurar Forma de Atendimento
               1.1.1.1 Selecionar Forma de Atendimento (WhatsApp, Telegram, Presencial)
               1.1.1.2 Personalizar Configurações de Atendimento (Notificações, Disponibilidade)
            1.1.2 Estabelecer Grade de Atendimento
               1.1.2.1 Selecionar Horários Disponíveis e Duração das Monitorias
               1.1.2.2 Priorizar Horários de Pico de Dificuldade nas Disciplinas
               1.1.2.3 Reservar Horários para Atendimento Extra (Sessões de Dúvidas)
         1.2 Solicitar Aluguel de Salas para Aulas de Monitorias
            1.2.1 Inserir Data, Horário Desejado e Duração da Monitoria
            1.2.2 Verificar Disponibilidade de Salas
               1.2.2.1 Consultar Sistema de Reservas de Salas
               1.2.2.2 Avaliar Opções de Salas Disponíveis (Localização, Capacidade)
            1.2.2 .3 Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis
               1.2.2.3.1 Notificar Usuário sobre Indisponibilidade de Salas
               1.2.2.3.2 Sugerir Alternativas (Outras Salas, Outros Horários)
         1.3 Trocar Mensagens Privadas com Professores e Alunos
               1.3.1 Selecionar Professor ou Aluno
               1.3.2 Enviar e Receber Mensagens
               1.3.3 Agendar Reunião Presencial (Se Necessário)
      2. Verificar Monitorias Anteriores
            2.1 Escolha entre os Registros de Monitorias Anteriores
            2.2 Visualização dos Dados Anteriores sem Possibilidade de Modificação
            2.3 Consultar Relatórios, Avaliações e Feedback de Monitorias Passadas

</details>

