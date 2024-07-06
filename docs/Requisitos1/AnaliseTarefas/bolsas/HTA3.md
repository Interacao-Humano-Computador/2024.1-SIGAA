# Análise Hierárquica de Tarefas no SIGAA - Aba Bolsas

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Análise de Tarefas](Análise-Hierárquica-de-Tarefas)
* [Análise Contextual](#Análise-Contextual)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)

## Introdução

A Análise Hierárquica de Tarefas (HTA) é uma técnica metodológica que se concentra em decompor uma tarefa complexa em hierarquias de sub-tarefas mais simples e gerenciáveis. Esta abordagem é amplamente utilizada na área de Interação Humano-Computador (IHC) para detalhar como os usuários interagem com um sistema, identificando os objetivos do usuário, as operações necessárias para alcançá-los e as estratégias utilizadas para executar essas operações. A HTA fornece uma visão clara da sequência de ações e das dependências entre as tarefas, permitindo o desenvolvimento de sistemas mais intuitivos e eficientes.

## Motivo da escolha

A escolha pela Análise Hierárquica de Tarefas foi feita pela sua capacidade de estruturar de maneira clara e sistemática as interações complexas entre os usuários e o sistema do SIGAA, especificamente na gestão de bolsas.

Este método facilita a identificação e a análise de problemas, permitindo otimizações que podem melhorar significativamente a experiência do usuário e a eficácia do sistema.

# Análise Hierárquica de Tarefas no SIGAA - Aba Bolsas

## Introdução

A funcionalidade da aba "Bolsas" no SIGAA permite aos estudantes acessar e gerenciar vários aspectos relacionados às bolsas estudantis, desde a inscrição até o acompanhamento e renovação de bolsas. Cada tarefa foi decomposta para facilitar a compreensão dos processos envolvidos e melhorar a interação do usuário com o sistema.

# Análise Hierárquica de Tarefas (HTA) para o Menu "Bolsas" no SIGAA

# Análise Hierárquica de Tarefas (HTA) para o Menu "Bolsas" no SIGAA

## Tabela 1: HTA para Cadastro Único de Bolsas
Nessa tarefa, o usuário tem o objetivo de acessar o Cadastro Único de Bolsas no menu do sistema, onde pode aderir ao cadastro, consultar suas adesões e gerar declarações de discente prioritário.

| Objetivos/Operações                              | Problemas e Recomendações                                                                                      |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **0. Acessar Cadastro Único**                    | **Input:** Seleção da opção "Cadastro Único" no menu Bolsas.<br>**Feedback:** Exibição das subopções.<br>**Plano:** Garantir visibilidade e entendimento das opções disponíveis. |
| **1. Aderir ao Cadastro Único (1>2)**            | **Input:** Seleção da opção "Aderir".<br>**Feedback:** Formulário de adesão é apresentado.<br>**Plano:** Assegurar que o formulário seja intuitivo e completo. |
| **2. Consultar Adesões (1/2)**                   | **Input:** Seleção da opção "Consultar Adesões".<br>**Feedback:** Visualização das adesões existentes.<br>**Plano:** Prover detalhes claros sobre o status de cada adesão. |
| **3. Declaração de Discente Prioritário**        | **Input:** Seleção da opção "Declaração de Discente Prioritário".<br>**Feedback:** Possibilidade de gerar declaração.<br>**Plano:** Simplificar o processo de geração e garantir a validade da informação. |

## Tabela 2: HTA para Declaração de Bolsista
Nessa tarefa, o usuário tem como objetivo acessar as declarações de bolsista, onde pode assinar ou visualizar declarações relativas ao não acúmulo de bolsas.

| Objetivos/Operações                              | Problemas e Recomendações                                                                                      |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **0. Acessar Declarações de Bolsista**           | **Input:** Seleção da opção "Declaração de Bolsista".<br>**Feedback:** Opções para assinar ou visualizar declarações são exibidas.<br>**Plano:** Assegurar clareza nas opções e processos. |
| **1. Assinar Declaração (1>2)**                  | **Input:** Clicar em "Assinar Declaração".<br>**Feedback:** Formulário para assinatura aparece.<br>**Plano:** Facilitar o processo de assinatura e garantir a segurança dos dados. |
| **2. Visualizar Assinaturas (1+2)**              | **Input:** Clicar em "Visualizar Assinaturas".<br>**Feedback:** Lista de declarações assinadas disponível.<br>**Plano:** Proporcionar uma visualização fácil e acessível das informações. |

## Tabela 3: HTA para Gestão de Bolsas
Nessa tarefa, o usuário tem como objetivo gerenciar suas bolsas na instituição, incluindo a visualização de oportunidades, o acompanhamento de registros de interesse e a visualização das bolsas que possui.

| Objetivos/Operações                              | Problemas e Recomendações                                                                                      |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **1. Visualizar Oportunidades de Bolsa (1>2)**   | **Input:** Seleção da opção "Oportunidades de Bolsa".<br>**Feedback:** Lista de oportunidades disponíveis.<br>**Plano:** Garantir atualização constante e precisão das oportunidades listadas. |
| **2. Acompanhar Registros de Interesse (1+2)**   | **Input:** Clicar em "Acompanhar Meus Registros de Interesse".<br>**Feedback:** Estado atual dos registros de interesse.<br>**Plano:** Assegurar que o usuário receba atualizações regulares sobre o status. |
| **3. Visualizar Minhas Bolsas na Instituição (1/2)** | **Input:** Seleção da opção "Minhas Bolsas na Instituição".<br>**Feedback:** Visualização das bolsas que o usuário possui.<br>**Plano:** Manter a informação clara e atualizada para facilitar o gerenciamento por parte do estudante. |

## Tabela 4: HTA para Solicitação e Gerenciamento de Bolsas Auxílio
**Introdução:** Nessa tarefa, o usuário tem como objetivo solicitar novas bolsas auxílio, acompanhar e renovar essas bolsas, focando em aspectos operacionais e administrativos.

| Objetivos/Operações                              | Problemas e Recomendações                                                                                      |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------|
| **1. Solicitar Bolsa Auxílio (1>2)**             | **Input:** Seleção da opção "Solicitação de Bolsa Auxílio".<br>**Feedback:** Formulário de solicitação é exibido.<br>**Plano:** Simplificar o formulário e fornecer orientações claras. |
| **2. Acompanhar Solicitação de Bolsa Auxílio (1+2)** | **Input:** Clicar em "Acompanhar Solicitação de Bolsa Auxílio".<br>**Feedback:** Status atual das solicitações.<br>**Plano:** Fornecer detalhes precisos sobre o progresso e eventuais atrasos. |
| **3. Renovar Bolsa Auxílio (1/2)**               | **Input:** Seleção da opção "Renovar Bolsa Auxílio".<br>**Feedback:** Formulário de renovação disponível.<br>**Plano:** Automatizar o preenchimento de dados conhecidos para facilitar o processo. |


## Conclusão
Como é possível observar, a análise hierárquica e a aplicação do método GOMS para a funcionalidade de pedido de monitoria revelaram uma estrutura complexa de tarefas e interações dentro do processo. Assim, ao desmembrar cada etapa em objetivos, passo a passo, métodos e regras, foi possível compreender detalhadamente as ações dos usuários e identificar áreas de relevância.

## Bibliografia
1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.

## Histórico de Versão
| Versão | Alteração                                   | Responsável  | Revisor         | Data       |
| ------ | ------------------------------------------- | ------------ | --------------- | ---------- |
| 1.0    | Criação e realização da análise hierárquica | Bruno Araújo | Iago Passaglia | 04/05/2024 |
