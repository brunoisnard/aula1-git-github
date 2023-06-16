# aula-git-github
Anotações de aulas Back-End 


git config --global user.name "[nome]"
Configura o nome relacionado aos commits

git config --global user.email "[endereco-de-email]"
Configura o email relacionado aos commits

git config --list
Lista as configurações atuais

Comandos básicos
git init
Inicializa um repositório git

git status
Verifica o status dos arquivos/diretórios e as modificações realizadas

git add [arquivo]
Adiciona o arquivo à staged area

git add . ou git add -A
Adiciona todos os arquivos modificados à staged area

git commit -m "Mensagem do commit"
Armazena os arquivos que estão na staged area para um novo commit, gravando-os no histórico de versão

git log
Apresenta o histórico de commits

Diferenças de arquivos
git diff
Apresenta as linhas modificadas dos arquivos

git diff --name-only
Apresenta os nomes dos arquivos que foram modificados

git diff [arquivo]
Apresenta as linhas modificadas no arquivo especificado no comando

Revertendo modificações
git reset [arquivo]
Retorna o arquivo para a staged area

git reset --soft HEAD~1
Retorna ao último commit, mantendo as alterações feitas nos arquivos

git reset --hard HEAD~1
Retona ao último commit, removendo as alterações feitas nos arquivos

git reset --soft [id do commit] / git reset --hard [id do commit]
Retorna ao commit do ID especificado, mantendo as alterações (soft) ou removendo as alterações (hard)

Branches
git branch [nome-da-branch]
Cria uma nova branch

git branch
Apresenta as branches existentes e destaca a branch atual

git checkout [nome-da-branch]
Muda para a branch informada no comando

git merge [nome-branch]
Integra as mudanças da branch especificada no comando com o histórico da branch atual

git branch -D [nome-branch]
Remove a branch do repositório local

git push [nome-remote] :[nome-branch]
Remove a branch do repositório remoto

Repositório remoto
git remote add [nome-remote] [url-remote]
Vincula o repositório remoto ao repositório local

git remote / git remote -v
Apresenta os repositórios remotos

git remote rm [nome-remote]
Desvincula o repositório remoto do repositório local

git remote set-url [nome-remote] [url-novo-remote]
Altera o repositório remoto vinculado ao repositório local

git push -u [nome-remote] [nome-branch-local]
Envia os arquivos da branch do repositório local para o repositório remoto (utilizado no primeiro push)

git push
Envia os arquivos da branch do repositório local para o repositório remoto (utilizado do segundo push em diante)

git pull [nome-remote] [nome-branch-local]
Envia os arquivos do repositório remoto para a branch do repositório local

git fetch
Busca as alterações feitas no repositório remoto, sem adicioná-las ao repositório local

git clone [url-remote]
Clona um repositório remoto para o repositório local

========================================================================

Para criar pasta:

mkdir {nome da pasta} para criar pasta		

cd: {nome da pasta} para entra na pasta 

git init: para iniciar o repositorio  

cd .. : para sair da pasta 

echo "# aula" >>README.MD : Comando pra criar arquivo dentro de uma pasta

touch nome do aquivo: para criar aquivo  

ls: comando para lista arquivos dentro da pasta 

git add  : comando pra adicionar arquivo

git add . : comando pra adicionar conteudo/ pasta

git nome do arquivo : para deletar um aquivo espesifico 

git reset : para desfazer um add especifico 

git status: ver o status de um aquivo

git reset --soft HEAD~1 : para desfazer um commmit 

git reset hard HEAD~1 : desfazer as alterações 
 

