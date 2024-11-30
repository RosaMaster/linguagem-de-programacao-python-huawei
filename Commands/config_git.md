

***Informando a versão do Git***

git --version

***Configurando nome Usuário***

git config --global user.name "[nome]"
git config --global user.name "Nome que sera utilizado"

***Configurando E-mail Usuário***

git config --global user.email "[e-mail]"
git config --global user.email "email@gmail.com"


***Listar Configuração***
$ git config --list
user.name=Fulano de Tal
user.email=fulanodetal@exemplo.br
color.status=auto
color.branch=auto
color.interactive=auto
color.diff=auto

***Comando Limpeza da Janela***

clear

***Iniciar um repositorio***

git init

***Adicionar o arquivo ao repositorio***

git add [nome.arquivo.extensão]
git add readme.txt

***Adicionar todos os arquivos ao repositorio***

git add --all 
git add -A
git add .

***Salvando arquivo / alterações ***

git commit -m "[nome]"
git commit -m "adicao do arquivo readme"

***Mostra pastas ocultas***

dir -a


***Mostra o Status do arquivo***

git status