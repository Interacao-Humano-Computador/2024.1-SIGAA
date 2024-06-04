# Relato dos Resultados da Avaliação da Análise de Tarefas


## Sumário

* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Entrevistas Executadas](#Entrevistas-Executadas)
* [Apresentação dos Usuários](#Apresentação-dos-Usuários)
* [Problemas Encontrados e Soluções](#Problemas-Encontrados-e-Soluções)
* [Feedback dos Usuários](#Feedback-dos-Usuários)
* [Correção das análises de Tarefas](#Correção-dos-Storyboards)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de Versão](#Histórico-de-Versão)


## Introdução


Após a realização das entrevistas para a avaliação da análise das tarefas, um conjunto de observações pôde ser pontuado, como é possível visualizar na [execução das entrevistas](DesignAvaliaçãoDesenvolvimento/Nível1/Entrevistas_Avaliacao/Execucao_Entrevistas.md). Desse modo, este documento apresenta os resultados obtidos durante esse processo e oferece uma análise detalhada das percepções dos participantes. Assim, através desses relatos, é possível identificar os principais pontos de destaque, bem como as áreas que requerem melhorias ou ajustes.


## Metodologia


A metodologia adotada para a análise dos resultados das avaliações das análises de tarefas é orientada pelos objetivos estabelecidos no [planejamento da avaliação por meio do framework DECIDE](DesignAvaliaçãoDesenvolvimento/Nível1/AnáliseTarefas/PlanejamentoAvaliaçãoAnáliseTarefas.md), que se baseia na opinião do usuário em relação à facilidade de uso e na lógica do fluxo das tarefas. Dessa maneira, inicialmente, os dados coletados durante as entrevistas serão organizados e categorizados em tabelas conforme os temas definidos. Em seguida, as análises de tarefas serão reformuladas com base nos feedbacks recebidos e nas observações dadas na [execução das entrevistas](DesignAvaliaçãoDesenvolvimento/Nível1/Entrevistas_Avaliacao/Execucao_Entrevistas.md). Com isso, essa análise da avaliação tem o objetivo de facilitar a elaboração de melhorias.


## Entrevistas Executadas

Como foi definido no planejamento, o método utilizado foi a inspeção por meio de entrevista e de questionários com os usuários. Desse modo, a tabela 1 mostra o cronograma executado das entrevistas realizadas.

<center> 

**Tabela 1:** Cronograma executado das entrevistas.

| Entrevistadores(s) | Entrevistado(s) | Horário de Início | Horário de Fim | Data | Local |
| ------------------ | ------------------ | ----------------- | -------------- | -------- | ----- |
| Larissa Stéfane | João Pedro Garcia | 13:10 | 13:40 | 23/05/2024 | FGA-UnB- Sala S8 |
| Larissa Stéfane | Leonardo Machado | 12:30 | 13:10 | 28/05/2024 | FGA-UnB- Sala S9 |
| Pedro Izarias | Erika Iwakiri | 15:00 | 15:40 | 02/06/2024 | Casa |
| Iago Passaglia | Ana Caroline Porto | 13:00 | 13:30 | 31/05/2024 | Casa do entrevistador |
| Breno Alexandre | Limírio Correia | 18:58 | 19:37 | 03/06/2024 | Plataforma Teams |

**Autores:** [Larissa Stéfane](https://github.com/SkywalkerSupreme), [Iago Passaglia](https://github.com/Paxxaglia), [Breno Alexandre](https://github.com/brenoalexandre0).
.
</center>

### Apresentação dos Usuários

Durante as entrevistas para avaliar as análises de tarefas, foram escolhidos participantes que refletissem o perfil dos usuários. Desse modo, cada participante foi selecionado com base em critérios relacionados ao contexto do sistema acadêmico, como seu nível de familiaridade com softwares acadêmicos e a frequência com que utiliza tecnologias semelhantes. Com isso, a tabela 2 mostra os participantes, a funcionalidade trabalhada e uma breve descrição do perfil deles.


<center> 
  
**Tabela 2:** Perfil dos entrevistados.

| Entrevistadores(s) | Entrevistado(s) | Perfil | Funcionalidade |
| ------------------ | ------------------ | ----------------- | -------- |
| Larissa Stéfane | João Pedro Garcia | <li> Estudante de engenharia aeroespacial na FGA-UnB no oitavo semestre. <br> <li> É do gênero masculino e tem 25 anos. <br> <li> Utiliza computadores e dispositivos móveis com frequência. <br> <li> Seu nível de habilidade com tecnologia é médio. <br> <li> Sua familiaridade com uso de sistemas acadêmicos é médio/baixo.| Aluguel de Sala |
| Larissa Stéfane | Leonardo Machado |  <li> Estudante de engenharia de software na FGA-UnB no sétimo semestre. <br> <li> É do gênero masculino e tem 21 anos. <br> <li> Utiliza computadores e dispositivos móveis diariamente. <br> <li> Seu nível de habilidade com tecnologia é alto. <br> <li> Sua familiaridade com o uso de sistemas acadêmicos é alta devido à frequência e tempo de uso. | Aba de monitoria |
| Pedro Izarias | Erika Iwakiri |  <li> Estudante de  de Letras - Tradução Inglês do Departamento de Linguas Estrangeiras e Tradução da UnB. <br> <li> É do gênero Feminino e tem 22 anos. <br> <li> Utiliza computadores e dispositivos móveis diariamente. <br> <li> Seu nível de habilidade com tecnologia é alto. <br> <li> Sua familiaridade com o uso de sistemas acadêmicos é alta devido à frequência e tempo de uso. | Realizar Matrícula |
| Iago Passaglia | Ana Caroline Porto | <li> Estudante de nutrição do quinto semestre. <br> <li>  É do gênero feminino e tem 20 anos. <br> <li>  Utiliza computadores e dispositivos móveis diariamente. <br> <li>  Seu nível de habilidade com tecnologia é médio. <br> <li>  Sua familiaridade com uso de sistemas acadêmicos é boa/alta.| Pré-cadastro de estágio |
| Breno Alexandre | Limírio Correia| <li> Estudante de Engenharia de Software. <br> <li>  É do gênero masculino e tem 22 anos. <br> <li>  Utiliza computadores e dispositivos móveis diariamente. <br> <li>  Seu nível de habilidade com tecnologia é alto. <br> <li>  Sua familiaridade com uso de sistemas acadêmicos é alta. |
| Bruno Araújo | Marcella Cristina| <li> Estudante de Engenharia de engenharia aeroespacial. <br> <li>  É do gênero feminino e tem 23 anos. <br> <li>  Utiliza computadores e dispositivos móveis diariamente. <br> <li>  Seu nível de habilidade com tecnologia é mediano. <br> <li>  Sua familiaridade com uso de sistemas acadêmicos é mediano. |

**Autores:** [Larissa Stéfane](https://github.com/SkywalkerSupreme), [Iago Passaglia](https://github.com/Paxxaglia), [Breno Alexandre](https://github.com/brenoalexandre0), [Bruno Araújo](https://github.com/brunocva).


</center>

## Problemas Encontrados e Soluções

Durante a análise dos resultados das entrevistas, diversos problemas foram identificados em relação às interações representadas nas análises de tarefas. Neste contexto, entre os principais desafios encontrados pelos usuários estão dificuldades de compreensão em determinadas etapas das tarefas, inconsistências no fluxo apresentado e as dificuldades na realização de algumas atividades específicas. No entanto, para cada problema identificado, foram propostas soluções adequadas visando melhorar a usabilidade e a eficiência do sistema. Estas soluções incluem ajustes e reformulação da análise das tarefas. Com base nisso, a tabela 3 mostra os problemas e soluções encontradas para as funcionalidades avaliadas.


<center>
  
**Tabela 3:** Problemas Encontrados e as suas Soluções

| Funcionalidade | Problema Encontrado | Descrição | Solução Proposta |
| ------------------- | --------- | ---------- | ------- |
| Aluguel de Sala |  <li> Formato de como o horário será representado e como será apresentado o formulário | O usuário relatou que permitir ao usuário escolher o horário de forma discursiva pode trazer problemas devido à falta de organização provocada por horários quebrados, por exemplo, 13:33. <br> <li> O usuário acredita que o formulário pode ser simplificado, pois a pessoa entra na sua conta, então, qualquer tarefa que ela realizar já vai ter os seus dados vinculados automaticamente. O ideal só para colher informações sobre o motivo do aluguel |  <li> Fazer o usuário selecionar os horários em tabelas já definidas, por exemplo, estrutura do heatmap. <br> <li> O formulário passa a ser apenas uma pergunta: “Qual o motivo para o aluguel” |
| Aba de monitoria |  <li> A definição do local da turma de modo mais intuitivo e com complexidade elevada e desnecessária nos meios de comunicação entre monitores e estudantes. |  <li> Para selecionar uma turma, pode ser complexo definir o local dela, uma vez que algumas não são definidas por endereços, mas sim por unidades. <br> <li> O monitor e os estudantes podem ficar confusos sobre qual meio de comunicação utilizar e alguns podem acabar não sendo utilizados e ficarem defasados. |  <li> Seguir o mesmo caminho/estrutura que a realização de matrículas. <br> <li> Retirar a opção de comunicação exclusiva pelo SIGAA e permitir ao monitor ter liberdade para escolher as opções de como se comunicar com os estudantes. |
| Realizar Matrícula |  <li> A relação entre os objetivos que compõem o diagrama não faz sentido. |  <li> Relação entre as tarefas está incorreta <br> <li> Os símbolos das relações entre as tarefas não condiz com o sistema, por exemplo na parte de escolher turmas a serem feiras e adicionar turmas selecionadas, o símbolo deve ser 1>2 e não 1+2, pois podem ser realizadas de maneira independente. |  <br> <li> Colocar os símbolos corretos para cada relação entre tarefas. |
| Pré=cadastro de estágio | Integração completa | A entrevistada alega que o preenchimento do formulário por parte da empresa poderia ser efetuado dentro do sistema | Preparar o HTA para representar a nova funcionalidade |
| Aba de RU | <li> A tarefa de Recarga de Créditos foi considerada muito extensa para leitura | <li>Muitos passos e opções existentes | Resumir e diminuir a quantidade de tarefas |
| Aba de RU | <li> Na tarefa de Recarga de Créditos, os itens 3.1 e 3.1.1 parecem redundantes na visão do usuário | <li>Parecem a mesma tarefa | Fundir as duas em uma |
| Aba de RU | <li> Considerou a tarefa de Pesquisa de Satisfação desnecessária pro sistema | <li>Pois apenas a empresa responsável pelo restaurante devia se preocupar com isso. | Remover funcionalidade |
| Aba de RU | <li> Na tarefa de Recarga de Créditos, dentro da opção de PIX como pagamento, o item 1.3.1.1 foi considerado redundante na visão dele. | <li>Pois a tarefa anterior fala sobre a mesma coisa  | Remover tarefa |
| Aba de RU | <li> Na tarefa de Recarga de Créditos, dentro da opção de PIX como pagamento, poderia ter uma opção de copiar a chave PIX. | <li>Para ter mais uma opção de pagamento dentro da opção de PIX | Adicionar tarefa |
| Declaração de bolsa |  <li> Poucas funcionalidades | O usuário relatou que algumas informações não parecem ser necessárias |  Ter funcionalidade direta |

**Autores:** [Larissa Stéfane](https://github.com/SkywalkerSupreme), [Iago Passaglia](https://github.com/Paxxaglia), [Breno Alexandre](https://github.com/brenoalexandre0), [Bruno Araújo](https://github.com/brunocva)

</center>


## Feedback dos Usuários

Ao analisarem a análise de tarefas, os participantes puderam expressar as suas opiniões conforme as respostas e observações dadas. Sendo assim, a tabela 4 mostra os feedbacks dos usuários segundo a funcionalidade.

**Tabela 4:** Feedback por funcionalidade

| Funcionalidade | A análise foi fácil ou difícil de seguir? | A sequência/ fluxo fez sentido? | As tarefas apresentadas foram coerentes? | Existem etapas desnecessárias ou confusas no fluxo das tarefas? |
| ------- | - | ---------- | ---- | --- | 
| Aluguel de Sala | Ele achou a análise de tarefas bem tranquila e com um fluxo fácil de ser entendido. | Ele acredita que a sequência das tarefas faz sentido e em uma ordem correta e esperada. | Ele falou que sim, pois o formato das tarefas para utilizar a funcionalidade segue a mesma dinâmica que os outros sistemas acadêmicos que ele utiliza. | Não, ele acredita que está bem coerente com o que é esperado. |
| Aba de monitoria | Uma parte que ele achou complicada foi em monitorar monitoria em relação à área de definir comunicação. Para ele, seria ideal tirar a parte de comunicar diretamente com outros estudantes e professores pelo SIGAA, pois isso pode deixar o monitor e os estudantes confusos em relação a qual meio de comunicação utilizar. | Para ele, a sequência fez sentido. | Sim, ele acha que as tarefas e o fluxo estão conforme o que ele está acostumado. | Sim, em relação ao formato de comunicação. |
| Realizar matrícula | Para a entrevistada, a análise foi fácil de seguir, apesar do problema com os símbolos de relação entre os objetivos. | Para ela, a sequência fez sentido. | Sim, ela concorda com as tarefas relacionadas a funcionalidade. | Sim, os símbolos de relação entre os objetivos está incorreto, deixando o diagrama da funcionalidade confuso. |
| Pré-cadastro de estágio | Para a entrevistada, foi fácil seguir os passos | Para ela, a sequência fez sentido. | Sim, a entrevistada acredita que o fluxo das atividades estão de forma coerente. | Não foram apontadas nenhuma parte desnecessária ou confusa. |
| Aba do RU | Sim, com exceção da tarefa de Recarga de Créditos, por ser muito extensa. | Achou bem coerente no geral. | Foram coerentes na visão dele. | Nada além do que foi dito anteriormente. |

**Autores:** [Larissa Stéfane](https://github.com/SkywalkerSupreme), [Iago Passaglia](https://github.com/Paxxaglia), [Breno Alexandre](https://github.com/brenoalexandre0), [Bruno Araújo](https://github.com/brunocva).


## Correção das análises de Tarefas


Após as sugestões de melhorias e com os feedbacks, foi possível reformular e melhorar as análises de tarefas. Essas novas versões podem ser visualizadas abaixo.


<details>

<summary size="20"><b> Aluguel de Sala - Reformulado </b></summary>


<div align="center">

FIgura 1: Reformulação do Aluguel de Sala

<br>

<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/storyboard/avaliacaoStoryAnalise/analiseTarefas_AluguelSala02.png">

<br>

Autora: Larissa Stéfane

<br>

</div>


</details>


<details>

<summary size="20"><b> Aba monitoria - Reformulado </b></summary>


<div align="center">

Figura 2: Reformulação da Aba de monitoria

<br>

<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/storyboard/avaliacaoStoryAnalise/analiseTarefas_Monitoria02.png">

<br>

Autora: Larissa Stéfane

<br>

</div>


</details>

<details>

<summary size="20"><b> Realizar Matrícula - Reformulado </b></summary>


<div align="center">

Figura 3: Reformulação da funcionalidade de Realizar Matrícula

<br>

<img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/storyboard/avaliacaoStoryAnalise/HTAMatriculaNovo.png">

<br>

Autor: Pedro Izarias

<br>

</div>


</details>


<details>

<summary size="20"><b> Pré-cadastro de estágio - Reformulado </b></summary>


<div align="center">

FIgura 4: Reformulação do Pré-cadastro de estágio

<br>

<img src="https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/HTA%20ESTAGIO.png?raw=true">

<br>

Autor: Iago Passaglia

<br>

</div>


</details>


## Referências Bibliográficas

1. Barbosa, S. D. J., & Silva, B. S. (2021). **Interação Humano-Computador e Experiência do Usuário**. Editora: Câmara Brasileira do Livro, SP, Brasil.

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |
| ------ | --------------------------------- | --------------- | --------------- | ---------- |
| 1.0 | Elaboração do documento | Larissa Stéfane | Bruno Araújo | 02/06/2024 |
| 1.1 | Adição dos resultados da análise de tarefas do aluguel de sala e da aba de monitoria. | Larissa Stéfane | Bruno Araújo | 02/06/2024 |
| 1.2 | Adição dos resultados da análise de tarefas da realização de matrícula | Pedro Izarias | Iago Passaglia | 03/06/2024 |
| 1.3 | Adição dos resultados da análise de pré-cadastro de estágio. | Iago Passaglia | - | 02/06/2024 |
| 1.4 | Adição dos resultados da análise aba do RU. | Breno Alexandre | Bruno Araújo | 03/06/2024 |
| 1.5 | Adição dos resultados da análise aba Declaração de Bolsa. | Bruno Araújo| - | 03/06/2024 |
