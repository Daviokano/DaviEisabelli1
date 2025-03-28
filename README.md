Davi Okano E isabelli cunha de melo

obs sobre o git:
1 - Não tinha a pasta em casa, só um arquivo referente ao projeto. Quando tiver no lab eu subo o resto do projeto. 
2 - Não uso windows, mas sim linux ubuntu, onde não existe o "git bash". Isso ocorre, pois o git bash é um terminal 
cujo objetivo é rodar comandos git e linux. Uma vez no ubuntu, o git bash já o seu terminal normal, sendo totalmente 
adaptado para rodar o git. 
3 - Acabei cometendo um erro na configuração do email, gravei o nome duas vezes. Mas para resolver isso, apliquei o passo
de configurar o email e o nome de novo, além de usar o comando: git commit --amend --reset-author (para editar o commit).
No final, apenas usei o git push -f origin main, para mandar às alterações (o -f serve como um atalho para o force, é
necessário quando você fez alguma alteração no commit que já foi enviado para o github, fonte: https://github.com/git-guides/git-push)


4 - estão os comandos:

cd Documents - Entrar onde está a pasta do projeto
cd nivia - Entrar na pasta do projeto 

git init - iniciar o repositório na sua máquina

git config --global user.name "Davi Silva Okano" - Configurar o nome
git config --global user.email "davi@okn.com.br" - Configurar o email

git add . - git add serve para fazer o git ler as mudanças 

git commit -m "" - adicionando todas às mudanças com uma mensagem, sobre o que foi mudado

git branch -M main - mudando para a branch principal 

git remote add origin https://github.com/Daviokano/AtividadeGit.git - adicionando o repositório remoto

git push -u origin main - mandando às alterações, obs: Não sei se é especíco do linux, mas pede uma verifição, para saber quem está adicionando no repositório.
                                                  Assim é necessário configurar uma "chave especial", concedendo às permissões necessárias para acessá-lo. A criação
                                                  da chave será feita no github.

5 - Pronto! Projeto subido, a única coisa feita posteriormente foi referente ao email, como já explicado.
