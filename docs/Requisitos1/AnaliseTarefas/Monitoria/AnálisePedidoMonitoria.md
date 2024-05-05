# Análise de Tarefas: Pedido de Monitoria na visão do estudante

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
Por meio da análise de tarefas, este documento apresenta a análise detalhada da funcionalidade de **pedido de monitoria**, uma parte essencial do sistema que visa facilitar o processo de solicitação de supervisão acadêmica por parte dos alunos. Sendo assim, através da decomposição das tarefas envolvidas nesse processo, utilizando-se o método de análise hierárquica e do GOMS (Goals, Operators, Methods, e Selection Rules), será buscado compreender e avaliar as interações dos usuários com a interface e identificar as áreas necessárias para que o pedido sejá solicitado no SIGAA.

## Objetivos
O objetivo de **pedido de monitoria** é oferecer aos estudantes uma maneira conveniente e eficiente de expressar seu interesse em oferecer apoio acadêmico adicional em disciplinas específicas com determinado docente.

## Análise Hierárquica de Tarefas
A análise de tarefas é um processo de decomposição das atividades dos usuários em partes menores, chamadas de tarefas, em um sistema ou interface. Com isso, as tarefas complexas são divididas em objetivos, subobjetivos e operações, e um plano é estabelecido para definir a ordem em que esses subobjetivos devem ser alcançados.

Abaixo, serão apresentados a análise contextual, o diagrame e a tabela desse processo.

### Análise Contextual
Como há um conjunto de tarefas a serem realizadas, há baixo há a análise contextual e hierárquica
utilizada.

### Análise Contextual
Como há um conjunto de tarefas a serem realizadas, há baixo há a análise contextual e hierárquica utilizada.

<details>
  <summary size="20"><b> Análise Contextual </b></summary> 

    0. Realizar Pedido de Monitoria (1>2)
      1. Selecionar Disciplina (1>2)
        1.1 Identificar Instituto ou Departamento (1+2) 
          1.1.1 Identificar Nível de Ensino
          1.1.2 Identificar Unidade 
       1.2 Localizar a Disciplina (Somente disciplinas cursadas e aprovadas) 
    
     2. Especificar Detalhes do Pedido (1>2)
    	 2.1 Escolher Professor 
    	 2.2 Selecionar Turma (Caso o professor lecione para diversas turmas da disciplina) 
    	 2.3 Adicionar Informações Adicionais (Horários preferenciais de atendimento, tópicos que possui mais facilidade, entre outros) 
    
     3. Inserir Dados Pessoais (1+2) 
    	 3.1 Preencher Nome e Fornecer Contato (E-mail mais utilizado e telefone) 
    	 3.2 Inserir Matrícula (Vai indicar o histórico no sistema)
    
     4. Adicionar Mensagem de Pedido (1+2)
    	 4.1 Escrever Motivação para Solicitar Monitoria 
    	 4.2 Descrever expectativas, necessidades e restrições 
    
     5. Revisar Pedido (1+2)
    	 5.1 Verificar Detalhes do Pedido 
    	 5.2 Confirmar Precisão dos Dados Pessoais 
    	 5.3 Revisar e Editar Mensagem de Pedido 
     6. Enviar Pedido de Monitoria 

</details>

Após enviar o pedido, ele fica em modo de análise até que seja aprovado tanto pelo docente quando pela coordenação.

### Diagrama de Atividades

O capítulo 6, Organização do espaço problema, do livro IHC (1), de Barbosa e Silva, indica a seguinte notação para ser utilizada no diagrama, de acordo com a imagem 1.

Desse modo, tendo isso e a análise contextual como base, a imagem 2 mostra o diagrama da análise hierárquica de tarefas.

### Tabela de Análise
A tabela 1 mostra a tabela da análise hierárquica de tarefas sobre a funcionalidade de pedido de monitoria.

<details>
  <summary size="20"><b> Tabela de Análise </b></summary> 

