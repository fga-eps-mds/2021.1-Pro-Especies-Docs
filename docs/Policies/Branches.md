# Política de Branches

| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 05/08/2021 | 1.0 | Criação do documento de *Branches*  | [Iuri Severo](https://github.com/iurisevero), [João Guedes](https://github.com/sudjoao), [Lucas Fellipe](https://github.com/lucasfcm9) e [Pedro Rodrigues](https://github.com/pedro-prp) |

As _branches_ devem seguir o seguinte padrão:

* O nome da *branch* deve ser abstraído do nome da história de usuário a qual se refere.

<b>Exemplo:</b>

```
CriarLogin
```

* O nome da *branch* deve possuir um '*tag*' que é o número da história de usuário a qual se refere.

<b>Exemplo:</b>

```
3CriarLogin
```

* A _branch_ deverá possuir o padrão CamelCase ```x-NomeDaBranch ```, em que o 'x' é o número da história de usuário.

<b>Exemplo:</b>

```
3-CriarLogin
```

* Caso a _branch_ não esteja associada a alguma história de usuário, não é necessario a adição da '*tag*'.

<b>Exemplo:</b>

```
RefatorarLogin
```