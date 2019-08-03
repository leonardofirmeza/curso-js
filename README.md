# Curso de JavaScript


Referência: [Caelum Desenvolvimento Web com HTML, CSS e JavaScript](https://www.caelum.com.br/download/caelum-html-css-javascript.pdf)




- Habilitar o subsistema Windows para Linux
- Instalar a distribuição do Ubuntu para Windows
- Baixar e instalar o terminal ZSH
- Criar a pasta Workspace
- Criar uma subpasta onde irá salvar os projetos
- Criar o arquivo README.md dentro da pasta
- Commitar os arquivos criados na pasta
- Adicionar a pasta de trabalho no repositório git



```
    1  pwd
    2  cd /mnt/c/Users/Leonardo/workspace //caminho da pasta workspace
    3  w
    4  vim /home/leonardo/.oh-my-zsh 
    5  reload
    6  r
    7  reload
    8  vim /home/leonardo/.oh-my-zsh
    9  r
   10  vim /home/leonardo/.oh-my-zsh
   11  r
   12  vim /home/leonardo/.oh-my-zsh
   13  source /home/leonardo/.zshrc
   14  r
   15  exit
   16  w
   17  pwd
   18  mkdir setup
   19  ll
   20  pwd
   21  cd setup                         // Criar pasta
   22  touch README
   23  code .                           // chmar a aplicação VS Code 
   24  git init
   25  git status
   26  git add README.md
   27  git status
   28  git commit -m "meu primeiro commit"      // comitar arquivo
   29  git config --global user.email "leonardofirmeza@hotmail.com"
   30  git config --global user.name "Leonardo Firmeza"
   31  git commit -m "meu primeiro commit"
   32  git status                       // Verificar status dos arquiovos da pasta
   33  git diff
   34  git commit -m "meu segundo commit"
   35  git add README.md
   36  git commit -m "meu segundo commit"
   37  git status
   38  git log                          // Verificar o log de alteração dos arquivos
   39  code
   40  code.
   41  code .
   42  git remote add origin https://github.com/leonardofirmeza/setup.git
   43  git push -u origin master
   44  ssh-keygen
   45  cat /home/leonardo/.ssh/id_rsa.pub
   46  git push -u origin master
   47  git remote add origin https://github.com/leonardofirmeza/setup.git
   48  vim .git/config
   49  git remote add origin https://github.com/leonardofirmeza/setup.git
   50  git push -u origin master
   51  vim .git/config
   52  git remote add origin git@github.com:leonardofirmeza/setup.git
   53  git push -u origin master
```

