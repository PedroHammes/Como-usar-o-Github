# Logs

**Após realizar uma série de `commits` em um repositório, é natural querer visualizar o que aconteceu nele.** Principalmente se for uma projeto grande e colaborativo com muitas pessoas trabalhando nele.

Para atender esta demanda, **o git possui um “histórico de eventos”**, chamado de **log, que guarda um registros de todas as alterações feitas em cada arquivo**.
Rode o comando:

```c
git log
```

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/071b5bd9-a838-42ce-8c53-cfcc94901de8/Untitled.png)

O `log` **retorna**, para cada alteração, o **usuário** que fez a alteração, a **data** de alteração e a **mensagem de alteração** (que, seguindo as boas práticas, deve ser autoexplicativa a respeito da alteração).

**Se você quiser as informações exibidas de forma mais enxuta**, use o comando abaixo:

```c
git log --pretty=onleine
```

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/24e5d7f4-d83e-4ea9-a927-6df2f994893f/Untitled.png)

Assim o `git` **retornará apenas a mensagem** de cada `commit`.

**Para ver apenas o último commit use:**

```c
git log --pretty=onleine -1
```

```c
git log -1
```

Esse comando exibirá apenas o `commit` **mais recenente** em apenas uma linha.

Esse comando exibirá apenas o `commit` **mais recenente** em várias linhas.

**Para conferir status de cada commit use:**

```c
git log --stat
```

ou

```c
git log --stat
```

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0aa0c870-3813-428f-a675-bc71deebddf0/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c40df019-f16d-48f6-8166-6f2e268915fd/Untitled.png)