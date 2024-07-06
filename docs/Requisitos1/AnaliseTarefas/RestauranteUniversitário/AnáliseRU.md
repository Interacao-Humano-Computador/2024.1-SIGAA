# Análise de Tarefas: Aba do Restaurante Universitário na visão do estudante

## Sumário
* [Introdução](#Introdução)
* [Objetivos](#Objetivos)
* [Análise Hierárquica de Tarefas](#Análise-Hierárquica-de-Tarefas)
    * [Análise Contextual](#Análise-Contextual)
    * [Diagrama de Atividades](#Diagrama-de-Atividades)
    * [Tabela de Análise](#Tabela-de-Análise)
* [GOMS](#GOMS)
    * [Definição dos objetivos(Goals)](#Definição-dos-objetivos)
    * [Definição dos operadores(Operators)](#Definição-dos-operadores(Operators))
    * [Definição dos Métodos](#Definição-dos-Métodos )
    * [Definição das Regras de Seleção](#Definição-das-Regras-de-Seleção)
    * [Execução do GOMS](#Execução-do-GOMS)
* [Conclusão](#Conclusão)
* [Bibliografia](#Bibliografia)
* [Histórico de versão](#Histórico-de-versão)
  
## Introdução
Por meio da análise de tarefas, este documento apresenta a análise detalhada das funcionalidades:
- **Consulta de Saldo:** visa disponibilizar uma verificação em tempo real dos créditos de um estudante no sistema do Restaurante Universitário.
- **Recarga de Créditos:** visa disponibilizar a recarga de créditos de um estudante no sistema do Restaurante Universitário.
- **Consulta de Cardápio:** visa disponibilizar e exibir o cardápio da semana que tem no site do Restaurante Universitário.

Portanto, para decompor as atividades envolvidas nestes processos, hierarquia analítica e GOMS (Goals, Operators, Methods, e Selection Rules), 
serão usados, procurando entender e avaliar a interação do usuário com a interface e identificar as áreas necessárias para execução de consultas através do SIGAA.

## Objetivos
O objetivo da **aba do Restaurante Universitário** é oferecer aos estudantes uma maneira conveniente e eficiente de gerenciar sua conta no RU.

## Análise Hierárquica de Tarefas
A análise de tarefas é o processo de decomposição das atividades do usuário em componentes menores, chamados tarefas, dentro de um sistema ou interface.
Para isso, tarefas complexas são divididas em objetivos, subobjetivos e operações, e é criado um plano para explicar como atingir esses subobjetivos.

Abaixo, serão apresentados a análise contextual, o diagrama e a tabela desse processo.

### Análise Contextual
Como há um conjunto de tarefas a serem realizadas, há baixo, no algoritmo 1, há a análise contextual e hierárquica utilizada.

<details>
  <summary size="20"><b> Algoritmo 1: Análise Contextual </b></summary> 
<br>
   
  **Algoritmo 1: Análise Contextual**

    0. Realizar Consulta de Saldo (1/2)
      1. Clicar na aba de Restaurante Universitário (1>2)

    0. Acessar Funcionalidade de Recarga de Créditos (1/2)
     1. Escolher Opção de Recarga (1>2)
       1.1 Opção de Cartão de Crédito ou Débito (1/2)
         1.1.1 Inserir Valor a ser Recarregado (1+2)
           1.1.1.1 Digitar Valor Desejado para Recarga
         1.1.2 Inserir Detalhes do Cartão de Crédito (1+2)
           1.1.2.1 Número do Cartão
           1.1.2.2 Data de Validade
           1.1.2.3 Código de Segurança
         1.1.3 Confirmar Transação com Cartão de Crédito (1>2)
           1.1.3.1 Autorizar Pagamento
           1.1.3.2 Verificar Transação Aprovada
       1.2 Opção de Boleto Bancário (1/2)
         1.2.1 Gerar Boleto com Valor a ser Pago (1>2)
           1.2.1.1 Gerar Boleto com Dados do Pagador
           1.2.1.2 Emitir Boleto com Valor Adequado
         1.2.2 Realizar Pagamento do Boleto (1>2)
           1.2.2.1 Efetuar Pagamento através do Banco ou Internet Banking
           1.2.2.2 Confirmar Pagamento do Boleto
       1.3 Opção de PIX (1/2)
         1.3.1 Inserir Valor a ser Recarregado (1>2)
         1.3.2 Gerar QR Code para Pagamento via PIX (1>2)
           1.3.2.1 Gerar Código QR com Dados da Transação
           1.3.2.2 Disponibilizar Código QR para Escaneamento
           1.3.2.3 Disponibilizar Código QR para copiar
         1.3.3 Efetuar Pagamento via PIX (1>2)
           1.3.3.1 Escanear/Colar QR Code com Aplicativo Bancário
           1.3.3.2 Confirmar Transação PIX
     2. Receber Confirmação e Comprovante (1>2)
       2.1 Visualizar Confirmação da Transação
         2.1.1 Receber Notificação de Sucesso
       2.2 Receber Comprovante de Pagamento (1>2)
         2.2.1 Gerar Comprovante em Formato Digital ou PDF
     3. Oferecer Suporte ao Usuário (1>2)
       3.1 Disponibilizar Canal de Atendimento ao Cliente
         3.1.1 Chat ao Vivo, Suporte por Telefone, E-mail, etc.

    0. Realizar Consulta de Cardápio (1/2)
      1. Opção de Consultar Cardápio (1>2)
         1.1 Opção do Refeitório (1/2)
            1.1.1 Escolher Campus (1>2)
               1.1.1.1 Selecionar Cardápio (1>2)
                  1.1.1.1.1 Baixar PDF
                  1.1.1.1.2 Imprimir PDF
                  1.1.1.1.3 Dar zoom
                  1.1.1.1.4 Tirar zoom
         1.2 Opção de ver o Cardápio do Restaurante Executivo (1/2)
            1.2.1 Selecionar Cardápio (1>2)
                  1.2.1.1 Baixar PDF
                  1.2.1.2 Imprimir PDF
                  1.2.1.3 Dar zoom 
                  1.2.1.4 Tirar zoom

<strong> Autor: </strong> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>

</details>

### Diagrama de Atividades

Para facilitar a visualização das tarefas, a figura 1 mostra o diagrama:

 <div align="center">
    Figura 1: Diagrama HTA da aba RU
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/HTAabaRU.png">
    <br>
    <strong> Autor: </strong> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>
    <br>
</div>

<br>

Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA da aba RU](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/HTAabaRU.png)

Após a [avaliação do diagrama com um usuário](/DesignAvaliaçãoDesenvolvimento/Nível1/Entrevistas_Avaliacao/Execucao_Entrevistas.md), ele foi refeito baseado no feedback da entrevista, como mostra a figura 2.

 <div align="center">
    Figura 2: Diagrama HTA da aba RU refeito
    <br>
    <img src="https://raw.githubusercontent.com/Interacao-Humano-Computador/2024.1-SIGAA/main/assets/HTAabaRU2.png">
    <br>
    <strong> Autor: </strong> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>
    <br>
</div>

<br>

Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA da aba RU](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/HTAabaRU2.png)

### Tabela de Análise
As tabelas de 1 a 4 mostram a tabela da análise hierárquica de tarefas sobre as funcionalidades.

<details>
  <summary size="20"><b> Tabelas de Análise </b></summary> 
<br>
<center>
   
**Tabela 1**: Análise Hierárquica de consulta de saldo.

| Objetivos/Operações                           | Relações | Problemas e Recomendações                                                                                                                                                                           |
| --------------------------------------------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0. Realizar Consulta de Saldo                 | 1/2      | **Input**: Necessidade de consultar o saldo no RU.<br>**Feedback**: O sistema carrega os dados.<br>**Plano**: Mostrar o saldo atual do estudante.<br>**Recomendação**: Prosseguir para a aba do RU. |
| 1. Clicar na aba de Restaurante Universitário | 1>2      | **Input**: Clicar na aba.<br>**Feedback**: Mostra o saldo atual.<br>**Plano:** Checar o saldo do estudante.<br>**Recomendação**: Nenhuma.                                                           |
<strong> Autor: </strong> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>

**Tabela 2**: Análise Hierárquica da Recarga de Créditos.

| Objetivos/Operações                           | Relações | Problemas e Recomendações                                                                                                                                                                           |
| --------------------------------------------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0. Acessar Funcionalidade de Recarga de Créditos | 1/2      | **Input**: Necessidade de recarregar o saldo no RU.<br>**Feedback**: O sistema carrega as áreas de preenchimento.<br>**Plano**: Recarregar o os créditos para serem usados no futuro.<br>**Recomendação**: Selecionar a opção de recarga de créditos. |
| 1. Escolher Opção de Recarga | (1>2)      | **Input**: Necessidade de escolhar a opção de pagamento.<br>**Feedback**: O sistema exibe as opções.<br>**Plano**: Escolher uma opção de pagamento.<br>**Recomendação**: Selecionar uma opção. |
| 1.1 Opção de Cartão de Crédito ou Débito | (1/2)      | **Input**: Necessidade de usar o cartão como forma de pagamento.<br>**Feedback**: O sistema carrega as áreas a serem preenchidas.<br>**Plano**: Preencher com os dados necessários.<br>**Recomendação**: Preencher com os dados corretos. |

<strong> Autor: </strong> <a href="https://github.com/brenoalexandre0"> Breno Alexandre </a>


</center>
</details>

## GOMS
GOMS é um método de análise de tarefas que define as atividades do usuário por objetivo (o que o usuário deseja alcançar), operador (ações realizadas, como clicar em um botão), método (sequência de ações para atingir um objetivo) e regras de seleção (critérios para escolha entre métodos alternativos). Como será trabalhar neste **aplicativo de monitoramento**, está demonstrado abaixo.

### Definição dos objetivos
1. **Clicar na aba de Restaurante Universitário**: O usuário clica na aba do Restaurante Universitário e verá o saldo imediatamente.

### Definição dos operadores(Operators)
- **Não há um**: Pois quando a aba for aberta, nada mais será necessário.

### Definição dos Métodos
- **Não há um**: Pois o saldo será exibido na tela de forma automática.

### Definição das Regras de Seleção
1. **Não há uma**: O sistema irá carregar o saldo automáticamente.

### Execução do GOMS

Abaixo, no algoritmo 2, há a execução do método GOMS.

<details>
  <summary size="20"><b> Algoritmo 2: GOMS </b></summary> 
<br>
   
   **Algoritmo 2:** Execução do GOMS.
      
      GOAL 0: Realizar Consulta de Saldo
      
      GOAL 1: Clicar na aba de Restaurante Universitário

**Fonte:** [Breno Alexandre](https://github.com/brenoalexandre0)
</details>

## Conclusão
Como é possível observar, a análise hierárquica e a aplicação do método GOMS para a funcionalidade de pedido de consulta de saldo revelaram uma estrutura muito simples de tarefas e interações dentro do processo.

## Bibliografia
**BARBOSA**, S. D. J., Silva, B. S., Silveira, M. S., Gasparini, I., Darin, T., & Barbosa, G. D. J. Interação Humano-Computador e Experiência do Usuário. (2021). pgs. 178-176.

## Histórico de Versão
| Versão | Alteração                                   | Responsável     | Revisor         | Data       |
| ------ | ------------------------------------------- | --------------- | --------------- | ---------- |
| 1.0    | Criação e realização da análise hierárquica | Breno Alexandre | Iago Passaglia | 09/05/2024 |
| 1.1    | Refatoração da análise hierárquica          | Breno Alexandre | Iago Passaglia | 11/05/2024 |
