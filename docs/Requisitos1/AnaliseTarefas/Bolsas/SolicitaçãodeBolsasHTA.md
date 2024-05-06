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

A funcionalidade de monitoramento proporcionará aos estudantes uma visão abrangente de sua participação em programas de monitoria ao longo dos semestres e permitirá que a monitoria atual tenha seus dados atualizados e incrementados. Sendo assim, este documento tem o objetivo de realizar uma análise detalhada das tarefas envolvidas nessa funcionalidade, visando compreender os processos subjacentes e identificar áreas de foco. Além disso, como essa funcionalidade também terá o objetivo de promover um conjunto de dados sobre o formato que a monitoria será dada, a nálise deverá permitir a análise para vários caminhos também.

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

## Análise de Tarefas



## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 04 de maio de 2024.
2. Vários Autores. GOMS. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/goms/#comprar-ingresso/>. Acesso em 04 de maio de 2024.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise GOMS | Iago Passaglia | Breno Alexandre | 04/05/2024 |