**Tabela 1**: Análise Hierárquica de pedido de monitoria
| Objetivos/Operações                              | Relações      | Problemas e Recomendações                                                                                              |
|--------------------------------------------------|---------------|-----------------------------------------------------------------------------------------------------------------------|
| 0. Realizar Pedido de Monitoria                  | 1 > 2         | **Input**: Necessidade de monitoria em uma disciplina específica.<br>**Feedback**: Professor recebe pedido de monitoria para ser analisado.<br>**Plano**: Realizar a seleção da disciplina desejada.<br>**Recomendação**: Prosseguir para especificar os detalhes do pedido. |
| 1. Selecionar Disciplina                        | 1 > 2         | **Input**: Escolha da disciplina desejada.<br>**Feedback**: Lista de disciplinas disponíveis de acordo com os critérios selecionados.<br>**Plano:** Selecionar a disciplina desejada.<br>**Recomendação**: Identificar instituto ou departamento relevante. |
| 1.1 Identificar Instituto ou Departamento        | 1 + 2         | **Plano**: Pesquisar institutos e departamentos.<br>**Recomendação**: Selecionar o instituto ou departamento relevante.            |
| 1.1.1 Identificar Nível de Ensino                |         | **Plano**: Identificar o nível de ensino da disciplina selecionada.<br>**Recomendação**: Escolher o nível de ensino adequado.       |
| 1.1.2 Identificar Unidade                        |         | **Plano:** Identificar a unidade acadêmica responsável pela disciplina selecionada.<br>**Recomendação**: Escolher a unidade adequada. |
| 1.2 Localizar a Disciplina (Somente disciplinas cursadas e aprovadas) |  | **Plano**: Localizar a disciplina dentro da estrutura de disciplinas aprovadas.<br>**Recomendação**: Selecionar a disciplina corretamente. |
| 2. Especificar Detalhes do Pedido                | 1 > 2         | **Input**: Preferências de horários de atendimento e tópicos específicos de dificuldade.<br>**Plano**: Especificar os detalhes do pedido.<br>**Recomendação**: Escolher professor e turma adequados. |
| 2.1 Escolher Professor                           |        | **Plano**: Selecionar o professor desejado para a monitoria.<br>**Recomendação**: Escolher um professor com disponibilidade adequada. |
| 2.2 Selecionar Turma (Caso o professor lecione para diversas turmas da disciplina) |  | **Plano**: Escolher a turma desejada para a monitoria.<br>**Recomendação**: Escolher uma turma compatível com a disponibilidade. |
| 2.3 Adicionar Informações Adicionais             |         | **Plano**: Inserir informações adicionais relevantes para o pedido de monitoria.<br>**Recomendação**: Inserir informações relevantes e claras. |
| 3. Inserir Dados Pessoais                        | 1 + 2         | **Input**: Nome, e-mail principal e telefone para contato.<br>**Feedback**: Confirmação dos dados pessoais.<br>**Plano**: Inserir os dados pessoais necessários.<br>**Recomendação**: Revisar os dados inseridos. |
| 3.1 Preencher Nome e Fornecer Contato            |        | **Plano**: Preencher o nome e fornecer informações de contato.<br>**Recomendação**: Fornecer informações corretas e atualizadas. |
| 3.2 Inserir Matrícula                            |          | **Plano**: Inserir a matrícula do aluno.<br>**Recomendação**: Verificar a matrícula para garantir a precisão dos dados. |
| 4. Adicionar Mensagem de Pedido                  | 1 + 2         | **Input**: Necessidades de informações relevantes que orientam a autorização do pedido.<br>**Plano**: Escrever uma mensagem de pedido contendo motivação, expectativas e restrições.<br>**Recomendação**: Elaborar uma mensagem clara e concisa. |
| 4.1 Escrever Motivação para Solicitar Monitoria  |          | **Plano**: Escrever a motivação para solicitar a monitoria.<br>**Recomendação**: Expressar claramente as razões para a solicitação. |
| 4.2 Descrever expectativas, necessidades e restrições |  | **Plano**: Descrever as expectativas, necessidades e restrições para a monitoria.<br>**Recomendação**: Detalhar as expectativas de forma precisa. |
| 5. Revisar Pedido                               | 1 + 2         | **Input**: Necessidade de conferir, pois os dados não poderão ser alterados depois. <br>**Plano**: Revisar todos os detalhes do pedido antes de enviar.<br>**Recomendação**: Verificar cuidadosamente todas as informações inseridas. |
| 5.1 Verificar Detalhes do Pedido                 |         | **Plano**: Verificar se todos os detalhes do pedido estão corretos.<br>**Recomendação**: Revisar cada detalhe minuciosamente. |
| 5.2 Confirmar Precisão dos Dados Pessoais        |          | **Plano**: Confirmar se os dados pessoais inseridos estão corretos.<br>**Recomendação**: Verificar a precisão dos dados pessoais. |
| 5.3 Revisar e Editar Mensagem de Pedido          |          | **Plano**: Revisar e editar a mensagem de pedido conforme necessário.<br>**Recomendação**: Garantir que a mensagem esteja clara e completa. |
| 6. Enviar Pedido de Monitoria                    |               |**Input**: Enviar o pedido para avaliação. <br>**Plano**: Enviar o pedido de monitoria para avaliação.<br>Recomendação: Enviar o pedido somente após revisão completa. |

