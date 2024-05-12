# Características do SIGAA


## Sumário


* [Introdução](#Introdução)

* [Metodologia](#Metodologia)

* [Funcionalidades](#Funcionalidades)

* [Características Principais da Plataforma](#Características-Principais-da-Plataforma)

* [Como o SIGAA Funciona?](#Como-o-SIGAA-Funciona?)

* [As Tecnologias Utilizadas](#As-Tecnologias-Utilizadas)

* [Controle do Usuário e Liberdade](#Controle-do-Usuário-e-Liberdade)

* [Portabilidade](#Portabilidade)

* [Estilização](#Estilização)

* [Pontos Positivos e Negativos](#Pontos-Positivos-e-Negativos)

* [Pontos Positivos](#Pontos-Positivos)

* [Pontos Negativos](#Pontos-Negativos)

* [Opiniões dos Usuários](#Opiniões-dos-Usuários)

* [Referências Bibliográficas](#Referências-Bibliográficas)




## Introdução


No desenvolvimento do projeto, se baseando no processo de design elaborado por Mayhew¹, um ponto importante é a análise do site SIGAA. Desse modo, este documento pretende realizar uma inspeção detalhada das suas características, considerando os principais elementos e tópicos identificados durante o desenvolvimento da primeira fase do projeto. Além disso, a análise da plataforma também terá como base informações obtidas em documentos anteriores e na navegação no SIGAA. Com isso, por meio desta análise, será buscado identificar tanto como o site funciona assim quanto os seus pontos fortes e fracos ao avaliar a sua estrutura e as suas funcionalidades.



## Metodologia

A análise do SIGAA foi da seguinte forma: inicialmente, foram realizadas análises diretas da plataforma SIGAA, explorando suas diversas funcionalidades e navegando por sua interface. Em paralelo, foram examinados documentos e manuais fornecidos pela UnB ou por outras instituições de ensino. Além disso, foram considerados os feedbacks e opiniões dos usuários, coletados por meio de entrevistas, questionários e brainstorm.

## Funcionalidades

Durantes as entrevistas com os usuários, a execução de brainstorm e a elaboração do estudo de campo, algumas das funcionalidades do SIGAA foram discutidas. Além disso, nos [manuais dos discentes](https://sigaa-manual-discente.readthedocs.io/pt/latest/)², [manuais dos docentes](https://portalsig.unb.br/images//Manuais/manual_docente_abaensino.pdf)³ , e nos [manuais dos servidores](https://manuais.ufs.br/pagina/20055-sigaa-manuais-direcionados-para-servidor-tecnico-administrativo) mais algumas funcionalidades foram identificadas.
Abaixo, há algumas das funcionalidades que o SIGAA oferece para os seus usuários.



### Docentes (Professores)

- Cadastrar Notas;

-Gerenciar Plano;

- Grade Horária;

- Consultar Turmas;

- Declarações;

- Avaliação Institucional;

- Orientações de Atividades;

- Consultar Cursos;

- Componentes Curriculares;

- Estruturas Curriculares;

- Unidades Acadêmicas;

- Declaração de Disciplinas Ministradas;

- Marcar Banca de TCC.



### Discentes (Estudantes)

- Matrícula Online;

- Consultar Horários;

- Consultar Notas;

- Consultar Frequência;

- Consultar Histórico;

- Solicitar Declarações;

- Realizar Avaliação Institucional;

- Visualizar Calendário Acadêmico;

- Acessar Caixa Postal;

- Alterar Senha;

- Visualizar Perfil e Dados Acadêmicos;

- Participar de Turmas Virtuais.



### Servidores técnicos-administrativos

- Gerenciar Matrículas;

- Gerar Documentos Acadêmicos;

- Registrar Atividades Administrativas;

- Emitir Relatórios;

- Atualizar Dados do Sistema;

- Acompanhar Solicitações de Serviços;

- Coordenar Eventos Acadêmicos;

- Emitir Comunicados Institucionais.

## Características Principais da Plataforma


### Como o SIGAA Funciona?

O SIGAA é uma aplicação web baseada em um modelo cliente-servidor, onde o navegador do usuário atua como o cliente e se comunica com os servidores que hospedam a plataforma. Desse modo, essa arquitetura permite que os usuários acessem o SIGAA com um navegador web e uma conexão com a Internet.

#### Internamente

Para funcionar corretamente, internamente, o SIGAA é composto por uma variedade de componentes, incluindo bancos de dados e serviços de rede. Esses componentes trabalham em conjunto para fornecer funcionalidades específicas aos usuários, como matrícula em disciplinas e lançamento de notas.

##### Comunicação com os servidores.

Além disso, a comunicação entre o navegador do usuário e os servidores é feita por meio de protocolos de comunicação padrão da web, como HTTP e HTTPS.

#### Segurança

O SIGAA implementa medidas de segurança, como autenticação de usuários, controle de acesso baseado em permissões e monitoramento de atividades.



### As Tecnologias Utilizadas

Por meio do atalho “Ctrl+U”, atalho para verificar o código do site, foi possível observar que o SIGAA, como a maioria das aplicações web, utiliza:

- HTML para estruturação de páginas;

- CSS para estilização;

- JavaScript para interatividade.



### Controle do Usuário e Liberdade

#### Limites Impostos aos usuários

O SIGAA, como qualquer sistema, impõe certos limites aos seus usuários, definidos pela sua arquitetura, pelas políticas da UnB e pelas funcionalidades disponíveis.



Alguns dos limites impostos são:



- **Aceso controlado**: Requer que os usuários tenham credenciais de acesso válidas para entrar na plataforma.

- **Permissões de usuários**: Dentro do SIGAA, diferentes usuários têm diferentes níveis de permissão, dependendo do seu papel na instituição. Por exemplo, um docente pode ter permissão para lançar notas em disciplinas específicas, enquanto um discente pode ter acesso apenas às suas próprias informações acadêmicas.

- **Disponibilidade de funcionalidades**: Nem todas as funcionalidades do SIGAA estão disponíveis para todos os usuários. Por exemplo, enquanto os docentes podem ter acesso à função de lançamento de notas, os servidores técnicos-administrativos podem ter permissão para gerenciar processos de matrícula e emitir declarações institucionais.

- **Restrição de tempo para a funcionalidade**: Algumas funcionalidades do SIGAA estão disponíveis apenas durante períodos específicos, determinados pela instituição de ensino. Por exemplo, as matrículas online só podem ser realizadas dentro do período de matrícula designado pelo calendário acadêmico.



#### Liberdade dada aos usuários

Algumas das liberdades que o SIGAA dá são:



- **Personalização do perfil:** Os usuários têm a liberdade de personalizar seus perfis dentro do SIGAA, adicionando informações adicionais, como foto de perfil e detalhes de contato.

- **Possibilidade de alteração de senha**: Permite que os usuários personalizem suas credenciais de acesso de acordo com suas preferências e necessidades de segurança.

- **Navegação por diversos tópicos:** A plataforma oferece liberdade de navegação por uma variedade de tópicos e áreas, como extensão, estágio, bolsas, entre outros, permitindo aos usuários explorar diferentes aspectos de sua vida acadêmica e profissional.


### Portabilidade

#### Funcionamento em Computadores.

Em computadores desktop e laptop, o SIGAA oferece uma experiência de usuário funcional, pois os usuários podem acessar todas as funcionalidades da plataforma por meio de navegadores da web padrão, como Google Chrome, Mozilla Firefox ou Microsoft Edge.



#### Limitações em Dispositivos Móveis.

Apesar de sua funcionalidade em computadores, o SIGAA enfrenta desafios significativos quando acessado por dispositivos móveis, como smartphones e tablets, uma vez que a interface do usuário não é totalmente responsiva nestes dispositivos.



### Estilização.


- **Estilo minimalista**: O SIGAA adota um estilo de design minimalista, caracterizado pela simplicidade e pela ênfase na funcionalidade.



- **Botões e ícones identificáveis**: Os botões e ícones são projetados para serem facilmente identificáveis e acionáveis. Para alguns, basta encostar o mouse.

- **Hierarquia de funcionalidades:** As funcionalidades são organizadas de forma hierárquica, onde algumas estão contidas dentro de outras, seguindo uma lógica de agrupamento.

- **Paleta de cores:** As cores predominantes são: Azul-claro, cinza e amarelo.



## Pontos Positivos e Negativos

Nas conversas e técnicas aplicadas com os usuários, os feedbacks foram:

### Pontos Positivos

- **Ampla Gama de Funcionalidades**: oferece uma ampla variedade de funcionalidades para diferentes usuários, incluindo docentes, discentes e servidores técnicos-administrativos.

- **Navegação Simplificada**: Algumas funcionalidades podem ser encontradas rapidamente e em poucos passos, por exemplo, emissão de histórico.

- **Agilidade dos processos acadêmicos**: O SIGAA oferece algumas funcionalidades que aceleram a realização de processos acadêmicos por diminuir a burocracia, por exemplo, trancamento de matrícula.



### Pontos Negativos

- **Primeiro Contato Desagradável**: Muitos usuários relatam uma experiência inicial confusa e desagradável ao utilizar o SIGAA pela primeira vez.



- **Dificuldade de Compreensão**: Alguns usuários enfrentam dificuldades para entender a lógica e o funcionamento do SIGAA.



- **VersãoMobile Pouco Útil**: A versão mobile do SIGAA é frequentemente criticada por ter funcionalidades limitadas.



## Conclusão

Portanto, por meio da análise das suas características, é possível observar que o SIGAA é uma plataforma robusta desenvolvida para atender às necessidades acadêmicas e administrativas das instituições de ensino que apresenta um conjunto de detalhes próprios.



## Bibliografia

1. Eduardo Rafael Mallmann. **Análise do Sistema Integrado de Gestão de Atividades Acadêmicas (SIGAA)** . Disponível em <https://repositorio.ifsc.edu.br/bitstream/handle/123456789/754/Artigo%20Final%20Correcoes%20feitas%20Eduardo%20R%20Mallmann.pdf?sequence=1&isAllowed=y>. Acesso em 12 de maio de 2024.

2. **SIGAA**. Disponível em <https://autenticacao.unb.br/sso-server/login?service=https%3A%2F%2Fsig.unb.br%2Fsigaa%2Flogin%2Fcas> Acesso em 12 de maio de 2024.



## Referências Bibliográficas

1. Barbosa e Silva. 2010. **Processos de Design de IHC – Capítulo 4**



2. Manual discentes. Disponível em <https://sigaa-manual-discente.readthedocs.io/pt/latest/>. Acesso em 12 de maio de 2024.



3. Manual docentes. Disponível em <https://portalsig.unb.br/images//Manuais/manual_docente_abaensino.pdf>. Acesso em 12 de maio de 2024

4. Manual dos servidores. Disponível em <https://manuais.ufs.br/pagina/20055-sigaa-manuais-direcionados-para-servidor-tecnico-administrativo>. Acesso em 12 de maio de 2024


## Histórico de Versão


| Versão | Alteração            | Responsável     | Revisor         | Data       |
| ------ | -------------------- | --------------- | --------------- | ---------- |
| 1.0    | Criação  e elaboração do documento | Larissa Stéfane | - | 12/05/2024 |




