## Criar um projeto novo

* Criar uma nova pasta no PC pra isso chamada `Git Tutorial`

* Abrir o VSCode nessa pasta

* Criar um novo arquivo `README.md`

* Escrever dentro dele `Escreve uma mensagem do que se trata o projeto`

* Salva o arquivo

Agora então é hora de usarmos o Git

* Abre o Git Bash que foi instalado na máquina (pode ser pelo terminal do VSCode mesmo)

* `git init` para inicializar o repositório

Foi criada uma pastinha `.git` e é ali que toda a mágica acontece, então não apague

* `git add README.md` para colocar o arquivo na área de stagging 

<img src="https://i1.wp.com/www.markus-gattol.name/misc/mm/si/content/git_git_add.png">

* `git commit -m "primeiro commit"` para de fato dar o commit no repositório

* `git branch -M "main"` para alterar o nome da branch principal de `master` para `main` (isso é uma boa prática atualmente recomendada) - Aqui como está sendo meu primeiro contato resolvi não alterar nada.

## Repositório no Github

* Depois de você ter criado a sua conta na plataforma, você irá em `Criar novo repositório`

Você vai preencher com as informações do projeto, então dar o nome do repositório, colocar uma breve descrição e criar

* Para passar o commit do meu repositório local (da minha máquina) para um repositório na plataforma do Github, usamos o `git remote add origin <link do repositório>` - Uma observação bem interessante é que usamos o git remote somente na primeira vez de mandar para o github, sei que é meio lógico, mas é um detalhe que resolvi citar aqui.

* `origin` é o nome utilizado para referenciar o nosso repositório - Origin funciona como um ""apelido"

Agora já temos o nosso repositório local conectado com o respositório do Github, porém o `commit` que damos na máquina não sobe automaticamente para a plataforma

* Para isso precisaremos empurrar, enviar para lá com o `git push -u origin main` - Lembrando que eu não alterei o nome da minha branch e deixei com master

Agora se recarregarmos a página iremos ver o nosso arquivo aqui na plataforma!

## Alterando e adicionando arquivo

Beleza, agora que temos o nosso repositório no Github configurado direitinho, podemos usar e abusar do que o Git oferece

A cada nova alteração refaço todos os passos: git add ., depois git commit -m "mensagem" e por fim o git push que aí de fato minhas alterações serão visíveis no github