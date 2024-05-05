# Análise de Tarefas: Analisar monitor na visão do estudante

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

Como foi falado no documento de planejamento das análises de monitoria, a ferramenta de avaliação oferecerá aos alunos a possibilidade de avaliar o desempenho dos monitores. Com base nisso, este documento pretende realizar uma análise detalhada das tarefas envolvidas na funcionalidade de avaliação de monitores por meio dos métodos de análise hierárquica de tarefas e GOMS (Goals, Operators, Methods, Selection Rules).

## Objetivos

Essa funcionalidade tem como objetivo principal fornecer aos estudantes a oportunidade de expressar suas opiniões e avaliações sobre o desempenho dos monitores que os auxiliam em disciplinas acadêmicas. Com isso, essa avaliação é crucial para garantir a qualidade do suporte oferecido pelos monitores e para contribuir para o aprimoramento dos programas de monitoria.

## Análise Hierárquica de Tarefas

A análise de tarefas envolve a decomposição das ações dos usuários em partes menores, chamadas de tarefas, em um sistema ou interface. Essa estratégia busca simplificar atividades complexas, fragmentando-as em metas, submetas e ações operacionais, e criando um roteiro para determinar a ordem correta de execução dessas submetas.

### Análise Contextual
Como há um conjunto de tarefas a serem realizadas, há baixo, no algoritmo 1, há a análise contextual e hierárquica utilizada.

<details>
  <summary size="20"><b>  Algoritmo 1:Análise Contextual </b></summary> 

      0. Avaliar Monitor (1>2)
          1. Selecionar Monitor a ser Avaliado (1>2)
              1.1 Identificar Disciplina Monitorada (1>2)
                  1.1.1 Verificar o Departamento Correspondente
                  1.1.2 Escolher Disciplina do Monitor
              1.2 Localizar o Monitor (1>2)
                  1.2.1 Acessar Lista de Monitores Disponíveis
                  1.2.2 Identificar o Monitor a ser Avaliado
          2. Preencher Formulário de Avaliação (1+2)
              2.1 Classificar Desempenho do Monitor (1+2)
                  2.1.1 Atribuir Notas para Diversos Critérios (Pontualidade, Conhecimento, Didática)
                  2.1.2 Registrar Comentários e Observações
              2.2 Indicar Satisfação com a Monitoria (1>2)
                  2.2.1 Selecionar Opções de Satisfação (Satisfeito, Insatisfeito, Neutro)
                  2.2.2 Justificar a Avaliação de Satisfação
          3. Enviar Formulário de Avaliação (1+2)
              3.1 Revisar Avaliação Preenchida (1+2)
                  3.1.1 Verificar Precisão das Respostas
                  3.1.2 Editar Avaliação, se Necessário
              3.2 Confirmar Envio da Avaliação
      
**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>

### Diagrama de Atividades

Para facilitar a visualização de tarefas, a figura 1 mostra o diagrama:

 <div align="center">
    Figura 1: Diagrama HTA da avaliação de monitores
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/AnaliseAvaliarMonitor.drawio.png">
    <br>
     Fonte: Larissa Stéfane
    <br>
</div>


Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA Avaliação de monitores](https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/AnaliseAvaliarMonitor.drawio.png)



### Tabela de Análise
A tabela 1 mostra a tabela da análise hierárquica de tarefas sobre a funcionalidade de pedido de monitoria.

<details>
  <summary size="20"><b> Tabela de Análise </b></summary> 

**Tabela 1**: Análise Hierárquica de avaliação de monitores


