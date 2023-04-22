# Repositórios
1. Novo Repositório
2. Crie
3. Github te dará 3 opções:
    - a. **Configuração rápida**: se você já fez esse tipo de coisa antes
    - b. **crie um novo repositório na linha de comando**
    - c. **envie um repositório existente a partir da linha de comando**

## Crie um novo repo na linha de comando
  1. echo "# voyager1.2" >> [README.md](http://readme.md/)
  2. git init
  3. git add [README.md](http://readme.md/)
  4. git commit -m "first commit"
  5. git branch -M main
  6. git remote add origin [https://github.com/PedroHammes/voyager1.2.git](https://github.com/PedroHammes/voyager1.2.git)
      1. Linkar o projeto local com o online (alterações de um afetam o outro)
  7. git push -u origin master
      1. username: email
      2. password: token gerado