# Documento de Arquitetura

|    Data    | Versão |              Descrição              |                         Autor                          |
| :--------: | :----: | :---------------------------------: | :----------------------------------------------------: |
| 19/08/2021 |  0.1   | Criação do documento de Arquitetura | [Natan Tavares Santana](https://github.com/Neitan2001) |
| 19/08/2021 |  0.2   |              Tópico 4               | [Natan Tavares Santana](https://github.com/Neitan2001) |
| 21/08/2021 |  0.3   |              Tópico 1               | [João Victor Batista](https://github.com/jvBatista) |

## 1. Introdução

### 1.1 Finalidade

<p align="justify"> &emsp;&emsp;Este documento de arquitetura tem como função apresentar uma visão sobre a arquitetura utilizada pelo aplicativo Pró-Espécies Peixes (nome em desenvolvimento) e mostrar como são feitas as conexões entre os elementos utilizados para que o software funcione. A comunicação dele com containers e banco de dados, são alguns destes elementos.</p>

### 1.2 Escopo

<p align="justify"> &emsp;&emsp;Pró-Espécies Peixes (nome em desenvolvimento) é um aplicativo mobile cuja finalidade principal é permitir a criação, edição, validação e exportação de relatórios de campo sobre espécies animais da área de ictiologia nativas do estado do Tocantins no Brasil, de modo a facilitar o levantamento e recolhimento de dados científicos de tais espécies para pesquisadores da região.</p>

<p align="justify"> &emsp;&emsp;Neste artigo serão exploradas todas as estruturas necessárias para o funcionamento do aplicativo e a devida arquitetura desse software, como por exemplo diagrama de classes, visão de casos de uso e visão lógica do produto.</p>

### 1.3 Referências

- Como documentar a Arquitetura de Software. http://www.linhadecodigo.com.br/artigo/3343/como-documentar-a-arquitetura-de-software.aspx
- Documento de arquitetura ADA. https://fga-eps-mds.github.io/2019.1-ADA/#/docs/project/architecture_doc?id=_1-introdu%c3%a7%c3%a3o
- Documento de arquitetura Aix. https://fga-eps-mds.github.io/2019.1-Aix/projeto/2019/03/29/documento-de-arquitetura/


## 4. Visão de Casos de Uso

### 4.1 Diagrama de casos de uso
![Diagrama de casos de uso](../Assets/Images/ArchitectureDocument/casos_de_uso.png)

### 4.2 Especificações dos casos de uso

|                   Casos de Uso                    |          Ator          |                                                 Descrição                                                 |
| :-----------------------------------------------: | :--------------------: | :-------------------------------------------------------------------------------------------------------: |
|             UC01 - Enviar Relatórios              |        Pescador        |              Preencher um relatório com os dados do peixe e enviar o mesmo para ser validado              |
|      UC02 - Enviar Relatórios posteriormente      |        Pescador        | Preencher um relatório do peixe e armazenar no celular para ser enviado assim que tiver acesso à internet |
|           UC03 - Acessar wiki de Peixes           | Pescador e Pesquisador |                           Acessar uma wiki com dados de peixes pré-cadastrados                            |
| UC04 - Disponibilizar relatórios para verificação |      Pesquisador       |                  Acessar relatórios feito por pescadores e visualizar os dados relatados                  |
|            UC05 - Confirmar relatório             |      Pesquisador       |                              Confirmar um relatório enviado por um pescador                               |
|          UC05 - Editar/Deletar Relatório          |      Pesquisador       |                    Editar ou deletar os dados de um relatório enviado por um pescador                     |