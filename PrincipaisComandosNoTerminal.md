# Principais Comandos no Terminal

### `cat [nome do arquivo]`  
Captura o conteúdo de um arquivo e mostra na tela.  
_Para sair da exibição use  `q`_.  

---

### `cd [caminho desejado]`  
Navega para a pasta especificada:  
* com `cd..` você volta para a pasta anterior
* com `cd../..` você volta duas pastas para trás
* com `cd../../..` você volta três pastas para trás, e etc  

---

### `clear`   
Limpa os textos que estão aparecendo no console.

---

### `cp [nome do arquivo] [nome do novo arquivo]`  
Copia o conteúdo de um arquivo para um novo arquivo

---

### `echo + [texto desejado]`  
Apresenta um texto no console.

---

### `history`  
Mostra o histórico de comandos.

* Se você quiser repetir um comando do histórico basta escrever:  
`!número do comando desejado`
* Se você quiser recuperar um comando específico use:  
`history | grep mv`
* `|` serve para pegar a saída de history (a lista de comandos anteriores)
* `grep` é um filtro
* `mv` é o comando filtrado  
  * Assim o console retornará uma lista com os comandos que contenham o comando filtrado e o número desses comandos no histórico, então basta usar `!número do comando desejado` para repetir o comando que você quiser.

---

### `Less [nome do arquivo]`  
Mostra o conteúdo de um arquivo no console.

---

### `ls`  
Mostra todos os elementos (pastas e arquivos) presentes no diretório atual.

---

### `mkdir [nome da pasta desejado]`  
Cria uma nova pasta.

---

### `mv [nome do arquivo] [nome do novo arquivo]`  
Move o conteúdo de arquivo para outro apagando o anterior.

---

### `nano [nome do arquivo].txt`  
Abre um editor de texto de linha de comando.

---

### `pwd`
Mostra em qual pasta o usuário está no momento na arvore de diretórios.

---

### `touch [nome desejado do arquivo]`
Cria ou atualiza um arquivo.

---

### `rm [nome do arquivo]`
Apaga um arquivo.

---

### `rm -rf [nome da pasta]`
Apaga uma pasta.

---

### `sudo [comando]`
Permite rodar comandos que necessitam de privilégio de super usuário.

---

### `exit`
Fecha a sessão atual.

---

### `>>`
Injeta algum conteúdo dentro de algum arquivo.
> **Ex.:** `echo ‘hello’ >> file.txt`  
_injeta o texto ‘hello’ dentro de file._

---

[Tópico Anterior](InstalacaoEConfiguracao.md) | [Início](README.md) | [Próximo Tópico](CicloDeVidaDosArquivos.md)