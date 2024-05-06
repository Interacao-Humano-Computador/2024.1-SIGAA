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

<details>
  <summary size="20"><b> Análise Contextual </b></summary> 
  
    0. Visualização de Monitoria (1/2)
      
      1. Verificar Monitoria Atual (1/2)
         
         1.1 Estabelecer Forma e Grade de Atendimento (1+2)
            
            1.1.1 Configurar Forma de Atendimento (1+2)
               
               1.1.1.1 Selecionar Forma de Atendimento (WhatsApp, Telegram, Presencial)
               
               1.1.1.2 Personalizar Configurações de Atendimento (Notificações, Disponibilidade)
            
            1.1.2 Estabelecer Grade de Atendimento (1+2)
               
               1.1.2.1 Selecionar Horários Disponíveis e Duração das Monitorias
               
               1.1.2.2 Priorizar Horários de Pico de Dificuldade nas Disciplinas
               
               1.1.2.3 Reservar Horários para Atendimento Extra (Sessões de Dúvidas)
         
         1.2 Solicitar Aluguel de Salas para Aulas de Monitorias (1>2)
            
            1.2.1 Inserir Data, Horário Desejado e Duração da Monitoria
            
            1.2.2 Verificar Disponibilidade de Salas (1>2)
               
               1.2.2.1 Consultar Sistema de Reservas de Salas
               
               1.2.2.2 Avaliar Opções de Salas Disponíveis (Localização, Capacidade)
            
            1.2.2 .3 Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis (1>2)
               
               1.2.2.3.1 Notificar Usuário sobre Indisponibilidade de Salas
               
               1.2.2.3.2 Sugerir Alternativas (Outras Salas, Outros Horários)
        
         1.3 Trocar Mensagens Privadas com Professores e Alunos (1>2)
               
               1.3.1 Selecionar Professor ou Aluno
              
               1.3.2 Enviar e Receber Mensagens
               
               1.3.3 Agendar Reunião Presencial (Se Necessário)
    
      2. Verificar Monitorias Anteriores (1>2)
           
            2.1 Escolha entre os Registros de Monitorias Anteriores
           
            2.2 Visualização dos Dados Anteriores sem Possibilidade de Modificação
           
            2.3 Consultar Relatórios, Avaliações e Feedback de Monitorias Passadas

</details>

### Diagrama de Atividades

Para facilitar a visualização de tarefas, a imagem 1 mostra o diagrama:


 <div align="center">
    Figura 1: Diagrama HTA do monitoramento de monitoria
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/AnaliseMonitoramentoMonitoria.drawio.png">
    <br>
     Fonte: Larissa Stéfane
    <br>
</div>

Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA do Monitoramento de Monitoria](https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/AnaliseMonitoramentoMonitoria.drawio.png)

### Tabela de Análise

A tabela 1 mostra a tabela da análise hierárquica de tarefas sobre a funcionalidade de pedido de monitoria.

<details>
  <summary size="20"><b> Tabela de Análise </b></summary> 

