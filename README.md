# Prova-Junho
### COMMIT 1 

git add .
git commit -m "commit 1"



### COMMIT 2

git add .
git commit -m "commit 2"



### TAG 1.0

git tag -a 1.0 -m 'versão de inicio'



### PUSH DA COMMIT 2 E TAG 1.0

git push origin main --tags



### CRIAR A BRANCH DEV

git branch dev
git checkout dev



### COMMIT 3

git add .
git commit -m "commit 3"



### COMMIT 4

git add .
git commit -m "commit 4"



## PUSH DA COMMIT 4 NA ORIGIN DEV

git push origin dev



### CRIAR A BRANCH TEMP

git branch temp
git checkout temp



### COMMIT 5

git add .
git commit -m "commit 5"



## PUSH DA COMMIT 5 NA ORIGIN TEMP

git push origin temp



## MERGE DAS BRANCHES TEMP E DEV

git checkout dev
git merge temp



## PUSH NA ORIGIN DEV

git push origin dev



### COMMIT 6

git add .
git commit -m "commit 6"



## MERGE DAS BRANCHES DEV E MAIN

git checkout main
git merge dev



### TAG 1.1

git tag -a 1.1 -m 'versão de entrega'



### PUSH DA COMMIT 6.1 E TAG 1.1

git push origin main --tags

