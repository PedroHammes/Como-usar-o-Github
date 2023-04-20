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
 *Assim o console retornará uma lista com os comandos que contenham o comando filtrado e o número desses comandos no histórico, então basta usar `!número do comando desejado` para repetir o comando que você quiser.

[Tópico Anterior](InstalacaoEConfiguracao.md) | [Início](README.md) | [Próximo Tópico]