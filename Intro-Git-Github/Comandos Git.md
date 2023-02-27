### Comandos B�sicos de GIT 
�	**git config**
Um dos comandos git mais usados � o git config que pode ser usado para definir valores de configura��o espec�ficos do usu�rio como e-mail, algoritmo preferido para diff, nome de usu�rio e formato de arquivo etc. Por exemplo, o seguinte comando pode ser usado para definir o email:
git config --global user.email sam@google.com
git config --global user.name "Fulano de Tal"

�	**git init**
Este comando � usado para criar um novo reposit�rio GIT. Uso:
git init
�	**git add**
O comando git add pode ser usado para adicionar arquivos ao �ndice. Por exemplo, o seguinte comando ir� adicionar um arquivo chamado temp.txt presente no diret�rio local para o �ndice:
git add temp.txt

�	**git clone**
O comando git clone � usado para fins de verifica��o de reposit�rio. Se o reposit�rio estiver em um servidor remoto, use:
git clone alex@93.188.160.58:/path/to/repository
Por outro lado, se uma c�pia de trabalho de um reposit�rio local for criada, use:
git clone /path/to/repository



�	**git commit**
O comando git commit � usado para confirmar as altera��es na cabe�a. Tenha em aten��o que quaisquer altera��es efetuadas n�o ir�o para o reposit�rio remoto. Uso:
git commit �m �coloque sua mensagem aqui�

�	**git status**
O comando git status exibe a lista de arquivos alterados juntamente com os arquivos que ainda n�o foram adicionados ou confirmados. Uso:
git status

git push � outro dos comandos git b�sicos mais usados. Um simples envio envia as altera��es feitas para o ramo mestre do reposit�rio remoto associado ao diret�rio de trabalho. Por exemplo:
git push origin master

�	**git checkout**
O comando git checkout pode ser usado para criar ramos ou alternar entre eles. Por exemplo, o seguinte cria um novo ramo e muda para ele:
command git checkout -b <branch-name>
Para simplesmente mudar de um ramo para outro, use:
git checkout <branch-name>

�	**git remote**
O comando git remote permite que um usu�rio se conecte a um reposit�rio remoto. O comando a seguir lista os reposit�rios remotos atualmente configurados:
git remote �v
Esse comando permite que o usu�rio se conecte a um servidor remoto:
git remote add origin <93.188.160.58>

�	**git branch**
O comando git branch pode ser usado para listar, criar ou excluir ramos. Para listar todos os ramos presentes no reposit�rio, use:
git branch
Para excluir um ramo:
git branch �d <branch-name>

�	**git pull**
Para mesclar todas as altera��es presentes no reposit�rio remoto para o diret�rio de trabalho local, o comando pull � usado. Uso:
git pull

�	**git merge**
O comando git merge � usado para mesclar uma ramifica��o no ramo ativo. Uso:
git merge <branch-name>

�	**git diff**
O comando git diff � usado para listar os conflitos. Para visualizar conflitos com o arquivo base, use
git diff --base <file-name>
O seguinte comando � usado para exibir os conflitos entre ramos about-to-be-merged antes de mescl�-los:
git diff <source-branch> <target-branch>
Para simplesmente listar todos os conflitos atuais, use:
git diff

�	**git tag**
A marca��o � usada para marcar compromissos espec�ficos com al�as simples. Um exemplo pode ser:
git tag 1.1.0 <insert-commitID-here>

�	**git log**
Executar o comando git log exibe uma lista de compromissos em uma ramifica��o, juntamente com os detalhes pertinentes. Um exemplo de sa�da pode ser:
commit 15f4b6c44b3c8344caasdac9e4be13246e21sadw
Author: Alex Hunter <alexh@gmail.com>
Date:   Mon Oct 1 12:56:29 2016 -0600

�	**git reset**
Para redefinir o �ndice e o diret�rio de trabalho para o estado do �ltimo commit, o comando git reset � usado. Uso:
git reset --hard HEAD

�	**git rm**
git rm pode ser usado para remover arquivos do �ndice e do diret�rio de trabalho. Uso:
git rm filename.txt

�	**git stash**
Provavelmente um dos menos conhecidos comandos git b�sicos � git stash que ajuda a salvar as mudan�as que n�o devem ser cometidos imediatamente, mas em uma base tempor�ria. Uso:
git stash

�	**git show**
Para visualizar informa��es sobre qualquer objeto git, use o comando git show. Por exemplo:
git show
�	git fetch
git fetch permite que um usu�rio obtenha todos os objetos do reposit�rio remoto que atualmente n�o residem no diret�rio de trabalho local. Exemplo de uso:
git fetch origin
�	git ls-tree
Para exibir um objeto de �rvore juntamente com o nome e o modo de cada item e o valor SHA-1 do blob, use o comando git ls-tree. Por exemplo:
git ls-tree HEAD
�	git cat-file
Usando o valor SHA-1, exiba o tipo de um objeto usando o comando git cat-file. Por exemplo:
git cat-file �p d670460b4b4aece5915caf5c68d12f560a9fe3e4
�	git grep
git grep permite que um usu�rio procure atrav�s das �rvores de conte�do frases e / ou palavras. Por exemplo, para pesquisar www.hostinger.com em todos os arquivos use:
git grep "www.hostinger.com"
�	gitk
gitk � a interface gr�fica para um reposit�rio local que pode ser invocado digitando e executando:
gitk
�	git instaweb
Com o comando git instaweb, um servidor web pode ser executado em interface com o reposit�rio local. Um navegador da Web tamb�m � automaticamente direcionado para ele. Por exemplo:
git instaweb �httpd=webrick
�	git gc
Para otimizar o reposit�rio atrav�s da coleta de lixo, que ir� limpar arquivos desnecess�rios e otimiz�-los, use:
git gc
�	git archive
O comando git archive permite que um usu�rio crie um arquivo zip ou tar contendo os componentes de uma �nica �rvore de reposit�rio. Por exemplo:
git archive --format=tar master
�	git prune
Atrav�s do comando git prune, os objetos que n�o t�m ponteiros de entrada s�o exclu�dos. Uso:
git prune
�	git fsck
Para executar uma verifica��o de integridade do sistema de arquivos git, use o comando git fsck. Todos os objetos corrompidos s�o identificados:
git fsck
�	git rebase
O comando git rebase � usado para reaplica��o de compromissos em outro ramo. Por exemplo:
git rebase master
Conclus�o
Alguns dos comandos git b�sicos usados com frequ�ncia. Certifique-se de verificar o nosso tutorial GIT para uma instru��o f�cil de seguir sobre como configurar e usar GIT.

https://www.hostinger.com.br/tutoriais/tutorial-do-git-basics-introducao
