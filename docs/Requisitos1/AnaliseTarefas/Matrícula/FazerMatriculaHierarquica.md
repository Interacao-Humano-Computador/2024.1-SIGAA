
# Análise Hierárquica de Tarefas no SIGAA - Matrícula (Visão do aluno)

## Introdução

A Análise Hierárquica de Tarefas (HTA) é uma técnica metodológica amplamente empregada na área de Interação Humano-Computador (IHC). Seu foco reside em desmembrar uma tarefa complexa em hierarquias de sub-tarefas mais simples e gerenciáveis. Por meio dessa abordagem, detalhamos a interação dos usuários com um sistema, mapeando seus objetivos, as operações necessárias para alcançá-los e as estratégias adotadas para executá-las. A HTA oferece uma visão clara da sequência de ações e das interdependências entre as tarefas, o que facilita o desenvolvimento de sistemas mais intuitivos e eficazes.

## Motivo da escolha

Optamos pela utilização da Análise Hierárquica de Tarefas devido à sua habilidade em organizar de forma clara e sistemática as interações complexas entre os usuários e o sistema do SIGAA, especificamente em relação à aba de Ensino e a parte de matrícula. Essa metodologia facilita a identificação e análise de problemas, possibilitando otimizações que têm o potencial de aprimorar substancialmente a experiência do usuário e a eficiência do sistema.

## Tabela 1:  Realização de matrícula
**Introdução:** Esta seção abrange todas as operações relacionadas a realização de matrícula, permitindo aos discentes, realizar matrícula em matérias durante o período previsto.

<details>
 <summary size="20"><b> Tabela de Realizar Matrícula </b></summary> 

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Realizar matrícula** | **Input:** O usuário precisa realizar a matrícula em matérias da universidade.<br>**Feedback:** O sistema deve possibilitar que o usuário faça a matrícula com facilidade.<br>**Plano:** Assegurar que as opções disponíveis sejam claramente visíveis e compreensíveis. |
| **1 Selecionar a aba Ensino 1>2** | **Input:** Seleção da opção "Ensino" no menu .<br>**Feedback:** Uma aba com todas as opções de ensino aparece na tela.<br>**Plano:** Garantir que a aba Ensino tenha as opções corretas. |
| **1.1. Escolher a opção Matrícula On-line 1>2** | **Input:** Escolher a opção Matrícula On-line na aba Ensino.<br>**Feedback:** Deve abrir uma aba com mais opções de matrícula.<br>**Plano:** Mostrar para o usuário todas as opções relacionadas. |
| **1.2. Escolher opção Realizar Matrícula** | **Input:** O usuário deve escolher a opção Realizar Matrícula.<br>**Feedback:** Uma nova página deve abrir com mais informações sobre a matrícula.<br>**Plano:** Informar ao usuário sobre as datas de matrícula. |
| **2. Selecionar a opção iniciar a seleção de turmas** | **Input:** Seleção da opção "Iniciar seleção de Turmas".<br>**Feedback:** Uma nova página deve ser aberta com as turmas a serem selecionadas.<br>**Plano:** Confirmar a opção do usuário. |
| **2.1. Selecionar matérias a serem feitas** | **Input:** Seleção por meio de checkbox das matérias desejadas.<br>**Feedback:** O sistema deve exibir um "check" dentro do elemento escolhido.<br>**Plano:** Tornar mais intuitiva a confirmação de escolha. |
| **2.2. Selecionar opção Adicionar Turmas Selecionadas** | **Input:** Seleção da opção adicionar turmas selecionadas.<br>**Feedback:** O sistema deve abrir uma página com as matérias escolhidas.<br>**Plano:** Confirmar com o usuário as matérias escolhidas. |
| **2.3. Selecionar opção confirmar matrícula** | **Input:** Seleção da opção Confirmar matrícula.<br>**Feedback:** Uma outra página deve abrir com os inputs de CPF e senha.<br>**Plano:** Confirmar a identidadedo usuário. |
| **3. Inserir CPF e senha 1+2** | **Input:** Preenchimento de CPF e senha de usuário.<br>**Feedback:** Mensagem positiva quanto á adição da matrícula.<br>**Plano:** Tornar mais intuitiva a confirmação de identidade. |
| **3.1. Selecionar a opção de Confirmar matrícula** | **Input:** Seleção da opção de Confirmar matrícula.<br>**Feedback:** O comprovante de matrícula aparecerá na tela.<br>**Plano:** Assegurar a escolha do usuário. |
</details>

<details>
 <summary size="20"><b> Tabela de Trancamento de matrícula </b></summary> 

## Tabela 2: Trancamento de matrícula
**Introdução:** Esta tabela descreve o processo pelo qual discentes passam para realizar o trancamento de uma ou várias disciplinas.

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Acessar Trancamento de matrícula** | **Input:** Seleção da opção "Trancamento de matrícula na aba Ensino".<br>**Feedback:** Serão exibidas as opções de Trancar e Exibir andamento do trancamento.<br>**Plano:** Garantir que as opções e processos sejam claros e compreensíveis. |
| **1. Selecionar a opção trancar 1>2** | **Input:** Seleção da opção "Trancar".<br>**Feedback:** A página listando as matérias aparece.<br>**Plano:** Tornar simples a escolha de matérias para trancar. |
| **2. Realizar o trancamento** | **Input:** Selecionar matérias para trancar e clicar em "Solicitar trancamento".<br>**Feedback:** A resposta sobre o sucesso do trancamento aparece.<br>**Plano:** Oferecer uma apresentação das informações de forma simples e de fácil acesso. |
</details>

### Diagrama de Atividades

Para facilitar a visualização de tarefas, a figura 1 mostra o diagrama:

 <div align="center">
    Figura 1: Diagrama HTA da ação de realizar matrícula
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/HTArealizarmatricula.png">
    <br>
     Fonte: Pedro Izarias
    <br>
</div>


Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA Realizar matrícula](https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/HTArealizarmatricula.png)

 <div align="center">
    Figura 2: Diagrama HTA da ação de trancamento de matrícula
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/HTAtrancamento.png">
    <br>
     Fonte: Pedro Izarias
    <br>
</div>


Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA Trancamento de matrícula](https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/HTAtrancamento.png)


## Conclusão
Como observado, a avaliação HTA das funções de realização de matrícula e trancamento de matrícula revelou uma complexidade na estrutura das tarefas e interações envolvidas. Ao desmembrar cada fase em metas, sequências de procedimentos, abordagens e orientações, pudemos examinar detalhadamente as atividades dos usuários e detectar pontos cruciais.

## Bibliografia
**BARBOSA**, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.

## Histórico de Versão
| Versão | Alteração                                   | Responsável   | Revisor         | Data       |
| ------ | ------------------------------------------- | ------------- | --------------- | ---------- |
| 1.0    | Criação e realização da análise hierárquica | Pedro Izarias | Breno Alexandre | 05/05/2024 |
| 1.1    | Adição dos diagramas | Pedro Izarias | - | 01/06/2024 |