</details>

## GOMS
O GOMS é um método de análise de tarefas que descreve as atividades dos usuários em termos de objetivos (o que o usuário deseja alcançar), operadores (as ações realizadas, como clicar em um botão), métodos (sequências de ações para alcançar um objetivo) e regras de seleção (critérios para escolher entre métodos alternativos). Essa abordagem em relação à funcionalidade de **pedido de monitoria** será mostrada a seguir.

### Definição dos objetivos

1. **Selecionar Disciplina**: O usuário pretende escolher a disciplina para a qual deseja solicitar monitoria.
2. **Especificar Detalhes do Pedido**: O usuário precisa fornecer informações específicas sobre o
pedido de monitoria, como indicar o professor, selecionar a turma e adicionar detalhes adicionais, como horários preferenciais.
3. **Inserir Dados Pessois**: O usuário precisa se identificar e mostrar os seus dados pessoais e de contato, como telefone.
4.  **Adicionar Mensagem de Pedido**: O usuário precisa indicar motivações e restrições.
5.  **Revisar Pedido**: Necessidade de conferir se dados estão corretos, pois não poderão ser alterados.
6. **Enviar Pedido de Monitoria**: O objetivo final é concluir o processo de solicitação de monitoria enviando o pedido com todas as informações necessárias.

### Definição dos operadores(Operators)
- **Selecione**: Usado para escolher opções, como disciplina, campus, departamento, professor e turma.
- **Localize**: Utilizado para encontrar informações específicas, como disciplina e departamento.
- **Especifique**: Para fornecer detalhes adicionais, como horários preferenciais e informações de contato.
- **Inserir/Preencher/Fornecer**: Ações para adicionar dados pessoais, como nome, matrícula e contato.
- **Adicionar/Escrever/Descrever**: Para incluir mensagens de pedido, como motivação para solicitar monitoria e expectativas.
  
### Definição dos Métodos
- **Identificar Faculdade ou Instituto e Localizar o Departamento**: Subtarefas para selecionar o campus e encontrar o departamento correspondente.
- **Localizar a Disciplina**: Subtarefa para encontrar a disciplina desejada, considerando apenas as disciplinas cursadas e aprovadas.
- **Adicionar Mensagem de Pedido**: Subtarefas para escrever a motivação, solicitar monitoria e descrever expectativas e necessidades.
- **Revisar Pedido**: Subtarefas para verificar detalhes do pedido, confirmar precisão dos dados pessoais e revisar/editar a mensagem de pedido.

### Definição das Regras de Seleção

