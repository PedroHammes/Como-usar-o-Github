# Commits

1. Crie um diretório e entre nele
2. Use o comando:
    
    ```c
    git init
    ```
    
3. Crie um arquivo.txt
    
    ```c
    touch myFile.txt
    ```
    
    Você pode usar o comando `nano myFile.txt` para abrir um editor de texto de linha de comando.
    
4. Use `git status`
    
    Com este comando podemos ver que existem muitos arquivos que ainda não são monitorados.
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c72d5568-70b2-49da-a35e-a9165818441a/Untitled.png)
    
5. Use `git add [nome do arquivo]` para monitorar o arquivo desejado ou `git add .` para monitorar todos os arquivos.
    1. Para manter as boas práticas, fazemos comits individuais, portando prefira usar o comando `git add [nome do arquivo]` e comittar apenas este arquivo. Só então passe outro arquivo para `staged` e assim por diante. 
    
    Agora o arquivo.txt está na área intermediária, antes do commit
    
    Se você usar `git status` novamente verá que o arquivo foi movido para a área de monitoramento e está guardando `commit`.
    
6. Use `git commit -m ‘mensagem’` para enviar o arquivo para a versão final
    
    Sempre que você envia um commit é preciso anexar uma mensagem, pois na árvore de commits haverão muitos commits, e uma mensagem objetiva do que foi feito no seu commit ajudará as pessoas a identificar as alterações.
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3de30c05-b852-4708-bf4c-4683a40278da/Untitled.png)

[Tópico Anterior](PrincipaisComandosNoTerminal.md) | [Início](README.md) | [Próximo Tópico]()