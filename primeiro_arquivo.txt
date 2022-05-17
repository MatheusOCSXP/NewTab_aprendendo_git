/* GIT */

https://git-scm.com/

Agora podemos identificar seu nome de usuário e e-mail para o git. Essas informações são importantes, pois cada commit efetuado por um usuário utiliza esses dados. Os comandos são os seguintes:

git config –global user.name “seunomedeusuario”
git config –global user.email seunome@dominio.com


Clonando um repositório existente

git clone url

Exemplo:

git clone https://github.com/...


Inicializando um repositório

cd /seu/diretorio/que/deseja/criargit init

Para controlar o versionamento dos arquivos existentes, você deve começar a monitorar esses arquivos e fazer um commit inicial. Você pode fazer isso com alguns comandos git add que especificam os arquivos que você quer monitorar, seguido de um git commit:

git add .
git commit -m “mensagem commit inicial”

Para visualizar o status dos seus arquivos, é usado o comando:

git status

É possível observar as mudanças feitas em arquivos monitorados modificados através do comando:

git diff

Para verificar o histórico dos commits efetuados em determinado repositório, existe o comando:

git log


Ignorando arquivos

Basta criar um arquivo chamado .gitignore. e incluir os arquivos e pastas que você não desejar commitar.


Criando tags

Para criar uma tag anotada é simples, basta executar o seguinte comando:

git tag -a v1.0


Criando repositório

*******


Enviando para o repositório remoto

É possível enviar o arquivo para o remoto de origem ou para um remoto em específico como:

git push origin master


Conflitos

git pull
git push


Mesclando branches

git branch
git pull
git pull origin "branch"
git pull origin master


Pull request


GitHub Pages

GitHub Pages é o serviço de hospedagem gratuito para sites estáticos.


Uso do Git em projetos em time (Gitflow)

