# Comandos Básicos para se trabalhar com terminal

## Windows

- Lista de diretórios contidos na pasta que estamos situados = (Directory)

  ​	**dir**

- Base do diretório atual = (Change Directory)

  ​	**cd /** 

- Entra na pasta selecionada = (Change Directory)

  ​	**cd** **“nome da pasta”**

  ​	**Ex:** **cd teste**

- Retroceder 1 nível de navegação = (Change Directory)

  ​	**cd ..**

- Limpar a tela = (Clear Screen)

  ​	**cls**

- Autocompletar preenchimento = Atalho útil para agilizar a digitação

  ​	**“Comando” + TAB**

- Criar pasta = (Make directory)

  ​	**mkdir “Nome da pasta”**

  ​	**Ex: mkdir teste**

- Printa de volta à informação na tela

  ​	**echo “informação desejada”**

  ​	**Ex: echo teste**

- “ >” Redirecionador de fluxo, ou seja , pega o output do echo e coloca dentro de um arquivo 

  ​	**echo “informação desejada” > “nome do arquivo”."extensão do arquivo"**

  ​	**Ex: echo teste > teste.txt**

- Deleta somente arquivos e não pastas = (Delete)

  ​	**del “nome do arquivo”**

  ​	**Ex: del teste**

- rmdir - /S - Exclui uma árvore de diretórios (o diretório especificado e todos os seus subdiretórios, incluindo todos os arquivos)) **- /Q** (Especifica o modo silencioso. Não solicita confirmação ao excluir uma árvore de diretórios. O parâmetro /q só funcionará se /s também for especificado.Cuidado: Quando você executa no modo silencioso, toda a árvore de diretórios é excluída sem confirmação. Certifique-se de que arquivos importantes sejam movidos ou submetidos a backup antes de usar a opção de linha de comando /q) Deleta o repositório inteiro junto do conteúdo dentro dele = (remove directory)

  ​	**rmdir “nome do repositório” /S /Q** 

  ​	**Ex: rmdir teste /S /Q**

## Linux

- Lista de diretórios contidos na pasta que estamos situados = (List)

  ​	**ls**

- Lista de diretórios ocultos contidos na pasta que estamos situados = (List)

  ​	**ls -a**

- Base do diretório atual = (change directory)

  ​	**cd /**

- Entra na pasta selecionada = (change directory)

  ​	**cd “nome da pasta”** 

  ​	**Ex: cd teste**

-  Retroceder 1 nível de navegação = (change directory)

  ​	**cd ..**

- Limpar a tela = (Clear)

  ​	**clear ou Ctrl + L**

- Autocompletar preenchimento

  ​	**“Comando” + TAB**

- Criar pasta = = (Make directory)

  ​	**mkdir “Nome da pasta”**

  ​	**Ex**: mkdir teste

- Move um arquivo = (move)

  ​	**mv “nome do arquivo.extensão” ./”nome do diretório ou pasta”/**

  ​	**Ex: mv teste.txt ./pasta/**

- Pegar permissão caso seja um subsistema =(superuser do) - (Switch User)

  ​	**sudo su**

- Printa de volta à informação na tela

  ​	**echo “informação desejada”**

  ​	**Ex: echo teste**

- “ >” Redirecionador de fluxo, ou seja , pega o output do echo e coloca dentro de um arquivo

  ​	**echo “informação desejada” > “nome do arquivo”.”extensão do arquivo”**

  ​	**Ex: echo teste > teste.txt**

- Cria o arquivo em branco

  ​	**echo > “nome do arquivo.extensão”**

  ​	**Ex: echo teste.txt**

-  rm(remove) - r(recursivo, deletar todas as pastas contidas lá dentro) - f(force, não aparecer nenhum tipo de confirmação) 

  ​	**rm -rf “nome do repositório”/**

  ​	**Ex: rm -rf pasta/**

