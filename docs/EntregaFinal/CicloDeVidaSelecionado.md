# Processo de Design

## Sumário 
* [Introdução](#Introdução)
* [Sobre o estudo](#Sobre-o-estudo)
* [Modelos](#Modelos)
* [Da metodologia](#Da-metodologia)
* [Análise de Requisitos](#Análise-de-Requisitos)
* [Design, Avaliação e Desenvolvimento](#Design-Avaliação-e-Desenvolvimento)
* [Instalação](#Instalação)
* [Motivos para a escolha](#Motivos-para-a-escolha) 
* [Bibliografia](#Bibliografia)
* [Histórico de versões](#Histórico-de-versões)

## Introdução

O processo de design é um conjunto de atividades metodológicas e sistemáticas focadas em criar e melhorar a interação entre usuários e sistemas computacionais, tendo como objetivo desenvolver produtos que sejam não apenas funcionais e eficientes, mas também acessíveis, fáceis de usar e proporcionem experiências positivas aos usuários. Este processo envolve compreender profundamente as necessidades, comportamentos e contextos dos usuários, para então traduzir esses insights em soluções de design inovadoras e eficazes.

## Sobre o estudo

O estudo foi orientado pelo livro de Barbosa e Silva (2010). Segundo os autores, o processo de design pode ser dividido em três atividades básicas:

1. **Análise da Situação Atual:** É o estudo e interpretação da situação atual na qual o sistema será inserido, isso inclui compreender as necessidades, características e restrições dos usuários, bem como identificar problemas e oportunidades de melhoria.
2. **Síntese de uma Intervenção:** Nesta etapa, é planejado e executada uma intervenção no sistema para melhorar a interação entre os usuários e o computador. Isso pode envolver a criação de protótipos, o desenvolvimento de novas funcionalidades ou a reformulação de aspectos existentes do sistema.
3. **Avaliação da Nova Situação:** Por fim, realizar uma avaliação para verificar o impacto da intervenção realizada, comparando a situação anterior à intervenção com a nova situação. Isso permite aos designers avaliar se as mudanças implementadas alcançaram os objetivos desejados e atenderam às necessidades dos usuários de forma satisfatória.

## Modelos

### Ciclo de vida simples:
É uma abordagem de desenvolvimento de sistemas interativos que segue uma sequência linear e bem definida de fases, geralmente composta por análise, design, implementação e avaliação. Proposto por Preece, Sharp e Rogers, essa abordagem é chamada de "simples" porque segue uma estrutura sequencial, na qual cada fase é completada antes de passar para a próxima. 

Em um ciclo de vida simples, como podemos ver na Figura 1, a análise inicial é realizada para compreender os requisitos do usuário e as necessidades do sistema. Em seguida, o design é elaborado com base nessas informações, criando interfaces e funcionalidades que atendam aos objetivos estabelecidos. Após o design, a implementação ocorre, na qual o sistema é desenvolvido de acordo com as especificações do design. Finalmente, a avaliação é conduzida para verificar se o sistema atende aos requisitos e expectativas do usuário, identificando possíveis melhorias e ajustes.

  <font size="2"><p>Figura 1: Ciclo de vida simples</p></font>
  <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/Simples.png">
  <font size="2"><p>Fonte: [SlidePlayer](https://slideplayer.com.br/slide/13462698/).</p></font>

### Ciclo de vida em Estrela:
No ciclo de vida em Estrela,como podemos ver na Figura 2, segundo Barbosa (2010, p. 104), o designer pode optar por onde começar a implementação. 
Este modelo segue uma abordagem iterativa e flexível, sem uma sequência fixa de atividades, semelhante ao modelo genérico de design de interação humano-computador. De acordo com Barbosa (2010), a única condição é que, após a conclusão de cada atividade, o designer avalie os resultados para garantir sua adequação. As diferentes etapas do ciclo de vida em Estrela estão conectadas pela avaliação; para progredir de uma atividade para outra, é fundamental passar por esse processo de avaliação.


  <font size="2"><p>Figura 2: Ciclo de vida em estrela</p></font>
  <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/Estrela.png">
  <font size="2"><p  ">Fonte: [SlidePlayer](https://slideplayer.com.br/slide/13462698/).</p></font>


### Engenharia de Usabilidade de Nielsen:
De acordo com as palavras de Nielsen (1993), a engenharia de usabilidade compreende uma série de atividades que se desenrolam ao longo de todo o ciclo de vida do produto, embora muitas delas ocorram mesmo antes do projeto da interface com o usuário ser elaborado. Barbosa (2010, p. 104) menciona que Nielsen apresenta o seguinte conjunto de atividades em seu ciclo de vida:

- Conheça seu usuário
- Realize uma análise competitiva
- Defina as metas de usabilidade
- Faça designs paralelos
- Adote o design participativo
- Faça o design coordenado da interface como um todo
- Aplique diretrizes e análise heurística
- Faça protótipos
- Realize testes empíricos
- Pratique design iterativo

<font size="2"><p>Fonte: BARBOSA e SILVA, 2011, p.105.</p></font>

## Da metodologia

Foi escolhido como método a engenharia de usabilidade proposta por Deborah Mayhew, cujo objetivo visa melhorar a experiência do usuário ao interagir com produtos digitais, garantindo que sejam fáceis de aprender, eficientes de usar, e que satisfaçam suas necessidades e expectativas. Se trata de uma abordagem sistemática para o desenvolvimento de interfaces de usuário com foco na usabilidade e é dividido em três fases principais:

### Análise de Requisitos

Esta fase envolve a compreensão profunda dos usuários, suas necessidades, objetivos e o contexto de uso do sistema. Inclui atividades como:
- Análise de tarefas
- Definição de perfis dos usuários (personas)
- A estipulação de metas de usabilidade objetivas e mensuráveis

### Design, Avaliação e Desenvolvimento

Nesta fase, o foco é no design da interface do usuário, considerando os requisitos levantados anteriormente. Envolve:
- Criação de protótipos de design em diferentes níveis de fidelidade, desde esboços iniciais até protótipos interativos
- Avaliação de cada protótipo em termos de usabilidade, que pode incluir testes com usuários, avaliação heurística por especialistas e outros métodos de avaliação de usabilidade
- Utilização do feedback dessas avaliações para refinar o design

### Instalação

A última fase do ciclo de vida abrange a implementação final do sistema e a sua entrega aos usuários. Inclui:
- Avaliação pós-implementação, que coleta feedback dos usuários reais para identificar áreas para melhorias futuras ou para informar o desenvolvimento de novos sistemas

A Engenharia de Usabilidade de Mayhew destaca a importância de um processo iterativo e centrado no usuário, onde a avaliação contínua e o refinamento do design são fundamentais para atingir altos níveis de usabilidade. Essa abordagem ajuda a garantir que os produtos finais sejam não apenas funcionais, mas também intuitivos, eficientes e agradáveis de usar.

<font size="2"><p>Figura 3: Ciclo de Mayhew.</p></font>
![Ciclo de Mayhew](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/assets/109971590/92f6c7a8-26f8-440a-81db-9957343fd000)
  <font size="2"><p>Fonte: [SlidePlayer](https://slideplayer.com.br/slide/13462698/).</p></font>

## Motivos para a escolha

O método de Mayhew é adequado para a avaliação de sistemas complexos, como o SIGAA, pois como demonstra a Figura 3 o método oferece uma abordagem estruturada que abrange desde a análise de requisitos até a instalação e avaliação pós-implementação.
Utilizando o framework DECIDE em conjunto com o método de Mayhew, é possível realizar uma avaliação detalhada que identifica não apenas os problemas de usabilidade, mas também fornece insights para melhorias contínuas no sistema.

## Bibliografia


## Histórico de versões

| Versão | Alteração                     | Responsável    | Revisor        | Data       |
|--------|-------------------------------|----------------|----------------|------------|
| 1.0    | Criação do documento          | Pedro Izarias | Iago Passaglia | 06/07/2024 |

