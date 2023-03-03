# Especificações do Projeto

A definição do problema e os pontos a serem tratados neste projeto foram formatados a partir da participação de esportistas em encontros com membros da equipe de desenvolvimento em ambientes recreativos durante as manhas dos finais de semana. Os usuários de bike relataram suas experiencias e expectativas e os dados levantados neste processo foram consolidados na forma de personas e histórias de usuários. 

## Personas

<table>
    <tbody>
        <tr>
            <td rowspan=3> <img src="/docs/img/flavia.png" width=80% height=80%> <br> Foto de Edward Cisnero em Unsplash </td>
            <td colspan=2> <h1>Flávia dos Santos</h1> </td> 
        </tr>
        <tr>
            <td rowspan=2><h4>Idade:</h4> 52 <br> <h4>Ocupação:</h4> Engenheira Civíl, é sócia de uma empresa de projetos. <br>Por causa da alta demanda de serviço no escritório tem pouco tempo para outras coisas importantes em sua vida.</td>
            <td><strong>Objetivo:</strong><br> <ul><li>Cuidar da saúde e se divertir;<br> Conhecer novas pessoas;</li></ul></td>
        </tr>
        <tr>
            <td><strong>Hobbies:</strong> <ul><li>Ouvir música;</li> <li>Ler bons livros;</li></li></ul></td>
        </tr>
  	    <tr>
            <td colspan="3"><strong>Motivações:</strong><br> <ul><li>Prefere resolver todas as suas necessidades por meio da internet, no momento que puder;</li> <li>Gostaria de diversificar a atividade física que realiza no período da noite;</ul></td></tr>
       <tr>
            <td colspan="3"><strong>Frustrações:</strong> <ul><li>Gosta de pedalar mas se sente desmotivada por não ter companhia.</li></td></tr>
    </tbody>
</table>

<table>
    <tbody>
        <tr>
            <td rowspan=3> <img src="/docs/img/bruno.png" width=80% height=80%> <br> Foto de Edward Cisnero em Unsplash </td>
            <td colspan=2> <h1>Bruno Caldeira</h1> </td> 
        </tr>
        <tr>
            <td rowspan=2><h4>Idade:</h4> 52 <br> <h4>Ocupação:</h4> Professor de alemão;</td>
            <td><strong>Objetivo:</strong><br> <ul><li>Propor passeios de bike;<br> Conhecer novas pessoas;</li></ul></td>
        </tr>
        <tr>
            <td><strong>Hobbies:</strong> <ul><li>Fazer ginástica;</li> <li>Jogar Games;</li></li></ul></td>
        </tr>
  	    <tr>
            <td colspan="3"><strong>Motivações:</strong><br> <ul><li>Gosta de criar roteiros diferentes de bike;</li> <li>Gostaria de reunir o maior número de pessoas e passeios de bike;</ul></td></tr>
       <tr>
            <td colspan="3"><strong>Frustrações:</strong> <ul><li>Não consegue reunir pessoas para seus passeios de bike;.</li></td></tr>
    </tbody>
</table>

<table>
    <tbody>
        <tr>
            <td rowspan=3> <img src="/docs/img/carlos.png" width=80% height=80%> <br> Foto de Edward Cisnero em Unsplash </td>
            <td colspan=2> <h1>Dr. Carlos Gomes</h1> </td> 
        </tr>
        <tr>
            <td rowspan=2><h4>Idade:</h4> 48 <br> <h4>Ocupação:</h4> Médico que atende em diversos hospitais;</td>
            <td><strong>Objetivo:</strong><br> <ul><li>Preencher seu tempo vago com atividades físicas;<br> Conhecer novas pessoas;</li></ul></td>
        </tr>
        <tr>
            <td><strong>Hobbies:</strong> <ul><li>Natação;</li> <li>Viagens;</li></li></ul></td>
        </tr>
  	    <tr>
            <td colspan="3"><strong>Motivações:</strong><br> <ul><li>Se sente mais seguro pedalando em grupos;</td></tr>
       <tr>
            <td colspan="3"><strong>Frustrações:</strong> <ul><li>Não conhece roteiros de bike na zona rural;</li></td></tr>
    </tbody>
</table>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Flávia dos Santos | Preciso fazer atividade física regular | Para manter meu peso controlado |
|Flávia dos Santos | Necessito de motivação para atividade física | Tenho que manter a regularidade para não desanimar |
|Bruno Caldeira | Propor roteiros diferentes de bike | Avaliar o nível de dificuldade e o público-alvo ideal para cada programação |
|Bruno Caldeira | Conhecer o maior número de esportistas | Gostaria de montar uma empresa de atividade outdoor |
|Dr. Carlos Gomes| Pedalar em grupos grandes | Me sinto mais seguro|
|Dr. Carlos Gomes | Fazer peladas longas em parques nacionais/estaduais e reservas naturais | Quero ter contato com a natureza |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O usuário Promoter deverá ser capaz de cadastrar roteiros ciclísticos no site | ALTA | 
|RF-002| O usuário Promoter deverá ser capaz de cadastrar informações básicas sobre os roteiros, tais como: data e horario de realização e nível de dificuldade | ALTA | 
|RF-002| O usuário Comum deverá ser capaz de visualizar os roteiros disponíveis no aplicativo Web sem fazer Login  | MÉDIA |
|RF-002| O usuário Comum deverá ser capaz de visualizar os roteiros disponíveis no aplicativo Web sem fazer Login  | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deverá permitir o cadastro de roteiros ciclísticos | MÉDIA | 
|RNF-002| O site deverá permitir a adesão do usuário comum ao roteiro desejados |  BAIXA | 
|RNF-002| O site deverá enviar notificação ao usuário Promoter a cada adesão |  BAIXA | 
|RNF-002| O site deverá enviar notificação ao usuário Comum, no dia anterior, a atividade programada |  BAIXA | 
|RNF-002| O site deverá permitir pesquisa aos dados cadastrados |  BAIXA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 15/06/2023 |
|02| O aplicativo deve envolver às tecnologias da Web backend, banco de dados e armazenamento em nuvem   |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho  |


## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
