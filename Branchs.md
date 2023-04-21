# Branch

## O que é

> **Branchs (ramos) são cópias do arquivo principal, onde podemos desenvolver features isoladas sem comprometer o código fonte.**
> 

**A branch master* é a principal**. Mas com as recentes atualizações do GIT **a branch master passou a se chamar main**.

**É possível misturar as branchs** usando o comando `merge`.

## Principais usos

### Como criar uma nova branch

1. A primeira coisa a ser feita é usar o comando `git branch` , para **ver quais branchs já existem e em qual você está**.
    1. A branch que você estiver terá um asterisco ao lado e estará destacada em verde.
        
        ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4669ec79-87e2-48de-b45f-09c11190425b/Untitled.png)
        
2. Use o comando `git branch [nome desejado]` para criar uma nova branch
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/51d10f10-44fe-41d3-b4f7-0ec4120b49ed/Untitled.png)
    

#### Como mudar de branch

1. Use o comando `git checkout [nome da branch destino]`
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1808c370-2067-4839-ad57-98ed63c8df82/Untitled.png)
    
2. Se você fizer uma alteração nesta branch e retornar para a master, as alterações serão visíveis na branch master também.
    1. Mas se você colocar as modificações em stage e depois commitar, ao mudar para a master essas alterações não serão visíveis, pois foram commitadas na branch testing e portanto existem apenas nela.

#### Como deletar uma branch

1. **Saia da branch que você quer deletar**
    1. Por segurança, vá para a branch master
2. Use o comando `git branch -d [nome da branch a ser deletada]`
    1. Ou `git branch -D [nome da branch a ser deletada]`
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b003327-b815-4d27-a50e-12e598c10bd5/Untitled.png)
    

#### Como criar e navegar para uma branch com único comando

1. Use o comando `git checkout -b [nome da branch que será criada]`
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/01d93d7f-2b63-4796-be41-3c5406f9e61d/Untitled.png)

[Tópico Anterior](VisualizarDiferencas.md) | [Início](README.md) | Próximo Tópico