# AmbienteDS-3
Criando novas branches, juntando branches. 

- git branch *(Checar qual Branch estou)*
- git checkout "branch" *(mudar de branch)*
- git checkout -b dev *(Cria nova Branch e vai para ela)*
- git push --set-upstream origin dev *(Adicionar a nova Branch no Git)*
- git checkout -b bugfix/modificar-titulo *(Criando branch dentro da dev para Bugfix)*
- git push --set-upstream origin bugfix/modificar-titulo *(Adicionar a nova Branch no Git)*
- git merge bugfix/modificar-titulo *(Indo na Dev e mesclando com a bugfix)*
- git branch --delete "branch" *(Deletar uma branch)*