1. **Verificar Elegibilidade do Estudante**: Antes de permitir o pedido de monitoria, o sistema deve verificar se o estudante já cursou e obteve uma menção mínima de MS ou SS na disciplina para a qual deseja ser monitor. Isso garante que apenas alunos qualificados possam se candidatar à monitoria.
2. **Avaliar Carga Horária do Estudante**: O sistema deve verificar se o estudante não está com a grade horária completa, com um limite máximo de 24 créditos, para garantir que ele tenha disponibilidade de tempo para cumprir as responsabilidades de monitoria, sem comprometer o desempenho acadêmico em outras disciplinas.
3. **Limitar Pedidos Simultâneos de Monitoria**: Para evitar sobrecarga de responsabilidades, o sistema deve permitir que o estudante faça apenas um pedido de monitoria por vez, impedindo que ele solicite monitoria para múltiplas disciplinas simultaneamente.

4. ### Execução do GOMS

### Execução do GOMS

Abaixo, há a execução do método GOMS

<details>
  <summary size="20"><b> GOMS </b></summary> 

      
      GOAL 0: Realizar Pedido de Monitoria
      
      GOAL 1: Selecionar Disciplina
      - METHOD 1.A: Escolher Campus
        - METHOD 1.A.A: Identificar Faculdade ou Instituto
          - OPERATOR 1.A.A.1: Selecionar o campus desejado.
        - METHOD 1.A.B: Localizar o Departamento
          - OPERATOR 1.A.B.1: Localizar e selecionar o departamento correspondente ao campus escolhido.
      - METHOD 1.B: Localizar a Disciplina
        - OPERATOR 1.B.1: Navegar pelas disciplinas disponíveis.
        - SELECTION RULE 1.B.1: Selecionar apenas disciplinas cursadas e aprovadas, com menção mínima de MS ou SS.
      
      GOAL 2: Especificar Detalhes do Pedido
      - METHOD 2.A: Indicar Professor
        - OPERATOR 2.A.1: Selecionar o professor desejado, se aplicável.
      - METHOD 2.B: Selecionar Turma
        - OPERATOR 2.B.1: Escolher a turma desejada, se necessário.
      - METHOD 2.C: Adicionar Informações Adicionais
        - OPERATOR 2.C.1: Inserir detalhes adicionais, como horários preferenciais e tópicos específicos.
      
      GOAL 3: Inserir Dados Pessoais
      - METHOD 3.A: Preencher Nome
        - OPERATOR 3.A.1: Digitar o nome do estudante.
      - METHOD 3.B: Inserir Matrícula
        - OPERATOR 3.B.1: Digitar o número de matrícula do estudante.
      - METHOD 3.C: Fornecer Contato
        - OPERATOR 3.C.1: Inserir e-mail ou número de telefone do estudante.
      
      GOAL 4: Adicionar Mensagem de Pedido
      - METHOD 4.A: Escrever Motivação para Solicitar Monitoria
        - OPERATOR 4.A.1: Escrever a motivação para solicitar monitoria.
      - METHOD 4.B: Descrever Expectativas e Necessidades
        - OPERATOR 4.B.1: Descrever as expectativas e necessidades relacionadas à monitoria.
      
      GOAL 5: Revisar Pedido
      - METHOD 5.A: Verificar Detalhes do Pedido
        - OPERATOR 5.A.1: Revisar todos os detalhes do pedido.
      - METHOD 5.B: Confirmar Precisão dos Dados Pessoais
        - OPERATOR 5.B.1: Verificar a precisão dos dados pessoais inseridos.
      - METHOD 5.C: Revisar e Editar Mensagem de Pedido
        - OPERATOR 5.C.1: Revisar e editar a mensagem de pedido conforme necessário.
      
      GOAL 6: Enviar Pedido de Monitoria
      - METHOD 6.A: Enviar Pedido de Monitoria
        - OPERATOR 6.A.1: Clicar no botão de enviar para concluir o pedido de monitoria.
      
</details>

## Conclusão
Como é possível observar, a análise hierárquica e a aplicação do método GOMS para a funcionalidade de pedido de monitoria revelaram uma estrutura complexa de tarefas e interações dentro do processo. Assim, ao desmembrar cada etapa em objetivos, passo a passo, métodos e regras, foi possível compreender detalhadamente as ações dos usuários e identificar áreas de relevância.

## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise hierárquica| Larissa Stéfane | - | 30/04/2024 |
| 1.1 | Execução do GOMS | Larissa Stéfane | - | 01/04/2024 |
