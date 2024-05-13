
# Princípios Gerais do Projeto

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Correspondências com as expectativas dos usuários](#Correspondências-com-as-expectativas-dos-usuários) 
    * [O que é expectativas?](#O-que-é-expectativas?)
    * [Como as expectativas são violadas no SIGAA](#Como-as-expectativas-são-violadas-no-SIGAA)
    * [Como as expectativas são aplicadas no SIGAA](#Como-as-expectativas-são-aplicadas-no-SIGAA)
    * [Como as expectativas serão utilizadas no projeto](#Como-as-expectativas-serão-utilizadas-no-projeto)
* [Antecipação das Necessidades do Usuário](#Antecipação-das-Necessidades-do-Usuário) 
    * [O que é Antecipação das Necessidades do Usuário?](#O-que-é-Antecipação-das-Necessidades-do-Usuário?)
    * [Como a antecipação é violada no SIGAA](#Como-a-antecipação-é-violada-no-SIGAA)
    * [Como a antecipação é aplicada no SIGAA](#Como-a-antecipação-é-aplicada-no-SIGAA)
    * [Como a antecipação será utilizada no projeto](#Como-a-antecipação-será-utilizada-no-projeto)
* [Visibilidade e reconhecimento](#Visibilidade-e-reconhecimento)
* [Equilíbrio entre controle e liberdade do usuário](#Equilibrio-entre-controle-e-liberdade-do-usuário)
* [Promoção da Eficiencia do Usuário](#Promoção-da-Eficiencia-do-Usuário)
* [Consistência e Padronização](#Consistência-e-Padronização)
* [Conteúdo Relavante e Expressão Adequada](#Conteúdo-Relavante-e-Expressão-Adequada)
* [Conclusão](#Conclusão)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

O SIGAA, como um sistema essencial para a gestão acadêmica, em seu aprimoramento, demanda uma abordagem centrada no usuário. Devido a isso, os princípios gerais que orientam este projeto são fundamentais para garantir que as funcionalidades do site atendam às expectativas e às necessidades dos usuários de forma eficaz e intuitiva. Assim, ao aplicar princípios como correspondência com as expectativas dos usuários e simplicidade nas estruturas das tarefas, será buscado criar uma experiência de uso que seja natural e fluida. Além disso, o equilíbrio entre controle e liberdade do usuário será essencial para garantir que os usuários se sintam capacitados ao utilizar o SIGAA.


Desse modo, esse documento tem o objetivo de fornecer uma visão abrangente sobre como cada um dos princípios gerais é retratado atualmente no site e como será aplicado nas funcionalidades do projeto. Com isso, ao detalhar as estratégias e as abordagens que serão adotadas para promover uma interação mais intuitiva, eficiente e satisfatória, é esperado se ter um guia de como desenvolver melhor cada tarefa.

## Metodologia

O grupo analisou o sistema SIGAA com o objetivo de identificar quais princípios gerais são priorizados. As análises foram conduzida utilizando através de reuniões e pesquisa em materiais acadêmicos. Assim foram identificados os princípios aplicáveis que poderiam ser melhor implementados ou que mais se adéquam ao contexto do sistema, levando em consideração o site em análise.

## Princípios Aplicáveis

## Correspondências com as expectativas dos usuários

### O que é expectativas?

O princípio de Correspondências com as Expectativas dos Usuários, conforme explicado no livro “Interação Humano-Computador e Experiência do Usuário”¹, refere-se à importância de projetar interfaces de usuário de forma que correspondam às expectativas naturais deles. Desse modo, isso implica em criar sistemas que permitam aos usuários entenderem facilmente os relacionamentos entre suas intenções, ações possíveis e os resultados dessas ações no sistema, ou seja, que seja intuitivo. Além disso, também é necessário ser fornecido um feedback informativo para os usuários, ao indicar que uma ação foi concluída com sucesso, o que ajuda a proporcionar uma sensação de satisfação e alívio.


### Como as expectativas são violadas no SIGAA


No contexto do SIGAA, é necessário que o site esteja alinhado com as expectativas dos usuários ao proporcionar uma navegação clara e uma utilização intuitiva. No entanto, ao analisar determinadas partes, é possível identificar que algumas funcionalidades violam esse princípio, apresentando desafios e dificuldades para os usuários.


Abaixo, há algumas funcionalidades que violam o princípio, os GIF de 1 até 7 mostram como elas estão no site, para visualizá-los, basta clicar nos triângulos:


<details>

<summary size="20"><b> Funcionalidade de ajuda </b></summary>

<div align="center">

GIF 1: Como funciona a funcionalidade de ajuda

![IHC_PG_AJUDA-GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/141f8e01-cca0-4caf-a3f6-48a7fbcad22b)

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

![IHC_PG_CALENDARIO_GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/e1f4dfba-ec56-4e34-b112-4f32d0909ca0)


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


![IHC_PG_EXTENSAO_GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/1d951cd4-206b-4c43-a220-a0cc9d623955)

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

![IHC_PG_MATRICULAS_GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/f2cd69f7-6626-4c56-8f75-70d9b921958b)

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

![IHC_PG_TAMANHOFONTE_GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/f8cc1afa-bfdc-4ca4-bbcf-f301f27f93e8)

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A função de aumentar ou diminuir o tamanho da fonte não está conforme a expectativa do usuário devido a vários fatores. Primeiramente, sua localização no canto superior da interface pode passar despercebida por muitos usuários, que geralmente esperam encontrar opções de formatação de texto em outras áreas. Além disso, o símbolo do ícone, representado por um "A+" e um "A-", pode não ser tão intuitivo quanto se espera. Embora possa ser associado à alteração de tamanho da fonte, para usuários com pouca experiência em informática, esse símbolo pode não ser imediatamente reconhecido como uma opção para ajustar o tamanho do texto e podem pensar que está ligado a outras funcionalidades.


</details>

### Como as expectativas são aplicadas no SIGAA


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

![IHC_PG_MATRICULAONLINE_GIMP](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/12b33062-cf47-4991-b295-eed78e01ce29)

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)

<br>

</div>


A localização da parte de fazer matrícula online corresponde às expectativas do usuário devido à sua colocação na aba de ensino. Assim como ocorre com a emissão de notas e histórico, os estudantes procuram naturalmente por funcionalidades relacionadas ao seu meio acadêmico na aba de ensino. Portanto, ao acessar essa aba, os usuários já esperam encontrar opções que facilitem suas atividades de estudo, como a realização da matrícula online.


</details>



### Como as expectativas serão utilizadas no projeto


Neste projeto de Análise de Interação Humano-Computador para o SIGAA, a equipe está focada em aprimorar a experiência do usuário através da refatoração de funcionalidades existentes e da implementação de novas ferramentas. Com isso, o objetivo é garantir que o sistema seja mais intuitivo e eficiente, correspondendo às expectativas dos usuários. Isso inclui melhorar a usabilidade das funcionalidades de matrícula, estágio e bolsas, além de introduzir novas ferramentas como monitoria, aluguel de sala, progressão de grade curricular e Restaurante Universitário.


Com base nisso, para aplicar o princípio de correspondência com a expectativa do usuário, as funcionalidades do projeto serão baseadas em:


- **Abordagem baseada na experiência do usuário**: As atividades serão projetadas com base em como os usuários realizariam essas tarefas pessoalmente. Isso significa que a interface do usuário será organizada para replicar os processos e fluxos de trabalhos vividos na prática.


- **Consideração da vivência dos usuários:** A elaboração será guiada pela compreensão das experiências e das necessidades dos usuários. Consequentemente, isso implica em uma análise aprofundada dos padrões de comportamento, preferências e desafios enfrentados pelos usuários durante a interação com o sistema.


- **Reformulação de nomenclaturas:** O nome de algumas abas ou funcionalidades será modificado para tornar as suas finalidades mais claras e compreensíveis para os usuários conforme os significados que eles esperam para cada termo.

- **Uso de ícones reconhecíveis:** Ícones serão selecionados com base em sua familiaridade e reconhecimento pelos usuários conforme o que eles estão acostumados e esperam deles.

## Simplicidade nas Estruturas das Tarefas

A simplicidade nas estruturas das tarefas se concentra em minimizar a complexidade das interações do usuário com o sistema. O objetivo é tornar as tarefas tão intuitivas quanto possível, reduzindo a sobrecarga e permitindo que os usuários se concentrem no que é mais importante, facilitando assim a execução e compreensão das tarefas.

O GIF 14 mostra a navegação no SIGAA.

![gif sigaa](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/140026699/416c052b-1e5c-415b-9510-75d81a08c715)


<details>

<summary size="20"><b>  Como o princípio é violado no SIGAA </b></summary>

<div align="center">

   No SIGAA, o princípio de simplicidade muitas vezes é violado devido à complexidade das interfaces e a quantidade de opções disponíveis. Como ilustrado nas imagens do sistema, os usuários se deparam com múltiplos menus e submenus que podem ser confusos e intimidadores, especialmente para novos usuários que ainda não estão familiarizados com a estrutura do sistema.

Figura 01: Botões iguais que cumprem a mesma função.

![6](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/140026699/520d3243-706c-4ad6-a772-15314f2d775f)

Fonte: [Bruno Araújo](https://github.com/brunocva)

Imagem 02: Ao utilizar o SIGAA com um smartphone, no modo WEB, algumas opções ficam 

![3](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/140026699/9cd10ea3-c0b1-4c33-9c1b-b27183b30410)

Fonte: [Bruno Araújo](https://github.com/brunocva)

</div> 
</details>

<details>

<summary size="20"><b>  Como o princípio é aplicado no SIGAA </b></summary>


</div> 
</details>

#### Como esse princípio será utilizado no projeto

No projeto de reformulação do SIGAA, vamos fortalecer a aplicação do princípio de simplicidade:
- **Reduzindo o número de passos necessários** para realizar algumas funções comuns, como inscrição em bolsas de estudo/acadêmica ou submissão de documentos.
- **Melhorando a navegação** através de uma interface mais limpa e intuitiva, onde opções menos utilizadas são agrupadas em menus secundários ou são acessíveis através de funcionalidades de busca aprimoradas.
- **Implementando designs responsivos** que se adaptam às necessidades do usuário, destacando as funcionalidades mais relevantes com base no contexto de uso.

Estas mudanças são projetadas para tornar o SIGAA mais acessível e menos desafiador para os usuários, garantindo uma experiência mais eficiente e agradável.

## Antecipação das Necessidades do Usuário


### O que é Antecipação das Necessidades do Usuário?


De acordo com o livro “Interação Humano-Computador e Experiência do Usuário”¹, o princípio de antecipação das necessidades do usuário preconiza que as aplicações devem ser proativas em fornecer informações e ferramentas, ou seja, devem ser previstas antes mesmo que o usuário as solicite explicitamente. Com isso, em vez de esperar que os usuários busquem ou coletem informações, o sistema deve antecipar suas necessidades e apresentar as informações relevantes de forma intuitiva e oportuna.

Além disso, o princípio de antecipação implica na capacidade do sistema em aprender com o usuário ao prever suas ações futuras para facilitar a interação. Consequentemente, isso inclui ajustar os valores padrões para melhor atender às necessidades do usuário em diferentes contextos. Em suma, visa oferecer uma experiência mais intuitiva e eficiente, antecipando e atendendo às necessidades do usuário de forma proativa.


### Como a antecipação é violada no SIGAA


No SIGAA, é possível observar algumas necessidades dos usuários não são atendidas no site, seja pela sua falta de implementação ou porque algumas implementadas não realizam tudo o que é necessário. Desse modo, os GIF 10 e 11 mostram algumas dessas situações, assim como as imagens 1, 2 e 3.


Para visualizar as situações, basta clicar nos triângulos:


<details>


<summary size="20"><b> Deficiência no SIGAA MOBILE: Impossibilidade de verificar presença </b></summary>


<div align="center">


GIF 10: Ausência da opção de verificar frequência no SIGAA MOBILE.

![antecipacao1](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/c2dc03c7-1df0-4d76-b5b7-3c454f14a470)

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)


<br>


</div>



A impossibilidade de verificar a frequência pelo SIGAA Mobile viola o princípio de **antecipação das necessidades do usuário** ao não antecipar a necessidade dos estudantes de acessarem informações importantes sobre sua frequência.


Assim, quando os alunos têm acesso ao SIGAA apenas pelo celular e precisam verificar a sua frequência, essa opção não apresenta as formas ou ferramentas de como ser acessada de forma explicita, o que torna a experiência do usuário desagradável.


</details>


<details>


<summary size="20"><b> Ausência da informação de localidade nas vagas de estágio. </b></summary>


<div align="center">


GIF 11: Ausência da informação de localidade nas vagas de estágio.

![antecipacao2](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/1dd7b90b-3bc4-4488-9c6b-c2725d16c2cc)

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)


<br>


</div>


A ausência da informação de localidade nas vagas de estágio no SIGAA viola o princípio de antecipação das necessidades do usuário, pois não fornece uma informação crucial quando os estudantes estão procurando por vagas, a localidade do estágio. Desse modo, ao não incluir a localização das vagas, o sistema deixa de antecipar a necessidade dos usuários de saber onde estão localizadas as oportunidades de estágio. Como resultado, os estudantes podem ter dificuldade em avaliar a conveniência das vagas em relação à sua localização geográfica, o que pode afetar suas decisões de candidatura.


</details>


<details>


<summary size="20"><b> Falta de informação sobre os tipos de mensagens e como inserir documentos nelas </b></summary>


<div align="center">


<div align="center">
    FImagem 1: Sem informação de como adicionar documentos.
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/antecipacao3.png">
    <br>
     Fonte: Larissa Stéfane
    <br>
</div>


<br>


</div>


A ausência de informações cruciais para enviar mensagens no SIGAA viola o princípio de antecipação das necessidades dos usuários, pois não fornece uma solução eficaz para uma necessidade comum dos estudantes em comunicação com a instituição. Por exemplo, muitos estudantes podem precisar enviar documentos ou mensagens para a coordenação, como atestados médicos para justificar ausências prolongadas. No entanto, o sistema não oferece orientações claras sobre como inserir documentos nas mensagens ou sobre a privacidade das comunicações. Como resultado, os usuários podem enfrentar dificuldades para realizar essa tarefa de maneira adequada.


</details>

<details>


<summary size="20"><b> Dificuldade em saber quais os dados corretos colocar no preenchimento de busca por bolsas </b></summary>


<div align="center">


GIF 13: Com quais informações completar?

![antecipacao4](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/141163236/46eee1e1-66a1-4ab3-beed-e1e8f95b8c36)

Fonte: [Larissa Stéfane](https://github.com/SkywalkerSupreme)


<br>


</div>


A ausência de explicações claras e informações adicionais para o preenchimento de dados viola o princípio de antecipação das necessidades dos usuários, pois não fornece uma solução eficaz para uma tarefa comum e frequente. Por exemplo, ao preencher o formulário de busca por bolsas ou inscrição em programas de monitoria, os estudantes podem enfrentar dificuldades em determinar quais informações precisam ser fornecidas e em que formato. Por exemplo, para identificar o orientador, pode haver dúvidas sobre se deve ser inserido apenas o primeiro e último nome, o nome completo com todos os nomes do meio ou o número da matrícula. Da mesma forma, para especificar a disciplina desejada, os estudantes podem ficar indecisos sobre se devem fornecer o código da disciplina, o nome completo ou se é necessário incluir a turma. Desse modo, a falta de orientações claras e informações adicionais torna o processo mais complexo e confuso para os usuários, indo de encontro à expectativa de antecipar e prover soluções que facilitem suas interações com o sistema.


</details>



### Como a antecipação é aplicada no SIGAA


Mesmo violando, em alguns pontos, o princípio de antecipação, o SIGAA também aplica esse princípio em várias outras funcionalidades, como é possível observar nas explicações abaixo. As imagens 5,6 e 7 mostram as funcionalidades implementadas no site.


<details>


<summary size="20"><b> Alterar dados pessoais </b></summary>


<div align="center">


<div align="center">
    Imagem 5: Alterar dados pessoais
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/docs/Midia/NovasFotos/antecipacao5.png">
    <br>
     Fonte: Larissa Stéfane
    <br>
</div>


<br>


</div>


A tarefa de alterar dados pessoais no sistema demonstra a aplicação do princípio de antecipação das necessidades dos usuários ao fornecer informações claras e orientações durante o processo. Isso porque, ao iniciar a alteração dos dados pessoais, o sistema apresenta de forma proativa os tipos de informações que o usuário pode modificar e antecipa as suas possíveis necessidades. Além disso, ao longo do processo, mensagens explicativas são exibidas em diversos pontos, fornecendo orientações adicionais sobre o preenchimento correto dos campos ou sobre quais dados são obrigatórios. Essas mensagens ajudam os usuários a compreenderem melhor o esperado deles em cada etapa, reduzindo a probabilidade de erros e tornando o processo mais intuitivo e eficiente.


</details>

## Como a antecipação será utilizada no projeto


No projeto, o princípio de antecipação das necessidades dos usuários será aplicado de várias maneiras para garantir uma experiência de usuário mais intuitiva e eficiente. Desse modo, ao refatorar e criar funcionalidades, serão considerados diversos tópicos para antecipar as necessidades dos usuários:


- **Análise do usuário**: Já foirealizada uma análise aprofundada do usuário-alvo, por meio do perfil dos usuários, para compreender suas necessidades, preferências e comportamentos ao utilizar o sistema.


- **Feedback dos usuários**: serão coletados feedbacks dos usuários em relação às funcionalidades para entender suas expectativas em relação ao sistema e identificar áreas onde as necessidades dos usuários não estão sendo atendidas ou são confusas.


- **Antecipação de ações:**: As funcionalidades serão projetadas para antecipar as ações dos usuários, oferecendo sugestões e orientações contextuais conforme necessário.


- **Informações claras e explicativas:** Serão fornecidas informações claras e explicativas em todo o sistema para orientar os usuários e ajudá-los a entender como realizar tarefas específicas.

## Visibilidade e reconhecimento
Antes de realizar qualquer ação, é importante que o usuário tenha uma compreensão prévia das opções disponíveis e das instruções para executá-las. Além disso, a interface deve fornecer informações de forma lógica e oportuna, de acordo com as necessidades do usuário.

### Aplicação
O site do SIGAA na página inicial após o login apresenta ícones que não seguem um padrão mas podem ser intuitivos e acompanham um título ou legenda identificando e reforçando qual é sua função, facilitando a navegação para os usuários. Isso é evidente na Figura 1, onde os ícones são consistentes com as tarefas que representam. A legenda identificando qual a função do ícone é evidente na Figura 2, na aba de Mural de Vagas de estágio.

<center>
  <font size="2"><p style="text-align: center">Figura 1: Aba SIGAA </p></font>
  <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/abasSIGAA.png">
 </center>

 <center>
  <font size="2"><p style="text-align: center">Figura 2: Icone Legendado </p></font>
  <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/IconeLegendado.jpeg">
 </center>

### Violação
No site SIGAA, após entrar em uma Turma Virtual de uma matéria os ícones de voltar para a página inicial, imprimir página e visualizar aulas paginadas não são intuitivos, são de tamanho disproporcional a página e não possuem nenhum título ou instrução que identifique qual seja a função. Isso é evidente na Figura 3, onde  é possível ver destacado os ícones que violam o princípio da Visibilidade e Reconhecimento. 

 <center>
  <font size="2"><p style="text-align: center">Figura 3: Icones de Violação </p></font>
  <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/TurmaVirtual.jpeg">
 </center>

## Equilíbrio entre controle e liberdade do usuário

O equilíbrio entre controle e liberdade do usuário refere-se a encontrar a medida certa de orientação fornecida ao usuário por um sistema ou interface, sem restringir excessivamente sua capacidade de agir de acordo com suas próprias preferências e necessidades. Isso implica em projetar interfaces que ofereçam suporte suficiente para ajudar os usuários a completar tarefas de forma eficiente e eficaz, ao mesmo tempo em que permitem flexibilidade e autonomia para que possam explorar e interagir com o sistema de maneiras que façam sentido para eles. Encontrar esse equilíbrio é crucial para garantir uma experiência de usuário positiva, onde os usuários se sintam capacitados e no controle, sem se sentirem sobrecarregados ou limitados pelas restrições do sistema.

### No SIGAA

A partir da análise da página inicial vista no GIF 1 e do sistema como um todo, podemos constatar que o SIGAA é um sistema bastante permissivo e sem qualquer instrução ou orientação para que o usuário se guie. Nesse cenário, os usuários têm liberdade para explorar e interagir com o SIGAA de acordo com suas próprias preferências e necessidades, sem restrições significativas impostas pelo sistema. No entanto, essa abordagem pode resultar em uma experiência de usuário que pode ser percebida como desorientadora ou confusa para alguns usuários, especialmente aqueles que podem precisar de mais orientação ou suporte para completar tarefas específicas. Enquanto a permissividade do sistema oferece aos usuários uma sensação de autonomia e controle, pode ser importante considerar a inclusão de recursos ou orientações adicionais para ajudar os usuários a navegar e utilizar o SIGAA de forma mais eficiente e eficaz. Vale ressaltar que não há um tutorial prévio para utilizar o sistema também no primeiro login do usuário.

## Consistência e Padronização

A consistência e padronização são elementos essenciais para o design eficaz de sistemas e interfaces. A consistência refere-se à aplicação uniforme de convenções de design, comportamentos e padrões em todo o sistema, garantindo que os elementos visuais e funcionais se comportem de maneira previsível e coerente. Por outro lado, a padronização envolve a adoção de diretrizes e normas de design reconhecidas e amplamente aceitas, promovendo uma experiência de usuário consistente e intuitiva.

### No SIGAA

Analisando as cores e os ícones de todo o sistema, podemos constatar que existe um padrão claro e que está aplicado a todas as partes do site. A seguir, podemos constatar pela página principal exibida na Imagem 6, que os ícones são bem representativos e que as mesmas cores estão presentes em todas as páginas.

<details>

<summary size="20"><b> Página principal do Sistema </b></summary>

<div align="center">

<div align="center">
    Imagem 6: Página principal SIGAA
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/PaginaInicial1.png">
    <br>
     Fonte: Pedro Augusto
    <br>
</div>

<br>

</div>

</details>

Outro ponto importante a destacar é que não apenas os ícones e as cores são padronizados, mas também os elementos do site, como os rótulos iniciais de "Ensino", "Pesquisa", "Extensão" e outros. Todos esses rótulos abrem suas respectivas opções em um menu suspenso "select", proporcionando uma consistência visual e funcional em todo o sistema. 
Quanto aos campos de texto e credenciais, observou-se uma falta de padronização na confirmação da matrícula, onde em alguns casos são solicitados a data de nascimento e senha do usuário, enquanto em outros momentos são requeridos o CPF e a senha. Infelizmente, não foi possível incluir uma imagem para ilustrar essa inconsistência, uma vez que a página de matrícula online está disponível apenas durante o período designado no calendário acadêmico.

## Promoção da Eficiencia do Usuário

A promoção da eficiência do usuário é um conceito fundamental em Interação Humano-Computador (IHC), que se concentra em projetar sistemas e interfaces de forma a permitir que os usuários realizem suas tarefas de maneira eficaz e eficiente. Isso envolve a criação de designs que minimizem a carga cognitiva do usuário, facilitando a localização de informações, a execução de ações e a conclusão de tarefas com rapidez e precisão.

### No SIGAA

Alguns recursos que promovem a eficiência a rapidez na navegação por parte do usuário estão presentes no sistema, como a presença de um sistema de diretórios clara, que permite o usuário se situar dentro das páginas do SIGAA, além de poder voltar em qualquer "diretório" anterior dentro da própria sem precisar utilizar várias vezes a opção voltar do navegador. A seguir podemos ver a presença desse recurso na Imagem 7:

<details>

<summary size="20"><b> Sistema de diretórios no SIGAA </b></summary>

<div align="center">

<div align="center">
    Imagem 7: Sistema de diretórios no SIGAA
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/DiretoriosSIGAA.png">
    <br>
     Fonte: Pedro Augusto
    <br>
</div>

<br>

</div>

</details>

Um outro recurso que melhora a eficiência da utilização pelo usuário é a presença de uma seção de "últimas atualizações" das disciplinas do usuário, que permite que o mesmo tenha acesso a todas as novas postagens de todas as matérias sem que precise acessar a página individual de cada uma, visto que levaria muito tempo. A seguir na Imagem 8:

<details>

<summary size="20"><b> Seção de "últimas atualizações </b></summary>

<div align="center">

<div align="center">
    Imagem 8: Seção de "últimas atualizações"
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/UltimasAtualizacoes.png">
    <br>
     Fonte: Pedro Augusto
    <br>
</div>

<br>

</div>

</details>

Apesar de haver alguns recursos que promovem a melhoria da eficiência do usuário, o sistema SIGAA carece de outros elemento que são comuns em sistemas universitários e até mesmo em geral, como a barra de pesquisa, que permite que o usuário busque por informações e serviços sem a necessidade de procurar rótulos ou em último caso, percorrer inteiramente o site.

## Conteúdo Relavante e Expressão Adequada

### O que é?

"Conteúdo relevante" refere-se ao material apresentado aos usuários que é significativo, útil e aplicável às suas necessidades, interesses ou objetivos. Esse conteúdo deve ser diretamente relacionado às tarefas que os usuários desejam realizar ou aos problemas que desejam resolver ao interagir com um sistema, aplicativo ou interface.

Por outro lado, "expressão adequada" diz respeito à forma como esse conteúdo é comunicado aos usuários. Envolve o uso de linguagem, tom, estilo e formato que são apropriados ao contexto e ao público-alvo. Uma expressão adequada leva em consideração as características dos usuários, como sua cultura, nível de educação, preferências linguísticas e até mesmo suas emoções.

Portanto, em resumo, conteúdo relevante e expressão adequada combinam-se para garantir que a informação fornecida aos usuários seja tanto útil quanto apresentada de uma forma que seja compreensível, atraente e relevante para eles.

### Como é aplicado no SIGAA

Apesar de alguns julgarem a interface como não-convidativa ou como ultrapassada, o SIGAA é um exemplo de como o conteúdo relevante é priorizado na experiência do usuário. Os recursos disponíveis no sistema estão diretamente relacionados às necessidades dos estudantes, professores e funcionários da instituição, como pode-se ver Gif 10. Desde funcionalidades para visualização de notas e grade curricular até a realização de matrículas e emissão de documentos acadêmicos, o SIGAA oferece uma gama abrangente de serviços que são essenciais para a comunidade acadêmica.


<div align="center">
GIF 14: Interface SIGAA

![Interface Sigaa ](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/interfaceCertoGif.gif?raw=true)

Fonte: [Iago Passaglia](https://github.com/paxxaglia)
</div>


Além disso, a expressão adequada é evidente na forma como o SIGAA apresenta informações de maneira clara e direta, mesmo dentro de uma interface visualmente mais datada. A linguagem utilizada é objetiva e informativa, facilitando a compreensão dos usuários, independentemente de seu nível de familiaridade com o sistema. Os menus são organizados de forma lógica e intuitiva, permitindo uma navegação eficiente, enquanto as instruções são fornecidas de maneira sucinta e compreensível.

### Como é violado no SIGAA

O uso de palavras menos comuns, como "discente" e "docente" (vide Figura 1), no SIGAA pode, em alguns casos, violar os princípios de conteúdo relevante e expressão adequada. Embora esses termos sejam familiares para os membros da comunidade acadêmica, como estudantes e professores, podem ser menos compreensíveis para usuários externos ou novatos na plataforma. 

<div align="center">
Imagem 9: Violação

![Discentes/Docentes - Sigaa](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/discentes.png?raw=true)

Fonte: [Iago Passaglia](https://github.com/paxxaglia)
</div>


A substituição desses termos por equivalentes mais simples, como "aluno" e "professor", poderia tornar a linguagem mais acessível e inclusiva para todos os usuários. Isso poderia evitar potenciais obstáculos à compreensão e melhorar a experiência do usuário, especialmente para aqueles menos familiarizados com o vocabulário acadêmico.


### Como será usado no projeto?

No projeto, a aplicação dos princípios de conteúdo relevante e expressão adequada é fundamental para garantir uma experiência positiva aos usuários. Isso será implementado das seguintes formas:

**Análise do público-alvo:** Será realizada uma análise detalhada do público-alvo do projeto, identificando suas necessidades, preferências e nível de familiaridade com o SIGAA.

**Adaptação da linguagem:** A linguagem utilizada no projeto será adaptada de acordo com o perfil do público-alvo. Isso incluirá evitar termos técnicos desnecessários e simplificar termos complexos sempre que possível.

**Relevância do conteúdo:** Todo o conteúdo apresentado no projeto será cuidadosamente selecionado para garantir sua relevância para os usuários. Isso incluirá informações essenciais e úteis que atendam às necessidades e objetivos dos usuários.

## Projeto para Erros
### Definição
Como tanto os usuários quanto os sistemas são propensos a erros, o sistema deve estar preparado para possíveis erros. Portanto, a configuração deve notificar o usuário sobre a ocorrência de um erro e fornecer instruções sobre como superar possíveis perdas ou ações indesejadas. Além disso, ações irreversíveis exigem confirmação constante do usuário.

### Violação
O site SIGAA possui métodos padrão de detecção de erros que, dependendo do tipo, podem até explicar o erro. Porém, na maior parte das vezes, o sistema não evita que os usuários cometam erros, principalmente porque os usuários do sistema têm muita liberdade nele, mas também porque o site tem um nível de poluição informacional muito alto, que pode ser visto no [Gif 14](#Como-é-aplicado-no-SIGAA), que representa a página inicial do site.

### Como será usado no projeto
Para reduzir a ocorrência de erros dos usuários, no projeto serão estudadas simplificações na interface, mensagens de erros claras e testes de usabilidade.

## Conclusão

Em conclusão, a análise dos princípios gerais no SIGAA resultou em uma compreensão abrangente das diretrizes essenciais que guiarão o desenvolvimento e aprimoramento deste sistema vital de gestão acadêmica. Além disso, aumentou a visão crítica que o grupo tem sobre o SIGAA, torando possível observar melhor os seus pontos fortes e fracos.


## Referências Bibliográficas
1. **BARBOSA**, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 11 de maio de 2024.

## Bibliografia
**NORMAN**, Don. The Psychology Of Everyday Things. Basic Books, New York, illustrated edition, 1988.

**VÁRIOS AUTORES**. Princípios Gerais. Repositório do Grupo Bilheteria Digital da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/principios/. Acesso em 11 de maio de 2024.


## Histórico de Versão
| Versão | Alteração                                                                            | Responsável     | Revisor        | Data       |
| ------ | ------------------------------------------------------------------------------------ | --------------- | -------------- | ---------- |
| 1.0    | Criação do documento                                                                 | Pedro Izarias   | Bruno Araújo   | 10/05/2024 |
| 1.1    | Adição da introdução                                                                 | Larissa Stéfane | Bruno Araújo   | 11/05/2024 |
| 1.2    | Adição do princípio Correspondências com as expectativas dos usuários                | Larissa Stéfane | Iago Passaglia | 11/05/2024 |
| 1.3    | Adição do Conteúdo Relavante e Expressão Adequada                                    | Iago Passaglia  | Bruno Araújo   | 11/05/2024 |
| 1.4    | Adição do princípio Antecipação das Necessidades do Usuário                          | Larissa Stéfane | Bruno Araújo   | 11/05/2024 |
| 1.5    | Adição da conclusão (Deve ser o último)                                              | Larissa Stéfane | Iago Passaglia | 11/05/2024 |
| 1.6    | Adição do projeto para erros                                                         | Breno Alexandre | Bruno Araújo   | 11/05/2024 |
| 1.7    | Adição da equilíbrio entre controle e liberdade do usuário                           | Pedro Izarias   | Bruno Araújo   | 11/05/2024 |
| 1.8    | Adição da consistência e padronização e promoção da eficiência do usuário no projeto | Pedro Izarias   | Bruno Araújo   | 12/05/2024 |
| 1.9    | Adição no projeto para erros                                                         | Breno Alexandre | Bruno Araújo              | 12/05/2024 |
| 2.0    | Correção de inconsistência                                                           | Larissa Stéfane | Bruno Araújo              | 12/05/2024 |
| 2.1    | Adição de Visibilidade e Reconhecimento no projeto                                   | Luana Medeiros  | Bruno Araújo              | 12/05/2024 |
| 2.2    | Adição do princípio da simplicidade                                   | Bruno Araújo  | -              | 12/05/2024 |
