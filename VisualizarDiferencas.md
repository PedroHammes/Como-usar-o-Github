# Visualizar Diferenças

O `git diff` analisa as diferenças entre as versões dos seus arquivos no último commit (head) e as versões deles atualmente (workdir).

O `git diff [nome do arquivo]` analisa as diferenças entre versões do arquivo.

* **-[alguma coisa] é o que foi removido**
* **+[alguma coisa] é o que foi adicionado**

O comando `git diff --name-only` retorna apenas o nome dos arquivos que tem diferenças entre suas versões atuais e as suas versões do último commit.