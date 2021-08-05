# Política de Pull Requests

| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 05/08/2021 | 1.0 | Criação do documento de *Pull Requests*  | [Iuri Severo](https://github.com/iurisevero), [João Guedes](https://github.com/sudjoao), [Lucas Fellipe](https://github.com/lucasfcm9) e [Pedro Rodrigues](https://github.com/pedro-prp) |

Os *pull requests* devem seguir o seguinte padrão:

* O *pull request* deve indicar em seu título o número e nome da *issue*, ao qual *issue* se refere.

<b>Exemplo</b>

```
#1 Criação da Rich Picture
```

* Para indicar que o *pull request* ainda não está completo para o merge, usa-se a '*tag*' WIP(*Work in Progress*).

<b>Exemplo</b>

```
WIP #1 NovoDocumento
```

* Para o conteúdo do *pull request*, deve ser descrito de forma sucinta.

```
Neste pull request se realizou:
  * US 01
  * Validação
  * Testes
  * Correção de bug ao...
```

* Deve conter um ```Reviewer```, em que indica-se pelo menos um membro da equipe de Métodos de Desenvolvimento de *Software* ou de Engenharia de Produto de *Software* a ser responsável por analisar as modificações submetidas.

* Deve conter um ou mais ```Assignees```, em que indica os membros da equipe que contribuíram com as modificações realizadas.

* Deve conter ```Labels```, em que adicionam-se as labels referentes ao *pull request*, de forma similar às da *issue* correspondente.

* Deve conter a ```Milestone```, em que é adicionada a sprint correspondente à execução das modificações.

* Deve conter a ```Issue```, em que, após a criação do *pull request*, deve-se conectar ele à sua *issue* correspondente através da interface do GitHub.