# Planejamento Análise Hierárquica de Tarefas para a aba do Restaurante Universitário
## Sumário
* [Introdução](#Introdução)
* [A Funcionalidade de Gerenciamento da conta no Restaurante Universitário](#A-Funcionalidade-de-Gerenciamento-da-conta-no-Restaurante-Universitário)
* [Metodologia](#Metodologia)
* [Cronograma](#Cronograma)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução
Durante as entrevistas com os estudantes e a entrevista de [brainstorm](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/docs/IdentificacaoNecessidadesUsuario/ExecBrainstorm.md), 
foi também debatido a necessidade de se ter uma funcionalidade sobre o Restaurante Universitário, pois ela quase não está presente no SIGAA. 
Dá no máximo para ver o extrato no RU dos últimos sete dias. A imagem 1 mostra que não há o RU na aba de funcionalidades:

<div align="center">
    Imagem 1: Abas de algumas funcionalidades (Não há o RU).
    <br>
    <img src="https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/abasSIGAA.png">
    <br>
     Fonte: Breno Alexandre
    <br>
</div>

##  

A imagem 2 mostra que até há a possibilidade de consulta de extrato no RU.

<div align="center">
    Imagem 2: Extrato do RU.
    <br>
    <img src="https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/extratoRU.jpeg">
    <br>
     Fonte: Breno Alexandre
    <br>
</div>

##  

Este documento visa planejar a análise das tarefas que compõem o processo de verificação de saldo, recarga de créditos, visualização do cardápio semanal e realização de pesquisas de satisfação do DRU, tudo sob a ótica do estudante que utiliza o SIGAA.

Para estabelecer a seção de gerenciamento de contas no RU, é essencial assegurar que o sistema seja tanto eficiente quanto eficaz em termos de usabilidade. Neste contexto, a análise de tarefas emprega uma metodologia hierárquica, a Análise Hierárquica de Tarefas (HTA), que facilita a representação ordenada das atividades em fases mais simples e controláveis. Ao fragmentar os objetivos dos estudantes em subobjetivos e tarefas detalhadas, é possível mapear os pontos de interação com o sistema, as ações dos usuários e os resultados almejados, detalhes que serão elucidados nos documentos de análise.

Adicionalmente, a avaliação das tarefas associadas às funcionalidades da seção do RU será feita por meio do método GOMS (Goals, Operators, Methods e Selection Rules). Esta técnica de avaliação de usabilidade foca em entender como os usuários navegam pelo sistema para alcançar suas metas. Assim, “Goals” (Metas) dizem respeito aos resultados que os usuários pretendem obter, “Operators” (Operadores) são as ações mentais e físicas executadas para atingir essas metas, “Methods” (Métodos) são as sequências de operadores necessárias para completar uma tarefa e “Selection Rules” (Regras de Seleção) guiam os usuários na escolha entre diferentes métodos disponíveis. A implementação do método GOMS permite identificar áreas para otimização e simplificação no gerenciamento de contas do RU.

## A Funcionalidade de Gerenciamento da conta no Restaurante Universitário
A aba de gerenciamento da conta no RU no sistema do SIGAA será concebida com o objetivo de agilizar os processos de consulta do saldo e do cárdapio, além deixar mais prático o ato de recarga.

Essa aba terá quatro funcionalidades principais, que incluem:

- Consultar o saldo atual.
- Fazer recarga.
- Consultar o cardápio da semana.
- Pesquisa de satisfação do DRU.

## Metodologia
Para avaliar o processo das funcionalidades de administração de contas no RU do ponto de vista do aluno, começaremos por entender e decompor os objetivos gerais dos usuários ao empregar essas funções. Estes serão então segmentados em subobjetivos mais detalhados, que se alinharão com as ações específicas que os alunos devem executar no SIGAA, apresentadas de forma contextual.

Posteriormente, um diagrama será desenvolvido para se integrar ao fluxo de interação, oferecendo um panorama do processo e evidenciando as conexões entre as diversas tarefas, além de auxiliar na identificação de possíveis pontos críticos ou deficiências no fluxo. Com o diagrama pronto, uma tabela será criada para detalhar cada tarefa, incluindo “input”, “feedback”, “plano” e “recomendação”.

Concluída a análise hierárquica, passaremos à análise GOMS das atividades. Isso envolverá uma nova revisão do escopo da tarefa e seus objetivos, seguida pela definição de métodos e operações. Esse procedimento tem como meta assegurar uma avaliação mais exata das tarefas.


## Cronograma
A tabela 1 mostra o cronograma da análise de cada uma das funcionalidades:

Tabela 1: Cronograma.

| Atividade                                                                | Data de início | Data de fim |
| ------------------------------------------------------------------------ | -------------- | ----------- |
| Elicitar requisitos por meio de entrevistas e brainstorming              | 20/04/2024     | 01/05/2024  |
| Definir objetivos de cada funcionalidade                                 | 06/05/2024     | 06/05/2024  |
| Planejar como cada funcionalidade deve funcionar                         | 06/05/2024     | 06/05/2024  |
| Executar análise hierárquica da funcionalidade de consulta do saldo      | 06/05/2024     | 06/05/2024  |
| Executar análise GOMS da funcionalidade de consulta do saldo             | 06/05/2024     | 06/05/2024  |
| Executar análise hierárquica da funcionalidade de recarga                | 06/05/2024     | 06/05/2024  |
| Executar análise GOMS da funcionalidade de recarga                       | 06/05/2024     | 06/05/2024  |
| Executar análise hierárquica da funcionalidade de consulta do cardápio   | 06/05/2024     | 06/05/2024  |
| Executar análise GOMS da funcionalidade de consulta do cardápio          | 06/05/2024     | 06/05/2024  |
| Executar análise hierárquica da funcionalidade da pesquisa de satisfação | 06/05/2024     | 06/05/2024  |
| Executar análise GOMS da funcionalidade da pesquisa de satisfação        | 06/05/2024     | 06/05/2024  |

Fonte: [Breno Alexandre](https://github.com/brenoalexandre0)

## Conclusão
A estruturação do plano para realizar a análise hierárquica de tarefas e a metodologia GOMS na seção de gerenciamento de contas do RU constitui uma base robusta e completa, que orientará o desenvolvimento e o refinamento dessa nova funcionalidade no sistema SIGAA.

## Bibliografia

Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. pgs. 177-187.

Projeto BCE. Disponível em: <https://interacao-humano-computador.github.io/2020.1-BCE/#/pages/ponto_de_controle_2/analise_tarefas>. Acesso em 06 de maio de 2024.

Projeto do Banco Central do Brasil. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/analise_tarefas>. Acesso em 06 de maio de 2024.
   
Projeto Domínio Público. Disponível em: <https://interacao-humano-computador.github.io/2023.2-Dominio-Publico/analise_de_requisitos/analise_de_tarefas/goms/>. Acesso em 06 de maio de 2024.
   
Projeto Lichess. Disponívem em: <https://interacao-humano-computador.github.io/2022.2-Lichess/analise_requisitos/analise_tarefas/>. Acesso em 06 de maio de 2024.

## Histórico de Versão
| Versão | Alteração                         | Responsável     | Revisor          | Data       |
| ------ | --------------------------------- | --------------- | ---------------- | ---------- |
| 1.0    | Criação e realização do documento | Breno Alexandre | Larissa Stéfane  | 06/05/2024 |
