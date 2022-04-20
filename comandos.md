# Principais  comandos git

## Inicializar repositório (somente 1x por repositório)
`git init` 
## Adiciona o arquivo ao git (coloca stash)
`git add nome-arquivo`

##  Adiciona vários arquivos ao git (coloca na memória)
`git add .`

## Mostra o status geral de uso do git
`git status`

## Mostra o histórico de commits
`git log`

## Realizar um commit com uma mensagem
`git commit -m "mensagem desejada"`

## Mudar o nome da branch de master para main (basta fazer 1x)
`git branch -M main`

## Fazer clone de um repositório 
`git clone endereço-repositóprio.git`

##  Adiciona uma referência do repositório remoto no ambiente local (somente 1x por repositório)
`git remote add origin endereço-repositório.git`

## Fazer o push (enviar) com -u para o repositório remoto (com -u somente 1x)
`git push -u origin main`
`git push u origin main`

## Recuperar histórico do repositório remoto
`git pull`

## Para mais informações de comandos:
 https://training.github.com/dowloads/pt-BR/github-git-cheat-sheet/
