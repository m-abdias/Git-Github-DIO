# Git e Terminal

## Comandos essenciais

### Comandos essenciais para trabalhar com Terminal

- Limpar tela
  ➔ crtl + l ou clear

- Criar uma pasta
  ➔ mkdir nome_da_pasta

- Entrar na pasta
  ➔ cd nome_da_pasta

- Sair da pasta
  ➔ cd ..

- Exibir o que tem dentro da pasta
  ➔ ls

- Excluir arquivo ou pasta
  ➔ rm nome_do_arquivo

- Excluir arquivo ou pasta de forma recursiva:
  ➔ rm -r nome

- Excluir arquivo ou pasta de forma recursiva e forçar ação:
  ➔ rm -rf nome

## Comandos para Git

### Trabalhando com Branches

- Listar branches já foram fundidos(merged) com a master/main
  ➔ git branch --merged

- Listar branches que não foram fundidos(merged) com a master
  ➔ git branch --no-merged

- Puxando arquivos de uma branch já existente
  ➔ git pull origin nomeBranch

- Criando um branch remoto com o mesmo nome
  ➔ git push origin novaBranch_nome

- Quando você tem problemas com merge e deseja desfazer o merge
  ➔ git merge --abort ou git reset --merge

- Alterando mensagens do commit
  ➔ git commit --amend -m "Minha nova mensagem
