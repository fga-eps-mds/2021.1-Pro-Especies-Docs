# Plano de Gerenciamento de Riscos

|    Data    | Versão |                Descrição                |                     Autor                     |
| :--------: | :----: | :-------------------------------------: | :-------------------------------------------: |
| 13/08/2021 |  1.0   | Criação da primeira versão do documento do Plano de Gerenciamento de Riscos | [Lucas Fellipe](https://github.com/lucasfcm9) |
| 09/09/2021 |  1.1   | Atualização da EAR e da identificação dos riscos | [Lucas Fellipe](https://github.com/lucasfcm9) |

## 1. Introdução

<p align="justify"> &emsp;&emsp;O Plano de Gerenciamento de Riscos fornece informações sobre papéis e responsabilidades relativas aos riscos, indicando como as atividades do gerenciamento dos riscos são incluídas no orçamento e no cronograma do projeto. Além disso, descreve as categorias de risco que podem ser expressas como uma EAR (Estrutura Analítica dos Riscos).</p>

## 2. Objetivo

<p align="justify"> &emsp;&emsp;O plano de gerenciamento de riscos tem como objetivo descrever quais são os riscos do projeto, como eles serão monitorados e controlados ao longo das <i>sprints</i>, visando entender seus impactos e procurando formas de mitigar esses possíveis riscos.</p>

<p align="justify"> &emsp;&emsp;A EAR facilita a identicação dos riscos em projetos. Tem por função mostrar as principais categorias de riscos para um projeto, auxiliando como guia para análise do contexto, da documentação e para o questionamento das partes interessadas, buscando ganho de tempo na identificação dos riscos. Os riscos podem ser divididos nas seguintes categorias:</p>

## 3. Estrutura Analítica dos Riscos

![EAR](../Assets/Images/EAR/EAR.png)


* Riscos Técnicos:

  |   **Tipo**   |                          Descrição                           |
  | :----------- | :----------------------------------------------------------- |
  |  Requisitos  | Riscos pela falta de mapeamento e elicitação de requisitos.  |
  | Tecnologias  |      Riscos gerados pela escolha da tecnologia errada.       |
  | Complexidade | Riscos gerados pela falta de conhecimento sobre as tecnologias escolhidas. |
  |  Qualidade   |      Riscos consequentes da qualidade do produto final.      |

  

* Riscos de Gerenciamento:

  |   **Tipo**   |                          Descrição                           |
  | :----------- | :----------------------------------------------------------- |
  |  Estimativa  |     Riscos que afetam o tempo de realização do projeto.      |
  |   Controle   |         Riscos que afetam o controle de atividades.          |
  | Planejamento | Riscos relacionados ao planejamento de elaboração do projeto. |
  | Comunicação  | Riscos relacionados aos meios de comunicação como, por exemplo, a falta de comunicação da equipe. |

  

* Riscos Organizacionais:

  |   **Tipo**   |                        **Descrição**                         |
  | :----------- | :----------------------------------------------------------- |
  |   Recursos   | Riscos que são consequentes da falta de material físico e/ou tecnológico. |
  | Priorização  | Riscos decorrentes pela má escolha de histórias de usuários nas <i>Sprints</i>. |
  | Dependências | Riscos que podem ser gerados por dependências que afetam a evolução do projeto. |

  

* Riscos externos:

  |             Tipo             |                        **Descrição**                         |
  | :--------------------------- | :----------------------------------------------------------- |
  | Cliente (<i>StakeHolder</i>) | Riscos gerados pelo cliente em relação ao produto, como mudanças repentinas no escopo devido a um pedido do cliente. |
  |         Pandemia COVID-19         | Riscos provenientes da COVID-19 que podem afetar os membros do grupo e atrasar a entrega das atividades, além de que não existe a possibilidade de encontros presenciais entre os alunos e o cliente. |

  ## 4. Análise Quantitativa de Riscos

  A análise quantitativa de riscos consiste na priorização e categorização dos riscos de acordo com 2 métricas:
  * **Probabilidade:** chances de um risco ocorrer;
  * **Impacto:** o quanto o risco impacta no projeto;

### Tabela 4.1 - Probabilidade

| **Probabilidade** |  Certeza  | **Peso** |
| :---------------: | :-------: | :------: |
|    Muito baixa    |  < 10%        |    1     |
|       Baixa       | de 10% a 25%  |    2     |
|       Média       | de 25% a 50%  |    3     |
|       Alta        | de 50% a 75%  |    4     |
|    Muito Alta     | > 75%         |    5     |

### Tabela 4.2 - Impacto

| **Impacto** |              **Descrição**              | Peso |
| :---------: | :-------------------------------------- | :--: |
| Muito baixo |            Pouco Expressivo             |  1   |
|    Baixo    |              Pouco Impacto              |  2   |
|    Médio    |              Impacto Médio              |  3   |
|    Alto     |             Grande Impacto              |  4   |
| Muito Alto  | Impacto impede a continuação do projeto |  5   |

O grau de risco é definido pela multiplicação da probabilidade pelo impacto. Conforme a tabela abaixo:

| Impacto/Probabilidade | Muito Baixa | Baixa | Média | Alta | Muito Alta |
| :-------------------: | :---------: | :---: | :---: | :--: | :--------: |
|      Muito Baixa      |      1      |   2   |   3   |  4   |     5      |
|         Baixa         |      2      |   4   |   6   |  8   |     10     |
|         Média         |      3      |   6   |   9   |  12  |     15     |
|         Alta          |      4      |   8   |  12   |  16  |     20     |
|      Muito Alta       |      5      |  10   |  15   |  20  |     25     |

Sendo que:

Risco >= 15: Elevado,

5 < Risco < 15: Médio e

Risco <= 5: Baixo.



## 5. Identificação dos Riscos

|  ID  |                              Se                              |                          Por conta                           |                        O impacto será                        |      Categoria EAR       |
| :--: | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- | :----------------------- |
|  1   |        o projeto não atender aos requisitos propostos        | do levantamento de requisitos falho e falta de validação constante | atraso na entrega do produto final e redefinição dos requisitos |        Requisitos        |
|  2   |           a tecnologia usada apresentar problemas            |                     do seu proprietário                      | atraso na entrega do produto final e troca de tecnologia equivalente |       Tecnologias        |
|  3   | a equipe de desenvolvimento não se adaptar as tecnologias escolhidas |  da falta de conhecimento ou da indisponibilidade da equipe  |               que o produto não será entregue                |       Complexidade       |
|  4   | o arquiteto não conseguir planejar e garantir a execução da arquitetura |  da falta de conhecimento das tecnologias do projeto  |               dificuldade na organização e atraso no desenvolvimento                |       Complexidade       |
|  5   |         houver dificuldades em realizar os testes          |                   da falta de conhecimento                   |         atraso na entrega das histórias de usuários          |       Complexidade       |
|  6   |                houver mudanças arquiteturais                 |               da falha na realização do escopo               | mais retrabalho, como alteração nas histórias de usuários planejadas, mudanças de infra e mudanças a nível de código |       Complexidade       |
|  7   |                a equipe não conseguir automatizar o *deploy* e a integração contínua                 |               da falta de conhecimento               | atraso na entrega do produto em ambiente de produção |       Complexidade       |
|  8  |                   houver mudança de escopo                   | da falha na realização do escopo e na elicitação dos requisitos |         refatoração dos requisitos e da documentação         |       Planejamento       |
|  9   |          o produto final estiver em baixa qualidade          |                 da equipe de desenvolvimento                 |                refatoração de todo o produto                 |        Qualidade         |
|  10   |   as atividades não forem concretizadas no prazo definido    |       da falta de integração dos integrantes da equipe       |                atraso na baseline do projeto                 | Estimativa/Dependências |
|  11   |          houver histórias de usuário mal definidas           |             da falha de elicitação de requisitos             | atraso na entrega do produto final e necessidade de refatoração das histórias |        Estimativa        |
|  12  |                 houver sprint mal planejada                  |                 de histórias mal planejadas                  | atraso na entrega do produto final, dificuldade de compreensão das histórias e necessidade de refatoração |  Estimativa/Priorização  |
|  13  |            houver falta de comunicação da equipe             |                da indisponibilidade da equipe                | dificuldade no gerenciamento e falta de alinhamento da equipe |       Comunicação        |
|  14  |           membros da equipe abandonarem o projeto            |             de desmotivação e indisponibilidade              |       sobrecarga entre os membros da equipe restantes        |         Recursos         |
|  15  | a qualidade do *software* não atender as expectativas do cliente | má implementação e erros na parte de elicitação de requisitos | descontentamento do cliente e possibilidade de cancelamento do projeto |    Cliente/Qualidade     |
|  16  |          houver perdas ou defeitos em equipamentos           |                       mal uso e roubos                       |                 atraso na entrega do projeto                 |         Recursos         |
|  17  |               houver o cancelamento do projeto               |               da falta de interesse do cliente               |           interrupção e/ou cancelamento do projeto           |         Cliente          |
|  18  |                     algum membro não poder participar das atividades e reuniões                      | de contrair a doença COVID-19                    |             Atraso na entrega das atividades       | Estimativa/Dependências
|  19  |          não ocorrer a contratação d@ *Designer* para a realização do protótipo de alta fidelidade           |     de variáveis externas ou por não encontrar um profissional adequado dentro do prazo estipulado      |  atraso na entrega do produto e/ou interrupção do projeto   | Cliente/Dependências  |
|  20  |          houver imaturidade na gerência do projeto           |     de negligências e abandono de integrantes da equipe      |  diminuição da qualidade do projeto e atraso das histórias   | Estimativa/Dependências  |



## 6. Interpretação

|  ID  |  Impacto   | Probabilidade | Avaliação |                         Contigência                          |                          Mitigação                           |
| :--: | :--------: | :-----------: | :-------: | :----------------------------------------------------------- | :----------------------------------------------------------- |
|  1   | Muito Alto |  Muito Alta   |    25     | Revalidar todo os requisitos com o *Product Owner* e com o cliente | Realizar constantes reuniões com os integrantes da equipe, com o cliente e pesquisas necessárias para obtenção de conhecimento e compreensão sobre o escopo do projeto |
|  2   | Muito Alto |     Baixa     |    10     |         Trocar para uma nova tecnologia equivalente          |             Escolher uma tecnologia com suporte              |
|  3   |    Alto    |     Alta      |    16     | Indicar treinamentos para a equipe de desenvolvimento sobre a tecnologia escolhida | Estabelecer treinamentos constantes sobre a tecnologia escolhida |
|  4   |    Crítico    |     Alta      |    16     | Realizar a mudança na arquitetura e buscar novas soluções | Buscar conhecimento na *internet*, com professores, alunos e/ou pessoas de fora da comunidade universitária |
|  5   | Muito Alto |     Alta      |    20     | Indicar treinamentos para a equipe de desenvolvimento sobre testes |       Estabelecer treinamentos constantes sobre testes       |
|  6   | Muito Alto |     Média     |    15     | Realizar a mudança de Arquitetura do projeto buscando outras tecnologias capazes de solucionar os problemas gerados | Buscar conhecimento com professores, alunos e pessoas fora do ambiente universitária, novas pesquisas e pensamentos críticos a respeito da arquitetura. |
|  7  |    Alto    |     Alta      |    16     | Procurar ajuda de professores, alunos e pessoas fora do ambiente universitário e aumentar o tempo de estudo | Realização de pesquisas constantes e consultoria com outros alunos, professores e pessoas fora do ambiente universitário |
|  8   | Muito Alto |     Baixa     |    10     |    Redefinir o mais rápido possível as mudanças de escopo    |         Manter a comunicação constante com o cliente         |
|  9   | Muito Alto |  Muito Alta   |    25     | Realizar a refatoração de código, testes e validação com o cliente | Realizar treinamentos de todas as tecnologias utilizadas, além de garantir a realização de testes, boas práticas de programação e validações constantes com o cliente |
|  10   | Muito Alto |  Muito Alta   |    25     | Realizar a entrega das histórias na próxima <i>Sprint</i> como dívida técnica | Planejar as atividades de forma mais coerente e dividi-las nas *sprints* com base nos pesos e dificuldade definida no <i>Planning Poker</i> |
|  11   |    Alto    |  Muito Alta   |    20     | Realizar uma refatoração das histórias para que entrem em conformidade com os requisitos pré-definidos | Realizar constantes reuniões entre os integrantes da equipe e o cliente e, além disso, realizar pesquisas necessárias para obtenção de conhecimento e compreensão sobre o escopo do projeto |
|  12  |    Alto    |     Alta      |    16     | Realizar o replanejamento da <i>Sprint</i> utilizando a priorização do <i>Backlog</i> do Produto | Montar o <i>Backlog</i> da <i>Sprint</i> utilizando a priorização |
|  13  | Muito Alto |     Alta      |    20     | Promover as mudanças necessárias, desde a realização de <i>Daily meetings</i> mais objetivas a mudanças de ferramentas para comunicação | Criando o plano de comunicação em que a equipe concorde totalmente |
|  14  |    Alto    |  Muito Alta   |    20     | Realocar as tarefas pré-definidas entre os membros restantes | Conversar com a equipe a fim de reafirmar a importância do projeto para que a equipe o priorize |
|  15  | Muito Alto |  Muito Alta   |    25     | Realizar a refatoração do código e dos testes e, além disso, validações com o cliente | Realizar treinamento de todas as tecnologias utilizadas, garantir a realização de testes, boas práticas de programação e validações com o cliente |
|  16  |    Alto    |     Média     |    12     | Realocar as tarefas entre os membros da equipe que possuem equipamentos sem defeitos |      Incentivar a manutenção recorrente de equipamentos      |
|  17  | Muito Alto |  Muito baixa  |     5     |  Oferecer a melhor possibilidade de produto para o cliente   |          Manter comunicação constante com o cliente          |
|  18  | Muito Alto |     Média     |    15     |  Realocar as atividades entre os membros da equipe          |                                  Conversar com a equipe a fim de reatribuir todas as tarefas enquanto o(s) membro(s) está(ão) ausente(s)                           |
|  19  | Muito Alto |     Muito Alta     |    25     |  A equipe elaborar o protótipo de alta fidelidade                           | - 
|  20  |    Alto    |     Média     |    12     | Conversar com os membros imaturos e mostrar que o projeto deve ser levado a sério | Manter o pensamento crítico e estratégico a respeito das métricas coletadas e realizando todos os rituais das metologias definidas |


## 7. BurnDown de Riscos
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTVH-Hl8czZKyUT7gAHaDADz76NQitwQn_dY24aJyR1hXXX4e4MAtM79dLgpTEabqA-Nibz6YKRlhtm/pubhtml" width="170px" height="600px"></iframe>



## Referências

* FILHO, Ateldy; GOMES, Vitor; SOUZA, João; DANTAS, Bruno; Ada - Plano de Gerenciamento de Riscos. Disponível em: <https://fga-eps-mds.github.io/2019.1-ADA/#/docs/project/risk_management_plan>. Acesso em: 13 ago. 2021.
* Aula13-1 - Gerenciamento dos Riscos: Processo: Planejar o gerenciamento dos riscos. Disponível em: <https://www.youtube.com/watch?v=HDMS7ftQJb0&feature=youtu.be>. Acesso em: 13 ago. 2021.