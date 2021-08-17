# Documento de Visão

| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 16/08/2021 | 1.0 | Criação do documento de visão  | [Natan Tavares Santana](https://github.com/Neitan2001) |
| 16/08/2021 | 1.1 | Tópico 1  | [Natan Tavares Santana](https://github.com/Neitan2001) |
| 17/08/2021 | 1.2 | Tópico 2  | [Natan Tavares Santana](https://github.com/Neitan2001) |

## 1. Introdução

### 1.1 Propósito

<p align="justify"> &emsp;&emsp;Este documento tem como objetivo esclarecer e documentar as características e aplicações do desenvolvimento da plataforma Pró-Espécies Peixes (nome em desenvolvimento). A fim de expressar a visão desse <i>software</i>, diversos aspectos relacionados ao mesmo serão expostos.</p>

### 1.2 Escopo

<p align="justify"> &emsp;&emsp;O Pró-Espécies Peixes (nome em desenvolvimento) é um aplicativo <i>mobile</i>, desenvolvido por alunos de Engenharia de Software da UnB do campus da FGA, que possui o objetivo de auxiliar o projeto “Pró-Espécies: Todos contra a extinção” que foi aprovado pela coordenação técnica do Ministério
do Meio Ambiente em 2014 e tem como agência executora o WWF-Brasil.</p>
<p align="justify">&emsp;&emsp;Neste projeto estão incluídos os Planos de Ação para conservação de espécies
avaliadas como criticamente ameaçadas de extinção pelas avaliações nacionais além dos Planos de Ação Territoriais (PATs) para territórios identificados como
prioritários para a conservação das espécies ameaçadas.</p>
<p align="justify">&emsp;&emsp;Dito isso, o Pró-Espécies Peixes (nome em desenvolvimento) atua dentro da ação 4.1 do Plano de Ação para conservação das espécies do Território Cerrado Tocantins com a finalidade aumentar o volume de informações disponíveis sobre as espécies de peixes que compõem parte significativa das espécies ameaçadas de extinção no Cerrado brasileiro.</p>

### 1.3 Definições, acrônimos e abreviações

| Termos      | Definição |
|:----------:|:------:|
| UnB | Universidade de Brasília | 
| FGA | Faculdade do Gama | 
| EPS | Equipe de Engenharia de Produto de Software | 
| MDS | Equipe de Métodos de Desenvolvimento de Software |
| Git | Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software|
| WWF-Brasil | O WWF-Brasil é uma organização da sociedade civil brasileira, apartidária e sem fins lucrativos que trabalha em defesa da vida, com o propósito de mudar a atual trajetória de degradação socioambiental|

### 1.4 Referências

- IBM Knowledge Center - Documento de Visão: A estrutura de tópicos do documento de visão. Disponível em: https://www.ibm.com/docs/pt-br/elm/6.0.5?topic=requirements-vision-document. Acesso em 16 de ago. de 2021;
- Disponível em: https://fga-eps-mds.github.io/2019.1-ADA/#/docs/product/vision_document?id=_1-introdu%c3%a7%c3%a3o. Acesso em 16 de ago. de 2021;
- Disponível em: https://fga-eps-mds.github.io/2019.1-Aix/projeto/2019/03/29/documento-de-visao/. Acesso em 16 de ago. de 2021;

### 1.5 Visão Geral
<p>&emsp;&emsp;Desta forma, a ideia principal deste documento de visão é fornecer de maneira objetiva e organizada os assuntos que tangem à problemática inicial.</p>
<p>&emsp;&emsp;As informações serão organizadas em tópicos referentes aos seguintes temas, como modelos de exemplo: o contexto da tecnologia no meio pedagógico, o detalhamento dos perfis interessados, as funcionalidades principais da ferramenta a ser produzida bem como característica técnicas do produto.</p>

## 2. Posicionamento

### 2.1 Oportunidades de negócios
<p>&emsp;&emsp;Um dos grandes desafios do projeto “Pró-Espécies: Todos contra a extinção” é a coleta de dados sobre as espécies ameaçadas de extinção dado que para fazer isso, é necessário muitos recursos e muito tempo em pesquisa de campo. Assim, umas das soluções levantadas para esse problema é usar o apio da população brasileira para fazer essa coleta de dados por meio de um aplicativo de celular.</p>
<p>&emsp;&emsp;Nesse sentido, o Pró-Espécies Peixes (nome em desenvolvimento) possui o objetivo de incentivar pescadores a fazer relatórios sobre os peixes pescados, a fim de mapear e juntar dados sobre peixes em risco de extinção.</p>

### 2.2 Descrição do Projeto

#### 2.2.1 Pesquisadores:
<table>
  <tr><th> O problema de </th><td>Falta de tempo/recurso para ir atrás dos dados das espécies de peixes em risco, que podem se encontrar em áreas de difícil acesso</td></tr>
  <tr><th> afeta </th><td>Pesquisadores do projeto “Pró-Espécies: Todos contra a extinção”</td></tr>
  <tr><th> cujo impacto é </th><td>Impossibilidade de coleta de dados necessários para levantar ações do projeto.</td></tr>
  <tr><th> uma boa solução seria </th><td>A criação de um aplicativo para que pescadores possam usar a fim de fazer relatórios</td></tr>
</table>

#### 2.2.2 Pescadores:

<table>
  <tr><th> O problema de </th><td>Falta de motivação para relatar espécies sensíveis a extinção em localidades de difícil acesso</td></tr>
  <tr><th> afeta </th><td>Pescadores</td></tr>
  <tr><th> cujo impacto é </th><td>Os pesquisadores ficarem sem dados para serem analisados.</td></tr>
  <tr><th> uma boa solução seria </th><td>A criação de um aplicativo acessível que facilite e incetive a criação de um relatório de peixe pelos pescadores</td></tr>
</table>

### 2.3 Sentença de Posição do Produto

<table>
  <tr><th> Para </th><td>Pesquisadores que não possuem tempo/recurso para ir atrás dos dados dessas espécies em risco e para pescadores que não possuem motivação para relatar espécies sensíveis a extinção em localidades de difícil acesso</td></tr>
  <tr><th> O Pró-Espécies Peixes </th><td>É um Aplicativo Mobile, que facilita o acesso dos dados das especies até o pesquisador, ondem os pescadores mapeam e as catalogam</td></tr>
  <tr><th> Diferente de  </th><td>Pesca+ e iNaturalist</td></tr>
  <tr><th> Nosso produto  </th><td>tem praticidade de acesso a informação, é acessível e focado na preservação das espécies de peixes</td></tr>
</table>