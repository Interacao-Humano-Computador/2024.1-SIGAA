# Análise de Tarefas: Declaração de Bolsista

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

## HTA para Solicitação de Bolsas
Esta tabela detalha as tarefas envolvidas na solicitação, acompanhamento e renovação de bolsas auxílio.

###  Declaração de Bolsista

Nesta tarefa, o usuário tem como objetivo acessar e interagir com as declarações de bolsista, podendo assinar declarações referentes ao não acúmulo de bolsas ou visualizar as declarações já assinadas.

| **Objetivos/Operações** | **Problemas e Recomendações** |
|-------------------------|-------------------------------|
| **0. Acessar Declarações de Bolsista** | **Input:** Seleção da opção "Declaração de Bolsista" no menu de bolsas.<br>**Feedback:** As opções para assinar ou visualizar declarações são exibidas.<br>**Plano:** Assegurar clareza e acessibilidade nas opções e descrições para evitar confusões. |
| **1. Assinar Declaração (0>1)** | **Input:** Clicar em "Assinar Declaração".<br>**Feedback:** Formulário para assinatura é apresentado, solicitando confirmação de dados e senha.<br>**Plano:** Simplificar o formulário garantindo segurança nos dados. Confirmações visuais de sucesso devem ser claras. |
| **2. Visualizar Assinaturas (0>2)** | **Input:** Clicar em "Visualizar Assinaturas".<br>**Feedback:** Lista de declarações assinadas é exibida.<br>**Plano:** Proporcionar uma fácil navegação e filtros eficientes para buscar declarações por datas ou outros critérios relevantes. |



Esta HTA simplifica e esclarece as relações entre as operações dentro da função "Solicitação de Bolsas", garantindo que os usuários possam navegar e completar suas tarefas com eficiência e eficácia.

### GOMS

# GOMS (Goals, Operators, Methods and Selection Rules)

## Introdução

O método GOMS é uma abordagem de análise de tarefas que ajuda a descrever como os usuários interagem com um sistema para alcançar seus objetivos. Esta análise se concentra especificamente nas tarefas relacionadas à declaração de bolsistas no sistema SIGAA, cobrindo as operações de "Assinar Declaração" e "Visualizar Assinaturas".

## Objetivo da Análise

Identificar e descrever as etapas que os usuários seguem para realizar a assinatura e visualização de declarações de bolsistas no SIGAA. Isso ajuda a otimizar a interface do usuário para essas tarefas, melhorando a eficiência e a satisfação do usuário.

## Tarefas Analisadas

# GOMS para Declaração de Bolsista

## Definição dos Objetivos

- **Assinar Declaração de Não Acúmulo de Bolsas:** Confirmar que o estudante não está recebendo múltiplas bolsas indevidamente.
- **Visualizar Declarações Anteriores:** Acessar informações sobre declarações de não acúmulo de bolsas previamente submetidas.

## Definição dos Operadores

- **Selecionar:** Escolher a opção "Declaração de Bolsista" no menu de bolsas.
- **Inserir:** Adicionar informações pessoais e senha para autenticação.
- **Consultar:** Buscar registros de declarações anteriores.
- **Exibir:** Mostrar informações das declarações já realizadas.
- **Confirmar:** Validar a declaração com a inserção de dados autenticados.
- **Navegar:** Mover-se entre diferentes seções ou telas relacionadas a bolsas.

## Definição dos Métodos

- **Assinar Declaração de Não Acúmulo:** Selecionar a declaração, inserir e confirmar dados pessoais e submeter.
- **Visualizar Declarações Anteriores:** Selecionar e exibir informações detalhadas das declarações previamente assinadas.

## Definição das Regras de Seleção

- **Escolher Declaração para Assinar ou Visualizar:** Decidir entre criar uma nova declaração ou revisar uma existente, baseado na necessidade do usuário.
- **Confirmar Identidade para Segurança:** Inserir senha para assegurar que a declaração é submetida pelo próprio estudante.

## Execução GOMS

         METHOD 0:
         - OP 0: Navegar até a seção "Bolsas" usando o menu principal.
         
         **GOAL 1: Assinar declaração de não acúmulo de bolsas**  
         **METHOD 1:**  
         - OP 1: Selecionar "Declaração de Bolsista" no menu de bolsas.
         - OP 2: Clicar em "Assinar Declaração".
         - OP 3: Confirmar identidade inserindo a data de nascimento e senha.
         - OP 4: Submeter a declaração e verificar a mensagem de sucesso.
         
         **GOAL 2: Visualizar declarações assinadas**  
         **METHOD 2:**  
         - OP 1: Selecionar "Declaração de Bolsista" no menu de bolsas.
         - OP 2: Clicar em "Visualizar Assinaturas".
         - OP 3: Revisar a lista de declarações assinadas.



### Declaração de Bolsistas

#### 1. Assinar Declaração
- **Goal**: Acessar e completar o formulário de assinatura de declaração de bolsista.
- **Operators**:
  - Navegar até a seção "Declaração de Bolsistas"
  - Selecionar "Assinar Declaração"
  - Preencher o formulário
  - Submeter o formulário
- **Methods**:
  - Usar a interface do sistema para navegar, selecionar e preencher as informações necessárias.
- **Selection Rules**:
  - Se o usuário precisa revisar a declaração antes de submeter, revisar o texto antes de finalizar o envio.

#### 2. Visualizar Assinaturas
- **Goal**: Acessar e revisar as assinaturas de declarações realizadas anteriormente.
- **Operators**:
  - Navegar até a seção "Declaração de Bolsistas"
  - Selecionar "Visualizar Assinaturas"
  - Visualizar os documentos assinados
- **Methods**:
  - Usar a interface do sistema para localizar e revisar documentos específicos.
- **Selection Rules**:
  - Se o usuário busca uma declaração específica, usar filtros para facilitar a busca.

## Conclusão

Esta análise GOMS revela áreas chave onde melhorias podem ser feitas para tornar a experiência do usuário mais eficiente e agradável. Otimizar os formulários e a navegabilidade pode reduzir erros e aumentar a satisfação dos usuários ao interagir com o sistema SIGAA.

## Bibliografia

- BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data     | Descrição                           | Autor(es)              | Revisor(es)         |
| ------ | -------- | ----------------------------------- | ---------------------- | ------------------- |
| 1.0    | 14/10/23 | Criação do documento | Bruno Araújo | -    |


