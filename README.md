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
- git init (inicializa um repositório Git)
- git add . (adiciona todos os arquivos para o controle de versão)
- git commit -m "Mensagem do Commit" (cria um commit com uma mensagem)
- git status (mostra o status dos arquivos no repositório)
- git log (mostra o histórico de commits)
- git diff (mostra as diferenças entre os arquivos)
- git branch (lista os branches do repositório)
- git checkout (muda para outro branch)
- git merge (mescla branches)
- git remote add origin "URL do repositório" (adiciona um repositório remoto)
- git push origin master (envia as alterações para o repositório remoto)
- git pull origin master (atualiza o repositório local com as alterações do remoto)
- git clone "URL do repositório" (clona um repositório remoto)
- git reset --hard (reseta o repositório para o último commit)
- git stash (armazena temporariamente as alterações não commitadas)
- git stash pop (aplica as alterações armazenadas com git stash)
- git tag (cria uma tag para um commit específico)
- git fetch (busca as alterações do repositório remoto sem mesclar)