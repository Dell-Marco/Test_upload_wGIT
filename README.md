# Teste de envio - Marco Dell'Osa
https://www.udemy.com/course/aprende-git-desde-cero/learn/lecture/48283385#overview

Abrir linha de comando e lançar: WINDOWS POWER SHELL

Ir até o diretório do teu projeto:

d:
cd users
cd marco_dellosa
cd mygit
cd mvp_s1
digitar: git init

vai aparecer esta msg: 
Initialized empty Git repository in D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/

abrir o VSCODE assim: code .

Ao criar um arquivo no VSCODE, deve aparecer a letra U no lado direito do nome

-----------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------
UPLOAD dos arquivos do projeto para o GITHUB

Devemos criar uma "caixa" com os arquivos, etiquetá-la e enviar para o GITHUB.
O processo de colocar os arquivos na "caixa" se chama GIT ADD.

É possível adicionar arquivo por arquivo na "caixa" ou adiciona-los todos de uma vez.


D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git add README.md	incluiu o README.md
D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git add script.js	incluiu o script.js
D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git status		verifica se os arquivos estão incluidos.

Se estiverem incluidos os nomes dos arquivos aparecem verde

D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git add .		incluiu todos os arquivos do projeto

--------------------
Agora que os arquivos estão na caixa precisamos "etiquetar" ou dar um nome a essa caixa. Este processo se chama COMMIT

D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git commit -m "initial commit"   uma mensagem qq entre aspas.

Como resposta vai mostrar os arquivos incluidos e
os arquivos que ficaram de fora.

Dando o comando abaixo podemos verificar o status:
D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git status
On branch main				--> [onde main é o nome que escolhemos nas configurações para a nossa raiz]
nothing to commit, working tree clean

Damos estes dois comandos para enviar para o Github:
D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git remote add origin https://github.com/Dell-Marco/MVP_S1.git
D:/Users/Marco_DellOsa/mygit/mvp_s1/.git/git push origin main

Irá aparecer uma janelinha do Github, onde clicamos em: Sign in with your browser
[talvez por um bug, a pagina do Github fica em branco, 
mas olhando para o terminal vemos que ele executou várias operações tipo essas:

	info: please complete authentication in your browser...
	Enumerating objects: 4, done.
	Counting objects: 100% (4/4), done.
	Delta compression using up to 4 threads
	Compressing objects: 100% (2/2), done.
	Writing objects: 100% (4/4), 341 bytes | 341.00 KiB/s, done.
	Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
	To https://github.com/Dell-Marco/MVP_S1.git
	 * [new branch]      main -> main
	PS D:\users\marco_dellosa\mygit\mvp_s1>



Olhamos então no link: https://github.com/Dell-Marco/MVP_S1.git
para verificar se foi feito o upload.
