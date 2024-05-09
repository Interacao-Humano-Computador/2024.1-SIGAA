# Análise de Tarefas: Consulta de Saldo no Restaurante Universitário na visão do estudante

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
Por meio da análise de tarefas, este documento apresenta a análise detalhada da funcionalidade de **consulta de saldo**, que visa disponibilizar uma verificação em tempo real dos créditos que um estudante
tem no sistema do Restaurante Universitário. Portanto, para decompor as atividades envolvidas neste processo, hierarquia analítica e GOMS (Metas, Operadores, Métodos e Métodos)
Regras de Seleção), será procurado entender e avaliar a interação do usuário com a interface e identificar as áreas necessárias para execução de consultas através do SIGAA.

## Objetivos
O objetivo de **consulta de saldo** é oferecer aos estudantes uma maneira conveniente e eficiente de checar seus créditos no RU.

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

    0. Realizar Consulta de Saldo (1>2)
      1. Clicar na aba de Restaurante Universitário

**Fonte:** [Breno Alexandre](https://github.com/brenoalexandre0)

</details>

### Diagrama de Atividades

Para facilitar a visualização das tarefas, a figura 1 mostra o diagrama:

 <div align="center">
    Figura 1: Diagrama HTA da Consulta de Saldo
    <br>
    <img src="https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/HTAconsultaSaldo.png">
    <br>
     Fonte: Breno Alexandre
    <br>
</div>

<br>

Para visualizar a imagem em uma qualidade melhor e em um tamanho maior clique em [Diagrama HTA da Consulta de Saldo](https://github.com/Interacao-Humano-Computador/2024.1-SIGAA/blob/main/assets/HTAconsultaSaldo.png)

### Tabela de Análise
A tabela 1 mostra a tabela da análise hierárquica de tarefas sobre a funcionalidade de consulta de saldo.

<details>
  <summary size="20"><b> Tabela de Análise </b></summary> 
<br>
   
**Tabela 1**: Análise Hierárquica de consulta de saldo.

| Objetivos/Operações                           | Relações | Problemas e Recomendações                                                                                                                                                                           |
| --------------------------------------------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 0. Realizar Consulta de Saldo                 | 1 > 2    | **Input**: Necessidade de consultar o saldo no RU.<br>**Feedback**: O sistema carrega os dados.<br>**Plano**: Mostrar o saldo atual do estudante.<br>**Recomendação**: Prosseguir para a aba do RU. |
| 1. Clicar na aba de Restaurante Universitário |          | **Input**: Clicar na aba.<br>**Feedback**: Mostra o saldo atual.<br>**Plano:** Checar o saldo do estudante.<br>**Recomendação**: Nenhuma.                                                           |

**Fonte:** [Breno Alexandre](https://github.com/brenoalexandre0)
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
| 1.0    | Criação e realização da análise hierárquica | Breno Alexandre | -               | 09/05/2024 |
