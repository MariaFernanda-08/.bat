# Como funcionam os Comandos Batch?
### Aqui você verá quais Comandos Batch servem para cada ocasião no script do CMD.
## O que são Comandos Batch?
Os Comandos Batch, ou BAT, são instruções dadas ao sistema operacional que serão executadas em *batch*, ou em lote, pelo prompt de comandos do Windows, em sequência, possibilitando a execução automatizada de tarefas. Logo que o *arquivo.bat* for inserido no scrpit, as intruções dos comandos irão ser realizadas. 
## Comandos:
  - **Como exibir o conteúdo de um arquivo?**
      - ```dir```
      - **Exemplo:**
      - C:\Users\Aluno\Desktop>```dir```
  - **Como criar um diretório(pasta)?**
      - ```mkdir```
      - **Exemplo:**
      - C:\Users\Aluno\Desktop>```mkdir``` e o nome que você quer chamá-lo.
      - Após apertar Enter, a pasta já foi criada.
  - **Como remover um diretório?**
      - ```rmdir```
      - **Exemplo:**
      - C:\Users\Aluno\Desktop>```rmdir``` + o nome da pasta que queira excluir.
      - Após esse código, a pasta já foi apagada.
  - **Como criar e remover arquivos?**
      - ```echo``` - *Escrever a mensagem/Criar*
      - ```del``` - *Remover*
      - **Exemplo:**
      - C:\Users\Aluno\Desktop\Pasta>```echo``` e o que você quer escrever > ```nome do arquivo.txt```
      - Após isso, o arquivo foi criado.
      - C:\Users\Aluno\Desktop\Pasta>```del``` e o ```nome do arquivo.txt```
      - Depois disso, o arquivo foi deletado.
  - **Como copiar e mover arquivos?**
      - ```copy``` - *Copiar*
      - ```move``` - *Mover*
      - **Exemplo:**
      - C:\Users\Aluno\Desktop\Pasta>copy ```nome do arquivo.txt``` C:\Users\Aluno\Desktop\Para_Onde_Você_Quer_Copiar
      - Então, o arquivo foi copiado.
      - C:\Users\Aluno\Desktop>move Pasta\ ```nome do arquivo.txt``` Pasta_Que_Quer\ ```nome do arquivo.txt```
      - Pronto, o arquivo foi movido.
  - **Como renomear arquivos?**
      - ```rename``` - *Renomear*
      - **Exemplo:**
      - C:\Users\Aluno\Desktop\Pasta>ren ```nome do arquivo.txt``` > ```outro nome do arquivo.txt```
      - Logo. seu arquivo foi renomeado.
   
  ![Batch](https://tecnologiaeinformacao.netlify.app/assets/imgs_posts/batch/intro-to-batch-ptbr/first-screen-cmd.png)
