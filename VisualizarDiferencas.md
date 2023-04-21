# Visualizar Diferenças

O `git diff` analisa as diferenças entre as versões dos seus arquivos no último commit (head) e as versões deles atualmente (workdir).

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a4e82ae9-f2b8-4bcd-914c-afc81a94fcb0/Untitled.png)

O `git diff [nome do arquivo]` analisa as diferenças entre atualizações do arquivo:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2a0317a6-bebf-4f17-b0af-d2fd15479803/Untitled.png)

**-[alguma coisa] é o que foi removido**

**+[alguma coisa] é o que foi adicionado**

O comando `git diff --name-only` retorna apenas o nome dos arquivos que tem diferenças:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/46ffc38d-1843-4cb9-bc46-1468ce749ac4/Untitled.png)