| Objetivos/Operações                                 | Relações | Problemas e Recomendações                                                                                                                                                                                                                                                                         |
|-----------------------------------------------------|----------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0. Avaliar Monitor                                  |     1>2      | **Input**: O usuário precisa avaliar o desempenho de um monitor em uma disciplina específica. <br> **Feedback**: O sistema deve fornecer uma interface intuitiva para o usuário realizar a avaliação. <br> **Plano**: O usuário seleciona a disciplina e o monitor a ser avaliado. <br> **Recomendação**: Garantir que a interface seja de fácil uso e compreensão.                     |
| 1. Selecionar Monitor a ser Avaliado               | 1>2      | **Input**: O usuário deve selecionar a disciplina e o monitor que deseja avaliar. <br> **Feedback**: Após a seleção, o sistema deve apresentar o formulário de avaliação correspondente. <br> **Plano**: O usuário navega pela lista de disciplinas e monitores disponíveis e faz sua seleção. <br> **Recomendação**: Facilitar a identificação e seleção dos monitores disponíveis.             |
| 1.1 Identificar Disciplina Monitorada              | 1>2      | **Input**: O sistema precisa saber qual disciplina está sendo monitorada para permitir a avaliação correta. <br> **Feedback**: Quando a disciplina é identificada, o sistema exibe uma lista de monitores relacionados. <br> **Plano**: O usuário escolhe a disciplina entre as opções fornecidas. <br> **Recomendação**: Garantir que todas as disciplinas disponíveis estejam atualizadas no sistema. |
| 1.1.1 Verificar o Departamento Correspondente      |      | **Plano**: O sistema verifica automaticamente o departamento associado à disciplina selecionada. <br> **Recomendação**: Manter uma associação precisa entre disciplinas e departamentos para evitar erros.            |
| 1.1.2 Escolher Disciplina do Monitor               |     |  **Plano**: O usuário navega pelas opções de disciplinas disponíveis e seleciona a desejada. <br> **Recomendação**: Facilitar a identificação das disciplinas, organizando-as de forma clara e intuitiva.             |
| 1.2 Localizar o Monitor                             | 1>2      | **Input**: O usuário precisa encontrar o monitor específico que deseja avaliar. <br> **Feedback**: Após a seleção do monitor, o sistema carrega seu perfil de avaliação. <br> **Plano**: O usuário pesquisa ou navega pela lista de monitores disponíveis. <br> **Recomendação**: Implementar uma funcionalidade de busca para facilitar a localização do monitor desejado.                             |
| 2. Preencher Formulário de Avaliação               | 1+2      | **Input**: O usuário deve preencher o formulário de avaliação com notas e comentários sobre o desempenho do monitor. <br> **Feedback**: Após preencher o formulário, o usuário deve receber uma confirmação de envio. <br> **Plano**: O sistema apresenta um formulário online com campos para avaliar diversos aspectos do monitor. <br> **Recomendação**: Garantir que o formulário seja intuitivo e fácil de preencher.                                                                                                                                                  |
| 2.1 Classificar Desempenho do Monitor               | 1+2      | **Input**: O usuário deve atribuir notas e comentários ao desempenho do monitor em vários aspectos. <br> **Feedback**: Após preencher as classificações, o sistema confirma o recebimento dos dados. <br> **Plano**: O usuário preenche as notas e os comentários conforme sua avaliação. <br> **Recomendação**: Fornecer exemplos de critérios de avaliação para orientar o usuário.                                                                                                                                                                         |
| 2.1.1 Atribuir Notas para Diversos Critérios        |    | **Plano**: O usuário atribui notas aos critérios de acordo com sua avaliação. <br> **Recomendação**: Disponibilizar uma escala de notas clara e compreensível para facilitar a classificação do usuário.                                                                       |
| 2.1.2 Registrar Comentários e Observações           |      | **Plano**: O usuário escreve os comentários e observações relevantes para sua avaliação. <br> **Recomendação**: Permitir um campo de texto expansível para acomodar comentários mais detalhados.                                                                            |
| 2.2 Indicar Satisfação com a Monitoria             | 1>2      | **Input**: O usuário precisa expressar sua satisfação geral com a monitoria. <br> **Feedback**: Após a seleção da satisfação, o sistema registra a avaliação final. <br> **Plano**: O usuário escolhe entre as opções de satisfação fornecidas. <br> **Recomendação**: Incluir uma seção opcional para comentários adicionais caso o usuário deseje explicar sua avaliação de satisfação.                                                                              |
| 2.2.1 Selecionar Opções de Satisfação              |   |**Plano**: O usuário escolhe entre as opções de satisfação fornecidas, como "Satisfeito", "Insatisfeito" ou "Neutro". <br> **Recomendação**: Oferecer opções claras e distintas para facilitar a escolha do usuário.                                                                                         |
| 2.2.2 Justificar a Avaliação de Satisfação         |      | **Plano**: O usuário escreve uma justificativa caso deseje explicar sua escolha de satisfação. <br> **Recomendação**: Disponibilizar um campo de texto para inserção de justificativas detalhadas.                                            |
| 3. Enviar Formulário de Avaliação                   | 1+2      | **Input**: O usuário deve revisar todas as respostas fornecidas antes de enviar a avaliação. <br> **Feedback**: Quando a revisão é concluída, o sistema permite a edição ou confirmação do formulário preenchido. <br> **Plano**: O usuário verifica todas as respostas e, se necessário, faz alterações. <br> **Recomendação**: Fornecer uma opção clara para editar as respostas revisadas antes do envio final.                                                                                                                                                                                                                     |
| 3.1 Revisar Avaliação Preenchida                    | 1+2      | **Input**: O usuário deve revisar todas as respostas fornecidas antes de enviar a avaliação. <br> **Feedback**: Quando a revisão é concluída, o sistema permite a edição ou confirmação do formulário preenchido. <br> **Plano**: O usuário verifica todas as respostas e, se necessário, faz alterações. <br> **Recomendação**: Fornecer uma opção clara para editar as respostas revisadas antes do envio final.                                                                                              |
| 3.1.1 Verificar Precisão das Respostas             |     |  **Plano**: O usuário revisa todas as respostas e verifica sua precisão. <br> **Recomendação**: Destacar visualmente quaisquer campos que necessitem de correção ou revisão para facilitar a identificação pelo usuário.                                                                                                     |
| 3.1.2 Editar Avaliação, se Necessário              |      | **Plano**: O usuário edita as respostas conforme necessário antes de enviar a avaliação. <br> **Recomendação**: Permitir edições simples e rápidas para corrigir quaisquer erros identificados pelo usuário.                                                                                         |
| 3.2 Confirmar Envio da Avaliação                   |      |  **Plano**: O usuário clica em um botão de confirmação após revisar e editar a avaliação, se necessário. <br> **Recomendação**: Destacar visualmente o botão de confirmação para facilitar sua identificação e uso pelo usuário. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>

