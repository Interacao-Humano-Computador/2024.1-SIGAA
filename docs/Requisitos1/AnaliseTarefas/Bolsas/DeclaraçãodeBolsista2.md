# Análise de Tarefas: Declaração de Bolsista

## Sumário
<ul>
    <li><a href="#Introdução">Introdução</a></li>
    <li><a href="#Objetivos">Objetivos</a></li>
    <li><a href="#Análise-Hierárquica-de-Tarefas">Análise Hierárquica de Tarefas</a>
        <ul>
            <li><a href="#Análise-Contextual">Análise Contextual</a></li>
            <li><a href="#Diagrama-de-Atividades">Diagrama de Atividades</a></li>
            <li><a href="#Tabela-de-Análise">Tabela de Análise</a></li>
        </ul>
    </li>
    <li><a href="#GOMS">GOMS</a>
        <ul>
            <li><a href="#Definição-dos-objetivos">Definição dos objetivos (Goals)</a></li>
            <li><a href="#Definição-dos-operadores">Definição dos operadores (Operators)</a></li>
            <li><a href="#Definição-dos-Métodos">Definição dos Métodos</a></li>
            <li><a href="#Definição-das-Regras-de-Seleção">Definição das Regras de Seleção</a></li>
            <li><a href="#Execução-do-GOMS">Execução do GOMS</a></li>
        </ul>
    </li>
    <li><a href="#Conclusão">Conclusão</a></li>
    <li><a href="#Bibliografia">Bibliografia</a></li>
    <li><a href="#Histórico-de-versão">Histórico de versão</a></li>
</ul>

## Introdução
A declaração de bolsista no SIGAA UNB é um recurso fundamental para estudantes que recebem bolsas de estudo na Universidade de Brasília. Essa funcionalidade proporciona aos bolsistas uma maneira eficiente de acessar e gerenciar informações essenciais relacionadas à sua bolsa. Este documento tem como objetivo realizar uma análise detalhada dessa ferramenta, destacando seus principais recursos e funcionalidades, além de identificar possíveis melhorias para aprimorar a experiência dos usuários.
Introdução - Solicitaç

## Objetivos
A funcionalidade de declaração de bolsista no SIGAA UNB visa atender a uma série de objetivos para melhorar a eficiência e transparência do processo de gestão de bolsas. Alguns dos principais objetivos incluem:

-Facilitar o acesso dos bolsistas a informações detalhadas sobre suas bolsas de estudo, incluindo termos, condições e status atual.

-Permitir que os bolsistas assinem declarações referentes ao não acúmulo de bolsas ou visualizem declarações já assinadas de forma rápida e conveniente.

-Garantir que o processo de declaração de bolsista seja transparente e eficaz, proporcionando uma comunicação clara entre os bolsistas e a instituição.

# Análise Hierárquica de Tarefas para o SIGAA

A análise hierárquica de tarefas (HTA) é uma técnica utilizada para desmembrar as atividades dos usuários em tarefas menores. Este processo facilita a compreensão dos objetivos do usuário, organiza os subobjetivos e operações necessárias, e determina a sequência mais eficiente para sua realização. Abaixo, detalhamos o contexto, o diagrama e a tabela que ilustram esse processo para a funcionalidade de Declaração de Bolsista no SIGAA.

## Análise Contextual

O módulo de Declaração de Bolsista no SIGAA permite aos usuários gerenciar declarações relativas a bolsas, incluindo a assinatura de documentos que confirmam o não acúmulo de bolsas e a visualização de declarações previamente assinadas. Este módulo é essencial para garantir a transparência e conformidade com as normativas acadêmicas.

## Análise Hierárquica de Tarefas para Declaração de Bolsista

O objetivo principal dessa análise é descrever as tarefas associadas ao acesso e interação com as declarações de bolsista. As seguintes tarefas foram identificadas:

1. **Acessar o módulo de Declaração de Bolsista**
   - A partir da interface principal do SIGAA, o usuário deve localizar e acessar a opção específica para declarações de bolsista.

2. **Assinar Declaração de Não Acúmulo de Bolsas**
   - 2.1 Navegar até a seção de assinatura de declarações.
   - 2.2 Ler e entender os termos da declaração.
   - 2.3 Assinar eletronicamente a declaração.
   - 2.4 Submeter a declaração assinada.

3. **Visualizar Declarações Assinadas**
   - 3.1 Navegar até a seção de declarações assinadas.
   - 3.2 Selecionar uma declaração específica para visualização.
   - 3.3 Revisar a declaração.

### Tabela HTA para Declaração de Bolsista

## Tabela HTA para Declaração de Bolsista
Nessa tarefa, o usuário tem como objetivo acessar as declarações de bolsista, onde pode assinar ou visualizar declarações relativas ao não acúmulo de bolsas.
![declaração de bolsa](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/140026699/d897fc92-af4b-4b19-8252-fade79edf978)

