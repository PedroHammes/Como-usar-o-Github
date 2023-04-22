# Repositórios
1. Novo Repositório
2. Crie
3. Github te dará 3 opções:
    - **Configuração rápida**: se você já fez esse tipo de coisa antes
    - **crie um novo repositório na linha de comando**
    - **envie um repositório existente a partir da linha de comando**

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
      - Nome do Token (use um nome autoexplicativo)
      - Selecione um prazo de expiração
      - Selecione um nível de acesso para um token  
        >Quem acessar o repo usando este token só poderá realizar as ações permitidas nesta etapa  
      - Gere o token
6. Copie o token e use-o imediatamente
      - Após sair da tela de geração você nunca mais verá este token, então use-o imediatamente.
      - Não é recomendado guardar este token em lugar algum porque perde o propósito de segurança.
7. Selecione o diretório do projeto e entre nele com o comando  `cd`
8. Estando dentro do repo use o comando abaixo:
    ```c
    git init
    ```
    Este comando irá inicializar o git no repo ou reiniciar caso ele já tenha sido inicializado. 
9. Nome e senha
      - Use seu nome de usuário do Github
      - Na senha, use o token gerado
        >O Github não faz mais a autenticação com senha, agora é somente com o token.

---
## Baixando Atualizações
1. Enrtre no arquivo desejado
2.  Clique no botão de editar
3.  Faça as alterações que você quiser e depois clique no botão de  `commitar`

Pronto, agora ao analisar os arquivos na sua máquina você verá que não forama lterados e você continua com uma versão antiga do código.
Use o comando abaixo para baixar as atualizações para a sua máquina:
```c
git pull origin  master
```

---
## Lendo os commits
1. Se você quiser ler o histórico de commits clique no botão de histórico
2. Aqui você verá todos os commits feitos (organizados por branches)
3. Clique em algum commit para abrir a página do commit:
  - No topo temos a mensagem do commit e a descrição estendida
  - No meio temos as alterações feitas no código
      - No lado esquerdo a versão antiga
      - No lado direito a versão nova
      - Compare as diferenças
  - No fim da página há uma sessão de comentários, onde as pessoas podem fazer comentários sobre o seu commit e você sobre o delas.

---
[Tópico Anterior](Merge.md) | [Início](README.md) | [Próximo Tópico](PullRequest.md)
