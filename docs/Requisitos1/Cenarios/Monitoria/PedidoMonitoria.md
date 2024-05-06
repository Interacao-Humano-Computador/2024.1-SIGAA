# Análise de Tarefas: Pedido de Monitoria na visão do estudante

## Sumário
* [Introdução](#Introdução)
* [Definição dos elementos](#Definição-dos-elementos)
* [Narrativa](#Narrativa)
* [Questionamento Sistemático](#Questionamento-Sistemático)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)
  
## Introdução

No contexto acadêmico, o desejo dos estudantes em atuarem como monitores representa uma importante contribuição para o ambiente educacional. No entanto, sem uma funcionalidade específica para o pedido de monitoria, os alunos podem enfrentar dificuldades ao tentar formalizar esse desejo. Devido a isso, este cenário destaca a lacuna existente no SIGAA em relação à ausência de um processo claro e direto para os estudantes expressarem seu interesse em se tornarem monitores. Além disso, ao explorar essa situação, é possível compreender as necessidades dos usuários para se fazer uma funcionalidade ideal.

## Definição dos elementos

A tabela 1 mostra os elementos em relação ao cenário de pedido para ser monitor.

**Tabela 1**: Elementos do cenário
| Elemento | Descrição |
| - | - | 
| **Ambiente** | Ambiente universitário que estimula os estudantes a serem monitores de matérias que lhe agradam. |
| **Atores** | Estudante entusiasmado para ser monitor, professor que vai trocar de disciplina, professor da mesma disciplina, mas que é de outro campus. |
| **Objetivos** | O estudante deseja ser monitor de uma matéria que gosta muito no seu campus da universidade. |
| **Planejamento** | O estudante envia um email ao professor da disciplina para solicitar monitoria, sem especificar suas habilidades ou limitações, e sem considerar a logística envolvida. |
| **Ações** | O estudante envia email ao professor solicitando monitoria. |
| **Eventos** | O estudante envia o email, o professor visualiza e aceita o pedido. O estudante percebe as dificuldades logísticas e desiste de ser monitor. |

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

## Narrativa

Jorge Reinan, um estudante dedicado do curso de Ciência da Computação, estava determinado a se tornar monitor da disciplina de Bancos de Dados 1. Ele havia se destacado na matéria no semestre anterior e sentia que poderia ajudar outros alunos a compreender melhor o conteúdo. Então, Inicialmente, Jorge procurou o professor que lhe ministrou a disciplina no semestre anterior para expressar seu interesse em se tornar monitor. No entanto, para sua surpresa, o professor informou que estaria trocando de disciplina no próximo semestre, deixando Jorge desapontado e incerto sobre como proceder.

Percebendo que precisava encontrar uma alternativa para alcançar seu objetivo, Jorge decidiu buscar orientação. Uma amiga, ciente de sua situação, sugeriu que ele consultasse o portal público do SIGAA, onde seria possível encontrar informações de contato dos professores que lecionavam Bancos de Dados 1 naquele semestre. Seguindo o conselho da amiga, Jorge acessou o portal e encontrou uma lista de e-mails dos docentes responsáveis pela disciplina.

Com a lista em mãos, Jorge começou a enviar e-mails para os professores, expressando seu interesse em se tornar monitor. Após alguns dias de espera ansiosa, Jorge finalmente recebeu uma resposta de um dos professores. O docente, embora não fosse o mesmo que lhe ministrou a disciplina anteriormente, estava aberto à ideia de ter um monitor e convidou Jorge para uma reunião para discutir os detalhes.

Empolgado com a possibilidade de se tornar monitor, Jorge compareceu à reunião com o professor. No entanto, durante a conversa, surgiram alguns problemas. O professor explicou que precisava de um monitor que tivesse um bom domínio sobre um tópico específico da disciplina, no qual Jorge admitiu ter dificuldades.  

Além disso, teve mais uma revelação, o professor lecionava em um campus diferente. Isso foi um golpe adicional para Jorge. Ele percebeu que a distância geográfica entre os campus dificultaria sua participação regular como monitor, pois seria inviável deslocar-se frequentemente para o outro local. 

Essa realidade fez Jorge repensar seus planos e avaliar se assumir a responsabilidade de monitoria naquelas circunstâncias seria realmente viável e benéfico para ele e para os alunos. Após cuidadosa reflexão e consideração dos obstáculos encontrados, Jorge tomou a difícil decisão de adiar seu objetivo de se tornar monitor.

## Questionamento Sistemático

Com base tanto na narrativa quanto na realidade vivida por diversos estudante, a tabela 2 mostra as questões, resposas e sugestões para os problemas encontrados na narrativa.

**Tabela 2: Questionamento Sistemático

| Situação                                                                                             | Questão                                                                                                         | Resposta                                                                                                          | Sugestão de Solução                                                                                                         |
|------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| Dificuldade de comunicação pessoal com os professores para discutir sobre o pedido de ser monitor. | Por que a comunicação pessoal com os professores é difícil para discutir o pedido de monitoria?              | A comunicação pessoal é difícil devido à falta de disponibilidade dos professores e à timidez dos estudantes. | Implementar uma funcionalidade no SIGAA que permita aos estudantes enviar solicitações de monitoria diretamente pelo sistema. |
|                                                                                                      | Como essa dificuldade afeta o processo de busca por monitoria?                                                | A dificuldade de comunicação resulta em atrasos na obtenção de respostas dos professores e desmotivação dos estudantes. | Garantir que os professores estejam disponíveis para receber solicitações de monitoria através do SIGAA.                    |
| Dificuldade de acesso aos professores em que o estudante não tem vínculo.                           | Por que foi difícil para os estudantes acessarem os professores que não tinham vínculo direto com eles?         | Foi difícil porque os contatos dos professores não estavam disponíveis publicamente e não havia um canal formal de comunicação. | Disponibilizar no SIGAA uma seção com os contatos dos professores responsáveis por cada disciplina.                          |
|                                                                                                      | Como o acesso facilitado a essas informações poderia ter ajudado os estudantes?                               | O acesso facilitado teria permitido uma comunicação mais direta e eficiente entre estudantes e professores, reduzindo a burocracia. | Certificar-se de que os estudantes tenham acesso rápido e fácil aos dados de contato dos professores.                       |
| Dificuldade dos professores em saber quais são os pontos fortes e fracos de determinado monitor.    | Por que os professores têm dificuldade em identificar os pontos fortes e fracos dos monitores?                | Os professores têm dificuldade porque não têm informações suficientes sobre os estudantes que desejam ser monitores. | Incluir no SIGAA uma seção para que os estudantes possam registrar suas habilidades e áreas de dificuldade.                |
|                                                                                                      | Como esse desconhecimento impacta na escolha de monitores adequados para as disciplinas?                        | Isso pode levar à seleção de monitores inadequados para as disciplinas, prejudicando a qualidade do apoio oferecido aos alunos. | Criar critérios de seleção de monitores que levem em consideração as informações registradas pelos estudantes.            |
| Erro quando um estudante vira monitor de uma turma que não faz parte do seu campus.                  | Por que ocorreu o erro de um estudante se tornar monitor de uma turma em outro campus?                         | O erro ocorreu devido à falta de conhecimento do estudante sobre onde o professor lecionava.  | Implementar no SIGAA a opção de escolher local e horário das disciplinas. |
|                                                                                                      | Como esse erro pode ser evitado no futuro?                                                                     | O erro pode ser evitado implementando-se validações no sistema para garantir que estudantes do campus correspondente possam se candidatar a monitoria. | Criar mecanismos de validação no SIGAA e aumentar a inormação.|

**Fonte:** [Larissa Stéfane](https://github.com/SkywalkerSupreme)

## Conclusão

Por meio da análise do ambiente, objetivos, atores e eventos, é possível observar e estudar melhor a narrativa do cenário, o que permite que as respostas sejam mais intuitivas no momento de preencher a tabela de questionamento sistemático. Desse modo, por meio desse cenário, foi possível pensar melhor sobre as necessidades do usuário ao elaborar a funcionalidade de pedido para ser monitor.


## Bibliografia

1. Barbosa, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. (2021). Interação Humano-Computador e Experiência do Usuário. Acesso em 28 de abril de 2024.
2. **Personas e Cenário**, Informática- Puc- rio. Disponível em <https://www.inf.puc-rio.br/~inf1403/docs/alberto2011_1/07_Personas_Cenarios.pdf>

## Histórico de Versão

| Versão | Alteração | Responsável | Revisor | Data |

| - | - | - | - | - |

| 1.0 | Criação e realização do documento | Larissa Stéfane | - | 05/05/2024 |

