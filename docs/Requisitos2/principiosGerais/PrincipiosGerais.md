
# Princípios Gerais do Projeto

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Correspondências com as expectativas dos usuários](#Correspondências-com-as-expectativas-dos-usuários) 
    * [O que é](#O-que-é)
    * [Como é violado no SIGAA](#Como-é-violado-no-SIGAA)
    * [Como é aplicado no SIGAA](#Como-é-aplicado-no-SIGAA)
    * [Como será utilizado no projeto](#Como-será-utilizado-no-projeto)
* [Equilíbrio entre controle e liberdade do usuário](#Equilibrio-entre-controle-e-liberdade-do-usuário)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

O SIGAA, como um sistema essencial para a gestão acadêmica, em seu aprimoramento, demanda uma abordagem centrada no usuário. Devido a isso, os princípios gerais que orientam este projeto são fundamentais para garantir que as funcionalidades do site atendam às expectativas e às necessidades dos usuários de forma eficaz e intuitiva. Assim, ao aplicar princípios como correspondência com as expectativas dos usuários e simplicidade nas estruturas das tarefas, será buscado criar uma experiência de uso que seja natural e fluida. Além disso, o equilíbrio entre controle e liberdade do usuário será essencial para garantir que os usuários se sintam capacitados ao utilizar o SIGAA.


Desse modo, esse documento tem o objetivo de fornecer uma visão abrangente sobre como cada um dos princípios gerais é retratado atualmente no site e como será aplicado nas funcionalidades do projeto. Com isso, ao detalhar as estratégias e as abordagens que serão adotadas para promover uma interação mais intuitiva, eficiente e satisfatória, é esperado se ter um guia de como desenvolver melhor cada tarefa.

## Metodologia


O grupo analisou o sistema SIGAA com o objetivo de identificar quais princípios gerais são priorizados. As análises foram conduzida utilizando através de reuniões e pesquisa em materiais acadêmicos. Assim foram identificados os princípios aplicáveis que poderiam ser melhor implementados ou que mais se adéquam ao contexto do sistema, levando em consideração o site em análise.

## Princípios Aplicáveis


### Simplicidade nas Estruturas das Tarefas

A simplicidade nas estruturas das tarefas é essencial para facilitar a interação do usuário com o sistema. Conforme Norman (1988) destaca, é recomendável simplificar a estrutura das tarefas para reduzir o planejamento e a resolução de problemas que elas exigem . Isso pode ser alcançado através de:

- Manutenção da tarefa com apoio tecnológico: Prover formas de apoio que auxiliem o usuário a aprender e realizar tarefas eficazmente.
- Visibilidade do processo da tarefa: Usar tecnologia para tornar processos invisíveis em visíveis, melhorando o feedback e controle do usuário.- 
- Automação de tarefas repetitivas: Automatizar tarefas ou partes delas para simplificar processos, mas com cautela para não remover o controle do usuário.

### Guia de Estilo - Elementos de Interação

#### Estilos de Interação

A escolha do estilo de interação adequado é crucial para a eficácia do sistema. Os estilos comuns incluem linguagens de comando, interação por menus, por formulários e manipulação direta . Cada estilo tem suas vantagens, e a escolha deve refletir as tarefas que o usuário necessita realizar e a familiaridade do usuário com o tipo de interação.

#### Seleção de um Estilo

Para o portal SIGAA da UNB, considerando que o público-alvo inclui estudantes e professores com diferentes níveis de habilidade tecnológica, um estilo de interação combinando menus e manipulação direta pode ser ideal. Isso permite acesso rápido às funções mais usadas e interação intuitiva com o sistema.

#### Aceleradores (Teclas de Atalho)

Aceleradores, como teclas de atalho, são essenciais para usuários frequentes que desejam eficiência e rapidez. Teclas de atalho para funções comuns como salvar (Ctrl+S) e imprimir (Ctrl+P) devem ser implementadas para acelerar a interação sem prejudicar a experiência dos usuários novatos .
Estas diretrizes baseiam-se nos princípios e técnicas de design de interação para criar uma experiência de usuário eficiente e agradável, mantendo um equilíbrio entre controle do usuário e liberdade dentro do sistema.

## Correspondências com as expectativas dos usuários


### O que é


O princípio de Correspondências com as Expectativas dos Usuários, conforme explicado no livro “Interação Humano-Computador e Experiência do Usuário”¹, refere-se à importância de projetar interfaces de usuário de forma que correspondam às expectativas naturais deles. Desse modo, isso implica em criar sistemas que permitam aos usuários entenderem facilmente os relacionamentos entre suas intenções, ações possíveis e os resultados dessas ações no sistema, ou seja, que seja intuitivo. Além disso, também é necessário ser fornecido um feedback informativo para os usuários, ao indicar que uma ação foi concluída com sucesso, o que ajuda a proporcionar uma sensação de satisfação e alívio.


### Como é violado no SIGAA


No contexto do SIGAA, é necessário que o site esteja alinhado com as expectativas dos usuários ao proporcionar uma navegação clara e uma utilização intuitiva. No entanto, ao analisar determinadas partes, é possível identificar que algumas funcionalidades violam esse princípio, apresentando desafios e dificuldades para os usuários.


Abaixo, há algumas funcionalidades que violam o princípio, os GIF de 1 até 7 mostram como elas estão no site:


<details>

<summary size="20"><b> Funcionalidade de ajuda </b></summary>


![IHC_PG_AJUDA-GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/141f8e01-cca0-4caf-a3f6-48a7fbcad22b)

<div align="center">

GIF 1: Como funciona a funcionalidade de ajuda

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A funcionalidade de ajuda no SIGAA não segue a correspondência com as expectativas do usuário devido à sua localização pouco evidente e à abordagem indireta para fornecer suporte. Isso porque, ao estar localizada no canto superior direito da página, fora do centro ou longe das abas de funcionalidades, os usuários podem não identificar facilmente a opção de ajuda. Além disso, ao acessar a ajuda, os usuários são redirecionados a um site com links e um desses links leva a uma página onde precisam navegar por uma série de manuais para encontrar a informação desejada. Consequentemente, isso é trabalhoso e confuso, já que a expectativa do usuário é obter uma resposta direta para sua dúvida, em vez de ter que ler vários documentos.


Desse modo, é possível observar que o pedido de ajuda pelo SIGAA é bem diferente de como o usuário está acostumado pessoalmente, onde o usuário perguntaria para alguém experiente sobre como fazer certa tarefa e, diretamente, teria uma resposta.

</details>

<details>

<summary size="20"><b> Procurar por um calendário acadêmico </b></summary>


<div align="center">

GIF 2: Encontrar o calendário acadêmico

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A busca pelo calendário acadêmico no SIGAA viola o princípio de correspondência com as expectativas do usuário, mesmo tendo duas formas de ser acessado. Na primeira abordagem, quando o usuário segue a lógica de que o calendário possa estar na aba de ensino, ele se depara com uma página repleta de informações sobre calendários de diversos semestres. Assim, a quantidade excessiva de dados pode facilmente sobrecarregar o usuário que inicialmente queria algo mais simples e dificulta a localização do que é desejado. Ao continuar e selecionar o semestre almejado, o usuário é redirecionado para um relatório que contém uma série de informações adicionais, muitas das quais podem não ser relevantes para a sua busca original, o que pode causar confusão e frustração, prejudicando a experiência.


O outro método de acessar o calendário acadêmico também não corresponde à expectativa, pois a localização da informação não está disposta de forma intuitiva. Isso porque a localização da opção de calendário acadêmico, uma informação geral da universidade, está entre informações pessoais, como dados institucionais e fotografia. Assim, essa localização pode dificultar o encontro, uma vez que está onde o usuário não esperaria encontrar. E é nessa opção que o usuário é levado para o link do site que contém a tabela do calendário acadêmico de forma objetiva e concisa.



</details>




<details>

<summary size="20"><b> Solicitar atendimento na DACES </b></summary>


<div align="center">

GIF 3: Atendimento para necessidades específicas

![IHC_PG_DACES](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/56655256-9df2-4ce3-93b3-a881e9702c3f)

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A funcionalidade de solicitar atendimento a DACES no SIGAA não está em correspondência com as expectativas do usuário devido à sua localização dentro da aba "Outros", juntamente com funcionalidades não relacionadas a ela, como turmas virtuais e coordenação do curso. Assim, isso contraria a expectativa natural do usuário de encontrar facilmente uma seção dedicada ao atendimento de necessidades especiais, onde possa encontrar serviços de forma direta e imediata.


Isso fica evidente ao se comparar como um estudante faria pessoalmente na secretaria. Ao entrar em contato com a secretaria, a primeira coisa que o estudante faria seria identificar claramente onde pode solicitar suporte relacionado a necessidades específicas. No entanto, no SIGAA, essa funcionalidade está inserida em uma seção genérica.


</details>

<details>

<summary size="20"><b> Organização da aba de extensão </b></summary>


<div align="center">

GIF 4: Organização da aba de extensão

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A aba de extensão no SIGAA viola a expectativa do usuário ao não priorizar as informações mais relevantes e frequentemente buscadas pelos estudantes. Isso porque, geralmente, quando um estudante acessa a aba de extensão, suas principais expectativas são de encontrar, primeiramente, opções para se inscrever em projetos de extensão ou acessar certificados de participação. No entanto, no SIGAA, essas opções são colocadas entre as últimas, o que contraria a lógica de priorização de informações conforme as necessidades dos usuários.



</details>


<details>

<summary size="20"><b> Localizar disciplina na matrícula </b></summary>


<div align="center">

GIF 5: Localizar disciplina na matrícula

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


Durante o processo de matrícula no SIGAA, o método de localização de disciplinas não corresponde às expectativas do usuário devido a alguns desafios significativos. Um ponto relevante é que, no início do processo, ele é solicitado a selecionar uma unidade para encontrar uma disciplina específica e aqui o usuário se depara com uma lista extensa de opções de unidades, o que pode ser confuso e sobrecarregar o usuário com escolhas. Além disso, há o problema adicional de o usuário muitas vezes não saber em qual unidade está localizada a disciplina que está procurando, o que aumenta ainda mais o desconforto.

Esse processo contrasta fortemente com a expectativa do usuário de uma busca simplificada e direta, como seria ao interagir pessoalmente com a secretaria, onde ele informaria a disciplina desejada e receberia informações claras sobre a unidade e as opções disponíveis.


</details>


<details>

<summary size="20"><b> Localizar extrato do RU </b></summary>


<div align="center">

GIF 6: Localizar extrato do RU

![IHC_PG_RU](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/4ca4b159-9804-450c-9e82-5baf452e5a7b)


Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A opção de acessar e verificar o extrato do saldo de crédito no Restaurante Universitário (RU) não corresponde às expectativas do usuário devido à sua localização inesperada e pouco intuitiva na interface do sistema. Geralmente, os usuários esperam encontrar informações relacionadas ao saldo de crédito do RU em uma área dedicada a serviços alimentares ou financeiros, em vez disso, estão localizadas com as informações pessoais acadêmicas. A posição do saldo está próxima à porcentagem de integralização acadêmica. Consequentemente, isso não reflete a experiência de vida do usuário, causando confusão e dificultando a localização da informação desejada.


</details>


<details>

<summary size="20"><b> Mudar o tamanho da fonte </b></summary>


<div align="center">

GIF 7: Mudar o tamanho da fonte

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A função de aumentar ou diminuir o tamanho da fonte não está conforme a expectativa do usuário devido a vários fatores. Primeiramente, sua localização no canto superior da interface pode passar despercebida por muitos usuários, que geralmente esperam encontrar opções de formatação de texto em outras áreas. Além disso, o símbolo do ícone, representado por um "A+" e um "A-", pode não ser tão intuitivo quanto se espera. Embora possa ser associado à alteração de tamanho da fonte, para usuários com pouca experiência em informática, esse símbolo pode não ser imediatamente reconhecido como uma opção para ajustar o tamanho do texto e podem pensar que está ligado a outras funcionalidades.


</details>

### Como é aplicado no SIGAA


Apesar de o SIGAA, em alguns pontos, não seguir a correspondência com a expectativa do usuário, em outros pontos e funções esse princípio é aplicado.


Abaixo, os GIF 8 e 9 apresentam algumas funcionalidades em que o princípio é aplicado:


<details>

<summary size="20"><b> Verificar notas e histórico </b></summary>

![IHC_PG_NOTAS](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/573b3435-72c1-4a23-9bc5-1ded862a3491)


<div align="center">

GIF 8: Verificar notas e histórico

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>



A parte de emitir notas e histórico no SIGAA está em correspondência com a expectativa do usuário devido à sua localização intuitiva e direta na interface do sistema. Assim, quando um estudante deseja acessar seu histórico acadêmico ou verificar suas notas, é natural que ele vá para a aba de ensino, pois essa é a área relacionada ao seu meio acadêmico e às suas atividades de estudo. Com isso, intuitivamente, o estudante já sabe que ela é o local apropriado para encontrar informações como notas e histórico.



</details>



<details>

<summary size="20"><b> Onde fazer a matrícula online? </b></summary>


<div align="center">

GIF 9 : Onde fazer a matrícula online

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A localização da parte de fazer matrícula online corresponde às expectativas do usuário devido à sua colocação na aba de ensino. Assim como ocorre com a emissão de notas e histórico, os estudantes procuram naturalmente por funcionalidades relacionadas ao seu meio acadêmico na aba de ensino. Portanto, ao acessar essa aba, os usuários já esperam encontrar opções que facilitem suas atividades de estudo, como a realização da matrícula online.


</details>



### Como será utilizado no projeto


Neste projeto de Análise de Interação Humano-Computador para o SIGAA, a equipe está focada em aprimorar a experiência do usuário através da refatoração de funcionalidades existentes e da implementação de novas ferramentas. Com isso, o objetivo é garantir que o sistema seja mais intuitivo e eficiente, correspondendo às expectativas dos usuários. Isso inclui melhorar a usabilidade das funcionalidades de matrícula, estágio e bolsas, além de introduzir novas ferramentas como monitoria, aluguel de sala, progressão de grade curricular e Restaurante Universitário.


Com base nisso, para aplicar o princípio de correspondência com a expectativa do usuário, as funcionalidades do projeto serão baseadas em:


- **Abordagem baseada na experiência do usuário**: As atividades serão projetadas com base em como os usuários realizariam essas tarefas pessoalmente. Isso significa que a interface do usuário será organizada para replicar os processos e fluxos de trabalhos vividos na prática.


- **Consideração da vivência dos usuários:** A elaboração será guiada pela compreensão das experiências e das necessidades dos usuários. Consequentemente, isso implica em uma análise aprofundada dos padrões de comportamento, preferências e desafios enfrentados pelos usuários durante a interação com o sistema.


- **Reformulação de nomenclaturas:** O nome de algumas abas ou funcionalidades será modificado para tornar as suas finalidades mais claras e compreensíveis para os usuários conforme os significados que eles esperam para cada termo.

- **Uso de ícones reconhecíveis:** Ícones serão selecionados com base em sua familiaridade e reconhecimento pelos usuários conforme o que eles estão acostumados e esperam deles.














## Equilíbrio entre controle e liberdade do usuário

O equilíbrio entre controle e liberdade do usuário refere-se a encontrar a medida certa de orientação fornecida ao usuário por um sistema ou interface, sem restringir excessivamente sua capacidade de agir de acordo com suas próprias preferências e necessidades. Isso implica em projetar interfaces que ofereçam suporte suficiente para ajudar os usuários a completar tarefas de forma eficiente e eficaz, ao mesmo tempo em que permitem flexibilidade e autonomia para que possam explorar e interagir com o sistema de maneiras que façam sentido para eles. Encontrar esse equilíbrio é crucial para garantir uma experiência de usuário positiva, onde os usuários se sintam capacitados e no controle, sem se sentirem sobrecarregados ou limitados pelas restrições do sistema.

### No SIGAA

## Conclusão

## Referências Bibliográficas
1. 


## Histórico de Versão
| Versão | Alteração | Responsável | Revisor | Data |
| - | - | - | - | - |
| 1.0 | Criação do documento | Pedro Izarias | Bruno Araújo | 10/05/2024 |
| 1.1 | Adição da introdução | Larissa Stéfane | Bruno Araújo | 11/05/2024 |
