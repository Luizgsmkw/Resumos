# Como criar um repositório no Git e enviar para o GitHub  (em 7 passos):computer:

1. Abrir o aplicativo Git Bash;

2. Utilizar o comando: cd nomeDaPasta (para entrar na pasta que você pretende criar o repositório) / Ex: cd projetos /;

   - **Dica um:** abrir o aplicativo na pasta desejada te polpa tempo, ou seja, você não vai precisar digitar o comando "cd"  
   - **Dica dois:** caso você ainda não tenha criado a pasta,  você pode fazer essa ação pelo Git por meio do comando: mkdir nomeDaPasta  / Ex: mkdir projetos /
   
2. Iniciar o repositório por meio do comando: git init  / com essa ação você  cria uma pasta.git  (é justamente nessa pasta que o Git guarda o histórico das alterações feitas);

   - **Atenção**: esse comando precisa ser efetuado dentro da pasta que você pretende iniciar o repositório 
   
2. Após iniciar o repositório, é preciso adicionar o arquivo no Git por meio do comando: git add nomeDoArquivo        / Ex: git add projeto1 /; 

   - **Informação**: após realizar esse comando o arquivo vai para o estado Staged (nesse estado o arquivo está esperando ser commitado)
   
2.  Agora é preciso commitar o arquivo com o comando: git commit -m "mensagem"    / Ex: git commit -m "Meu primeiro projeto" /;

   - **Dica**: o conteúdo da mensagem é importante para você lembrar o tipo de alteração que fez no arquivo quando olhar o histórico de alterações no GitHub (repositório remoto). 
   - **Dica**: após realizar o comando"git commit" é aconselhável utilizar o comando: git status (se o Git informar que não tem nada na área de Staged para commitar é porque sua ação foi concluída com sucesso)
   
2. Após commitar seu arquivo é o momento de envia-lo para o GitHub. Mas primeiro você precisa criar um repositório remoto, para realizar essa ação é só utilizar o comando: git remote add nomeDoRepositorio URL   / Ex: git remote add origin URL /;  

2.  Agora com seu repositório remoto criado você pode enviar o arquivo com o comando: git push nomeDoRepositorio master  / Ex: git push origin master / 

   - **Informação**: Na próxima vez que você quiser mandar um novo arquivo é só digitar o comando: git push
   
   
   
   
   
   

