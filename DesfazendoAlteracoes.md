# Desfazendo Alterações

## Editando commit
Imagine que você modificou um tópico do `arquivoA`  e fez o commit.  
Mas o arquivoB tem o mesmo tópico a ser adicionado, portanto **seria ideal fazer um único commit** para a mesma alteração nos dois arquivos.

Neste caso, **você pode alterar o commit** para que ele envie também a atualização de `arquivoB`  .  
Para isso, use o comando:

```c
git commit --amend
```
>Este comando irá abrir o editor de texto nano, no terminal
Aqui você podera alterar a mensagem do commit para incluir na descrição uma nota sobre a alteração do `arquivoB`  .  
_Linhas iniciadas com `#`  serão consideradas comentários._  

Se você quiser **alterar apenas a mensagem**, basta não ter nada em `staging`  .  
Use o `git commit --amend`  novamente e altere a mensagem do commit.

---

## Como remover um arquivo de Staging
Para remover um arquivo da área de seleção existem duas opções:
    
>**Método recomendado pelo próprio terminal**
    Use o comando: 
```c
git restore --staged [nome do arquivo]
```

>**Método alternativo**
    Use o comando:
```c
git reset HEAD [nome do arquivo]
```
Ele vai _resetar o arquivo para como ele estava no último commit._
    
**As mudanças permanecerão no seu arquivo do VSCode**, mas se você usar `git status`  verá que **os arquivos saíram da área de seleção**.
    
**Irá remover o arquivo da área de seleção**.

---  

## Como desfazer alterações no arquivo
    
>**Método recomendado pelo próprio terminal**
Use o comando:
```c
git restore [nome do arquivo]
```
**Removerá as alterações e deixará o arquivo da forma como estava no último commit**.

>**Método alternativo**
Use o comando:
```c
git checkout -- [nome do arquivo]
```
**Removerá as alterações e deixará o arquivo da forma como estava no último commit**.

---

[Tópico Anterior](VisualizarDiferencas.md) | [Início](README.md) | Próximo Tópico