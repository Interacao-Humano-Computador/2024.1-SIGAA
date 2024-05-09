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

No contexto do sistema SIGAA, que é usado para gerenciar informações acadêmicas e administrativas em instituições de ensino, o método GOMS será aplicado para analisar duas tarefas específicas: cadastrar estágios e gerenciar informações relacionadas a esses estágios. Ao utilizar o método GOMS, podemos descrever de forma detalhada as etapas e operações envolvidas nessas tarefas, identificar possíveis pontos de fricção ou ineficiência e informar o design de uma interface mais intuitiva e eficiente para os usuários do SIGAA.

## Objetivos
O objetivo de se utilizar o método GOMS é fornecer uma estrutura sistemática para analisar a interação entre os usuários e a tarefa do cadastro/gerenciamento de estágios do SIGAA na visão do aluno. 

## Análise de tarefas

### Pré-cadastro estágios

Nesta tarefa, o objetivo do usuário é efetuar o pré-cadastro de um estágio

    GOAL 0: Fazer login na página para vizualizar o painel principal
    GOAL 1: Acessar aba de estágios
        OP 1.1: Guiar o mouse para a aba "Estágio"
        OP 1.2:  Guiar o mouse para a aba "Pré-cadastro de Estágio"
        OP 1.3: Pressionar o botão esquerdo do mouse
    GOAL 2: Encontrar convênio responsável pelo estágio
        OP 2.1: Guiar o mouse para algum dos campos de filtro
        OP 2.2: Inserir pesquisa para encontrar o instituto/pessoa responsável pelo estágio
        OP 2.3: Guiar o mouse para o botão "Selecionar Convênio de Estágio"
        OP 2.4: Pressionar o botão esquerdo do mouse
    GOAL 3: Efetuar o pré-cadastro do estágio
        OP 3.1: Preencher todos os campos obrigatórios (marcados com *)
        OP 3.2: Selecionar horários em que o estágio acontecerá
        OP 3.2: Guiar mouse para a opção "Continuar"
        OP 3.3: Pressionar o botão esquerdo do mouse
        OP 3.4: Guiar mouse para a opção "Confirmar"
        OP 3.5: Pressionar o botão esquerdo do mouse

### Gerenciar estágios

  Nessa tarefa, o objetivo do usúario é verificar como está o andamento e o status do estágio cadastrado

    GOAL 0: Fazer login na página para vizualizar o painel principal
    GOAL 1: Acessar aba de estágios
        OP 1.1: Guiar o mouse para a aba "Estágio"
        OP 1.2:  Guiar o mouse para a aba "Gerenciar Estágio"
        OP 1.3: Pressionar o botão esquerdo do mouse
    GOAL 2: Verificar informações de um cadastro específico
        OP 2.1: Guiar o mouse para a opção 'Visualizar Menu'
        OP 2.2: Clicar na opção Visualizar Estágio


## Conclusão

A aplicação do método GOMS ao sistema SIGAA, especificamente nas tarefas de pré-cadastro e gerenciamento de estágios, proporcionou uma análise detalhada das ações necessárias para a realização dessas atividades. Através deste método, foi possível identificar cada etapa envolvida, desde o login no sistema até a execução final das tarefas específicas, destacando os operadores e métodos utilizados pelo usuário.

A análise realizada oferece uma visão clara dos processos cognitivos e das interações físicas que os usuários precisam executar, permitindo identificar potenciais áreas de melhoria no design da interface. Por exemplo, a redução do número de cliques necessários e a simplificação dos processos de navegação podem diminuir a carga cognitiva e melhorar a eficiência do usuário na realização de suas tarefas.

## Bibliografia
Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 04 de maio de 2024.

Vários Autores. GOMS. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/analise-de-tarefas/goms/#comprar-ingresso/>. Acesso em 04 de maio de 2024.

## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação e realização da análise GOMS | Iago Passaglia | Breno Alexandre | 04/05/2024 |
