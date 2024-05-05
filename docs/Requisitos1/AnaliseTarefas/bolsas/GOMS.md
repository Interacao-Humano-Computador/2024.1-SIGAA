# Análise de tarefas: Solicitação de Bolsas Estudantil através do SIGAA

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
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
A técnica GOMS (Goals, Operators, Methods, Selection Rules) é uma abordagem de análise de tarefas que busca descrever as etapas que um usuário segue para realizar uma tarefa em um sistema. Esse método se baseia em um conjunto de regras que detalham como as metas do usuário são alcançadas através da seleção de operadores, métodos e regras de seleção. Essa abordagem é valiosa para avaliar a eficiência e usabilidade das interfaces de usuário e sistemas, e também auxilia na identificação de possíveis problemas e áreas de melhoria.

As tarefas são caracterizadas da seguinte forma:

- Objetivos: representam as metas que o usuário pretende alcançar ao utilizar o sistema.
- Operadores: são as ações cognitivas ou físicas que o sistema permite que o usuário execute, como inserir dados via teclado, selecionar opções em menus ou clicar em botões.
- Métodos: consistem em sequências estabelecidas de sub-objetivos e operadores que habilitam o usuário a atingir um objetivo maior.
- Regras de seleção: são utilizadas para determinar qual método aplicar em uma determinada situação.


## Objetivo da Análise
O objetivo desta análise é identificar as tarefas realizadas pelos usuários no módulo "Bolsas" do Sistema Integrado de Gestão de Atividades Acadêmicas (SIGAA), visando aprimorar essas interações para garantir que os usuários possam alcançar seus objetivos de maneira eficiente e eficaz. Isso inclui identificar possíveis melhorias na interface que possam ajudar os usuários a realizar suas tarefas com maior facilidade e menos erros, melhorando a experiência do usuário com o sistema (Barbosa e Silva, 2021).

## Motivo da Escolha
A escolha do SIGAA como objeto de estudo deve-se à sua ampla utilização por estudantes, servidores técnicos-administrativos e professores em diversas universidades, incluindo a Universidade de Brasília (UnB), que tem acordo com o sistema desde _____________. Como uma ferramenta essencial para a administração de atividades acadêmicas, entender e otimizar a interação dos usuários com o módulo "Bolsas" pode significativamente impactar a eficiência acadêmica e administrativa, oferecendo suporte melhorado para todos os envolvidos no processo educacional.

## Análise de Tarefas

Para a análise das tarefas, ao observar o site, foram identificados cinco campos principais em bolsas, como mostra a Figura 1.

## Análise GOMS para o Módulo "Bolsas" no SIGAA
O método GOMS (Goals, Operators, Methods, Selection Rules) é uma técnica poderosa de análise de tarefas que esquematiza as interações do usuário com um sistema em termos de metas, operadores, métodos e regras de seleção. Esta abordagem será aplicada à funcionalidade do módulo "Bolsas" do SIGAA, detalhando como os estudantes realizam atividades relacionadas à gestão de suas bolsas acadêmicas.

### Execução do GOMS

      GOAL 0: Ir até a opção Bolsas

      GOAL 1: Acessar a funcionalidade de consulta
        - OP 1: Navegar até a seção "Bolsas"
        - *OP 2: Selecionar "Cadastro Único"
        - *OP 3: Clicar em "aderir"
          - *METH 1: Utilizar a navegação pelo menu principal para acessar a página de consulta

      GOAL 2: Visualizar e analisar as adesões existentes
          - OP 1: Revisar a lista de adesões exibidas*
            - *METH 1: Navegar pelas entradas na lista para verificar detalhes específicos

      Bolsas - Cadastro Único - Declaração de Discente Prioritário

      GOAL 0: Emitir declaração de discente prioritário
        - *GOAL 1: Acessar a funcionalidade de emissão de declaração
          - OP 1: Navegar até a seção "Bolsas"
          - OP 2: Selecionar "Cadastro Único"
          - OP 3: Clicar em "Declaração de Discente Prioritário"
            - METH 1: Usar o menu para acessar a funcionalidade
      - GOAL 2: Emitir a declaração
          - OP 1: Preencher os campos necessários
          - OP 2: Submeter a declaração
            - *METH 1: Confirmar a submissão e esperar pela emissão da declaração
      
      Bolsas - Declaração de Bolsista
      
      GOAL 0: Assinar declaração de bolsista
        - GOAL 1: Assinar declaração
          - *OP 1: Navegar até "Bolsas"
          - *OP 2: Clicar em "Declaração de Bolsista"
          - *OP 3: Selecionar "Assinar Declaração"
            - *METH 1: Usar o menu para encontrar e acessar a opção de assinatura
      - GOAL 2: Assinar e submeter a declaração
          - OP 1: Ler a declaração
          - OP 2: Assinar eletronicamente
          - OP 3: Submeter a assinatura
            - METH 1: Verificar a autenticidade da assinatura antes de submeter
      
      Bolsas - Acompanhar Meus Registros de Interesse
      
      GOAL 0: Acompanhar registros de interesse em bolsas
        - GOAL 1: Acessar registros de interesse
          - OP 1: Navegar até "Bolsas"
          - OP 2: Clicar em "Acompanhar Meus Registros de Interesse"
            - METH 1: Utilizar a navegação pelo menu para acessar o registro de interesses
      - GOAL 2: Analisar e gerenciar os registros
          - OP 1: Avaliar o status atual dos interesses
          - OP 2: Fazer alterações se necessário
            - METH 1: Interagir com o sistema para atualizar ou modificar registros conforme necessário
      
      Bolsas - Minhas Bolsas na Instituição
      
      GOAL 0: Visualizar bolsas atuais na instituição
        - GOAL 1: Acessar a visão geral das bolsas
          - OP 1: Navegar até "Bolsas"
          - OP 2: Selecionar "Minhas Bolsas na Instituição"
            - *METH 1: Usar o menu para acessar a lista de bolsas atuais
      - GOAL 2: Revisar detalhes e condições das bolsas
          - OP 1: Analisar a lista e detalhes das bolsas recebidas
        -   METH 1: Utilizar opções de detalhamento para compreender termos e condições associadas
      
      Bolsas - Renovar Bolsa Auxílio
      
      GOAL 0: Renovar a bolsa auxílio
        - GOAL 1: Acessar a funcionalidade de renovação
          - *OP 1: Navegar até "Bolsas"
          - *OP 2: Selecionar "Renovar Bolsa Auxílio"
            - *METH 1: Usar o menu para chegar à página de renovação
      - GOAL 2: Preencher e submeter o formulário de renovação
          - OP 1: Inserir as informações requeridas para a renovação
          - OP 2: Revisar e confirmar os dados inseridos
          - OP 3: Clicar em "Submeter Renovação"
            - METH 1: Seguir os passos no formulário e confirmar para completar a renovação

## Conclusão
Como é possível observar, a análise hierárquica e a aplicação do método GOMS para a funcionalidade de pedido de monitoria revelaram uma estrutura complexa de tarefas e interações dentro do processo. Assim, ao desmembrar cada etapa em objetivos, passo a passo, métodos e regras, foi possível compreender detalhadamente as ações dos usuários e identificar áreas de relevância.

## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.


## Histórico de Versão
| Versão | Alteração                            | Responsável  | Revisor         | Data       |
| ------ | ------------------------------------ | ------------ | --------------- | ---------- |
| 1.0    |  Criação inicial do documento GOMS.  | Bruno Araújo | Breno Alexandre | 05/05/2024 |


