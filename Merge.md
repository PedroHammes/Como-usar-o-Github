# Merge

- **O merge envia as alterações commitadas em uma branch para a outra.**
- Apenas a branch alvo sofrerá as alterações
- Você precisa estar na branch que deseja receber o merge e então usar o comando `git merge [nome da branch a ser incorporada]`

# Na prática

1. Crie e vá para a branch vostok1:
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d2592447-4cd8-4aa6-8c07-36cfb604758c/Untitled.png)
    
2. Crie e adicione algum conteúdo ao arquivo, então comite as alterações:
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0019695f-2512-4e7f-b8ac-55b1813a401e/Untitled.png)
    
3. Retorne para a branch master e verá que não há o arquivo vostok1, pois ele foi commitado apenas na branch vostok1.
4. Para adicionar o conteúdo commitado na branch vostok1 à branch master use o comando `git merge vostok1`
5. Use o `git log` para ver o histórico de acontecimentos e lá você verá o merge
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/051a2acb-9f48-42bc-976f-4523a45a92b1/Untitled.png)
    
6.