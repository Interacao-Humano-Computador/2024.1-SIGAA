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

    0. Realizar Pedido de Monitoria
      1. Selecionar Disciplina (1/2)
        1.1 Escolher Campus (1+2)
          1.1.1 Identificar Faculdade ou Instituto (1>2)
          1.1.2 Localizar o Departamento (1>2)
       1.2 Localizar a Disciplina (Somente disciplinas cursadas e aprovadas) (1>2)
    
     2. Especificar Detalhes do Pedido (1>2)
    	 2.1 Indicar Professor (Se aplicável) (1>2)
    	 2.2 Selecionar Turma (Se o professor tiver múltiplas turmas) (1>2)
    	 2.3 Adicionar Informações Adicionais (Como horários preferenciais, tópicos específicos para focar) (1>2)
    
     3. Inserir Dados Pessoais (1>2)
    	 3.1 Preencher Nome (1>2)
    	 3.2 Inserir Matrícula (1>2)
    	 3.3 Fornecer Contato (E-mail ou número de telefone) (1>2)
    
     4. Adicionar Mensagem de Pedido (1>2)
    	 4.1 Escrever Motivação para Solicitar Monitoria (1>2)
    	 4.2 Descrever Expectativas e Necessidades (1>2)
    
     5. Revisar Pedido (1>2)
    	 5.1 Verificar Detalhes do Pedido (1>2)
    	 5.2 Confirmar Precisão dos Dados Pessoais (1>2)
    	 5.3 Revisar e Editar Mensagem de Pedido (1>2)
     6. Enviar Pedido de Monitoria (1>2)

Após enviar o pedido, ele fica em modo de análise até que seja aprovado tanto pelo docente quando pela coordenação.

### Diagrama de Atividades

O capítulo 6, Organização do espaço problema, do livro IHC (1), de Barbosa e Silva, indica a seguinte notação para ser utilizada no diagrama, de acordo com a imagem 1.

Desse modo, tendo isso e a análise contextual como base, a imagem 2 mostra o diagrama da análise hierárquica de tarefas.

### Tabela de Análise
A tabela 1 mostra a tabela da análise hierárquica de tarefas sobre a funcionalidade de pedido de monitoria.

| Objetivos/Operações | Relações | Problemas e Recomendações |
|--|--|--|
| 0. Realizar Pedido de Monitoria | | |
| 1. Selecionar Disciplina | (1/2) | **Input:** Facilitar a busca pela disciplina desejada. <br> **Feedback:** Confirmar se a disciplina escolhida é a correta. <br> **Plano:** Implementar uma barra de pesquisa para facilitar a localização. <br> **Recomendação:** Melhorar a usabilidade do sistema para uma navegação mais intuitiva. |
| 1.1 Escolher Campus | (1+2) | **Input:** Disponibilizar opções claras e organizadas dos campi. <br> **Feedback:** Garantir que o estudante selecione o campus correto. <br> **Plano:** Incluir descrições dos campi para facilitar a escolha. <br> **Recomendação:** Oferecer uma lista de campi com descrições breves para orientar a escolha. |
| 1.1.1 Identificar Faculdade ou Instituto | (1>2) | **Input:** Facilitar a identificação da faculdade ou instituto. <br> **Feedback:** Garantir que o estudante escolha a faculdade ou instituto correto. <br> **Plano:** Incluir logotipos ou nomes completos das faculdades e institutos. <br> **Recomendação:** Melhorar a identificação visual das faculdades e institutos. |
| 1.1.2 Localizar o Departamento | (1>2) | **Input:** Tornar mais fácil a localização do departamento. <br> **Feedback:** Confirmar que o departamento selecionado é o desejado. <br> **Plano:** Incluir descrições breves dos departamentos. <br> **Recomendação:** Facilitar a identificação dos departamentos através de descrições sucintas. |
| 1.2 Localizar a Disciplina | (1>2) | **Input:** Facilitar a busca por disciplinas previamente cursadas e aprovadas. <br> **Feedback:** Garantir que o estudante selecione a disciplina correta. <br> **Plano:** Oferecer uma lista de disciplinas cursadas e aprovadas. <br> **Recomendação:** Aprimorar a navegação para uma seleção mais rápida e precisa das disciplinas. |
| 2. Especificar Detalhes do Pedido | (1>2)| |
| 2.1 Indicar Professor | (1>2) | **Input:** Facilitar a seleção do professor desejado. <br> **Feedback:** Confirmar se o professor escolhido é o correto. <br> **Plano:** Implementar uma lista de professores com suas respectivas disciplinas. <br> **Recomendação:** Aprimorar a busca por professores para uma escolha mais precisa. |
| 2.2 Selecionar Turma | (1>2) | **Input:** Tornar mais fácil a seleção da turma desejada. <br> **Feedback:** Confirmar se a turma selecionada é a correta. <br> **Plano:** Incluir informações adicionais sobre as turmas, como horários e locais de aula. <br> **Recomendação:** Melhorar a visualização das turmas para uma escolha mais informada. |
| 2.3 Adicionar Informações Adicionais | (1>2) | **Input:** Facilitar a inclusão de informações relevantes para o pedido de monitoria. <br> **Feedback:** Confirmar se as informações adicionais são necessárias ou relevantes. <br> **Plano:** Oferecer campos específicos para informações adicionais. <br> **Recomendação:** Simplificar o processo de adição de informações complementares. |
| 3. Inserir Dados Pessoais | (1>2) | |
| 3.1 Preencher Nome | (1>2) | **Input:** Facilitar o preenchimento do nome do estudante. <br> **Feedback:** Confirmar a precisão do nome inserido. <br> **Plano:** Utilizar um campo de preenchimento automático baseado no cadastro do estudante. <br> **Recomendação:** Implementar preenchimento automático com base no perfil do estudante. |
| 3.2 Inserir Matrícula | (1>2) | **Input:** Tornar mais fácil a inserção do número de matrícula. <br> **Feedback:** Confirmar a exatidão da matrícula inserida. <br> **Plano:** Utilizar um campo de preenchimento automático baseado no cadastro do estudante. <br> **Recomendação:** Implementar preenchimento automático com base no perfil do estudante. |
| 3.3 Fornecer Contato | (1>2) | **Input:** Facilitar o fornecimento de informações de contato. <br> **Feedback:** Confirmar a precisão das informações de contato fornecidas. <br> **Plano:** Utilizar campos específicos para e-mail e número de telefone. <br> **Recomendação:** Simplificar o processo de inserção de informações de contato. |
| 4. Adicionar Mensagem de Pedido | (1>2) | |
| 4.1 Escrever Motivação para Solicitar Monitoria| (1>2) | **Input:** Facilitar a inclusão de uma mensagem explicativa para o pedido de monitoria. <br> **Feedback:** Confirmar se a mensagem de motivação é clara e relevante. <br> **Plano:** Oferecer um campo específico para a mensagem de motivação. <br> **Recomendação:** Simplificar o processo de inserção da mensagem de motivação. |
| 4.2 Descrever Expectativas e Necessidades | (1>2) | **Input:** Facilitar a descrição das expectativas e necessidades do estudante em relação à monitoria. <br> **Feedback:** Confirmar se as expectativas e necessidades estão claramente descritas. <br> **Plano:** Oferecer um campo específico para a descrição das expectativas e necessidades. <br> **Recomendação:** Simplificar o processo de inserção das expectativas e necessidades. |
| 5. Revisar Pedido | (1>2) | |
| 5.1 Verificar Detalhes do Pedido | (1>2) | **Input:** Facilitar a revisão dos detalhes do pedido de monitoria. <br> **Feedback:** Confirmar se os detalhes do pedido estão corretos. <br> **Plano:** Oferecer uma visualização resumida dos detalhes do pedido para revisão. <br> **Recomendação:** Aprimorar a visualização dos detalhes do pedido para uma revisão mais eficiente. |
| 5.2 Confirmar Precisão dos Dados Pessoais | (1>2) | **Input:** Facilitar a verificação da precisão dos dados pessoais inseridos. <br> **Feedback:** Confirmar se os dados pessoais estão corretos e atualizados. <br> **Plano:** Oferecer uma visualização resumida dos dados pessoais para revisão. <br> **Recomendação:** Aprimorar a visualização dos dados pessoais para uma verificação mais eficaz. |
| 5.3 Revisar e Editar Mensagem de Pedido | (1>2) | **Input:** Facilitar a revisão e edição da mensagem de pedido de monitoria. <br> **Feedback:** Confirmar se a mensagem de pedido está clara e precisa. <br> **Plano:** Oferecer um campo de edição para a mensagem de pedido. <br> **Recomendação:** Simplificar o processo de edição da mensagem de pedido. |
| 6. Enviar Pedido de Monitoria | (1>2) | |

