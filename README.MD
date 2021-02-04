# Dicas básicas para utilização do github

## Você deseja criar pontos na história da produção do seu projeto

git init

git add <file_name> or  git add .

git commit -m "added page"

## Você deseja verificar mudanças feitas no seu projeto. (Exibe hash do commit,

git log

## Para verificar detalhes do commit

git show <hash commit>

## Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito. (Criar nova branch

git branch <name_branch>

## Para acessar a nova branch

git checkout <name_brach>

## Visualizar todas as branchs

git branch

## Você adiciona as novas funcionalidades ao seu projeto em produção (Dentro da master)

git merge <name_branch>

## Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

git branch -D <name_branch>

## Você quer colocar seu projeto na nuvem.

git remote add origin https://github.com/mathcard/github_basicSkills.git

git push -u origin master

## Você vai pegar um projeto já iniciado, para trabalhar com o time
    1. Ocorre o erro quando a linha foi editada em dois arquivos diferentes.
    2. Necessário resolver o conflito.

## Antes de enviar a resolução, precisamos atualizar o projeto local.

git pull

## Você precisa voltar um arquivo para um determinado momento da linha do tempo.

git log // Para descobri o momento

git checkout <hash_commit> — <name_file>

## Você precisa recuperar algo deletado.

git log // Para descobri o momento

git checkout <hash_commit> — <name_file>


- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempoo
- `git commit` // adiciona um ponto na linha do tempo
- `git log` // visualiza os pontos na linha do tempo / commit
- `git status` // informa o estado das alterações do nosso projeto
- `git show` // apresenta determinado ponto na história
- `git branch` // gerenciar novas linhas do tempo
- `git checkout` // manipula as linhas do tempo
- `git merge` // unir linhas do tempo
- `git push` // envia alterações locais para o repositório remoto
- `git clone` // clonar um projeto / repositório
- `git pull` // puxa do repositório remoto