# Guia de Estilo do projeto

## Sumário
* [Introdução](#Introdução)
* [Introdução do guia de estilo](#Introdução-do-guia-de-estilo)
     *  [Objetivo do Guia de estilo](#Objetivo-do-Guia-de-estilo)
     *  [Organização e Conteúdo do Guia de Estilo](#Organização-e-Conteúdo-do-Guia-de-Estilo)
     *  [Público-Alvo do Guia de Estilos](#Público-Alvo-do-Guia-de-Estilos)
     *  [Como Utilizar o Guia](#Como-Utilizar-o-Guia)
     *  [Como Manter o Guia](#Como-Manter-o-Guia)
* [Resultados de análise](#Resultados-de-análise) 
* [O que é expectativas?](#O-que-é-expectativas?)
* [Descrição do ambiente de trabalho do usuário](#Descrição-do-ambiente-de-trabalho-do-usuário)
* [Elementos de interface](#Elementos-de-interface)
* [Elementos de interação](#Elementos-de-interação)
* [Elementos de ação](#Definir-elementos-de-ação) 
* [Vocabulário e padrões](#Vocabulário-e-padrões)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

O guia de estilo apresentado neste documento serve como um recurso fundamental para orientar o design de interface no projeto de análise do SIGAA. Sendo assim, concebido como um registro das principais decisões de design adotadas, este guia visa garantir a consistência, a eficácia e a usabilidade do projeto. Com isso, ao abordar aspectos como layout, tipografia, simbolismo, cores, visualização de informação e design de elementos de interface, o guia busca oferecer diretrizes claras e detalhadas para a equipe.

##  Introdução do guia de estilo

### Objetivo do Guia de Estilo:

Este guia de estilo do SIGAA tem como objetivo principal fornecer diretrizes claras para o design de interface, com o intuito de melhorar a usabilidade, a consistência e a eficácia do sistema. Além disso, esse guia busca abordar os problemas identificados nas avaliações por heurística e nas entrevistas, questionários e brainstorm realizados com os usuários.

Para isso, ele abordará os seguintes elementos e pontos:

#### Layout

- Proporção e grids;
- Metáforas espaciais;
- Design gráfico de exibidores e ferramentas.

#### Tipografia
- Uso de diferentes tipos de fonte em diálogos, formulários e relatórios.

#### Simbolismo 

- Clareza e consistência no design de ícones.

#### Cores

- Utilização adequada das cores para garantir acessibilidade e estética.

#### Elementos de interface

- Design de botões, menus, campos de entrada e outros widgets.

#### Usabilidade

- Análise dos problemas identificados nas avaliações por heurística e nos requisitos elicitados pelos usuários.

- Identificação de soluções para melhorar a experiência do usuário em áreas como controle do sistema, prevenção de erros e ajuda/documentação.

### Organização e Conteúdo do Guia de Estilo

Esse guia de estilo está estruturado em seções que abrangem diferentes aspectos do design de interface citados anteriormente. Sendo assim, cada seção oferece diretrizes específicas, exemplos ilustrativos e justificativas baseadas nas avaliações por heurística e nos requisitos dos usuários, garantindo, assim, uma abordagem metódica.

###  Público-Alvo do Guia de Estilos
O público-alvo destina-se tanto aos integrantes do grupo que estão desenvolvendo este projeto quanto a equipe responsável por desenvolver e realizar a manutenção do SIGAA. Dentre os principais destinatários estão:
#### Programadores
Os programadores utilizam o guia de estilo como referência durante o processo de implementação do design de interface. Então, eles precisam seguir as diretrizes estabelecidas para garantir a consistência visual e funcional do sistema.

#### Designers
Os designers de interface criam e atualizam o guia de estilo. Desse modo, eles são responsáveis por elaborar as diretrizes de design, incluindo layout, tipografia, cores e elementos de interface, alinhadas com as necessidades dos usuários e os requisitos do sistema. Por isso este guia é importante para eles.

#### Gerentes de Projeto
Os gerentes de projeto utilizam o guia de estilo para garantir a conformidade com os padrões estabelecidos durante todas as fases do projeto. 

### Como Utilizar o Guia
#### Em produção 
Durante a fase de produção, os integrantes do grupo, atuando como desenvolvedores e designers, devem consultar o guia de estilo para garantir a implementação consistente das diretrizes de design definidas aqui. Além disso, a equipe deve utilizar o guia como referência para resolver problemas de usabilidade identificados durante as técnicas de elicitação de informações realizadas com os usuários.

#### Em manutenção 
Durante a manutenção do SIGAA, esse guia de estilo deve ser utilizado para avaliar e atualizar as interfaces existentes, levando em consideração feedback dos usuários e novas tendências de design. Além disso, ele também deve ser utilizado como guia referência para responder a perguntas dos usuários e solucionar problemas de usabilidade de forma consistente.

### Como Manter o Guia
As formas de manter esse guia atualizado são:
- Estabelecer um processo de revisão regular para garantir a relevância contínua do guia de estilo.
-  Monitorar mudanças no sistema, coletar feedback dos usuários e propor atualizações para o guia.
- Documentar todas as alterações feitas no guia para garantir transparência e rastreabilidade ao longo do tempo.

## Resultados de análise

De acordo com as repostas obtidas nos [questionários](https://interacao-humano-computador.github.io/2024.1-SIGAA/#/PerfilUsuario/Estudantes/Questionarios/An%C3%A1liseResultados), podemos traçar o ambiente de trabalho do usuário e identificar as propriedades seguintes:
-Sistema operacional: de acordo com a análise do questionário, constatou-se que 7% dos entrevistados utilizam o sistema iOS da Apple, 34% utilizam o Android e 50% utilizam sistemas operacionais desktop, incluindo principalmente o Windows, o Mac OS e diversas distribuições Linux, como Ubuntu, ArchLinux ou Debian. Diante dessas estatísticas, é crucial que o sistema em questão seja completamente compatível com todos, ou pelo menos a maioria, dos sistemas operacionais utilizados pelos usuários do SIGAA.
- Tamanho e resolução da tela: com base nos resultados do questionário, observa-se que a maioria dos entrevistados utiliza diferentes tipos de dispositivos para acessar o SIGAA. Cerca de 20% prefere o computador desktop, com telas geralmente de 1920x1080px e entre 21 e 27 polegadas. Outros 30% preferem o uso do notebook, com resolução semelhante à dos desktops, mas com telas menores, de 13 a 15 polegadas. Por fim, aproximadamente 47% dos entrevistados optam por smartphones ou tablets, com tamanhos de tela variando de 5 a 6,5 polegadas para smartphones e de 7 a 12 polegadas para tablets. Diante dessa diversidade de dispositivos, é crucial ajustar o design do site para garantir uma experiência de usuário consistente e otimizada, independentemente do dispositivo utilizado.
- Dispositivos e acessórios: dado que 20% dos usuários acessam o sistema por meio de desktops, é importante considerar os acessórios que serão utilizados para as tarefas no SIGAA. Nesse contexto, o mouse é o acessório mais comum, juntamente com um teclado externo. Outros 30% preferem laptops e notebooks, equipados principalmente com trackpads integrados, que oferecem uma experiência de uso diferente do mouse. Por fim, os restantes 50% utilizam smartphones e tablets, onde os sensores touchscreen são predominantes, proporcionando uma experiência distinta em relação aos acessórios anteriores. Portanto, o sistema deve ser projetado levando em conta essas diferentes formas de interação, garantindo que todos os recursos do site sejam acessíveis, independentemente do periférico ou acessório utilizado.
- Ambiente de uso: outro fator importante a ser considerado é a variedade de contextos e locais nos quais o sistema será utilizado. Devido a essa diversidade, duas características são fundamentais para o sistema. Primeiramente, a segurança é essencial, uma vez que o sistema precisa proteger os dados dos usuários contra acessos não autorizados, mantendo a integridade e a confidencialidade das informações. Em segundo lugar, a consistência do sistema é crucial, pois será utilizado em diferentes tipos de conexões de internet, algumas mais estáveis do que outras. Portanto, é necessário garantir um desempenho consistente em diferentes condições de rede e velocidades de conexão, proporcionando uma experiência de usuário fluida e sem interrupções.

Com base nas informações obtidas, o guia de estilo deve incluir diretrizes abrangentes que abordem todas as questões levantadas e assegurem a padronização de todos os elementos do site que possam influenciar a usabilidade e a experiência do usuário do SIGAA.

## Vocabulário e padrões

### Terminologia:

Gerenciar a consistência terminológica é uma responsabilidade crucial do designer, pois influencia diretamente na experiência do usuário. Ao avaliar a terminologia utilizada, é importante considerar tanto a uniformidade quanto a diversidade, visando uma interação coesa e acessível. Durante o desenvolvimento do projeto, é fundamental equilibrar o uso de linguagem técnica e termos familiares aos usuários, visando aprimorar a intuitividade do sistema.

### Tipos de tela:

As diferentes telas projetadas devem aderir aos padrões delineados no guia de estilo, levando em conta o conteúdo específico de cada página. O guia de estilo oferece orientações para três tipos de tela: a inicial, a informativa e as demais. É essencial seguir os padrões estabelecidos para os elementos de interface, interação e ação conforme indicado no Figma.

### Sequências de diálogos

Ao planejar as sequências de diálogos, é necessário integrar feedbacks e confirmações após a execução de uma operação. Garantir que o usuário receba retorno adequado sobre o status das ações realizadas é prioritário. Este feedback pode ser fornecido de diversas maneiras, como mensagens de conclusão bem-sucedida ou alertas em caso de erros, os quais devem ser claramente indicados na interface.

## Elementos de Interface

Os elementos sobre disposição espacial e grid, janelas, tipografia, símbolos não tipográficos, cores e animações são apresentados na figura 1.

Figura 1 - Elementos da Interface.
<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fdesign%2F3V51JoJoglQBIBh8VR67vQ%2FIHC%252FSIGAA---Elementos-da-Interface%3Fnode-id%3D0%253A1%26t%3DtceCGlbnz1DNj2wo-1" allowfullscreen></iframe>

**Fonte:** [Breno Alexandre](https://github.com/brenoalexandre0).

## Bibliografia

VÁRIOS AUTORES. Guia de Estilo. Repositório do BCB da disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: https://interacao-humano-computador.github.io/2023.1-BancoCentral/#/analise_requisitos/guia_estilo. Acesso em 12 de maio de 2024.


**FIGMA**. Disponível em: <https://www.figma.com>. 2016. Acesso em: 11 mai. 2024.

## Histórico de Versão

| Versão | Alteração                                | Responsável     | Revisor         | Data       |
| ------ | ---------------------------------------- | --------------- | --------------- | ---------- |
| 1.0    | Criação do documento                     | Larissa Stéfane | Breno Alexandre | 11/05/2024 |
| 1.1    | Adição dos tópicos da introdução do guia | Larissa Stéfane | Breno Alexandre | 11/05/2024 |
| 1.2    | Adição dos Elementos de Interface        | Breno Alexandre | Bruno Araújo    | 11/05/2024 |
| 1.3    | Adição do Vocabulário e Padrões          | Iago Passaglia  |      Larissa Stéfane       | 12/05/2024 |
