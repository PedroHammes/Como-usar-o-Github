# Merge
## O que é
>**O merge envia as alterações commitadas de uma branch para a outra.**
Apenas a branch alvo sofrerá as alterações.  
Você precisa estar na branch que deseja receber o merge e então usar o comando:
```c
git merge [nome da branch a ser incorporada]
```

## Como usar

1. Crie e vá para a branch arquivoA:
```c
git checkout -b vostok
```
2. Crie e adicione algum conteúdo ao arquivo, então comite as alterações:
```c
touch arquivoA.txt
git add arquivoA.txt
git commit -m "Criação e edição de arquivoA"
```
3. Retorne para a branch master e verá que não há o arquivoA, pois ele foi commitado apenas na branch arquivoA.
4. Para adicionar o conteúdo commitado na branch arquivoA à branch master use o comando  `git merge arquivoA`
5. Use o  `git log`  para ver o histórico de acontecimentos e lá você verá o merge