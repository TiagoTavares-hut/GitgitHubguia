# Guia Definitivo Git e GitHub
- Git => Software de Versionamento Local => Faz o Controle de Versões de Arquivos e Pastas de um Projeto de Forma Local, 
- GitHub => Site de Versionamento na Nuvem => Faz o controle de versãoes na Nuvem (Internet)
(Git Push)

## Passo para Criar um Versionamento

- 1° Passo - Instalar o Git no Computador
- 2° Passo - Configurar o Git com Email e Usuário do GitHub
    - git config --global user.name "Seu Nome"
    - git config --global user.email "Seu Email"
- 3° Passo - Iniciar o Git na Pasta do Projeto
    - git init (vai criar a pasta oculta .git dentro do projeto)
    - git remote add origin "o endereço do repositório online"
4° Passo - Fazer o Controle de Versão
    - git add . (vai adicionar todos os arquivos para versionamento)
    - git commit -m "Adicionar o Comentario" (faz o versionamento Local)
    - git push -u origin (fazer o versionamento na nuvem)
- 5° Passo - Atualizar Repositorio Local
    - git pull (atualiza o repositório local com as alterações do repositório remoto)
- 6° Passo - Copiar meu repositório para outro computador
    - git clone "o endereço do repositório na nuvem" (clona o repositório remoto para o computador local)
## Todos os Comandos do Git

### Inicialização e Configuração
- `git init` — Inicializa um novo repositório Git
- `git config --global user.name "Seu Nome"` — Configura o nome do usuário
- `git config --global user.email "Seu Email"` — Configura o email do usuário
- `git config --list` — Lista todas as configurações do Git

### Controle de Versão
- `git add .` — Adiciona todos os arquivos para o controle de versão
- `git commit -m "Mensagem"` — Cria um commit com uma mensagem
- `git status` — Mostra o status dos arquivos no repositório
- `git log` — Mostra o histórico de commits
- `git diff` — Mostra as diferenças entre os arquivos

### Branches
- `git branch` — Lista os branches do repositório
- `git checkout nome-do-branch` — Muda para outro branch
- `git merge nome-do-branch` — Mescla branches
- `git rebase nome-do-branch` — Aplica commits de um branch em outro

### Repositório Remoto
- `git remote add origin URL` — Adiciona um repositório remoto
- `git push origin main` — Envia as alterações para o repositório remoto
- `git pull origin main` — Atualiza o repositório local com as alterações do remoto
- `git clone URL` — Clona um repositório remoto
- `git fetch` — Busca as alterações do repositório remoto sem mesclar

### Outros Comandos Úteis
- `git reset --hard` — Reseta o repositório para o último commit
- `git stash` — Armazena temporariamente as alterações não commitadas
- `git stash pop` — Aplica as alterações armazenadas com git stash
- `git tag` — Cria uma tag para um commit específico
- `git cherry-pick hash` — Aplica um commit específico de outro branch
- `git revert hash` — Reverte um commit específico
- `git rm arquivo` — Remove um arquivo do repositório
- `git mv antigo novo` — Renomeia ou move um arquivo
- `git show hash` — Mostra detalhes de um commit específico
- `git blame arquivo` — Mostra quem modificou cada linha de um arquivo
- `git reflog` — Mostra o histórico de referências do repositório
- `git bisect` — Ajuda a encontrar um commit que introduziu um bug
- `git submodule` — Gerencia submódulos dentro de um repositório
- `git archive` — Cria um arquivo compactado de um repositório ou branch
- `git clean -f` — Remove arquivos não rastreados do diretório de trabalho
- `git ls-files` — Lista os arquivos rastreados pelo Git
- `git ls-remote` — Lista referências de um repositório remoto
- `git shortlog` — Resume o histórico de commits por autor
- `git describe` — Fornece uma descrição legível de um commit
- `git grep "termo"` — Busca por um termo específico nos arquivos do repositório
- `git worktree` — Gerencia múltiplas árvores de trabalho para um repositório

### Atalhos (Aliases)
- `git config --global alias.co checkout` — Cria um atalho para o comando checkout
- `git config --global alias.br branch` — Cria um atalho para o comando branch