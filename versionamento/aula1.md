# Criando uma branch

- criar uma branch com git checkout -b tarefa/minha-primeira-branch;
- fazer uma alteração nessa branch;
- verificar no repositório remoto.


## Para criar novas branchs, vamos:

- voltar para a main com git checkout main;
- criar uma nova branch com git checkout -b exemplo-branch;
- fazer uma alteração nessa branch;
- verificar no repositório remoto.

## Unificando os ramos:

Você pode realizar esta ação por meio de dois comandos distintos:

- Realizar o download das informações fornecidas pela outra branch, com 
- git pull origin tarefa/minha-primeira-branch; ou
- Fazer a mesclagem com a outra branch, com git merge tarefa/minha-primeira-branch.

## Criação de tags:

- No terminal do seu repositório local, crie uma tag para marcar o ponto atual com o comando git tag –a v1.0 –m "minha primeira tag".
-  Para ver as tags criadas, execute o comando git tag.
- Para ver informações sobre uma tag específica, como a v1.0, digite o comando git show v1.0.
- Vamos "empurrar", ou seja, publicar as tags no repositório remoto com o comando git push origin --tags.
- Agora acesse o repositório remoto pelo seu navegador. No github, encontre a tag criada e publicada.
-  Clique em releases para ter acesso às informações que foram adicionadas a esse ponto atual de nosso código.
- Clique em v1.0 para visualizar o que está na tag.