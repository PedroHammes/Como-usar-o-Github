# Logs

>**Após realizar uma série de `commits` em um repositório, é natural querer visualizar o que aconteceu nele.**  
Principalmente se for uma projeto grande e colaborativo com muitas pessoas trabalhando nele.  

Para atender esta demanda, **o git possui um “histórico de eventos”**, chamado de ``log``, **que guarda um registros de todas as alterações feitas em cada arquivo**.  

Para executar, rode o comando:

```c
git log
```

>O `log` **retorna para cada alteração:**  
 * O **usuário** que fez a alteração;
 * A **data** de alteração;
 * A **mensagem de alteração** (que, seguindo as boas práticas, deve ser autoexplicativa a respeito da alteração).
---
**Se você quiser as informações exibidas de forma mais enxuta**, use o comando abaixo:

```c
git log --pretty=oneline
```

Assim o `git` **retornará apenas a mensagem** de cada `commit`.

---

**Para ver apenas o último commit use:**

```c
git log --pretty=onleine -1
```
>_Esse comando exibirá apenas o `commit` **mais recenente** em apenas uma linha._

**Ou**
```c
git log -1
```
>_Esse comando exibirá apenas o `commit` **mais recenente** em várias linhas._

**Para conferir status de cada commit use:**

```c
git log --stat
```