## GOMS

O GOMS é uma técnica que analisa as atividades dos usuários, descrevendo seus objetivos (o que desejam alcançar), os operadores utilizados (ações como clicar em um botão), os métodos empregados (sequências de ações para atingir objetivos específicos) e as regras de seleção (critérios para escolher entre diferentes métodos). Esta metodologia será empregada na análise da funcionalidade de avaliação de monitores.

### Definição dos objetivos

1. **Avaliar Monitor**: Este é o objetivo principal da funcionalidade, que envolve todo o processo de avaliação do desempenho de um monitor.
2. **Selecionar Monitor a ser Avaliado**: O usuário precisa escolher qual monitor deseja avaliar entre os disponíveis.
3. **Identificar Disciplina Monitorada**: É necessário identificar a disciplina para a qual o monitor está prestando serviço para direcionar corretamente a avaliação.
4. **Localizar o Monitor**: Uma vez identificada a disciplina, o usuário precisa localizar o monitor específico que deseja avaliar.
5. **Preencher Formulário de Avaliação**: Depois de selecionar o monitor, o usuário deve preencher um formulário com suas avaliações e feedback.
6. **Classificar Desempenho do Monitor**: Neste ponto, o usuário avalia diversos aspectos do desempenho do monitor, como pontualidade, conhecimento e didática.
7. **Indicar Satisfação com a Monitoria**: Além de avaliar o desempenho, o usuário expressa sua satisfação geral com a monitoria.
8. **Enviar Formulário de Avaliação**: Após preencher o formulário, o usuário envia suas avaliações para registro.
9. **Revisar Avaliação Preenchida**: Antes de finalizar o processo, o usuário revisa todas as informações fornecidas para garantir precisão e completude.