## GOMS
O GOMS é um método de análise de tarefas que descreve as atividades dos usuários em termos de objetivos (o que o usuário deseja alcançar), operadores (as ações realizadas, como clicar em um botão), métodos (sequências de ações para alcançar um objetivo) e regras de seleção (critérios para escolher entre métodos alternativos). Essa abordagem em relação à funcionalidade de **pedido de monitoria** será mostrada a seguir.

### Definição dos objetivos

1. **Selecionar Disciplina**: O usuário pretende escolher a disciplina para a qual deseja solicitar monitoria.
2. **Especificar Detalhes do Pedido**: O usuário precisa fornecer informações específicas sobre o
pedido de monitoria, como indicar o professor, selecionar a turma e adicionar detalhes adicionais, como horários preferenciais.
3. **Enviar Pedido de Monitoria**: O objetivo final é concluir o processo de solicitação de monitoria enviando o pedido com todas as informações necessárias.

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

      GOAL 0: Realizar Pedido de Monitoria
      
      GOAL 1: Selecionar Disciplina
      - METHOD 1.A: Escolher Campus
        - METHOD 1.A.A: Identificar Faculdade ou Instituto
          - OPERATOR 1.A.A.1: Clicar na opção de campus desejada.
        - METHOD 1.A.B: Localizar o Departamento
          - OPERATOR 1.A.B.1: Localizar e clicar na opção de departamento correspondente ao campus selecionado.
      - METHOD 1.B: Localizar a Disciplina
        - OPERATOR 1.B.1: Pesquisar ou navegar pelas disciplinas disponíveis.
        - SELECTION RULE 1.B.1: Permitir apenas a seleção de disciplinas cursadas e aprovadas pelo estudante, com menção mínima de MS ou SS.
      
      GOAL 2: Especificar Detalhes do Pedido
      - METHOD 2.A: Indicar Professor
        - OPERATOR 2.A.1: Selecione o professor desejado, se aplicável.
      - METHOD 2.B: Selecionar Turma
        - OPERATOR 2.B.1: Escolher a turma desejada, se o professor tiver múltiplas turmas.
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


## Conclusão
Como é possível observar, a análise hierárquica e a aplicação do método GOMS para a funcionalidade de pedido de monitoria revelaram uma estrutura complexa de tarefas e interações dentro do processo. Assim, ao desmembrar cada etapa em objetivos, passo a passo, métodos e regras, foi possível compreender detalhadamente as ações dos usuários e identificar áreas de relevância.

## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise hierárquica| Larissa Stéfane | - | 30/04/2024 |
| 1.1 | Execução do GOMS | Larissa Stéfane | - | 01/04/2024 |
