# Análise de Tarefas: Histórico

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Análise Hierárquica de Tarefas](Análise-Hierárquica-de-Tarefas)
* [GOMS](#GOMS)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Observação
A aluna Luana Medeiros que estava trabalhando com essa funcionalidade durante o projeto, decidiu alterar a funcionalidade trabalhada, portanto a funcionalidade de Histórico não será mais trabalhada.

## Introdução 
Como foi falado no documento de planejamento das análises de histórico, a ferramenta de emitir histórico oferecerá aos alunos a possibilidade de ter um documento oficial sobre o histórico acadêmico. Com base nisso, este documento pretende realizar uma análise detalhada das tarefas envolvidas na funcionalidade de emitir histórico por meio dos métodos de análise hierárquica de tarefas e GOMS (Goals, Operators, Methods, Selection Rules).

## Objetivos
Essa funcionalidade tem como objetivo principal fornecer aos estudantes a ferramenta de emitir histórico para que eles tenham acesso fácil e rápido ao histórico acadêmico. Sendo esse um documento importante para os estudantes.

## Análise Hierárquica de Tarefas
A análise de tarefas envolve a decomposição das ações dos usuários em partes menores, chamadas de tarefas, em um sistema ou interface. Essa estratégia busca simplificar atividades complexas, fragmentando-as em metas, submetas e ações operacionais, e criando um roteiro para determinar a ordem correta de execução dessas submetas.

### Análise Contextual

Na tabela 1 podemos ver a análise relacionada a Emitir Histórico.

**Tabela 1**: Emitir Histórico

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Acessar aba de emitir histórico** | **Input:** Seleção da opção "Emitir Histórico" no menu Histórico.<br>**Feedback:** Exibição de arquivo sendo baixado.<br>**Plano:** Assegurar fácil acesso e visibilidade da opção de solicitação. |
| **1. Confirmar a emissão do histórico** | **Input:** Conferir se o arquivo foi baixado corretamente e está abrindo.<br>**Feedback:** Histórico acadêmico é apresentado.<br>**Plano:** Assegurar que o histórico seja intuitivo e completo. |

<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

Na tabela 2 podemos ver a análise relacionada a Visualizar Matérias Optativas

**Tabela 2**: Visualizar Matérias Optativas

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Acessar aba de Grade Currícular** | **Input:** Seleção da opção "Grade Currícular" no menu Histórico.<br>**Feedback:** Exibição da grade do período em que o aluno se encontra.<br>**Plano:** Assegurar fácil acesso e visibilidade da opção de solicitação. |
| **1. Acessar Matérias Optativas** | **Input:** Seleção da opção "Matérias Optativas" no menu Grade Currícular.<br>**Feedback:** Matérias Optativas possíveis para o curso do aluno são apresentadas.<br>**Plano:** Assegurar que a visualização das matérias seja intuitiva e completa. |

<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

Na tabela 3 podemos ver a análise relacionada a Visualizar Pré-Requisitos

**Tabela 3**: Visualizar Pré-Requisitos

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Acessar aba de Grade Currícular** | **Input:** Seleção da opção "Fluxograma" no menu Histórico.<br>**Feedback:** Exibição do fluxograma do curso em que o aluno se encontra.<br>**Plano:** Assegurar fácil acesso e visibilidade da opção de solicitação. |
| **1. Conferir Pré-Requisitos** | **Input:** Conferir pré-requisitos de matérias desejadas.<br>**Feedback:** Exibição do fluxograma do curso em que o aluno se encontra.<br>**Plano:** Assegurar que a visualização das matérias seja intuitiva e completa. |

<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

## GOMS
O GOMS é uma técnica que analisa as atividades dos usuários, descrevendo seus objetivos (o que desejam alcançar), os operadores utilizados (ações como clicar em um botão), os métodos empregados (sequências de ações para atingir objetivos específicos) e as regras de seleção (critérios para escolher entre diferentes métodos). Esta metodologia será empregada na análise da funcionalidade de Emitir Histórico

### Definição dos objetivos

1. **Emitir Histórico**: Este é o objetivo principal da funcionalidade, que envolve o processo de emitir o histórico acadêmico do aluno.
2. **Entrar na aba de histórico**: O usuário precisa entrar na aba de histórico para ter acesso a tudo relacionado.
3. **Identificar a opção desejada**: É necessário identificar qual sera a opção desejada.
4. **Selecionar a opção de Emitir Histórico**: Uma vez identificada a opção desejada, o usuário precisa executar a ação.
5. **Conferir emissão de histórico**: Depois de selecionar a opção de emitir histórico, deve conferir que o arquivo foi baixado ou aberto.
6. **Revisar emissão de histórico**: Antes de finalizar o processo, o usuário revisa todas as informações fornecidas para garantir precisão e completude.

### Execução do GOMS

  Nessa tarefa, o objetivo do usúario é emitir o histórico

    GOAL 0: Fazer login na página para vizualizar o painel principal
    GOAL 1: Acessar aba de histórico
        OP 1.1: Guiar o mouse para a aba "Histórico"
        OP 1.2:  Guiar o mouse para a aba "Emitir Histórico"
        OP 1.3: Pressionar o botão esquerdo do mouse
    GOAL 2: Verificar se o arquivo esta sendo baixado
        OP 2.1: Guiar o mouse para a opção 'Downloads' do navegador 
        OP 2.2: Pressionar o botão esquerdo do mouse
        OP 2.3: Verificar se o arquivo desejado está presente 
    GOAL 3: Verificar informações do histórico
        OP 3.1: Guiar o mouse para a aba que se abriu no navegador que contém o histórico acadêmico
        OP 3.2: Pressionar o botão esquerdo do mouse
        OP 3.3: Conferir informações presentes no histórico
        
<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

 ## Conclusão

Ao analisar a função de Emitir Histórico usando uma abordagem hierárquica e aplicando o método GOMS, percebe-se uma estrutura de tarefas e interações. Esse método detalhado, ao decompor cada etapa em objetivos, procedimentos, métodos e regras, proporcionou uma compreensão aprofundada das atividades dos usuários, identificando áreas críticas.

## Bibliografia

Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). **Interação Humano-Computador e Experiência do Usuário**.

Carlos Mar, Msc. **Modelo GOMS – Análise de Tarefas**. Maio de 2014. Disponível em: <https://carlosmardotcomdotbr.wordpress.com/wp-content/uploads/2014/04/modelotarefasgoms.pdf>. Acessado em 01 de maio de 2024.

## Histórico de Versão

| Versão | Alteração                                   | Responsável    | Revisor         | Data       |
| ------ | ------------------------------------------- | -------------- | --------------- | ---------- |
| 1.0    | Criação e realização da análise hierárquica | Luana Medeiros | Breno Alexandre | 06/05/2024 |
