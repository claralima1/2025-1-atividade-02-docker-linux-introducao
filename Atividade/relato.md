# Relatório - Introdução a linux usando docker no windows

## 1. Iniciar um contêiner Fedora

Para iniciar um contêiner Fedora, foi preciso abrir o aplicativo Docker Desktop e exercutar o seguinte comando no prompt de comando do windows:

![imagem 0](/Atividade/Imagens/imagem0.PNG)


* O comando **"-it"** é executado para utilizar o modo interativo.

* O comando **"--name fedora-tutorial"** é executado para informar o nome do contêiner.

* O comando **"fedora:latest"** é executado para informar que imagem será utilizada.

A junção desses comandos cria e inicia um novo contêiner Docker baseado na imagem Fedora Linux.


## 2. Navegação Básica

![imagem 1](/Atividade/Imagens/imagem1.PNG)

* O comando **"pwd"** foi utilizado para verificar em qual diretório está.

* O comando **"ls"** foi utilizado para listar os arquivos e pastas do diretório atual.

* O comando mkdir foi utilizado para criar uma nova pasta.

* O comando **"cd"** é utilizado para entrar em uma pasta.

* O comando **"cd .."** volta para o diretório anterior ao atual.

## 3. Manipulação de Arquivos

![imagem 2](/Atividade/Imagens/imagem2.PNG)

* O comando **"cd ~"**  é executado para voltar ao diretório **"home"**.

* O comando **"pwd"** foi utilizado para verficar o diretório atual.

* O comando **"touch arquivo1.txt"** foi executado para criar o arquivo **"arquivo1.txt"**

* O comando **"mv arquivo1.txt documento.txt"** foi executado para renomear o arquivo **"arquivo1.txt"** para **"documento.txt"**.

* O comando **"cd"** foi utilizado para entrar na pasta **"atividades"**.

* O comando **"mkdir backup"** foi utilizado para criar um subdiretório chamado **backup**.

* O comando **" cp ~/documento.txt backup/"** foi utilizado parar copiar o arquivo **"documento.txt"** para o subdiretório **backup**.

* O comando **"ls"** foi utilizado para verificar se o arquivo foi copiado.

* O comando **"cd ~"** foi utilizado para voltar ao diretório home.

* O comando **"pwd"** foi utilizado para confirmar o local atual.

* O comando **"rm documento.txt"** foi executado para excluir o arquivo **"documento.txt"**.

* O comando **"ls atividades/bacuk/"** foi executado para verificar se o arquivo anda existe no subdiretório **"bakup"**.

## 4. Gerenciamento de pacotes

![imagem 3](/Atividade/Imagens/imagem4.PNG)

* O comando **"dnf update -y"** foi executado para listar os pacotes.

![imagem 4](/Atividade/Imagens/imagem6.PNG)

* O comando **"dnf install nano -y"** foi utilizado para instalar o editor de texto 
**nano**.

![imagem 5](/Atividade/Imagens/imagem7.PNG)


* o comando **"dnf remove nano -y"** foi executado para remover o nano.

## 5. Permissões de arquivos

![imagem 6](/Atividade/Imagens/imagem8.PNG)

* O comando **"touch script.sh"** foi executado para criar um arquivo chamado **script.sh**.

* O comando **"chmod u+x script.sh"** concede permissão de execução ao dono 

* O comando **"ls -l script.sh"** verifica as permissões do arquivo.

## 6. Processos em Execução

![imagem 7](/Atividade/Imagens/imagem9.PNG)
![imagem 8](/Atividade/Imagens/imagem10.PNG)

* O comando **"ps aux"** foi executado para listar os processos em execução.

* O comando **8"sleep 60 &"** foi executado para executar um processo em segundo plano.

* O comando **"ps aux | grp sleep"** foi executado para encontrar o processo **PID**

* O comando **"kill <PID>"** foi executado para encerrar o processo.

## 6. Encerrando o Contêiner

![imagem 9](/Atividade/Imagens/imagem10.PNG)
![imagem 10](/Atividade/Imagens/imagem11.PNG)

* O comando **"exit"** foi executado para sar do contêiner.

* O comando **"docker rm fedora-tutorial"** foi executado para remover o contêiner.