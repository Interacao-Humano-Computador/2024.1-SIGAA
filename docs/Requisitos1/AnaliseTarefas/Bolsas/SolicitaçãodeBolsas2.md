# Análise de Tarefas: Solicitação de Bolsas

- [Introdução](#introdução)
- [Objetivos](#objetivos)
- [Análise Hierárquica de Tarefas](#análise-hierárquica-de-tarefas)
  - [Análise Contextual](#análise-contextual)
  - [Tabela: HTA para Solicitação de Bolsas](#tabela-hta-para-solicitação-de-bolsas)
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

         Acessar o módulo de Solicitação de Bolsas
         A partir da interface principal do SIGAA, o usuário deve localizar e acessar a opção "Solicitação de Bolsas" dentro do menu correspondente.
         Selecionar a opção "Solicitação de Bolsa Auxílio"
         2.1 Clicar na opção para abrir o formulário de solicitação.
         2.2 Ler as condições do edital disponíveis para entender os critérios e requisitos necessários.
         Escolher a opção de bolsa desejada
         3.1 Analisar as diferentes opções de bolsas oferecidas e selecionar a que melhor se adequa às necessidades do estudante.
         Preencher os campos requeridos no formulário
         4.1 Inserir todas as informações necessárias conforme solicitado no formulário.
         4.2 Justificar a necessidade da bolsa e anexar documentos comprobatórios.
         4.3 Submeter o formulário para análise.
         Acompanhar a Solicitação de Bolsas Auxílios
         5.1 Voltar ao módulo de solicitação de bolsas para verificar o status da solicitação.
         5.2 Analisar o feedback recebido e tomar ações conforme necessário.
         Renovar Bolsa Auxílio
         6.1 Clicar na opção "Renovar Bolsa Auxílio".
         6.2 Conferir os dados cadastrais e atualizar se necessário.
         6.3 Preencher o questionário de renovação e anexar documentos adicionais se requeridos.
         6.4 Confirmar a submissão da renovação da bolsa.

#### Tabela: HTA para Solicitação de Bolsas
Para facilitar a visualização de tarefas, a imagem 1 mostra o diagrama:
![Solicitação de bolsas HTA](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/140026699/1f870d1a-355d-4a7c-bdac-beb1203396c7)


Esta tabela detalha as tarefas envolvidas na solicitação, acompanhamento e renovação de bolsas auxílio.

### Tabela de Análise para Solicitação de Bolsas

| Objetivos / Operações                                       | Relações  | Problemas e Recomendações                                        |
|-------------------------------------------------------------|-----------|-----------------------------------------------------------------|
| **0. Acessar o módulo de Solicitação de Bolsas**            |           | **Input:** Localização e acesso ao módulo.                      |
| **1. Selecionar a opção "Solicitação de Bolsa Auxílio"**    | 1 > 2, 3  | **Input:** Escolha da opção para iniciar o processo de solicitação.|
| **2. Ler as condições do Edital**                           | 2 > 3     | **Input:** Leitura e compreensão dos requisitos do edital.      |
| **3. Escolher a opção de bolsa**                            | 3 > 4     | **Input:** Seleção do tipo de bolsa desejada.                   |
| **4. Preencher os campos requeridos no formulário**         | 4 > 5     | **Input:** Inserção de dados pessoais e documentos.             |
| **5. Submeter a solicitação**                               | 5 > 6     | **Feedback:** Confirmação da submissão da solicitação.          |
| **6. Acompanhar a Solicitação de Bolsas Auxílios**          | 6 > 7     | **Input:** Verificação do status da solicitação.                |
| **7. Conferir status da solicitação**                       | 7 > 8     | **Feedback:** Informação sobre o progresso ou resultados da análise.|
| **8. Clicar em Renovar Bolsa Auxílio**                      | 8 > 9, 10 | **Input:** Início do processo de renovação da bolsa.            |
| **9. Conferir cadastro e preencher o questionário**         | 9 > 10    | **Input:** Atualização de informações e resposta ao questionário.|
| **10. Anexar documentos necessários e confirmar a submissão** |           | **Feedback:** Finalização do processo de renovação da bolsa.    |


### Execução do GOMS

#### GOMS para "Solicitação de Bolsas"

```
Nessa tarefa, o usuário possui o objetivo de preencher e submeter um formulário para solicitar uma bolsa de auxílio.
         - GOAL 0: Solicitar uma bolsa de auxílio.
           - METHOD 0.A: Selecionar "Solicitação de Bolsa - Solicitação de Bolsa Auxílio".
             - OP. 0.A.1: Clicar na opção "Solicitação de Bolsa Auxílio".
           - METHOD 0.B: Preencher o formulário.
             - OP. 0.B.1: Entrar dados no formulário.
           - METHOD 0.C: Submeter o formulário.
             - OP. 0.C.1: Clicar em "Continuar".
             - (SEL. RULE: o usuário preencheu todas as informações necessárias e deseja prosseguir.)
```
## Conclusão

Esta análise GOMS revela áreas chave onde melhorias podem ser feitas para tornar a experiência do usuário mais eficiente e agradável. Otimizar os formulários e a navegabilidade pode reduzir erros e aumentar a satisfação dos usuários ao interagir com o sistema SIGAA.

## Bibliografia

- BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data     | Descrição                           | Autor(es)              | Revisor(es)         |
| ------ | -------- | ----------------------------------- | ---------------------- | ------------------- |
| 1.0    | 05/05/24 | Criação                             | Bruno Araújo           | -                   |
