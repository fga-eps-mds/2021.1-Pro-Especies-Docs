# Documento de Visão

|    Data    | Versão |                                      Descrição                                      |                             Autor                              |
| :--------: | :----: | :---------------------------------------------------------------------------------: | :------------------------------------------------------------: |
| 16/08/2021 |  0.1   |                            Criação do documento de visão                            |     [Natan Tavares Santana](https://github.com/Neitan2001)     |
| 16/08/2021 |  0.2   |                                     Introdução                                      |     [Natan Tavares Santana](https://github.com/Neitan2001)     |
| 17/08/2021 |  0.3   |                                   Posicionamento                                    |     [Natan Tavares Santana](https://github.com/Neitan2001)     |
| 19/08/2021 |  0.4   |                         Visão Geral do Produto e Restrições                         |      [João Victor Batista](https://github.com/jvBatista)       |
| 20/08/2021 |  0.5   |                                 Recursos do Produto                                 | [Gabriel Freitas Balbino](https://github.com/gabrielfreitass1) |
| 20/08/2021 |  0.6   |                    Descrições da Parte Interessada e do Usuário                     | [Daniel Coimbra dos Santos](https://github.com/DanielCoimbra)  |
| 21/08/2021 |  0.7   | Precedência e Prioridade, Outros Requisitos do Produto e Requisitos de Documentação |   [Paulo Henriuqe Rezende](https://github.com/phrezende-eng)   |
| 21/08/2021 |  1.0   |                Correção de erros ortográficos e adição de referência                |     [Natan Tavares Santana](https://github.com/Neitan2001)     |
| 25/08/2021 |  1.1   |                Revisão do documento, correção de erros e formatação do documento    |     [Lucas Fellipe](https://github.com/lucasfcm9)              |

## 1. Introdução

### 1.1 Propósito

Este documento tem como objetivo esclarecer as características e aplicações da plataforma Pró-Espécies Peixes, a fim de expressar a visão deste <i>software</i>. Dessa forma, diversos aspectos relacionados ao mesmo serão expostos.

### 1.2 Escopo

<p align="justify">&emsp;&emsp;O Pró-Espécies Peixes é um aplicativo <i>mobile</i>, desenvolvido por alunos de Engenharia de <i>Software</i> da UnB do campus da FGA, que possui o objetivo de auxiliar o projeto “Pró-Espécies: Todos contra a extinção” que foi aprovado pela coordenação técnica do Ministério
do Meio Ambiente em 2014 e tem como agência executora o WWF-Brasil. Neste projeto estão incluídos os Planos de Ação para conservação de espécies
classificadas como criticamente ameaçadas de extinção pelas avaliações nacionais além dos Planos de Ação Territoriais (PATs) para territórios identificados como
prioritários para a conservação das espécies ameaçadas.</p>
<p align="justify">&emsp;&emsp;Sendo assim, o Pró-Espécies Peixes atua dentro da ação 4.1 do Plano de Ação para conservação das espécies do Território Cerrado Tocantins com a finalidade aumentar o volume de informações disponíveis sobre as espécies de peixes que compõem parte significativa das espécies ameaçadas de extinção no Cerrado brasileiro.</p>

### 1.3 Definições, acrônimos e abreviações

|   Termos   |                                                                                                Definição                                                                                                 |
| :--------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|    UnB     |                                                                                         Universidade de Brasília                                                                                         |
|    FGA     |                                                                                            Faculdade do Gama                                                                                             |
|    EPS     |                                                                               Equipe de Engenharia de Produto de *Software*                                                                                |
|    MDS     |                                                                             Equipe de Métodos de Desenvolvimento de *Software*                                                                             |
|    Git     |                                                 Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de *software*                                                 |
| WWF-Brasil | O WWF-Brasil é uma organização da sociedade civil brasileira, apartidária e sem fins lucrativos que trabalha em defesa da vida, com o propósito de mudar a atual trajetória de degradação socioambiental |

### 1.4 Referências

- IBM Knowledge Center - Documento de Visão: A estrutura de tópicos do documento de visão. Disponível em: https://www.ibm.com/docs/pt-br/elm/6.0.5?topic=requirements-vision-document. Acesso em: 16 ago. 2021;.
- *Documento de Visão*. ADA. Disponível em: https://fga-eps-mds.github.io/2019.1-ADA/#/docs/product/vision_document?id=_1-introdu%c3%a7%c3%a3o. Acesso em: 16 ago. 2021.
- *Documento de Visão*. AIX. Disponível em: https://fga-eps-mds.github.io/2019.1-Aix/projeto/2019/03/29/documento-de-visao/. Acesso em: 16 ago. 2021.
- WWF- Brasil. Disponível em: https://www.wwf.org.br/wwf_brasil/. Acesso em: 16 ago. 2021.

### 1.5 Visão Geral
A ideia principal deste documento de visão é fornecer, de maneira objetiva e organizada, os assuntos que tangem à problemática inicial. As informações serão organizadas em tópicos referentes aos seguintes temas, como modelos de exemplo: o contexto da tecnologia no meio ambiental, o detalhamento dos perfis interessados, as funcionalidades principais da ferramenta a ser produzida, bem como características técnicas do produto.</p>

## 2. Posicionamento

### 2.1 Oportunidades de negócios
<p>&emsp;&emsp;Um dos grandes desafios do projeto “Pró-Espécies: Todos contra a extinção” é a coleta de dados sobre as espécies ameaçadas de extinção, dado que, para fazer isso, é necessário uma grande quantidade de recursos e muito tempo em pesquisa de campo. Assim, umas das soluções levantadas para esse problema é usar o apoio da população brasileira para fazer essa coleta de dados por meio de um aplicativo de celular. Nesse sentido, o aplicativo do Pró-Espécies possui o objetivo de incentivar pescadores a fazerem relatórios sobre os peixes pescados, a fim de mapear e juntar dados sobre peixes em risco de extinção.</p>

### 2.2 Descrição do Projeto

#### 2.2.1 Pesquisadores:
<table>
  <tr><th> O problema de </th><td>Falta de tempo/recurso para ir atrás dos dados das espécies de peixes em risco, que podem se encontrar em áreas de difícil acesso.</td></tr>
  <tr><th> Afeta </th><td>Pesquisadores do projeto “Pró-Espécies: Todos contra a extinção”.</td></tr>
  <tr><th> Cujo impacto é </th><td>Impossibilidade de coleta de dados necessários para levantar ações do projeto.</td></tr>
  <tr><th> Uma boa solução seria </th><td>A criação de um aplicativo para que pescadores possam usar a fim de fazer relatórios</td></tr>
</table>

#### 2.2.2 Pescadores:

<table>
  <tr><th> O problema de </th><td>Falta de motivação para relatar espécies sensíveis a extinção em localidades de difícil acesso.</td></tr>
  <tr><th> Afeta </th><td>Pescadores.</td></tr>
  <tr><th> Cujo impacto é </th><td>Os pesquisadores ficarem sem dados para serem analisados.</td></tr>
  <tr><th> Uma boa solução seria </th><td>A criação de um aplicativo acessível que facilite e incetive a criação de um relatório de peixe pelos pescadores.</td></tr>
</table>

### 2.3 Sentença de Posição do Produto

<table>
  <tr><th> Para </th><td>Pesquisadores que não possuem tempo/recurso para ir atrás dos dados dessas espécies em risco e para pescadores que não possuem motivação para relatar espécies sensíveis a extinção em localidades de difícil acesso.</td></tr>
  <tr><th> O Pró-Espécies Peixes </th><td>É um aplicativo <i>mobile</i>, que facilita o acesso dos dados das espécies até o pesquisador, onde os pescadores mapeam e catalogam tais dados.</td></tr>
  <tr><th> Diferente de  </th><td>Pesca+ e iNaturalist.</td></tr>
  <tr><th> Nosso produto  </th><td>Tem praticidade de acesso a informação, é acessível e focado na preservação das espécies de peixes.</td></tr>
</table>

## 3. Descrições da Parte Interessada e do Usuário

### 3.1 Resumo da Parte Interessada:
| **Nomes**                                   | **Descrição**                                                                                    | **Responsabilidades**                                                                                    |
| ------------------------------------------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- |
| Equipe de Desenvolvimento de *Software*       | Estudantes da disciplina de Métodos de Desenvolvimento de *Software*, da Universidade de Brasília. | Desenvolver e implementar o *Software* descrito no documento.                                              |
| Equipe de Engenharia de Produto de *Software* | Estudantes da disciplina de Engenharia de Produto de *Software*, da Universidade de Brasília.      | Gestão da Equipe de Desenvolvimento, garantindo a viabilidade do produto por meio de entregas contínuas. |
| Equipe de Orientação                        | Professores e monitores das disciplinas de EPS e MDS.                                            | Auxiliar a equipe durante o desenvolvimento do *Software*.                                                 |

### 3.2 Resumo do Usuário:
  O aplicativo do Pró-Espécies tem como principal objetivo coletar dados sobre o nicho ecológico de peixes, inicialmente no Estado do Tocantins. Os usuários podem ser dividos em dois grupos:
  - O pesquisador, que é quem busca os dados sobre os peixes;
  - Os pescadores, sejam guias de pesca, pescadores esportivos ou pescadores recreativos, os principais agentes da coleta dos dados.

### 3.3 Ambiente do Usuário:
O usuário irá usar um *smartphone* para fazer os registros. Como os locais de pesca/pesquisa serão corpos d'água em geral, é importante salientar que a conexão à *internet* será escassa. Por esse motivo, o aplicativo suportará a falta de internet durante a composição dos relatórios.

### 3.4 Perfis das Partes Interessadas:
  #### 3.4.1 Equipe de Desenvolvimento de Software
| **Representantes**       | Daniel Coimbra, Gabriel Freitas, Natan Tavares, João Victor e Paulo Henrique                     |
| ------------------------ | ------------------------------------------------------------------------------------------------ |
| **Descrição**            | Desenvolvimento do *Software*.                                                                     |
| **Tipo**                 | Estudantes da disciplina de Métodos de Desenvolvimento de *Software*, da Universidade de Brasília. |
| **Responsabilidades**    | Desenvolvimento, implementação e testes do *Software*.                                              |
| **Critérios de Sucesso** | Entrega do aplicativo com todas as funcionalidades, dentro do prazo estipulado.                  |
| **Envolvimento**         | Alto.                                                                                            |

#### 3.4.2 Equipe de Engenharia de Produto de Software
| **Representantes**       | Iuri Severo, João Pedro, Lucas Fellipe e Pedro Rodrigues                                                                                    |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Descrição**            | Estudantes da disciplina de Engenharia de Produto de *Software*, da Universidade de Brasília.                                                |
| **Responsabilidades**    | Cada um dos alunos tem um responsabilidade diferente na Equipe: *Product Owner*, Arquiteto De *Software*, Engenheiro *DevOps* e *Scrum Master*. | --------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Critérios de Sucesso** | Certificar de manter as entregas dentro do prazo e controlar a qualidade do *Software* em desenvolvimento                                    |
| **Envolvimento**         | Alto.                                                                                                                                      |

#### 3.4.3 Equipe de Orientação
Hilmer Rodrigues Neri, professor da Universidade de Brasília, das matérias Métodos de Desenvolvimento de Software e Engenharia de Produto de Software, que tem como objetivos:
* Capacitar o aluno a compreender e aplicar conhecimentos de diferentes métodos, ferramentas, procedimentos e paradigmas de desenvolvimento de *software*.
* Formar o aluno em diferentes técnicas de como se gerenciar, de forma sistemática e disciplinada, todo o ciclo de vida do *software*.

### 3.5 Perfis do Usuário
  #### 3.5.1 Pesquisador
  Pesquisadores que terão acesso a áreas restritas do aplicativo. Como leitura e escrita dos relatórios enviados, além das demais funcionalidades do aplicativo. Serão como moderadores do aplicativo.
  #### 3.5.2 Pescador esportivo
  Pescadores entusiastas, podem contribuir com suas observações e pescas de espécies da região.
  #### 3.5.3 Pescador artesanal 
  Pescadores locais, de linha de frente. Esses possuem acesso às espécies de peixes, seja observando ou pescando. Além disso, serão capazes de contribuir para a coleta.
### 3.6 Principais Necessidades da Parte Interessada ou do Usuário:
  #### 3.6.1 Necessidades da Parte Interessada
  Uma forma de coletar de dados de peixes, inicialmente para o estado do Tocantins. A população que já tem contato com essas espécies poderá ajudar o estado fazendo relatórios sobre pescas e observações, enviando-os através do aplicativo do Pró-Espécies.
  #### 3.6.2 Necessidades do Usuário
  O usuário irá se beneficiar da biblioteca de dados sobre as espécies de peixes, com grande contribuição da equipe dos pesquisadores. Também será possível se orientar utilizando georeferência em um mapa.
  
## 4. Visão Geral do Produto

### 4.1 Perspectiva do Produto

<p>&emsp;&emsp;O produto tem por objetivo principal a disponibilização de informações a respeito da fauna aquática (principalmente peixes) do Brasil, inicialmente com ênfase no estado do Tocatins. Diferentemente dos demais no mercado, que buscam, em sua maioria, incetivar a prática da pesca, o produto aborda o tema da pesca visando facilitar o levantamento e recolhimento de dados para pesquisadores da área de ictiologia da região e, assim, ajudar a preservação de tais espécies de peixes. Dessa forma, o produto possui funcionalidades que incentivam a participação de pescadores locais, não reforçando a prática da pesca em si, mas sim, procurando a colaboração de tais profissionais para que possam, através do preenchimento e envio de relatórios, contribuir com a coleta de dados científicos.</p>

### 4.2 Resumo das Capacidades

| Benefício para o Cliente                                                                                                                      | Recursos de Suporte                                                                                                                               |
| --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Facilitar o recolhimento de dados científicos para usuários pesquisadores, para os quais faltam tempo, recursos e acesso a áreas mais remotas | Sistema de criação e envio de relatórios flexíveis por parte dos usuários pescadores para os pesquisadores, como alternativa a pesquisas de campo |
| Disponibilizar, para os usuários pescadores, informações a respeito de espécies de peixes da região                                           | Sistema de biblioteca que contém informações, fornecidas pelos pesquisadores, a respeito de variadas espécies de peixes                           |
| Disponibilizar, para os usuários pescadores, referências sobre a localização de espécies de peixes da região                                  | Sistema de mapeamento da região foco do produto com indicação da localização de espécies de peixes selecionadas pelos pesquisadores               |

## 5. Recursos do Produto

### 5.1 Realizar Relatórios
O usuário consegue fazer um relatório sobre um peixe e mandá-lo para um pesquisador analisá-lo.

### 5.2 Ajudar Pesquisadores
Pesquisadores previamente cadastrados conseguem visualizar relatórios feitos por outros usuários e, assim, identificar novas espécies ou atualizar informações sobre os já existentes.

### 5.3 Georeferência 
O usuário consegue visualizar onde é possivel encontrar uma espécie de peixe com a ajuda de um mapa com a georeferência da espécie. No caso, essa função não estará disponível para espécies em risco de extinção.

### 5.4 Biblioteca Virtual
O usuário consegue acessar uma biblioteca virtual de peixes pré-cadastrados e visualizar uma foto da espécie e suas informações.

## 6. Restrições
- Acesso à internet;
- Acesso a um dispositivo com sistema operacional **Android API 19** ou superior e/ou **iOS 9** ou superior;
- Toda interação com o aplicativio deve ser feita de forma intuitiva e natural, de modo que o usuário não tenha dúvidas sobre como realizar determinada ação dentro da plataforma. As funcionalidades as quais os usuários têm acesso devem ser de fácil entendimento. Dessa forma, a complexidade e dinamismo das funcionalidades serão limitados, visando priorizar a clareza e acessibilidade do produto.

## 7. Precedência e Prioridade
Para o MVP serão realizadas as funcionalidades na seguinte ordem:
 - Biblioteca Virtual;
 - Realizar Relatórios;
 - Biblioteca Virtual;
 - Georeferência.

## 8. Outros Requisitos 
### 8.1 Padrões Aplicáveis:
 - Padrões de conformidade da plataforma (iOS/Android).

## 9. Requisitos de Documentação
- 10.1 Notas sobre a liberação: Será necessário a apresentação da documentação da qualidade *software* a cada release.
- 10.2 Guia de uso: No ambiente local haverá a guia de execução de funcionamento do produto para a melhor usuabilidade para quem quiser contribuir com o *software*.
