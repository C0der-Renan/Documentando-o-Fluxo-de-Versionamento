# Documentando-o-Fluxo-de-Versionamento

#🚀 Sessão 1: O Passo a Passo da Criação e Envio:

#o início:

Primeiro de tudo você deve clicar em create new no (+) no canto superior direito do seu github ali perto da barra de perfil, depois clique em new repository e após isso coloque um nome pro repositório, uma descrição básica do que vai ser aquele repositório, se o seu repositório estiver em desenvolvimento ainda, você pode deixá-lo privado para você fazer alterações futuras, caso não precise pode deixar público, mesmo clique também no botão read-me que é pelo read-me que você vai colocar a descrição do seu projeto, códigos, como ele funciona, guia de como alguém pode usar seu projeto ou dar continuidade nele. Por fim clique em create repository e está pronto. 

#conexão:

Crie um repositório no GitHub, como descrito acima copie a URL gerada (SSH ou HTTPS) e execute os comandos no terminal para vincular e subir os dados:

#Bash
git remote add origin URL_DO_SEU_REPOSITORIO
git push -u origin main

#primeiro envio:

exitem duas formas de fazer envios de arquivos pelo git-hub de forma manual va no repositorio desejado clique em ADD file e arraste o arquivo desejado, a outra forma e via terminal. No computador, mova o arquivo que você gostaria de fazer upload para GitHub para o diretório local que foi criado quando você clonou o repositório, abra Git Bash mude o diretório de trabalho atual para o seu repositório local, Prepare a arquivo para commit em seu repositório local.
$ git add .

# Adds the file to your local repository and stages it for commit. Para cancelar o preparo de um arquivo, use 'git reset HEAD ARQUIVO'.
Faça commit do arquivo que você preparou no repositório local.

$ git commit -m "Add existing file"
# Commits the tracked changes and prepares them to be pushed to a remote repository. Para remover esse commit e modificar o arquivo, use "git reset --soft HEAD~1", faça o commit e adicione o arquivo novamente.
Efetue push das alterações no repositório local para o GitHub.com.

$ git push origin YOUR_BRANCH
# Pushes the changes in your local repository up to the remote repository you specified as the origin

sessão 02: 

pra que serve o readme: o readme e a forma que outros devs vão ver como funciona seu codigo no git-hub de forma mai facil de resumir e a forma como você vai descrever seu projeto desde como ele funciona e o que precisa pra rodar ele, simplificando mais e ai onde fica a descrição do seu projeto com mais detalhes possiveis para que outra pessoas possam ler e entendam como funciona o seu proejto.



