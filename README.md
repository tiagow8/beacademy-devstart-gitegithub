# beacademy-devstart-gitegithub
Repositório criado com a finalidade de fazer e entregar os exercicios propostos em aula pelos professores do programa BeAcademy-devstart.

# Comandos git Apresentados em aulas: 💻📚
Comandos basico para desde a inicialização da criação de um projeto até subir para o repositório.

Iniciar o repositório git:

  git init
Verificar o status do arquivo:

  git status
Adicionar todos os arquivos e salvar :

  git add .
ou Adicionar o arquivo que você deseja:

  git add nome-do-arquivo
Adicionar o commit :

  git commit -m "mensagem explicativa"
selecionar qual branch deseja:

  git branch -M Master ou main
Selecionar qual o repositório que sera enviado:

  git remote add origin *e digitar o endereço do repositório*
Enviar o arquivo para o repositório:

  git push -u origin main ou Master
# Comando de Ramificação 🖇️
Criar uma branch:

 git branch "nome da nova branch"
ou Criar uma branch e entrar nela:

 git checkout -b "nome da nova branch"
Acessar branch:

 git checkout "nome da branch"
Para ver qual branch você possui:

 git branch
Para unificar as branch:

 git merge "nome da  branch"
Para apagar a branch:

 git branch -d "nome da  branch"
# Comando para clonar repositorio: 🔗
 git clone url_do_projeto
# Comando para usar stash: ⛔
Quando precisar guarda rapidamente aquele arquivo para ter que resolver algum outro poblema sem precisar ter que fazer commit no arquivo sendo que ele não esta nem perto do esperado:

 git stash
lista os arquivo guardado no stash:

 git stash list
volta o stash mais recente:

 git stash pop
aplica o stash mais recente:

 git stash apply
ou escolher qual stash você que voltar:

 git stash apply@{ *aqui botar o numero da stash*}
fazer a limpeza do stash:

 git stash drop