### Definição dos operadores(Operators)

- **Escolher**: Selecionar uma opção específica entre várias disponíveis, como disciplina, critérios de avaliação ou opções de satisfação.
- **Acessar**: Entrar em uma seção específica da plataforma, como a lista de monitores disponíveis ou o formulário de avaliação.
- **Localizar**: Encontrar informações específicas dentro da plataforma, como o monitor a ser avaliado ou a disciplina monitorada.
- **Atribuir**: Dar notas ou classificações a critérios de desempenho do monitor, como pontualidade, conhecimento e didática.
- **Registrar**: Inserir informações relevantes, como comentários, observações ou justificativas.
- **Revisar**: Verificar a precisão das informações inseridas ou a consistência do formulário preenchido.
- **Certificar-se**: Confirmar que todas as informações estão corretas antes de prosseguir para a próxima etapa.
- **Enviar**: Submeter o formulário de avaliação preenchido para registro.
- **Aguardar**: Esperar por uma resposta ou confirmação após o envio do formulário de avaliação.
- **Salvar**: Arquivar ou armazenar uma cópia da avaliação preenchida para referência futura.
- **Retornar**: Voltar à página inicial ou à seção principal da plataforma após concluir o processo de avaliação.

### Definição dos Métodos

- **Identificar Disciplina Monitorada**: Escolher a disciplina específica que está sendo monitorada para realizar a avaliação.
- **Localizar o Monitor a Ser Avaliado**: Acessar a lista de monitores disponíveis e identificar o monitor específico que será avaliado.
- **Preencher Formulário de Avaliação**: Atribuir notas aos critérios de desempenho do monitor e registrar comentários ou observações relevantes.
- **Enviar Formulário de Avaliação**: Certificar-se de que todas as informações foram inseridas corretamente e submeter o formulário preenchido para registro.
- **Receber Confirmação de Envio**: Aguardar a confirmação de que a avaliação foi recebida com sucesso após o envio do formulário.
- **Finalizar Avaliação**: Arquivar a avaliação preenchida para referência futura e retornar à página inicial da plataforma.

### Definição das Regras de Seleção

- Os estudantes só podem avaliar monitores das disciplinas em que estão matriculados no semestre atual.
- Todos os campos obrigatórios do formulário de avaliação devem ser preenchidos corretamente para que o envio seja confirmado.
- O formulário de avaliação só pode ser enviado uma vez.
- O processo de avaliação só pode ser finalizado após o envio do formulário e a confirmação de recebimento.
- Após a conclusão da avaliação, o usuário deve ser redirecionado automaticamente para a página inicial.

### Execução do GOMS


Abaixo, no algoritmo 2, há a execução do método GOMS

<details>
  <summary size="20"><b> Algoritmo 2: GOMS </b></summary> 

