# DIO | Resumos Git e GitHub 

Repositório para armazenar resumos sobre Git e GitHub do curso Versionamento de Código do Git e GitHub da [Digital Innovation One](https://www.dio.me/).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 💻 Resumos das Aulas 

| Aulas | Resumos |
|-------|------|
| Gravando alterações no Repositório Local | [Resumos](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/potencia-tech-ifood-programacao-do-zero&tab=undefined&moduleId=undefined) |
|Desfazendo Alterações no Repositório Local | [Resumos](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/3f9f2336-6fd5-44cb-ba39-d1a4f6448023) |
| Enviando e Baixando Alterações com o Repositório Remoto | [Resumos](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/dd17c56e-2327-493c-942a-358a49a26549) |
| Trabalhando com Branches | [Resumos](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/2c7fd2b1-e7c4-4947-9b07-ffcbfb4bd689) |
| Trabalhando com Branches - Comandos | [Resumos](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/80018fab-daac-4917-8527-a6be2e0c3cf0) |

## ⌨ Comandos
```
git config
git init
git clone < URL > | --branch < branch > --single-branch
git remote add < remoto(origin) > < URL do repositório remoto >
--- adiciona um novo repositório local a partir de um repositório remoto
git status
git push -u --set-upstream < remoto(origin) > < local(main) >
--- envia para o repositório remoto(origin) as atualizações feitas localmente(main).
git pull
--- trás para o repositório local(main) as atualizações feitas no remoto(origin).
git commit -m --message < "texto do commit" > | --amend --message <"renomear commit">
git log
git add
git reset --soft | --mixed | --hard
git reflog
git restore --staged < arquivo >
git branch -v --verbose | --list | --delete
--- manipulações referentes as branches
git merge < branch para mesclar >
--- mescla as a branch escolhida na atual
git remote show origin
git fatch < repositório remoto(origin) > < repositório local(main)>
git diff
git checkout < branch > | -b
git stash pop | apply | list
--- arquiva alterações que você fez para serem trabalhadas posteriormente
```
Terminal
```
cat = "concatenate"
cd = "change directory"
pwd = "present working directory"
dir = "directory"
mkdir = "make directory"
touch = criar um arquivo vazio
rm -rf <file>
echo <cria mensagem>
```


## 🔍 Referências 
- [Digital Innovation One](https://www.dio.me/)
