# Política de Branches

| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 05/08/2021 | 1.0 | Criação do documento de *Branches*  | [Iuri Severo](https://github.com/iurisevero), [João Guedes](https://github.com/sudjoao), [Lucas Fellipe](https://github.com/lucasfcm9) e [Pedro Rodrigues](https://github.com/pedro-prp) |
| 13/09/2021 | 2.0 | Atualização da política de *Branches* | [João Guedes](https://github.com/sudjoao)) |

As _branches_ devem seguir o seguinte padrão:

* O nome da *branch* deve ser abstraído do nome da história de usuário a qual se refere.

<b>Exemplo:</b>

```
CriarLogin
```

* O nome da *branch* deve possuir um '*tag*' que é o código do épico e da história de usuário a qual se refere.

<b>Exemplo:</b>

```
E01US03CriarLogin
```

* A _branch_ deverá possuir o padrão CamelCase ```ExUSy-NomeDaBranch ```, em que o 'x' é o número do épico e 'y' o número da história de usuário.

<b>Exemplo:</b>

```
E01US03-CriarLogin
```

* Caso a _branch_ não esteja associada a alguma história de usuário, adiciona-se a tag com o número da issue.

<b>Exemplo:</b>

```
4-RefatorarLogin
```