# Jornadas de Usuário e Sequenciador

| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 09/08/2021 | 1.0 | Criação do documento das atividades de Jornadas de Usuário e Sequenciador  | [Lucas Fellipe](https://github.com/lucasfcm9) |

Reunião realizada no *Discord*.

**Data**: 07 de Agosto de 2021

**Redigida por**: Lucas Fellipe

**Participantes**:

- Daniel Coimbra (MDS)
- Gabriel Freitas (MDS)
- Iuri Severo (EPS)
- João Pedro (EPS)
- Lucas Fellipe (EPS)
- Natan Tavares (MDS)
- João Victor (MDS)
- Paulo Henrique (MDS)
- Pedro Rodrigues (EPS)

Hoje vai acontecer as seguintes atividades: **Jornadas de Usuário** e **Sequenciador**.

## Jornadas de Usuário

<p align="justify"> &emsp;&emsp;Essa etapa consiste na elaboração de um percurso de um usuário por uma sequência de passos para alcançar um determinado objetivo. Nesse caso, utilizamos as <i>personas</i> criadas anteriormente. Essa jornada tem o objetivo de caracterizar a interação da pessoa com o produto. Além disso, a equipe consegue relacionar as funcionalidades definidas anteriormente e atribuí-las as etapas da jornada. Para a realização da atividade, dividimos a equipe em 3 grupos distintos para a elaboração de 3 jornadas.</p>

- Grupo 1 (João Victor, Natan Tavares e Pedro Rodrigues);
- Grupo 2 (Lucas Fellipe e Paulo Henrique);
- Grupo 3 (Iuri Severo, Daniel Coimbra e Gabriel Freitas);

O Grupo 1 ficou responsável pela elaboração da jornada da <i>persona</i> Jerson da Silva, que é o Pescador Esportivo. A jornada ficou da seguinte forma:

- Acorda as 7h e liga a TV para acompanhar o Globo Rural;
- Após seu café da manhã, decide pesquisar sobre um peixe o qual estava buscando;
- Numa rápida pesquisa, ele encontra um app chamada Pró-espécies;
- Baixa o aplicativo, graças a uma interface fácil, consegue realizar o cadastro e continuar;
  - *Design* minimalista (funcionalidade);
  - Linguagem simples (funcionalidade);
  - Sessão de usuário (funcionalidade).
- A funcionalidade que mais o chama atenção é o mapa de calor;
  - Mapa de calor (funcionalidade);
  - Disponibilizar *wiki* de peixes (funcionalidade);
  - Possibilidade de georeferência (funcionalidade).
- Após verificar que na sua região existe uma localidade para o peixe, ele sai para pescar;
  - Mapa de calor (funcionalidade);
  - Disponibilizar *wiki* de peixes (funcionalidade);
  - Possibilidade de georeferência (funcionalidade).
- Ele pesca um peixe diferente, o qual ele não conhecia em anos de pesca competitiva;
- Tira uma foto e solta o mesmo;
  - Fazer relatórios flexíveis (funcionalidade).
- Após isso, ele usa o aplicativo para identificar o peixe raro e já usa os dados para iniciar um registro;
  - CRUD de peixes (funcionalidade);
  - Fazer relatórios flexíveis (funcionalidade);
  - Disponibilizar *wiki* de peixes (funcionalidade).
- Ele volta para a casa após a pescaria e agora com acesso a internet, ele envia o relatório aos pesquisadores;
  - Disponibilizar relatório para os pesquisadores (funcionalidade);
  - Poder enviar relatórios posteriormente (funcionalidade).
- Depois de um certo tempo, ele recebe o retorno do relatório com os dados corrigidos;
  - Pesquisadores poderem modificar os dados (funcionalidade);
  - Disponibilizar relatório para os pesquisadores (funcionalidade).
- Agora ele pode compartilhar com os seus amigos o peixe que pegou e se preparar para o dia seguintes.
  - PBL (funcionalidade);
  - Compartilhar nas redes sociais (funcionalidade).

O Grupo 2 ficou responsável pela elaboração da jornada da <i>persona</i> Joãozão, que é o pesquisador. A jornada ficou da seguinte forma:

- Acorda cedo para ir trabalhar;
- Ao tomar seu café da manhã, ele tenta se planejar mentalmente para o seu dia;
- Chega no laboratório às 8h da manhã;
- Começa a ler tudo sobre a área de Ictiologia;
- Durante a sua leitura, descobre que existe um aplicativo que mostra as espécies sensíveis a extinção encontradas por pescadores;
- Dentro do aplicativo, o pesquisador consegue verificar as informações dos peixes encontrados pelos pescadores;
  - CRUD do peixe (funcionalidade);
  - Disponibilizar *wiki* (funcionalidade);
  - Disponibilizar relatório para os pesquisadores (funcionalidade).
- Devido aos dados que o aplicativo fornece, ele é capaz de prosseguir com alguma pesquisa;
  - Disponibilizar *wiki* (funcionalidade);
  - Disponibilizar relatório para os pesquisadores (funcionalidade).
- Com isso, consegue ter mais contato com outros pesquisadores da área e evoluir suas pesquisas;
  - Disponibilizar relatório para os pesquisadores (funcionalidade).
- Além dos contatos, ele finaliza seus estudos para determinada palestra.

O Grupo 3 ficou responsável pela elaboração da jornada da <i>persona</i> Seu Jorge, que é o Guia de Pesca/Pescador Artesanal. A jornada ficou da seguinte forma:

- Acorda cedo;
- Arruma os equipamentos para o serviço;
- Vai para a água/pescar;
  - Mapa de calor (funcionalidade).
- Busca informações sobre os peixes;
  - *Wiki* (funcionalidade).
- Tem contato direto com espécies (novas ou não) de peixes;
- Conhece o que pescou;
  - *Wiki* (funcionalidade).
- Aponta informações sobre o que foi pescado;
  - CRUD de peixes (funcionalidade);
  - Poder enviar relatórios posteriormente (funcionalidade).
- Volta do trabalho;
- Vende o que pescou/reporta informações para superiores;
  - Reportar para o servidor (funcionalidade).
- Dormir.


## Sequenciador

O Sequenciador de funcionalidades auxilia na organização e visualização das funcionalidades e da sequência de validação incremental do produto. Essa etapa possui algumas regras, são elas:
- Uma onde pode conter no máximo três cartões;
- Uma onda não pode conter mais de um cartão vermelho;
- Uma onda não pode conter três cartões somente amarelos ou vermelhos;
- A soma de esforço dos cartões não pode ultrapassar 5 **E's**;
- A soma de valor dos cartões não pode ser menos de quatro **$'s** e quatro ❤️'s;
- Se um cartão depende de outro, esse outro deve estar em alguma onda anterior.

A equipe discutiu bastante sobre o MVP (**Produto Mínimo Viável**) e como dividiríamos os cartões nas suas respectivas ondas seguindo todas as regras.

As ondas ficaram da seguinte forma:

- **Onda 1**:
  - Registrar dados de um peixe;
  - Sessão de usuário;
  - Disponibilizar *wiki* de espécies de peixes.
- **Onda 2**:
  - Visualizar dados de um peixe;
  - Fazer relatórios flexíveis;
  - Editar e remover dados de um peixe.
- **Onda 3**:
  - Disponibilizar relatórios para os pesquisadores;
  - Possibilidade de georeferência.
- **Onda 4**:
  - Pesquisadores poderem modificar o relatório;
  - Mapa de calor (peixes).
- **Onda 5**:
  - Possibilitar filtros na *wiki*;
  - Poder enviar relatórios posteriormente.
- **Onda 6**:
  - Combinar relatórios com a *wiki*;
  - Fazer uma "peixedex" na *wiki*.
- **Onda 7**:
  - Compartilhar pescas em redes sociais;
  - PBL (Pontos, Medalhas e *Ranking*).

<p align="justify"> &emsp;&emsp;Logo após isso, a equipe discutiu durante um bom tempo sobre em qual onda seria o nosso MVP. Decidimos por definir o nosso MVP na onda 4, mais especificamente, na funcionalidade de "<b>Pesquisadores poderem modificar o relatório</b>". Nesse caso, todas as outras funcionalidades entram como incremento no nosso produto.</p>

# Referências
- CAROLI, Paulo; *Lean Inception: como alinhar pessoas e construir o produto certo*, 2019.