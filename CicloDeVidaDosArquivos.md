# Ciclo de Vida dos Arquivos

## Estado de Arquivo
> Os arquivos possuem **2 estados**:  
1. Monitorado
2. Não monitorado

### Arquivos Monitorados
> São arquivos que já sofreram `commit` ou estão em `stage`.  
**Você pode conferir o status desses arquivos usando o comando `git status`.**
A partir de agora o git sabe que esses arquivos **fazem parte do seu projeto**.

Arquivos monitorados podem estar:
1. **Inalterados**
    * No último `commit` ele tinha um conteúdo `x` e **atualmente permanece com o mesmo conteúdo do último `commit`**.
2. **Modificados**
    * No último commit ele tinha um conteúdo `x` e **atualmente tem um conteúdo `y` ou** `xy` (**diferente do último** `commit`).
3. **Selecionados**
    * Quando você adiciona ele para `stage`, com o git `add`.

### Arquivos não Monitorados
> Arquivos que **não estavam no último `commit`**, **nem estão na área de seleção** ( `git add` ).

## Ciclo de vida dos arquivos

![File Status Licecycle](https://th.bing.com/th/id/R.440edcf13b2028ba30c03d94fbeaacaa?rik=JkwZslcM0qJEbA&riu=http%3a%2f%2fblog.4linux.com.br%2fwp-content%2fuploads%2f2017%2f07%2fGit_ciclo.vida_.png&ehk=ztDLfdWuEyYrBbAM%2b%2biV2HUE%2fwYnUHkNem64SxKDhO8%3d&risl=&pid=ImgRaw&r=0)

---

[Tópico Anterior](PrincipaisComandosNoTerminal.md) | [Início](README.md) | [Próximo Tópico]()