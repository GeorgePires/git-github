#  ESTUDANDO GIT E GITHUB 


<p align="center">
  <img alt="img-repo" src="./src/img/img-repo.png" width="80%">
</p>


## Estados do Git

     [✅] Modificado (modified)
     [✅] Preparado (staged)
     [✅] Consolidado (committed)
    
## Comandos Basicos
```bash
     [✅] git clone <link do repositorio> #clonar um repositório remoto já existe 
     [✅] git init    #iniciando repositorio git
     [✅] git status
     [✅] git add . |ou <nome do arquivo>
     [✅] git commit -m "[CARD] Comentario"
     [✅] git log 
     [✅] git remote add origin <link do repositorio> 
     [✅] git push -u origin  master #Subindo arquivo para repositório remoto
```

## Branch
````bash
     #Cria nova branch
     [✅] git branch  <nome da branch>

     #Troca para a nova branch
     [✅] git checkout <nome da branch>

     #Cria e troca para a nova branch
     [✅] git checkout -b <nome da branch>

     #Exclui uma branch
     [✅] git branch -d <nome da branch>

     #Lista todas as branches
     [✅] git branch 
     
     #Lista todas as branches local e remota.
     [✅] git branch -a

     #Listar branches com informações dos últimos commits
     [✅] git branch -v
````
## 
## Atualizar repositório local de acordo com o repositório remoto
````
     [✅] git pull

````
## Mais sobre git log

```bash
# Como verificar o histórico de commits, através do git log e algumas de suas opções:

     [✅] git log --oneline
     [✅] git log -p
     [✅] git log --graph


```

## Editar comentário do commit
```bash
     git commit --amend
```
 


---