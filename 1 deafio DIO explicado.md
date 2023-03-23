# Passo-a-passo 1 desafio DIO



- Pasta **Workspace** em OS(C:) 
  - Pasta 1 desafio DIO
  - Esse arquivo que vos fala para descrever o passo-a-passo que eu fiz para criação de repositório no GitHub

- Abrir GitBash na pasta 1 desafio DIO 
  - função "ls" para verificar se o arquivo realmente está na pasta

- Iniciar o git na pasta com "git init" e _commitar_ o arquivo lá de dentro com "git commit"
  - _qnd vc inicia o git na pasta, aparece (master) em azul na frente do nome da sua pasta_, _isso cria um arquivo oculto (.git) na pasta tbmm, onde ficarão armazenados as modificações e criação de objetos no seu arquivo_. 
  - uso da função "git status" sempre que desejar verificar se algum arquivo/pasta está untracked/tracked/staged e commited _uso sempre após qualquer modificação só para verificar msm_

- abrir o site do GitHub, entrar na sua conta e criar um novo repositório, o meu chamei de "1 desafio DIO REP"

  - agora 'empurraremos' o repositório local (do computador) para o remoto (GitHub) - esse repositório local é o que criamos qnd iniciamos o git na pasta 1 desafio DIO
  - após criar um repositório novo e vazio no GitHub, copiamos a url gerada e vamos colar no git bash para direcionar o nosso diretório do repositório local para o remoto.
    - para isso, vamo no git bash e direcionamos o diretório através do comando "git remote add _origin_(pode ser qualquer nome em origin mas normalmente usa-se esse msm) e a url. 

  - após o direcionamento do diretório, vamos mandar o repositório local para o remoto através do comando "git push origin master"
    - _pedirá sua permissão_ 

-  e seu repositório já estará no GitHub :) 

### OBS: sempre que alterar seu documento, como por exemplo esse que escrevo, precisará mandá-lo novamente para o GitHub pq senão não apareceram as alterações lá. 