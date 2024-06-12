# Verificação dos Cenários

## Sumário
* [Introdução](#Introdução)
* [Metodologia](#Metodologia)
* [Lista de Verificação](#Lista-de-Verificação)
* [Inspeção](#Inspeção)
* [Conclusão e Observações](#Conclusão-e-Observações)
* [Referências Bibliográficas](#Referências-Bibliográficas)
* [Histórico de versão](#Histórico-de-versão)


## Introdução

Este documento tem como objetivo apresentar a verificação e a avaliação, por parte do grupo 2, dos cenários elaborados no projeto dos Correios desenvolvido pelo grupo 3. Desse modo, para garantir a conformidade dos cenários com os padrões estabelecidos, foi criada uma lista de verificação baseada em referências acadêmicas e práticas na área de engenharia de requisitos. Com isso, esta lista de verificação será utilizada para revisar detalhadamente cada cenário, assegurando que todos os elementos essenciais estejam presentes e adequadamente descritos.

## Metodologia

Inicialmente, a integrante [Larissa Stéfane](https://github.com/SkywalkerSupreme) será responsável por elaborar a lista de verificações, que servirá como base para a análise dos cenários do projeto dos Correios. Em seguida, outro  integrante da equipe ficará responsável por avaliar ao menos um cenário específico do projeto dos Correios utilizando a lista de verificação elaborada. Durante a avaliação, os integrantes documentarão suas observações.

## Lista de Verificação

A tabela 1 apresenta a lista de verificação com base em pontos citados em livros e artigos.

Esses livros e artigos podem ser acessados por meio dos links na coluna **Rastreabilidade**.

<center>

**Tabela 1:** Lista de verificação para os cenários


| ID | Pergunta da Verificação | Explicação | Rastreabilidade | Captura de Tela | 
|----|------------------------|-----------------------|-----------------| - |
| 1  | O título do cenário representa explicitamente o tema? | É necessário que o título do cenário seja descritivo e forneça uma ideia clara do conteúdo do cenário. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) | - |
| 2  | O objetivo do cenário está claramente definido? | Certificar-se de que os objetivos que motivam as ações realizadas pelos atores estão definidos na descrição do cenário. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf)  e Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172 | - |
| 3  | O contexto do cenário está bem descrito, incluindo pré-condições, local e tempo? | Verificar se o contexto do cenário fornece informações suficientes sobre a situação, as pré-condições, o local e o tempo. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) | - |
| 4  | Os recursos envolvidos no cenário estão identificados? | Os recursos, ou seja, os objetos com os quais  os atores lidam precisam estar identificados. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) | - |
| 5  | Os atores envolvidos no cenário estão definidos? | Verificar se os atores, ou seja, as pessoas ou estruturas organizacionais que têm um papel no cenário, estão identificados de acordo com a sua característica principal. Por exemplo, Cidadão usuário do aplicativo dos correios. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) e Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172| - |
| 6  | Os episódios do cenário estão bem definidos? | Certificar-se de que cada episódio do cenário representa uma ação realizada por um ator, incluindo outros atores envolvidos e os recursos utilizados, ou seja, mostra o passo a passo para o cenário se concretizar. | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) | - |
| 7 | As ações dos atores estão descritas de forma observável? | Certificar-se de que as ações dos atores são descritas de forma clara e sequêncial para o contexto do cenário, assim, não há nenhuma falta de algum passo.  | Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172 | - |
| 8  | As restrições e as exceções dos episódios estão explicitadas? | É necessário que as restrições e as  exceções que afetam os episódios do cenário estejam explicitadas e detalhadas | [Cenários - PUC-Rio](https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) | - |
| 9  | O ambiente ou contexto do cenário está detalhado? | Verificar se os detalhes do ambiente ou do contexto que motivam ou explicam os objetivos, as ações e as reações dos atores do cenário estão descritos. | Interação Humano-Computador e Expectativas dos Usuários – Capítulo 8, página 172| - |
| 10 | O cenário está escrito em linguagem natural simples? | Verificar se o cenário está escrito em linguagem natural simples,  ou seja, se a compreensão por parte dos leitores é fluida e não confusa. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) |
| 11 | Há a descrição do que o sistema e os usuários esperam quando o cenário se finalizar ?| É necessário ter a explicação do que acontece no final do cenário | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) | - |
| 12 | As possíveis falhas e as suas tratativas estão descritas? | Verificar se as possíveis falhas que podem ocorrer durante o cenário e as suas tratativas estão descritas na narrativa. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) | - |
| 13 | As informações sobre acontecimentos que podem ocorrer durante o cenário estão incluídas? | Verificar se acontecimentos que podem acontecer durante os episódios do cenário estão incluídos na descrição do cenário. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) | - |
| 14 | Há uma descrição sobre o estado inicial e o final do contexto no cenário? | Certificar-se de que o estado inicial e final estejam descritos. | [Retraining: Requirements Engineering](https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios) | - |
| 15 | Os requisitos presentes estão descritos no cenário? | Verificar se os requisitos ou as funcionalidades e os serviços esperados do sistema estão descritos e com rastreabilidade no projeto. | [Uso de cenários para especificação de requisitos de qualidade e avaliação de arquitetura](https://www.devmedia.com.br/uso-de-cenarios-para-especificacao-de-requisitos-de-qualidade-e-avaliacao-de-arquitetura/22528) | - |


<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>
## Inspeção

<center>

Tabela 2: Identificação do artefato avaliado
 
| Entrega | Nome | Versão | Data de desenvolvimento | Autor(es) | Revisor |
| ------- | ---- | ------ | ----------------------- | --------- | ------- |
| ------- | ---- | ------ | ----------------------- | --------- | ------- |

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

<center>

Tabela 3: Inspeção do questionário

| ID |  Pergunta | Resposta <br> Sim/Não/ Incompleto/ Não se aplica | Observação | 
| -- | ----------| ---------- | --------------- | 
| -- | ----------| ---------- | --------------- | 
| -- | ----------| ---------- | --------------- | 
| -- | ----------| ---------- | --------------- | 

<b> Autora: </b> <a href="https://github.com/SkywalkerSupreme">Larissa Stéfane</a>.

</center>

## Conclusão e Observações


## Referências Bibliográficas

1. Cenários. PUC-RIO. Disponível em: <https://www-di.inf.puc-rio.br/~julio/bnncap3.pdf> . Acesso em 09 junnho de 2024.

2. Cenários. Retraining: Requirements Engineering. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-cenarios> . Acesso em 09 junnho de 2024.

3. Interação Humano-Computador e Experiência do Usuário. Simone Diniz Junqueira Barbosa edição de 03 de maio de 2021.

4. Uso de cenários para especificação de requisitos de qualidade e avaliação de arquitetura. DevMedia. Disponível em: <https://www.devmedia.com.br/uso-de-cenarios-para-especificacao-de-requisitos-de-qualidade-e-avaliacao-de-arquitetura/22528> . Acesso em 09 junnho de 2024.

5. VAZQUEZ, Carlos Eduardo; SIMÕES, Guilherme Siqueira de. Engenharia de Software de Requisitos – Software Orientado ao Negócio. Editoras FATTOS e Brasport. Disponível em: <https://analisederequisitos.com.br/wp-content/uploads/2023/06/engenharia-de-requisitos-software-orientado-ao-negocio.pdf> . Acesso em 09 junnho de 2024.

## Histórico de versão

| Versão | Alteração                           | Responsável     | Revisor         | Data       |
| ------ | ----------------------------------- | --------------- | --------------- | ---------- |
| 1.0    | Criação do documento  e elaboração da lista de verificação              | Larissa Stéfane |  Bruno Araújo        | 12/06/2024 |