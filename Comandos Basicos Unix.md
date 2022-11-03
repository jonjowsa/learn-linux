# Comandos básicos S.O. Unix. /Lixux

## lista pasta e arquivos contidos na pasta 
~~~
$ ls 
$ ls -l 
$ ls -la 
~~~

## lista o diretório que encontra 
~~~
$ dir 
~~~
 

## movimenta uma pasta ou arquivo par outro diretório 
~~~
$ mv (nome_do_arquivo) (nome_do_diretorio) 
~~~
 
 ## criar copia um arquivo 
~~~
$ cp (nome_do_arquivo) (nome_do_arquivoNOVO) (nome_do_diretorio) 
~~~
 ## remover pasta vazia 
~~~ 
$ rmdir 
~~~
 
## remover pasta e/ou arquivos de um diretório  
~~~ 
$ rm –r (nome do diretório. 
~~~
 
## Criar arquivos via editores Unix. 
~~~ 
$ vi (nome do arquivo.extensao) (nome_do_diretorio) //ou estar no diretório. 
~~~
Terminou de editar o arquivo?
- Então aperte CTRL+ C
- Digite --> :w [para escrever]
- CTRL+ C novamente
- Digite --> :qa [para gravar] 

## Criar/ Editar arquivos via NANO 
Ex:
~~~
$ nano /etc/www/teste.txt
~~~
 - Ctrl+O –Salvar arquivo
 - Ctrl+X – Sair 
 
## Comando CAT , mostra o conteudo do arquivo. 
~~~
$ cat /etc/www/teste.txt  
~~~
~~~
$ "Nome do comando" --help  // apresenta lista de argumento auxiliares. 
~~~