| Objetivos/Operações | Relações | Problemas e Recomendações |
|---------------------|----------|--------------------------|
| 0. Visualização de Monitoria | (1/2) | **Input:** Solicitação de visualização do status de monitorias. <br> **Feedback:** Apresentação das informações de monitorias atuais e anteriores. <br> **Plano:** Desenvolver uma interface intuitiva para a visualização dos dados. <br> **Recomendação:** Incluir filtros e opções de ordenação para facilitar a navegação. |
| 1. Verificar Monitoria Atual | (1/2) | **Input:** Requisição para ver o status da monitoria atual. <br> **Feedback:** Apresentação do status atual da monitoria. <br> **Plano:** Acessar os dados do sistema de monitoramento. <br> **Recomendação:** Garantir que as informações sejam atualizadas em tempo real. |
| 1.1 Estabelecer Forma e Grade de Atendimento | (1+2) | **Input:** Preferências do usuário, disponibilidade de horários. <br> **Feedback:** Confirmação de seleções. <br> **Plano:** Personalizar configurações conforme preferências do usuário. <br> **Recomendação:** Facilitar a seleção de horários com uma interface intuitiva. |
| 1.1.1 Configurar Forma de Atendimento | (1+2) | **Input:** Opções de formas de atendimento. <br> **Feedback:** Confirmação da seleção. <br> **Plano:** Facilitar o acesso às configurações. <br> **Recomendação:** Oferecer opções adicionais de comunicação, como videoconferência. |
| 1.1.1.1 Selecionar Forma de Atendimento (WhatsApp, Telegram, Presencial) | | **Plano:** Integrar sistemas de comunicação selecionados para garantir a compatibilidade. <br> **Recomendação:** Fornecer guias ou tutoriais sobre o uso das formas de comunicação selecionadas. |
| 1.1.1.2 Personalizar Configurações de Atendimento (Notificações, Disponibilidade) | | |
| 1.1.2 Estabelecer Grade de Atendimento | (1+2) | **Input:** Disponibilidade de horários, preferências do usuário. <br> **Feedback:** Confirmação das seleções. <br> **Plano:** Organizar horários de acordo com preferências do usuário. <br> **Recomendação:** Permitir a seleção de múltiplos horários simultaneamente. |
| 1.1.2.1 Selecionar Horários Disponíveis e Duração das Monitorias |  | **Plano:** Organizar horários conforme preferências do usuário. <br> **Recomendação:** Oferecer opções de duração de monitorias pré-definidas. |
| 1.1.2.2 Priorizar Horários de Pico de Dificuldade nas Disciplinas | | **Plano:** Priorizar horários mais requisitados. <br> **Recomendação:** Oferecer sugestões com base nas estatísticas de dificuldade. |
| 1.1.2.3 Reservar Horários para Atendimento Extra (Sessões de Dúvidas) |  | **Plano:** Reservar horários conforme demanda. <br> **Recomendação:** Disponibilizar horários extras em períodos de pico de dificuldade. |
| 1.2 Solicitar Aluguel de Salas para Aulas de Monitorias | (1>2) | **Input:** Data, horário e duração desejados. <br> **Feedback:** Confirmação da solicitação. <br> **Plano:** Verificar a disponibilidade de salas. <br> **Recomendação:** Facilitar o acesso às informações sobre disponibilidade de salas. |
| 1.2.1 Inserir Data, Horário Desejado e Duração da Monitoria |  |  **Plano:** Verificar a disponibilidade de salas. <br> **Recomendação:** Oferecer opções de duração de monitoria pré-definidas. |
| 1.2.2 Verificar Disponibilidade de Salas | (1>2) | **Input:** Requisição de reserva de sala. <br> **Feedback:** Informação sobre disponibilidade de salas. <br> **Plano:** Oferecer alternativas em caso de indisponibilidade. <br> **Recomendação:** Notificar o usuário sobre as opções disponíveis. |
| 1.2.2.1 Consultar Sistema de Reservas de Salas |  | **Plano:** Integrar-se ao sistema de reservas. <br> **Recomendação:** Facilitar a pesquisa e reserva de salas. |
| 1.2.2.2 Avaliar Opções de Salas Disponíveis (Localização, Capacidade) | | **Plano:** Apresentar detalhes sobre as salas disponíveis. <br> **Recomendação:** Incluir informações sobre localização e capacidade das salas. |
| 1.2.2.3 Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis | (1>2) | **Input:** Indisponibilidade de salas. <br> **Feedback:** Informação sobre alternativas. <br> **Plano:** Sugerir alternativas de salas ou horários. <br> **Recomendação:** Oferecer opções de horários flexíveis para a monitoria. |
| 1.2.2.3.1 Notificar Usuário sobre Indisponibilidade de Salas | | **Plano:** Informar ao usuário sobre a indisponibilidade. <br> **Recomendação:** Oferecer soluções alternativas para a realização da monitoria. |
| 1.2.2.3.2 Sugerir Alternativas (Outras Salas, Outros Horários) | |**Plano:** Apresentar opções alternativas de salas ou horários. <br> **Recomendação:** Facilitar o acesso às opções alternativas. |
| 1.3 Trocar Mensagens Privadas com Professores e Alunos | (1>2) | **Input:** Interação com professores e alunos. <br> **Feedback:** Respostas às mensagens. <br> **Plano:** Facilitar a comunicação privada. <br> **Recomendação:** Garantir a privacidade das mensagens. |
| 1.3.1 Selecionar Professor ou Aluno | | **Plano:** Integrar sistema de seleção com banco de dados de usuários. <br> **Recomendação:** Facilitar a busca e seleção de contatos. |
| 1.3.2 Enviar e Receber Mensagens | | **Plano:** Implementar sistema de mensagens seguro e eficiente. <br> **Recomendação:** Criptografar mensagens para garantir privacidade. |
| 1.3.3 Agendar Reunião Presencial (Se Necessário) | | **Plano:** Integrar sistema de mensagens com calendário. <br> **Recomendação:** Disponibilizar opções de agendamento com base na disponibilidade de professores e alunos. |
| 2. Verificar Monitorias Anteriores | (1>2) | **Input:** Solicitação para visualizar monitorias anteriores. <br> **Feedback:** Apresentação das monitorias anteriores. <br> **Plano:** Acessar o histórico de monitorias. <br> **Recomendação:** Organizar e apresentar as informações de forma clara e concisa. |
| 2.1 Escolha entre os Registros de Monitorias Anteriores | | **Plano:** Desenvolver interface intuitiva para seleção de registros. <br> **Recomendação:** Incluir opções de filtro e busca para facilitar a seleção. |
| 2.2 Visualização dos Dados Anteriores sem Possibilidade de Modificação | | **Plano:** Implementar sistema de visualização de dados seguro e eficiente. <br> **Recomendação:** Garantir acesso apenas a usuários autorizados. |
| 2.3 Consultar Relatórios, Avaliações e Feedback de Monitorias Passadas | | **Plano:** Integrar relatórios, avaliações e feedback ao sistema de visualização de dados. <br> **Recomendação:** Disponibilizar ferramentas de análise para extrair insights dos dados anteriores. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>

