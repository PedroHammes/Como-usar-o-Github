# Branch

## O que é
> **Branchs (ramos) são cópias do arquivo principal, onde podemos desenvolver features isoladas sem comprometer o código fonte.**

**A branch  `master`  é a principal**.  
Mas com as recentes atualizações do GIT **a  `branch master`  passou a se chamar  `main`**.

**É possível misturar as branchs** usando o comando  `merge` .

## Principais usos
### Como criar uma nova branch
1. A primeira coisa a ser feita é usar o comando  `git branch`  , para **ver quais branchs já existem e em qual você está**.
    >A branch em que você estiver terá um asterisco ao lado e estará destacada em verde.
    
2. Use o comando  `git branch [nome desejado]`  para criar uma nova branch
---
#### Como mudar de branch
1. Use o comando  `git checkout [nome da branch destino]`
2. Se você fizer uma alteração nesta branch e retornar para a master, **as alterações serão visíveis na branch master também.**
    >Mas se você colocar as modificações em stage e commitar, ao mudar para a master essas alterações não serão visíveis, **pois foram commitadas na  ``branch testing``  e portanto existem apenas nela**.
---
#### Como deletar uma branch
1. **Saia da branch que você quer deletar**
    >Por segurança, vá para a branch master
2. Use o comando: 
```c
git branch -d [nome da branch a ser deletada]
```
  Ou 
  ```c
  git branch -D [nome da branch a ser deletada]
  ```
---
#### Como criar e navegar para uma branch com único comando
1. Use o comando:
```c
git checkout -b [nome da branch que será criada]
```
---
[Tópico Anterior](VisualizarDiferencas.md) | [Início](README.md) | Próximo Tópico