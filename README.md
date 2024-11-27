# minicurso-github

## Siglas

- U: Untracked
  - Arquivo novo
- M: Modified
  - Arquivo já adicionado, porém modificado

## Clonar repositório

- git clone "link"

## Criar nova branch

- git checkout -b nome-branch → Cria uma nova branch e já entra nela

## Commit

- git add "nome" → Prepara o arquivo para fazer o commit
- git commit → Upa para o repo local | git commit -m "Nome do commit"
- git push -u origin nome-branch → Empurra para o repositório online, isso só quando criamos um branch nova e ela não está no github ainda
- git push -u → Empurra para o repositorio online

### Após dar o comando git commit

- Digitar o nome do commit no topo
- Apertar ESC
- SHIFT + :
- Digitar wq
- git push -u

## Puxar do repositorio

- git pull → Puxa todas as mudanças do repositorio online

## Branch

- git branch → Visualizar branchs
- git checkout nome-branch → mudar para essa branch
- git checkout -d nome-branch → Deletar branch
- git status → Mostra alguns detalhes e a branch que estamos agora

### Deletar branch

- git checkout nome-branch → Para sair da branch que voce quer remover
- git branch -d nome-branch → Para remover a branch especifica

### Rollback nos arquivos

- git checkout . | nomeDoArquivo → Reseta o arquivo ou tudo para o último commit
- git reset --hard origin/nomeBranch → Volta para o status original da branch do repositório