## GOMS
O GOMS é uma estratégia de avaliação de tarefas que descreve as ações dos usuários em termos de objetivos (o que o usuário pretende alcançar), operadores (as ações executadas, como pressionar um botão), métodos (sequências de ações para atingir um objetivo) e regras de seleção (critérios para escolher entre métodos alternativos). Esta abordagem será aplicada à funcionalidade de monitoramento de monitoria.

### Definição dos objetivos

1. **Verificar Monitoria Atual:** Checar o estado atual (informações) da monitoria em curso.
2. **Estabelecer Forma e Grade de Atendimento:** Definir como será conduzida a monitoria e organizar os horários disponíveis.
3. **Configurar Forma de Atendimento:** Escolher a plataforma de comunicação e personalizar as configurações.
4. **Estabelecer Grade de Atendimento:** Definir os horários de funcionamento e priorizar os horários de pico de dificuldade.
5. **Solicitar Aluguel de Salas para Aulas de Monitorias:** Fazer a solicitação de salas para realizar as monitorias presenciais.
6. **Verificar Disponibilidade de Salas:** Checar a disponibilidade de salas de acordo com os critérios especificados.
7. **Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis:** Informar o usuário sobre a falta de salas disponíveis e sugerir alternativas.
8. **Trocar Mensagens Privadas com Professores e Alunos:** Comunicar-se privadamente com os participantes da monitoria.
9. **Verificar Monitorias Anteriores:** Acessar informações sobre monitorias passadas para consulta ou análise.



