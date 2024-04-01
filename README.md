# Orientações sobre o git:
Instale o git no seu ambiente operacional e, em seguida, utilize a linha de comando para trabalhar com os comandos do git.
## `git init`
Cria um repositório _local_ com o nome da pasta atual. Também é possível definir o nome do repositório usando o comando `git init`:
```
git init nome_repositorio
```
## `git status`
Mostra em qual etapa as alterações realizadas nos arquivos estão. Podem ser:
 - *work directory*: arquivos novos e arquivos com alterações que ainda não foram movidas para *staged* e/ou comitadas.
 - *staged*: arquivos prontos para receberem um commit. Os arquivos são transferidos do _work directory_ para o _staged_ aplicando o comando `git add`.
## `git ls-files`
Lista os arquivos que estão no repositório local.
## `git add`
Adiciona o _arquivo_ especificado (ou todos) para a etapa de _staged_. 
## `git commit`
Criar uma _versão_ do arquivo por um processo chamado _*commit*_.
## `git stash`
Grava/salva as mudanças realizadas nos arquivos em um espaço temporário e volta a última versão.
## `git log`
Lista todos os _commits_ realizados no projeto ou no arquivo específicado.
## `git whatchanged`
Lista todos os _commits_ realizados no projeto ou no arquivo específicado.
## `git branch`
Mostra os _branchs_ existentes e permite criar um novo _branch_. 
## `git checkout`
Permite trocar de _branch_. 
```
git checkout nomebranch
```

Também é possível criar um branch e acessa-lo utilizando o parâmetro _-b_
```
git checkout -b nomebranch
```
## `git merge`
Faz o _merge_ de um _branch_ em outro:
1. acesse o branch de destino
2. informe o comando _get merge_ com o nome do _branch_ a ser mesclado. 
## `git clone`
Faz uma copia de um reposiório remoto para a maquina local. 
## `git remote`
Define o endereço deum repositório remoto.
## `git push`
Atualizado o repositório remoto com as versões criadas desde a última atualização.
## `git pull`
Baixa as atualizações do repositório remoto.
