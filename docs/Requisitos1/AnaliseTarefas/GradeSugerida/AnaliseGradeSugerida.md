# Análise de Tarefas: Grade Sugerida

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Análise Hierárquica de Tarefas](Análise-Hierárquica-de-Tarefas)
* [GOMS](#GOMS)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)


## Introdução 
A funcionalidade "Grade Sugerida" foi criada para oferecer aos alunos uma forma eficiente de planejar suas aulas conforme suas preferências e necessidades acadêmicas. Esta ferramenta permite que os alunos personalizem sua grade horária ao escolher horários preferenciais, matérias desejadas, matérias a serem evitadas, e professores prioritários. As preferências são opcionais, o aluno pode marcá-las se desejar. Com base nisso, este documento pretende realizar uma análise detalhada das tarefas envolvidas na funcionalidade de "Grade Sugerida" por meio dos métodos de análise hierárquica de tarefas e GOMS (Goals, Operators, Methods, Selection Rules).

## Objetivos
O principal objetivo da funcionalidade "Grade Sugerida" é fornecer aos estudantes uma ferramenta que facilite a criação de uma grade horária personalizada, que atenda às suas preferências acadêmicas e pessoais, levando em consideração o histórico acadêmico e o índice de rendimento acadêmico (IRA).

## Análise Hierárquica de Tarefas
A análise de tarefas envolve a decomposição das ações dos usuários em partes menores, chamadas de tarefas, em um sistema ou interface. Essa estratégia busca simplificar atividades complexas, fragmentando-as em metas, submetas e ações operacionais, e criando um roteiro para determinar a ordem correta de execução dessas submetas.

### Análise Contextual
Na tabela 1 podemos ver a análise relacionada a Definir Preferências.

**Tabela 1**: Definir Preferências

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Acessar aba de Grade Sugerida** | **Input:** Seleção da opção "Grade Sugerida" no menu principa, na aba "Estudos".<br>**Feedback:** Exibição da interface de "Grade Sugerida".<br>**Plano:** Assegurar fácil acesso e visibilidade da opção de solicitação. |
| **1. Selecionar Horário Preferencial (Opcional)** | **Input:** Seleção do horário (Diurno, Vespertino, Noturno).<br>**Feedback:** Horário selecionado é exibido como ativo.<br>**Plano:** Assegurar que a seleção de horários seja intuitiva e clara. |
| **2. Escolher Matérias Desejadas (Opcional)** | **Input:** Seleção das matérias desejadas.<br>**Feedback:** Matérias escolhidas são exibidas em uma lista de selecionados.<br>**Plano:** Assegurar que a escolha de matérias seja fácil e intuitiva. |
| **3. Escolher Matérias Não Desejadas (Opcional)** | **Input:** Seleção das matérias não desejadas. <br>**Feedback:** Matérias escolhidas são exibidas em uma lista de excluídos.<br>**Plano:** Assegurar que a exclusão de matérias seja fácil e clara. |
| **4. Priorizar Professores (Opcional)** | **Input:** Seleção dos professores prioritários. <br>**Feedback:** Professores escolhidos são exibidos em uma lista de prioridade.<br>**Plano:** Assegurar que a escolha de professores seja intuitiva e clara. |

<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

Na tabela 2 podemos ver a análise relacionada a Gerar Grade Sugerida.

**Tabela 2**: Gerar Grade Sugerida

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Confirmar Preferências** | **Input:** Revisão e confirmação das preferências definidas.<br>**Feedback:** Preferências confirmadas são exibidas.<br>**Plano:** Assegurar que a revisão e confirmação sejam claras e simples. |
| **1. Solicitar Grade Sugerida** | **Input:** Clique no botão para gerar grade sugerida.<br>**Feedback:** Mensagem de processamento e grade sugerida exibida.<br>**Plano:** Assegurar que o botão de solicitação seja visível e de fácil acesso. |

<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

Na tabela 3 podemos ver a análise relacionada a Revisar Grade Sugerida

**Tabela 3**: Revisar Grade Sugerida

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|----------------------------|
| **0. Visualizar Grade Sugerida** | **Input:** Exibição da grade sugerida com base nas preferências. <br>**Feedback:** Grade exibida com opções de alteração.<br>**Plano:** Assegurar que a grade sugerida seja clara e compreensível. |
| **1. Sugerir Nova Grade** | **Input:** Clique no botão para sugerir nova grade. <br>**Feedback:** Mensagem de processamento e nova grade exibida.<br>**Plano:** Assegurar que o botão de nova sugestão seja visível e de fácil acesso. |

<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

## GOMS
O GOMS é uma técnica que analisa as atividades dos usuários, descrevendo seus objetivos (o que desejam alcançar), os operadores utilizados (ações como clicar em um botão), os métodos empregados (sequências de ações para atingir objetivos específicos) e as regras de seleção (critérios para escolher entre diferentes métodos). Esta metodologia será empregada na análise da funcionalidade de "Grade Sugerida".

### Definição dos objetivos
1. **Acessar Grade Sugerida**: O objetivo principal da funcionalidade é permitir que o aluno acesse a aba de Grade Sugerida.
2. **Definir Preferências (Opcional)**: O usuário pode definir suas preferências de horário, matérias e professores.
3. **Confirmar Preferências**: O usuário confirma suas escolhas para gerar a grade sugerida.
4. **Gerar Grade Sugerida**:Após confirmar, o sistema processa e gera a grade sugerida.
5. **Revisar Grade Sugerida:**: O usuário revisa a grade gerada e pode solicitar uma nova sugestão, se necessário.
   
### Execução do GOMS
Nessa tarefa, o objetivo do usuário é gerar uma grade horária sugerida.

    GOAL 0: Fazer login na página para vizualizar o painel principal
    GOAL 1: Acessar Grade Sugerida
        OP 1.1: Guiar o mouse para o menu principal "Estudos".
        OP 1.2: Guiar o mouse para a aba "Grade Sugerida".
        OP 1.3: Pressionar o botão esquerdo do mouse.
    GOAL 2: Definir Preferências (Opcional)
        OP 2.1: Selecionar Horário Preferencial (Opcional)
           OP 2.1.1: Guiar o mouse para a opção de horário (Diurno, Vespertino, Noturno).
           OP 2.1.2: Pressionar o botão esquerdo do mouse para selecionar.
        OP 2.2: Escolher Matérias Desejadas (Opcional)
           OP 2.2.1: Guiar o mouse para a lista de matérias disponíveis.
           OP 2.2.2: Pressionar o botão esquerdo do mouse nas matérias desejadas.
        OP 2.3: Escolher Matérias Não Desejadas (Opcional)
           OP 2.2.1: Guiar o mouse para a lista de matérias disponíveis.
           OP 2.2.2: Pressionar o botão esquerdo do mouse nas matérias indesejadas.
        OP 2.4: Priorizar Professores (Opcional)
           OP 2.2.1: Guiar o mouse para a lista de professores.
           OP 2.2.2: Pressionar o botão esquerdo do mouse nos professores prioritários.
    GOAL 3: Confirmar Preferências
        OP 3.1: Guiar o mouse para o botão de confirmação.
        OP 3.2: Pressionar o botão esquerdo do mouse.
    GOAL 4: Gerar Grade Sugerida
        OP 4.1: Guiar o mouse para o botão de gerar grade.
        OP 4.2: Pressionar o botão esquerdo do mouse.
        OP 4.3: Aguardar a exibição da grade sugerida.   
    GOAL 5: Revisar Grade Sugerida
        OP 5.1: Visualizar a grade sugerida.
        OP 5.2: Avaliar se a grade atende às preferências.
        OP 5.3: Se necessário, sugerir nova grade. 
           OP 5.3.1: Guiar o mouse para o botão de nova sugestão.
           OP 5.3.2: Pressionar o botão esquerdo do mouse.
           
<font size="3"><p style="text-align: center">Fonte: [Luana Medeiros](https://github.com/LuaMedeiros).</p></font>

 ## Conclusão
 Ao analisar a funcionalidade "Grade Sugerida" usando uma abordagem hierárquica e aplicando o método GOMS, percebe-se uma estrutura de tarefas e interações. Esse método detalhado, ao decompor cada etapa em objetivos, procedimentos, métodos e regras, proporcionou uma compreensão aprofundada das atividades dos usuários, identificando áreas críticas que podem ser melhoradas para uma experiência mais intuitiva e eficiente.
 
## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). **Interação Humano-Computador e Experiência do Usuário**.

2. Carlos Mar, Msc. **Modelo GOMS – Análise de Tarefas**. Maio de 2014. Disponível em: <https://carlosmardotcomdotbr.wordpress.com/wp-content/uploads/2014/04/modelotarefasgoms.pdf>. Acessado em 01 de maio de 2024.


## Histórico de Versão
| Versão | Alteração                                   | Responsável    | Revisor         | Data       |
| ------ | ------------------------------------------- | -------------- | --------------- | ---------- |
| 1.0    | Criação do documento                        | Luana Medeiros | -               | 20/06/2024 |
