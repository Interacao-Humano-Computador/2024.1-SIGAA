# Análise de Tarefas: Declaração de Bolsista

- [Introdução](#introdução)
- [Objetivos](#objetivos)
- [Análise Hierárquica de Tarefas (HTA)](#análise-hierárquica-de-tarefas-hta)
  - [Análise Contextual](#análise-contextual)
  - [Diagrama de Atividades](#diagrama-de-atividades)
  - [Tabela de Análise](#tabela-de-análise)
- [GOMS](#goms)
  - [Definição dos Objetivos](#definição-dos-objetivos)
  - [Definição dos Operadores](#definição-dos-operadores)
  - [Definição dos Métodos](#definição-dos-métodos)
  - [Definição das Regras de Seleção](#definição-das-regras-de-seleção)
  - [Execução do GOMS](#execução-do-goms)
- [Conclusão](#conclusão)
- [Bibliografia](#bibliografia)
- [Histórico de Versão](#histórico-de-versão)

## Introdução

A solicitação de bolsa é um processo importante para estudantes que buscam apoio financeiro para sua educação. Entender o fluxo e os requisitos envolvidos nesse procedimento é fundamental para garantir que os alunos possam acessar os recursos de forma eficiente e transparente. Este documento tem como objetivo analisar o processo de solicitação de bolsa, identificando pontos-chave e possíveis áreas de otimização para aprimorar a experiência dos solicitantes e facilitar o acesso aos recursos disponíveis.

## Objetivos

A funcionalidade de solicitação de bolsa no SIGAA da UNB tem como objetivo atender a uma série de metas para simplificar e agilizar o processo de solicitação de apoio financeiro. Alguns dos principais objetivos incluem:

- Permitir que os estudantes preencham e enviem formulários de solicitação de bolsa de forma fácil e intuitiva, fornecendo todas as informações necessárias de maneira clara.
- Facilitar o acompanhamento do status da solicitação de bolsa, fornecendo atualizações regulares sobre o progresso do processo.
- Garantir que o processo de solicitação de bolsa seja transparente e justo, fornecendo feedback claro aos solicitantes e garantindo uma comunicação aberta entre os estudantes e a instituição.

## Análise Hierárquica de Tarefas

A análise de tarefas consiste em desmembrar as atividades dos usuários em elementos menores, denominados tarefas, que estão inseridas em um sistema ou interface. Essa abordagem visa simplificar tarefas complexas, dividindo-as em objetivos, subobjetivos e operações, e estabelecendo um plano para determinar a sequência adequada de realização desses subobjetivos. Abaixo, serão fornecidos detalhes sobre a análise contextual, o diagrama e a tabela que ilustram esse processo.

### Análise Contextual

Como há um conjunto de tarefas a serem realizadas, abaixo está a análise contextual e hierárquica utilizada.

         1.Acessar o módulo de Solicitação de Bolsas
           1.1A partir da interface principal do SIGAA, o usuário deve localizar e acessar a opção "Solicitação de Bolsas" dentro do menu correspondente.
         2.Selecionar a opção "Solicitação de Bolsa Auxílio"
           2.1 Clicar na opção para abrir o formulário de solicitação.
           2.2 Ler as condições do edital disponíveis para entender os critérios e requisitos necessários.
         3.Escolher a opção de bolsa desejada
           3.1 Analisar as diferentes opções de bolsas oferecidas e selecionar a que melhor se adequa às necessidades do estudante.
         4.Preencher os campos requeridos no formulário
           4.1 Inserir todas as informações necessárias conforme solicitado no formulário.
           4.2 Justificar a necessidade da bolsa e anexar documentos comprobatórios.
           4.3 Submeter o formulário para análise.
         5.Acompanhar a Solicitação de Bolsas Auxílios
           5.1 Voltar ao módulo de solicitação de bolsas para verificar o status da solicitação.
           5.2 Analisar o feedback recebido e tomar ações conforme necessário.
         6.Renovar Bolsa Auxílio
           6.1 Clicar na opção "Renovar Bolsa Auxílio".
           6.2 Conferir os dados cadastrais e atualizar se necessário.
           6.3 Preencher o questionário de renovação e anexar documentos adicionais se requeridos.
           6.4 Confirmar a submissão da renovação da bolsa.

#### Tabela: HTA para Solicitação de Bolsas
Para facilitar a visualização de tarefas, a imagem 1 mostra o diagrama:
![Solicitação de bolsas HTA](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/140026699/1f870d1a-355d-4a7c-bdac-beb1203396c7)


Esta tabela detalha as tarefas envolvidas na solicitação, acompanhamento e renovação de bolsas auxílio.

### Tabela de Análise para Solicitação de Bolsas

### Tabela de Análise para Solicitação de Bolsas

| Objetivos / Operações                                       | Relações | Problemas e Recomendações                                       |
|-------------------------------------------------------------|----------|-----------------------------------------------------------------|
| 0. Acessar o módulo de Solicitação de Bolsas                |          | **Input:** Localização e acesso ao módulo.                      |
| 1. Selecionar a opção "Solicitação de Bolsa Auxílio"        | 1 > 2    | **Input:** Escolha da opção para iniciar o processo de solicitação. |
| 2. Ler as condições do Edital                               | 2 > 3    | **Input:** Leitura e compreensão dos requisitos do edital.      |
| 3. Escolher a opção de bolsa                                | 3 > 4    | **Input:** Seleção do tipo de bolsa desejada.                   |
| 4. Preencher os campos requeridos no formulário             | 4 > 5    | **Input:** Inserção de dados pessoais e documentos.             |
| 5. Submeter a solicitação                                   | 5 > 6    | **Feedback:** Confirmação da submissão da solicitação.          |
| 6. Acompanhar a Solicitação de Bolsas Auxílios              | 6 > 7    | **Input:** Verificação do status da solicitação.                |
| 7. Conferir status da solicitação                           |          | **Feedback:** Informação sobre o progresso ou resultados da análise. |

# GOMS

## Introdução
O método GOMS é uma abordagem de análise de tarefas que ajuda a descrever como os usuários interagem com um sistema para alcançar seus objetivos. Esta análise se concentra especificamente nas tarefas relacionadas à Declaração de Bolsistas no sistema SIGAA, cobrindo as operações de "Assinar Declaração" e "Visualizar Assinaturas"

# Definição dos Objetivos

Identificar e descrever as etapas que os usuários que utilizaram a opção do menu Bolsas, Solicitação de Bolsas, no SIGAA, para realizar a solicitação, acompanhamento e renovação de bolsas no SIGAA. Isso visa ajudar a otimizar a interface do usuário para essas tarefas, melhorando a eficiência e a satisfação do usuário.

## Tarefas Analisadas

- **Solicitar Bolsa Auxílio**: Envolve o preenchimento e a submissão de um formulário socioeconômico para solicitar uma bolsa auxílio.
- **Acompanhar Solicitação de Bolsa Auxílio**: Permite verificar o status atual da solicitação de bolsa auxílio.
- **Renovar Bolsa Auxílio**: Permite aos discentes contemplados com bolsa auxílio solicitar a renovação de suas bolsas.

## Definição dos Operadores

- **Selecionar**: Escolher opções específicas dentro do módulo de bolsas.
- **Preencher**: Adicionar informações pessoais e outras necessárias no formulário.
- **Submeter**: Enviar o formulário preenchido para análise.
- **Consultar**: Verificar o status atual da solicitação de bolsa.
- **Renovar**: Solicitar a renovação de uma bolsa já concedida.

## Definição dos Métodos

- **Solicitar Bolsa Auxílio**: Acessar o formulário, preencher os dados necessários, e submeter.
- **Acompanhar Solicitação de Bolsa Auxílio**: Selecionar a opção para verificar o status atual da solicitação.
- **Renovar Bolsa Auxílio**: Acessar a opção de renovação, preencher os dados necessários para a renovação, e submeter.

## Definição das Regras de Seleção

- **Escolher o Tipo de Bolsa**: Decidir qual tipo de bolsa auxílio deseja solicitar com base nas opções disponíveis.
- **Verificar Requisitos**: Antes de submeter a solicitação, verificar se todos os requisitos e documentações estão completos.

## Solicitar Bolsa Auxílio

- **Goal**: Acessar e completar o formulário de solicitação de bolsa auxílio.
- **Operators**:
  - Navegar até a seção "Solicitação de Bolsa Auxílio"
  - Preencher o formulário
  - Submeter o formulário
- **Methods**:
  - Usar a interface do sistema para inserir todas as informações requeridas e submeter a solicitação.
- **Selection Rules**:
  - Se todas as informações e documentos necessários estiverem completos, proceder com a submissão.

## Acompanhar Solicitação de Bolsa Auxílio

- **Goal**: Verificar o status da solicitação de bolsa auxílio.
- **Operators**:
  - Navegar até "Acompanhar Solicitação de Bolsa Auxílio"
  - Consultar o status da solicitação
- **Methods**:
  - Usar a interface do sistema para localizar a solicitação e verificar seu status atual.
- **Selection Rules**:
  - Se o usuário precisa de informações atualizadas sobre sua solicitação, usar esta funcionalidade.

## Renovar Bolsa Auxílio

- **Goal**: Renovar uma bolsa auxílio existente.
- **Operators**:
  - Navegar até "Renovar Bolsa Auxílio"
  - Preencher o formulário de renovação
  - Submeter a renovação
- **Methods**:
  - Usar a interface do sistema para renovar a bolsa, preenchendo todas as informações necessárias.
- **Selection Rules**:
  - Se a bolsa atual está prestes a expirar e o usuário deseja continuar recebendo o auxílio, proceder com a renovação.

### Execução do GOMS

```
Nessa tarefa, o usuário possui o objetivo de solicitar uma bolsa de auxílio.
   - **GOAL 0**: Acessar a funcionalidade de solicitação de bolsa auxílio.
     - **METHOD 0.A**: Navegar até a seção "Bolsas".
       - **OP. 0.A.1**: Clicar na aba "Bolsas".
     - **METHOD 0.B**: Selecionar a opção "Solicitação de Bolsa Auxílio".
       - **OP. 0.B.1**: Clicar na opção "Solicitação de Bolsa Auxílio".
       - **SEL. RULE**: Se o usuário deseja solicitar uma bolsa auxílio.
     - **METHOD 0.C**: Preencher e submeter o formulário de solicitação.
       - **OP. 0.C.1**: Entrar dados no formulário.
       - **OP. 0.C.2**: Clicar em "Continuar".
       - **SEL. RULE**: Se o usuário preencheu todas as informações necessárias e deseja prosseguir.

Nessa tarefa, o usuário possui o objetivo de acompanhar a solicitação de uma bolsa de auxílio.
   - **GOAL 1**: Acessar a funcionalidade de acompanhamento de bolsa auxílio.
     - **METHOD 1.A**: Navegar até a seção "Bolsas".
       - **OP. 1.A.1**: Clicar na aba "Bolsas".
     - **METHOD 1.B**: Selecionar "Acompanhar Solicitação de Bolsa Auxílio".
       - **OP. 1.B.1**: Clicar na opção "Acompanhar Solicitação de Bolsa Auxílio".
       - **SEL. RULE**: Se o usuário deseja verificar o status da sua solicitação de bolsa auxílio.
     - **METHOD 1.C**: Visualizar o status da solicitação.
       - **OP. 1.C.1**: Observar as informações exibidas na tela sobre o status atual da solicitação.

Nessa tarefa, o usuário possui o objetivo de renovar uma bolsa de auxílio existente.
   - **GOAL 2**: Acessar a funcionalidade de renovação de bolsa auxílio.
     - **METHOD 2.A**: Navegar até a seção "Bolsas".
       - **OP. 2.A.1**: Clicar na aba "Bolsas".
     - **METHOD 2.B**: Selecionar "Renovar Bolsa Auxílio".
       - **OP. 2.B.1**: Clicar na opção "Renovar Bolsa Auxílio".
       - **SEL. RULE**: Se o usuário deseja renovar sua bolsa auxílio.
     - **METHOD 2.C**: Preencher e submeter o formulário de renovação.
       - **OP. 2.C.1**: Inserir dados requeridos no formulário de renovação.
       - **OP. 2.C.2**: Clicar em "Submeter" ou "Continuar".
       - **SEL. RULE**: Se o usuário completou todos os campos necessários e deseja continuar com a renovação.
```
## Conclusão

Esta análise GOMS revela áreas chave onde melhorias podem ser feitas para tornar a experiência do usuário mais eficiente e agradável. Otimizar os formulários e a navegabilidade pode reduzir erros e aumentar a satisfação dos usuários ao interagir com o sistema SIGAA.

## Bibliografia

- BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data     | Descrição                           | Autor(es)              | Revisor(es)         |
| ------ | -------- | ----------------------------------- | ---------------------- | ------------------- |
| 1.0    | 05/05/24 | Criação                             | Bruno Araújo           | Iago Passaglia |
