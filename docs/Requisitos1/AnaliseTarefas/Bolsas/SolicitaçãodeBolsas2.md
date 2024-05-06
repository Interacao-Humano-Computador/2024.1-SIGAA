# Análise de Tarefas: Solicitação de Bolsas
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

A solicitação de bolsa é um processo importante para estudantes que buscam apoio financeiro para sua educação, entender o fluxo e os requisitos envolvidos nesse procedimento é fundamental para garantir que os alunos possam acessar os recursos de forma eficiente e transparente. Este documento tem como objetivo analisar o processo de solicitação de bolsa, identificando pontos-chave e possíveis áreas de otimização para aprimorar a experiência dos solicitantes e facilitar o acesso aos recursos disponíveis.

## Objetivos
A funcionalidade de monitoramento visa atender a uma série de objetivos para aumentar a eficácia de acesso a dados e melhorar a organização. Alguns dos principais objetivos incluem:

- Permitir acesso a informações detalhadas sobre a participação em programas de monitoria ao longo de vários semestres, anteriores e atuais.
- Possibilitar que os estudantes monitores documentem e disponibilizem uma grade horária de atendimento.
- Permitir que seja realizado o aluguel de salas para aula de monitoria atual.
- Permitir que o monitor envie mensagens para a turma ou para o docente no privado.

## Análise Hierárquica de Tarefas

A análise de tarefas consiste em desmembrar as atividades dos usuários em elementos menores, denominados tarefas, que estão inseridas em um sistema ou interface. Essa abordagem visa simplificar tarefas complexas, dividindo-as em objetivos, subobjetivos e operações, e estabelecendo um plano para determinar a sequência adequada de realização desses subobjetivos. Abaixo, serão fornecidos detalhes sobre a análise contextual, o diagrama e a tabela que ilustram esse processo.

### Análise Contextual

Como há um conjunto de tarefas a serem realizadas, há baixo há a análise contextual e hierárquica utilizada.

# Análise Hierárquica de Tarefas (HTA) para Solicitação de Bolsas no SIGAA

## Tabela: HTA para Solicitação de Bolsas
Esta tabela detalha as tarefas envolvidas na solicitação, acompanhamento e renovação de bolsas auxílio.

| Objetivos/Operações                                   | Problemas e Recomendações                                                                                                  |
|-------------------------------------------------------|--------------------------------------------------------------------------------------------------|
| **0. Acessar Solicitação de Bolsas**                  | **Input:** Seleção da opção "Solicitação de Bolsas" no menu "Bolsas".<br>**Feedback:** Exibição das opções de solicitação de bolsa.<br>**Plano:** Assegurar fácil acesso e visibilidade das opções de solicitação. |
| **1. Solicitar Bolsa Auxílio (1>2)**                  | **Input:** Clicar em "Solicitar Bolsa Auxílio".<br>**Feedback:** Formulário de solicitação é apresentado.<br>**Plano:** Garantir que o formulário seja intuitivo e fácil de preencher, oferecendo instruções claras. |
| **2. Acompanhar Solicitação de Bolsa Auxílio (1+2)**  | **Input:** Clicar em "Acompanhar Solicitação de Bolsa Auxílio".<br>**Feedback:** Status atual da solicitação é exibido.<br>**Plano:** Prover atualizações regulares sobre o status da solicitação, permitindo ao usuário acompanhar o progresso. |
| **3. Renovar Bolsa Auxílio (1/2)**                    | **Input:** Clicar em "Renovar Bolsa Auxílio".<br>**Feedback:** Formulário de renovação é disponibilizado.<br>**Plano:** Simplificar o processo de renovação com preenchimento automático de informações conhecidas e claras instruções de submissão. |

Esta HTA simplifica e esclarece as relações entre as operações dentro da função "Solicitação de Bolsas", garantindo que os usuários possam navegar e completar suas tarefas com eficiência e eficácia.

### GOMS

## GOMS para "Solicitação de Bolsas"

### Nessa tarefa, o usuário possui o objetivo de preencher e submeter um formulário para solicitar uma bolsa de auxílio.
         - GOAL 0: Solicitar uma bolsa de auxílio.
           - METHOD 0.A: Selecionar "Solicitação de Bolsa - Solicitação de Bolsa Auxílio".
             - OP. 0.A.1: Clicar na opção "Solicitação de Bolsa Auxílio".
           - METHOD 0.B: Preencher o formulário.
             - OP. 0.B.1: Entrar dados no formulário.
           - METHOD 0.C: Submeter o formulário.
             - OP. 0.C.1: Clicar em "Continuar".
             - (SEL. RULE: o usuário preencheu todas as informações necessárias e deseja prosseguir.)
         
         ### Nessa tarefa, o usuário possui o objetivo de verificar o status atual de suas solicitações de bolsa auxílio.
         - GOAL 1: Acompanhar solicitação de bolsa auxílio.
           - METHOD 1.A: Visualizar informações atualizadas sobre o status da solicitação.
             - OP. 1.A.1: Clicar em "Acompanhar Solicitação de Bolsa Auxílio".
             - (SEL. RULE: o usuário necessita acompanhar uma solicitação existente.)
         
         ### Nessa tarefa, o usuário possui o objetivo de renovar uma bolsa auxílio existente.
         - GOAL 2: Renovar bolsa auxílio.
           - METHOD 2.A: Selecionar "Renovar Bolsa Auxílio".
             - OP. 2.A.1: Clicar na opção "Renovar Bolsa Auxílio".
           - METHOD 2.B: Preencher o formulário de renovação.
             - OP. 2.B.1: Entrar dados no formulário de renovação.
           - METHOD 2.C: Submeter o formulário de renovação.
             - OP. 2.C.1: Clicar em "Cadastrar".
             - (SEL. RULE: o usuário deseja renovar uma bolsa e já preencheu todas as informações.)


## Conclusão

Esta análise GOMS revela áreas chave onde melhorias podem ser feitas para tornar a experiência do usuário mais eficiente e agradável. Otimizar os formulários e a navegabilidade pode reduzir erros e aumentar a satisfação dos usuários ao interagir com o sistema SIGAA.

## Bibliografia

- BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data     | Descrição                           | Autor(es)              | Revisor(es)         |
| ------ | -------- | ----------------------------------- | ---------------------- | ------------------- |
| 1.0    | 05/05/24 | Criação do documento GOMS para SIGAA | Bruno Araújo | -     |