| Objetivos / Operações                                     | Relações | Problemas e Recomendações                                     |
|-----------------------------------------------------------|----------|--------------------------------------------------------------|
| 0. Solicitar bolsas                                       | 1 > 1.1, 1.2, 1.3 |                                                              |
| 1. Selecionar a opção "Solicitação de Bolsa Auxílio"      | 1.1 > 1.1.1       |                                                              |
| 1.1 Ler as condições do Edital                            | 1.1.1 > 1.1.1.1   | Input: Leitura do edital.                                    |
| 1.1.1 Escolher opção de bolsa                             | 1.1.1.1           | Input: Selecionar tipo específico de bolsa.                  |
| 1.1.1.1 Preencher os campos requeridos no formulário      | 1.1.1.1.1         | Input: Preenchimento de informações necessárias.             |
| 1.1.1.1.1 Justificar e anexar documentos                  |                   | Input: Justificativa para a solicitação e anexação de documentos comprobatórios. |
| 1.1.1.1.1.1 Continuar com a solicitação                  |                   | Feedback: Submissão final da solicitação de bolsa.           |
| 1.2 Acompanhar Solicitação de Bolsas Auxílios             | 1.2.1             | Input: Acompanhamento do status da solicitação.              |
| 1.2.1 Conferir status da solicitação                      |                   | Feedback: Visualização do status atual da solicitação.       |
| 1.3 Clicar em Renovar Bolsa Auxílio                       | 1.3.1             | Input: Seleção da opção de renovação da bolsa.               |
| 1.3.1 Conferir cadastro e preencher o questionário        | 1.3.1.1           | Input: Verificação dos dados cadastrais e preenchimento de questionário adicional. |
| 1.3.1.1 Anexar documentos necessários e confirmar a submissão |               | Feedback: Anexação de documentos adicionais e confirmação da submissão da renovação. |

# GOMS

## Introdução
O método GOMS é uma abordagem de análise de tarefas que ajuda a descrever como os usuários interagem com um sistema para alcançar seus objetivos. Esta análise se concentra especificamente nas tarefas relacionadas à declaração de bolsistas no sistema SIGAA, cobrindo as operações de "Assinar Declaração" e "Visualizar Assinaturas".

## Objetivo da Análise
Identificar e descrever as etapas que os usuários seguem para realizar a assinatura e visualização de declarações de bolsistas no SIGAA. Isso ajuda a otimizar a interface do usuário para essas tarefas, melhorando a eficiência e a satisfação do usuário.

## Tarefas Analisadas

# GOMS para Declaração de Bolsista

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

### Assinar Declaração
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

### 2. Visualizar Assinaturas
- **Goal**: Acessar e revisar as assinaturas de declarações realizadas anteriormente.
- **Operators**:
  - Navegar até a seção "Declaração de Bolsistas"
  - Selecionar "Visualizar Assinaturas"
  - Visualizar os documentos assinados
- **Methods**:
  - Usar a interface do sistema para localizar e revisar documentos específicos.
- **Selection Rules**:
  - Se o usuário busca uma declaração específica, usar filtros para facilitar a busca.

## Execução GOMS

Nessa tarefa, o usuário possui o objetivo de acessar a funcionalidade de declaração de bolsista no sistema.
```
         - GOAL 0: Acessar a funcionalidade de declaração de bolsista.
           - METHOD 0.A: Navegar até a seção "Bolsas".
             - OP. 0.A.1: Clicar na aba "Bolsas".
           - METHOD 0.B: Selecionar a opção "Declaração de Bolsista".
             - OP. 0.B.1: Clicar na opção "Declaração de Bolsista".
             - (SEL. RULE: o usuário deseja realizar ou revisar uma declaração.)
```
         
Nessa tarefa, o usuário possui o objetivo de assinar digitalmente a declaração que atesta o não acúmulo indevido de bolsas.
         - GOAL 1: Assinar a declaração de não acúmulo de bolsas.
           - METHOD 1.A: Ler as instruções na tela.
             - OP. 1.A.1: Ler informações apresentadas na tela.
           - METHOD 1.B: Inserir dados pessoais e senha.
             - OP. 1.B.1: Inserir informações nos campos apropriados.
           - METHOD 1.C: Submeter a declaração.
             - OP. 1.C.1: Clicar em "Confirmar".
             - (SEL. RULE: o usuário confirma que as informações estão corretas.)


Nessa tarefa, o usuário possui o objetivo de revisar declarações de bolsista anteriormente submetidas.
         - GOAL 2: Visualizar assinaturas anteriores.
           - METHOD 2.A: Selecionar "Visualizar Assinaturas".
             - OP. 2.A.1: Clicar na opção "Visualizar Assinaturas".
             - (SEL. RULE: o usuário deseja verificar declarações previamente submetidas.)

## Conclusão

Esta análise GOMS revela áreas chave onde melhorias podem ser feitas para tornar a experiência do usuário mais eficiente e agradável. Otimizar os formulários e a navegabilidade pode reduzir erros e aumentar a satisfação dos usuários ao interagir com o sistema SIGAA.

## Bibliografia

- BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versão

| Versão | Data     | Descrição                           | Autor(es)              | Revisor(es)         |
| ------ | -------- | ----------------------------------- | ---------------------- | ------------------- |
| 1.0    | 14/10/23 | Criação do documento | Bruno Araújo | -    |
