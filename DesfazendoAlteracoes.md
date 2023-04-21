# Desfazendo Alterações

# Editando commit

Imagine que você modificou um tópico de apollo 11 e fez o commit

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e5d93a35-9c9d-45e9-b72d-96065e12c89c/Untitled.png)

Mas a apollo 12 tem o mesmo tópico a ser adicionado, portanto **seria ideal fazer um único commit** para a mesma alteração nos dois arquivos.

Neste caso, **você pode alterar o commit** para que ele envie também a atualização da apollo 12. Para isso, use o comando:

```c
git commit --amend
```

Irá abrir o editor de texto nano, no terminal:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/13ed1ec7-4cc8-4eb5-bd38-78ef46a5cce5/Untitled.png)

Aqui você podera alterar a mensagem do commit.

**Linhas iniciadas com `#` serão consideradas comentários.**

Se você quiser **alterar apenas a mensagem**, basta não ter nada em `staging` , use o `git commit --amend` novamente e altere a mensagem do commit.

# Como remover um arquivo de Staging

Para remover um arquivo da área de seleção existem duas opções:

- **Método da OBC**
    
    Use o comando: `git reset HEAD [nome do arquivo]`
    
    Ele vai **resetar o arquivo para como ele estava no último commit.**
    
    **As mudanças permanecerão no seu arquivo do VSCode**, mas se você usar `git status` verá que **os arquivos saíram da área de seleção**.
    
- **Método recomendado pelo próprio terminal**
    
    Use o comando: `git restore --staged [nome do arquivo]`
    
    **Irá remover o arquivo da área de seleção**.
    

# Como desfazer alterações no arquivo

- **Método da OBC**
    
    Use o comando: `git checkout -- [nome do arquivo]`
    
    **Removerá as alterações e deixará o arquivo da forma como estava no último commit**.
    
- **Método recomendado pelo próprio terminal**
    
    Use o comando: `git restore [nome do arquivo]`
    
    **Removerá as alterações e deixará o arquivo da forma como estava no último commit**.