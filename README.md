# Comandos Básicos

## Configuração e Inicialização

- `git init`: Inicializa um repositório Git vazio.
- `git clone [URL]`: Clona um repositório Git existente.

## Gerenciamento de Mudanças

- `git add [arquivo]`: Adiciona um arquivo específico ao índice (staging area).
- `git add .` ou `git add --all`: Adiciona todas as alterações ao índice.
- `git commit -m "[mensagem]"`: Cria um novo commit com as alterações do índice.

## Branches

- `git branch`: Lista todas as branches existentes.
- `git branch [nome]`: Cria uma nova branch com o nome especificado.
- `git branch -d [nome]`: Deleta uma branch especificada.
- `git checkout [nome]`: Muda para uma branch específica.
- `git merge [branch]`: Mescla uma branch específica na branch atual.
- `git merge --abort`: Aborta uma mesclagem em andamento.
- `git log --graph`: Mostra o histórico de commits em forma de gráfico.

## Remoto

- `git remote add [nome] [URL]`: Adiciona um repositório remoto.
- `git remote -v`: Lista todos os repositórios remotos configurados.
- `git pull [remoto] [branch]`: Puxa as alterações do repositório remoto.
- `git push [remoto] [branch]`: Empurra as alterações para o repositório remoto.

## Comandos de Informação

- `git status`: Mostra o estado atual do repositório..
- `git diff`: Mostra as diferenças entre o diretório de trabalho e o índice.
- `git log`: Mostra o histórico de commits do repositório.
- `git log --pretty=oneline`: Mostra o histórico de commits do repositório em linhas.
- `git log --stat`: Mostra o histórico de commits para ver o historico de commits.
- `git show [commit]`: Mostra as alterações feitas em um commit específico.

## Comandos de Desfazer

- `git restore [arquivo]`: Desfaz as alterações feitas em um arquivo específico.
- `git [arquivo]`: Remove um arquivo específico do índice.
- `git reset --hard [commit]`: Desfaz todas as alterações desde um commit específico.
- `git revert [commit]`: Desfaz um commit específico, criando um novo commit para desfazer as alterações.

## Comandos de Ramificação

- `git branch`: Lista todas as branches existentes.
- `git branch [nome]`: Cria uma nova branch com o nome especificado.
- `git branch -d [nome]`: Deleta uma branch especificada.
- `git checkout [nome]`: Muda para uma branch específica.
- `git merge [branch]`: Mescla uma branch específica na branch atual.

# Comandos Avançados

## Stash

- `git stash`: Salva temporariamente as alterações locais em um stash.
- `git stash apply`: Aplica as alterações de um stash no branch atual.

## Rebase

- `git rebase [branch]`: Reorganiza os commits da branch atual sobre a branch especificada.
- `git rebase --continue`: Continua o processo de rebase após resolver conflitos.

## Cherry-pick

- `git cherry-pick [commit]`: Aplica um commit específico em outra branch.

## Bisect

- `git bisect start`: Inicia o processo de bisect.
- `git bisect bad`: Marca o commit atual como "ruim" (contém o problema).
- `git bisect good`: Marca o commit atual como "bom" (não contém o problema).
- `git bisect reset`: Termina o processo de bisect.

## Amend

- `git commit --amend`: Modifica o commit mais recente com alterações adicionais.

## Clean

- `git clean`: Remove arquivos não rastreados do diretório de trabalho.

## Cherry 

- `git cherry`: Mostra commits que ainda não foram mesclados em outra branch. 

# Comandos de Configuração

- `git config --global user.name "[nome]"`: Define o nome do usuário para os commits. 
- `git config --global user.email "[email]"`: Define o email do usuário para os commits. 
- `git config --global alias.[alias] "[comando]"`: Cria um alias para um comando Git. 

git remote add origin https://github.com/liliassz/Comandos-do-Git.git