### Definição dos operadores(Operators)

- **Selecionar:** Escolher entre opções disponíveis, como forma de atendimento, professor ou período.
- **Inserir:** Adicionar informações, como data, horário e duração da monitoria.
- **Consultar:** Buscar informações, como registros de monitorias anteriores e disponibilidade de salas.
- **Exibir:** Mostrar mensagens de notificação, disponibilidade de salas e registros de monitorias.
- **Enviar/Responder:** Enviar e responder mensagens privadas entre professores, alunos e monitores.
- **Editar:** Modificar informações previamente inseridas, como detalhes da monitoria ou configurações de atendimento.
- **Confirmar:** Validar escolhas feitas pelo usuário, como confirmação de reservas de salas ou configurações de atendimento.
- **Cancelar:** Anular ações realizadas, como cancelamento de reservas de salas ou exclusão de mensagens privadas.
- **Navegar:** Mover-se entre diferentes seções ou telas da plataforma de monitoria, como navegação entre registros de monitorias anteriores.
- **Interagir:** Engajar-se em atividades colaborativas, como troca de mensagens privadas ou agendamento de reuniões presenciais.


### Definição dos Métodos
- **Estabelecer Forma e Grade de Atendimento:** Configurar preferências de atendimento, como forma de comunicação e horários disponíveis.
- **Solicitar Aluguel de Salas:** Inserir dados de reserva de salas e verificar disponibilidade.
- **Trocar Mensagens Privadas:** Iniciar, responder e agendar conversas privadas.
- **Visualizar Dados Anteriores de Monitorias:** Acessar registros passados, pesquisar e filtrar informações relevantes.
- **Consultar Relatórios e Avaliações:** Analisar relatórios e feedback de monitorias anteriores sem possibilidade de modificação.


### Definição das Regras de Seleção
- **Selecionar Forma de Atendimento:** Escolher entre opções de comunicação, como WhatsApp, Telegram ou atendimento presencial.
- **Priorizar Horários de Pico de Dificuldade:** Dar preferência a horários em que há maior demanda de dúvidas.
- **Sugerir Alternativas de Salas:** Oferecer opções alternativas caso não haja salas disponíveis para reserva.
- **Pesquisar Monitorias por Disciplina, Professor ou Período:** Filtrar registros de monitorias anteriores com base em critérios específicos.
- **Notificar Usuário sobre Indisponibilidade de Salas:** Informar o usuário quando não houver salas disponíveis para reserva.

### Execução do GOMS


Abaixo, há a execução do método GOMS

