# Repositórios
1. Novo Repositório
2. Crie
3. Github te dará 3 opções:
    - a. **Configuração rápida**: se você já fez esse tipo de coisa antes
    - b. **crie um novo repositório na linha de comando**
    - c. **envie um repositório existente a partir da linha de comando**

## Crie um novo repo na linha de comando
```c
  1. echo "# arquivo1" >> README.md
  2. git init
  3. git add README.md
  4. git commit -m "first commit"
  5. git branch -M main //se retornar uma mensagem de erro tente: git branch -M master
  6. git remote add origin [link forncecido]
      a. Linkar o projeto local com o online (alterações de um afetam o outro)
  7. git push -u origin master //ou main
      a. username: email
      b. password: token gerado
```

---

[Tópico Anterior](Merge.md) | [Início](README.md) | [Próximo Tópico](PullRequest.md)