**Algoritmo 2**: GOMS
         
         GOAL 1: Avaliar Monitor
         - METHOD 1.A: Selecionar Monitor a ser Avaliado
           - *OPERATOR 1.A.1*: Escolher qual monitor deseja avaliar entre os disponíveis.
           - *OPERATOR 1.A.2*: Identificar a disciplina monitorada pelo monitor selecionado.
             - SELECTION RULE 1.A.2: O usuário só pode avaliar monitores das disciplinas em que está matriculado no semestre atual.
         
          GOAL 2: Preencher Formulário de Avaliação
         - METHOD 2.A: Preencher Formulário de Avaliação
           - *OPERATOR 2.A.1*: Atribuir notas aos critérios de desempenho do monitor, como pontualidade, conhecimento e didática.
           - *OPERATOR 2.A.2*: Registrar comentários ou observações relevantes sobre o desempenho do monitor.
         
          GOAL 3: Enviar Formulário de Avaliação
         - METHOD 3.A: Enviar Formulário de Avaliação
           - *OPERATOR 3.A.1*: Certificar-se de que todas as informações foram inseridas corretamente no formulário.
           - *OPERATOR 3.A.2*: Submeter o formulário preenchido para registro.
         
          GOAL 4: Revisar Avaliação Preenchida
         - METHOD 4.A: Revisar Avaliação Preenchida
           - *OPERATOR 4.A.1*: Verificar a precisão e a completude das informações fornecidas no formulário.
           - *OPERATOR 4.A.2*: Editar a avaliação, se necessário, para corrigir possíveis erros ou omissões.
         
          GOAL 5: Classificar Desempenho do Monitor
         - METHOD 5.A: Classificar Desempenho do Monitor
           - *OPERATOR 5.A.1*: Atribuir notas para critérios como pontualidade, conhecimento e didática.
           - *OPERATOR 5.A.2*: Registrar observações ou comentários adicionais sobre o desempenho do monitor.
         
         GOAL 6: Indicar Satisfação com a Monitoria
         - METHOD 6.A: Indicar Satisfação com a Monitoria
           - *OPERATOR 6.A.1*: Selecionar opções de satisfação, como Satisfeito, Insatisfeito ou Neutro.
           - *OPERATOR 6.A.2*: Justificar a avaliação de satisfação, se necessário.
         
          GOAL 7: Identificar Disciplina Monitorada
         - METHOD 7.A: Identificar Disciplina Monitorada
           - *OPERATOR 7.A.1*: Verificar o departamento correspondente à disciplina monitorada.
           - *OPERATOR 7.A.2*: Escolher a disciplina específica do monitor para realizar a avaliação.
         
          GOAL 8: Localizar o Monitor
         - METHOD 8.A: Localizar o Monitor
           - *OPERATOR 8.A.1*: Acessar a lista de monitores disponíveis na plataforma.
           - *OPERATOR 8.A.2*: Identificar o monitor desejado na lista disponível.
         
          GOAL 9: Finalizar Avaliação e Retornar à Página Inicial
         - METHOD 9.A: Finalizar Avaliação
           - *OPERATOR 9.A.1*: Arquivar a avaliação preenchida para referência futura.
           - *OPERATOR 9.A.2*: Retornar à página inicial da plataforma.
             - SELECTION RULE 9.A.2: Garantir que o usuário seja redirecionado automaticamente para a página inicial após concluir o processo de avaliação.

  **Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>

## Conclusão

Ao analisar a função de avaliar monitores usando uma abordagem hierárquica e aplicando o método GOMS, percebe-se uma estrutura complexa de tarefas e interações. Esse método detalhado, ao decompor cada etapa em objetivos, procedimentos, métodos e regras, proporcionou uma compreensão aprofundada das atividades dos usuários, identificando áreas críticas.

## Bibliografia

1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). **Interação Humano-Computador e Experiência do Usuário**. Acesso em 30 de abril de 2024.
2. Carlos Mar, Msc. **Modelo GOMS – Análise de Tarefas**. Maio de 2014. Disponível em <https://carlosmardotcomdotbr.wordpress.com/wp-content/uploads/2014/04/modelotarefasgoms.pdf>. Acesso em 01 de maio de 2024.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise hierárquica| Larissa Stéfane | -| 02/04/2024 |
| 1.1 | Execução do GOMS | Larissa Stéfane | - | 03/05/2024 |
| 1.2 | Organização do documento e adição dos diagramas | Larissa Stéfane | - | 05/05/2024 |
