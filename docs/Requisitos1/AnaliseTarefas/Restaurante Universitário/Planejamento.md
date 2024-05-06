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
um assunto discutido foi a necessidade de se ter uma funcionalidade destinada aos assuntos do Restaurante Universitário, uma vez que ela quase não está presente no SIGAA. 
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

Deste modo, este documento tem o intuito de realizar um planejamento da análise das tarefas envolvidas no processo de consulta de saldo, recarga de crédito, consulta de cardápio da semana
e pesquisa de satisfação do DRU na perspectiva do estudante ao se utilizar o SIGAA.

Com base nisso, para criar a área de gerenciamento da conta no RU, será necessário garantir a eficiência e eficácia na usabilidade do sistema. 
Por isso, a análise de tarefas adotada nesta fase segue uma abordagem hierárquica, conhecida como Análise Hierárquica de Tarefas (HTA), que permite uma representação sistemática das atividades 
em etapas menores e mais gerenciáveis. Com isso, ao decompor as metas dos estudantes em submetas e tarefas específicas, será possível identificar os pontos de entrada no sistema, as operações 
realizadas pelos usuários e os resultados esperados, algo que será apresentado nos documentos da execução da análise.

Além disso, a análise de tarefas para as funcionalidades presentes na aba do RU será conduzida utilizando o método GOMS (Goals, Operators, Methods, e Selection Rules). 
Esse método é uma abordagem de avaliação de usabilidade que se concentra na compreensão de como os usuários interagem com um sistema para atingir seus objetivos. 
Com isso, o "Goals" (objetivos) referem-se aos resultados desejados pelos usuários, "Operators" (operadores) são ações mentais e físicas realizadas para alcançar esses objetivos, 
"Methods" (métodos) são as sequências de operadores necessárias para concluir uma tarefa e "Selection Rules" (regras de seleção) determinam como os usuários escolhem entre métodos alternativos. 
Ao aplicar o método GOMS, é possível identificar pontos de otimização e simplificação nas tarefas de gerenciamento da conta no RU.

## A Funcionalidade de Gerenciamento da conta no Restaurante Universitário
A aba de gerenciamento da conta no RU no sistema do SIGAA será concebida com o objetivo de agilizar os processos de consulta do saldo e do cárdapio, além deixar mais prático o ato de recarga.

Essa aba terá quatro funcionalidades principais, que incluem:

- Consultar o saldo atual.
- Fazer recarga.
- Consultar o cardápio da semana.
- Pesquisa de satisfação do DRU.

## Metodologia

Para analisar o processo das funcionalidades de gerenciamento da conta no RU na perspectiva do estudante, inicialmente, será realizada uma análise e uma compreensão dos objetivos gerais do usuário ao utilizar essas funcionalidades. Assim, esses objetivos serão divididos em subobjetivos mais específicos, que serão então relacionados com as operações concretas que o estudante precisará realizar no SIGAA. Essas operações serão mostradas contextualmente.

Em seguida, para ser contextualizado dentro do fluxo de interação, será elaborado um diagrama, uma vez que ele fornecerá uma visão geral do processo, destacando as inter-relações entre as diferentes tarefas e ajudando a identificar possíveis gargalos ou lacunas no fluxo. Após a elaboração do diagrama, será elaborada uma tabela detalhando cada tarefa conforme o “input”, “feedback”, “plano” e “recomendação”.

Após a realização da análise hierárquica, será realizada a análise por meio do GOMS para as atividades. Para isso, será mais uma vez revisado o escopo da tarefa com os seus objetivos, então serão definidos os seus métodos e operações. Com isso, este processo visa garantir uma análise mais precisa das tarefas.

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
O planejamento da execução da análise hierárquica de tarefas e da GOMS para a aba de gerenciamento da conta no RU apresenta uma estrutura sólida e abrangente para o desenvolvimento e aprimoramento desta funcionalidade que será criada no sistema do SIGAA.

## Bibliografia

Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. pgs. 177-187.

Projeto BCE. Disponível em: <https://interacao-humano-computador.github.io/2020.1-BCE/#/pages/ponto_de_controle_2/analise_tarefas>. Acesso em 06 de maio de 2024.

Projeto do Banco Central do Brasil. Disponível em: <https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/analise_tarefas>. Acesso em 06 de maio de 2024.
   
Projeto Domínio Público. Disponível em: <https://interacao-humano-computador.github.io/2023.2-Dominio-Publico/analise_de_requisitos/analise_de_tarefas/goms/>. Acesso em 06 de maio de 2024.
   
Projeto Lichess. Disponívem em: <https://interacao-humano-computador.github.io/2022.2-Lichess/analise_requisitos/analise_tarefas/>. Acesso em 06 de maio de 2024.

## Histórico de Versão
| Versão | Alteração                         | Responsável     | Revisor | Data       |
| ------ | --------------------------------- | --------------- | ------- | ---------- |
| 1.0    | Criação e realização do documento | Breno Alexandre | -       | 06/05/2024 |