<details>
  <summary size="20"><b> GOMS </b></summary> 

      GOAL 0: Verificar Monitoria Atual
      - METHOD 0.A: Visualizar Informações de Monitoria
        - OPERATOR 0.A.1: Acessar a funcionalidade de visualização de monitoria.
        - OPERATOR 0.A.2: Navegar pelas opções de monitoria atual e passada.
        - SELECTION RULE 0.A.2: Priorizar visualização de monitorias atuais antes das passadas.
      
      GOAL 1: Estabelecer Forma e Grade de Atendimento
      - METHOD 1.A: Estabelecer Forma e Grade de Atendimento
        - OPERATOR 1.A.1: Selecionar a forma de atendimento.
        - OPERATOR 1.A.2: Editar as configurações de atendimento, se necessário.
        - OPERATOR 1.A.3: Confirmar as configurações estabelecidas.
        - SELECTION RULE 1.A.1: Selecionar Forma de Atendimento tem que estar entre as opções.
      
      GOAL 2: Configurar Forma de Atendimento
      - METHOD 2.A: Configurar Forma de Atendimento
        - OPERATOR 2.A.1: Selecionar a plataforma de comunicação.
        - OPERATOR 2.A.2: Personalizar as configurações de atendimento.
        - OPERATOR 2.A.3: Confirmar as configurações configuradas.
      
      GOAL 3: Estabelecer Grade de Atendimento
      - METHOD 3.A: Estabelecer Grade de Atendimento
        - OPERATOR 3.A.1: Definir os horários de funcionamento.
        - OPERATOR 3.A.2: Priorizar os horários de pico de dificuldade.
        - OPERATOR 3.A.3: Confirmar as configurações estabelecidas.
        - SELECTION RULE 3.A.2: Priorizar Horários de Pico de Dificuldade.
      
      GOAL 4: Solicitar Aluguel de Salas para Aulas de Monitorias
      - METHOD 4.A: Solicitar Aluguel de Salas
        - OPERATOR 4.A.1: Inserir data, horário desejado e duração da monitoria.
        - OPERATOR 4.A.2: Consultar disponibilidade de salas.
        - OPERATOR 4.A.3: Selecionar e confirmar a reserva da sala desejada.
        - SELECTION RULE 4.A.2: Sugerir Alternativas de Salas.
      
      GOAL 5: Verificar Disponibilidade de Salas
      - METHOD 5.A: Verificar Disponibilidade de Salas
        - OPERATOR 5.A.1: Consultar o sistema de reservas de salas.
        - OPERATOR 5.A.2: Selecionar uma sala disponível.
      
      GOAL 6: Exibir Mensagem de Indisponibilidade se Não Houver Salas Disponíveis
      - METHOD 6.A: Verificar Disponibilidade de Salas
        - OPERATOR 6.A.1: Consultar o sistema de reservas de salas.
        - OPERATOR 6.A.2: Exibir mensagem de indisponibilidade se não houver salas disponíveis.
        - OPERATOR 6.A.3: Confirmar a visualização da mensagem.
        - SELECTION RULE 6.A.1: Notificar Usuário sobre Indisponibilidade de Salas.
      
      GOAL 7: Trocar Mensagens Privadas com Professores e Alunos
      - METHOD 7.A: Trocar Mensagens Privadas
        - OPERATOR 7.A.1: Selecionar o destinatário da mensagem (professor ou aluno).
        - OPERATOR 7.A.2: Enviar ou responder mensagens privadas.
        - OPERATOR 7.A.3: Confirmar o envio ou resposta da mensagem.
      
      GOAL 8: Verificar Monitorias Anteriores
      - METHOD 8.A: Visualizar Dados Anteriores de Monitorias
        - OPERATOR 8.A.1: Acessar registros de monitorias anteriores.
        - OPERATOR 8.A.2: Pesquisar monitorias por disciplina, professor ou período.
        - OPERATOR 8.A.3: Filtrar monitorias por estado (aprovadas, rejeitadas, pendentes).
        - SELECTION RULE 8.A.2: Pesquisar Monitorias por Disciplina, Professor ou Período.

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

</details>

## Conclusão

Ao examinar a funcionalidade de monitoramento de monitoria por meio de uma análise hierárquica e a aplicação do método GOMS, evidencia-se uma estrutura intricada de tarefas e interações. Essa abordagem minuciosa, ao desagregar cada etapa em objetivos, procedimentos, métodos e regras, permitiu uma compreensão aprofundada das ações dos usuários, destacando áreas de importância.

## Bibliografia

1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). **Interação Humano-Computador e Experiência do Usuário**. Acesso em 30 de abril de 2024.
2. Carlos Mar, Msc. **Modelo GOMS – Análise de Tarefas**. Maio de 2014. Disponível em <https://carlosmardotcomdotbr.wordpress.com/wp-content/uploads/2014/04/modelotarefasgoms.pdf>. Acesso em 01 de maio de 2024.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise hierárquica| Larissa Stéfane | Breno Alexandre | 30/04/2024 |
| 1.1 | Execução do GOMS | Larissa Stéfane | Breno Alexandre | 01/05/2024 |
| 1.2 | Reorganização da estrutura e adição da imagem | Larissa Stéfane | Bruno Araújo | 05/05/2024 |
