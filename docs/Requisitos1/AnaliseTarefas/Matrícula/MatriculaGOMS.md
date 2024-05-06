
# Análise de Tarefas: Tarefas de estágio na visão do estudante (GOMS)

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Análise de Tarefas](Análise-Hierárquica-de-Tarefas)
* [Análise Contextual](#Análise-Contextual)
* [Pré-cadastro estágios](#Pré-cadastro-estágios)
* [Gerenciar estágios](#Gerenciar-estágios)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução
O método GOMS (Goals, Operators, Methods, and Selection Rules) é uma técnica de modelagem cognitiva utilizada para analisar e prever como os usuários interagem com sistemas computacionais. Ele divide a interação em metas, operadores, métodos e regras de seleção, fornecendo uma estrutura sistemática para compreender os processos cognitivos e de interação do usuário.

No contexto do sistema SIGAA, que é usado para gerenciar informações acadêmicas e administrativas em instituições de ensino, o método GOMS será aplicado para analisar duas tarefas específicas: fazer matrícula, retirar e trancar matrícula. Ao utilizar o método GOMS, podemos descrever de forma detalhada as etapas e operações envolvidas nessas tarefas, identificar possíveis pontos de fricção ou ineficiência e informar o design de uma interface mais intuitiva e eficiente para os usuários do SIGAA.

## Objetivos
O objetivo de se utilizar o método GOMS é fornecer uma estrutura sistemática para analisar a interação entre os usuários e as tarefas de realizar matrícula, trancar matrícula e retirar matrícula em matérias no SIGAA na visão do aluno. 

## Análise de tarefas

### Realizar matrícula

Nesta tarefa, o objetivo do usuário é efetuar a matrícula em uma matéria
    GOAL 0: Fazer login na página para vizualizar o painel principal
    GOAL 1: Acessar aba de ensino
        OP 1.1: Guiar o mouse para a aba "Ensino"
        OP 1.2:  Guiar o mouse para a aba "Matrícula online"
        OP 1.3: Pressionar o botão esquerdo do mouse
    GOAL 2: Escolher método de matrícula
        OP 2.1: Guiar o mouse para algum das opções de matrícula (Normal, Extraordinária, Turma de Férias, etc)
        OP 2.2: Guiar o mouse para a opção escolhida
        OP 2.3: Pressionar o botão esquerdo do mouse
    GOAL 3: Procurar a matéria
        OP 3.1: Preencher todos os campos obrigatórios (marcados com *)
        OP 3.2: Selecionar qual o campus e a faculdade da matéria escolhida
        OP 3.2: Guiar mouse para a opção "Pesquisar"
        OP 3.3: Pressionar o botão esquerdo do mouse
    GOAL 4: Realizar matrícula
        OP 4.1: Selecionar a matéria em questão
        OP 4.2: Guiar o mouse até a opção de adicionar matrícula
        OP 4.3: Pressionar o botão esquerdo do mouse
        OP 4.4: Preencher com sua matrícula e senha nos campos em questão
        OP 4.5: Guiar o mouse até a opção confirmar
        OP 4.6: Pressionar o botão esquerdo do mouse

### Realizar trancamento
  Nesta tarefa, o objetivo do usuário é trancar uma matrícula em uma matéria
    GOAL 0: Fazer login na página para vizualizar o painel principal
    GOAL 1: Acessar aba de ensino
        OP 1.1: Guiar o mouse para a aba "Ensino"
        OP 1.2:  Guiar o mouse para a aba "Trancamento de matrícula"
        OP 1.3: Pressionar o botão esquerdo do mouse
    GOAL 2: Escolher opção trancamento
        OP 2.1: Guiar o mouse para a opção "trancamento"
        OP 2.2: Guiar o mouse para a opção escolhida
        OP 2.3: Pressionar o botão esquerdo do mouse
    GOAL 3: Escolher a matéria
        OP 3.1: Escolher pelo checkbox quais matérias deseja trancar
        OP 3.2: Guiar mouse para a opção "Solicitar trancamento"
        OP 3.3: Pressionar o botão esquerdo do mouse


## Conclusão

A aplicação do método GOMS ao sistema SIGAA, especificamente nas tarefas de trancamento e realização da matrícula, proporcionou uma análise detalhada das ações necessárias para a realização dessas atividades. Através deste método, foi possível identificar cada etapa envolvida, desde o login no sistema até a execução final das tarefas específicas, destacando os operadores e métodos utilizados pelo usuário.

A análise realizada oferece uma visão clara dos processos cognitivos e das interações físicas que os usuários precisam executar, permitindo identificar potenciais áreas de melhoria no design da interface. Por exemplo, a redução do número de cliques necessários e a simplificação dos processos de navegação podem diminuir a carga cognitiva e melhorar a eficiência do usuário na realização de suas tarefas.

## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 04 de maio de 2024.
2. Vários Autores. GOMS. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/goms/#comprar-ingresso/>. Acesso em 04 de maio de 2024.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise GOMS | Pedro Augusto | Breno Alexandre | 06/05/2024 |
