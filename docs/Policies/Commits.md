# Política de Commits

| Data       | Versão | Descrição            | Autor             |
|:----------:|:------:|:--------------------:|:-----------------:|
| 05/08/2021 | 1.0 | Criação do documento de *Commits*  | [Iuri Severo](https://github.com/iurisevero), [João Guedes](https://github.com/sudjoao), [Lucas Fellipe](https://github.com/lucasfcm9) e [Pedro Rodrigues](https://github.com/pedro-prp) |


* Os *commits* devem ser escritos em inglês, na forma infinitiva, e ainda conter uma breve descrição:

**Exemplo:**

```Create a new document```

* A *issue* deve ser citada no *commit* por questões de rastreabilidade, para isso, basta adicionar:

```
#<number_of_issue>
```

**Exemplo:**

```#01 Create a new document```

**Observação:** Por padrão, o caracter '#' define uma linha de comentário na mensagem do *commit*. Para resolver esse problema, digite na linha de comando:

```git config --local core.commentChar '!'```

* Para que uma pessoa seja inclusa como contribuinte no gráfico de *commits* do GitHub, basta incluir a instrução ```Co-authored-By:``` na mensagem:

**Exemplo:**

```
#01 Create a new document


Co-authored-By: Lucas Fellipe <lucasfcm9@gmail.com>
Co-authored-By: João Pedro <isudjoao@gmail.com>
```

* Para *commits* que encerram a resolução de uma _issue_, deve-se iniciar a mensagem do *commit* com Fix ```#<numero_da_issue> <mensagem>```, para que a _issue_ seja encerrada automaticamente quando mesclada na ```main```.

**Exemplo:**

```
Fix #5 Create a new document.
```

* Para *commits* que incluem uma pequena mudança em uma _issue_ que já teve sua resolução encerrada, deve-se iniciar a mensagem do *commit* com *HOTFIX* ```#<numero_da_issue> <mensagem>```

**Exemplo:**

```
HOTFIX #5 Add new anwser
```