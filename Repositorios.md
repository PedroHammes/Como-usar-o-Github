# Repositórios
1. Novo Repositório
2. Crie
3. Github te dará 3 opções:
    - a. **Configuração rápida**: se você já fez esse tipo de coisa antes
    - b. **crie um novo repositório na linha de comando**
    - c. **envie um repositório existente a partir da linha de comando**

## Configuração Rápida

---
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
## Envie um repositório existente a partir da linha de comando

---
## Autenticação por Token
1. Entre na sua conta Github
2. Configurações
3. Configurações de Desenvolvedor
4. Token de Acesso Pessoal
5. Gerar novo token
    a. Nome do Token (use um nome autoexplicativo)
    b. Selecione um prazo de expiração
    c. Selecione um nível de acesso para um token
      >Quem acessar o repo usando este token só poderá realizar as ações permitidas nesta etapa
    d. Gere o token
6. Copie o token e use-o imediatamente
    a. Após sair da tela de geração você nunca mais verá este token, então use-o imediatamente.
    b. Não é recomendado guardar este token em lugar algum porque perde o propósito de segurança.
7. Selecione o diretório do projeto e entre nele com o comando  `cd`
8. Estando dentro do repo use o comando abaixo:
    ```c
    git init
    ```
    Este comando irá inicializar o git no repo ou reiniciar caso ele já tenha sido inicializado. 
9. Nome e senha
    a. Use seu nome de usuário do Github
    b. Na senha, use o token gerado
      >O Github não faz mais a autenticação com senha, agora é somente com o token.

---
[Tópico Anterior](Merge.md) | [Início](README.md) | [Próximo Tópico](PullRequest.md)