# aulas

## Clonar repositorio das aulas

git clone https://github.com/melem-dev/aulas

#

## Inicializar repositorio

    git init

## Cadastrar usuario

    git config --global user.name "Pedro Melem"
    git config --global user.email "melem.dev@gmail.com"

## Adicionar referencia de repositorio

    git remote add origin https://github.com/{user}/{repo}

## Alterar link da referencia

    git remote set-url origin https://github.com/{user}/{repo}

## Sincronizar com repositorio na nuvem

    git pull origin main

## Adicionar os arquivos dentro do commit

    git add .

## Salvar o commit

    git commit -m "Meu primeiro commit"

## Subir os arquivos do repositorio local

    git push origin master
