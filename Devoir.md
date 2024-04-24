# ETAPE INSTALLATION DE MYSQL

Etape 1:Télechargement du source sur github   
      mysql 8.3.0.tar.gz  
Etape 2:Décompression et désarchivage du fichier source  
```bash
tar -zxvf mysql 8.3.0.tar.gz
```
Etape 3:Installation  
```bash
cd mysql 8.3.0

$mysql 8.3.0/
$mysql 8.3.0/ ./configure
ERROR:./configure:no such file or directory
$mysql 8.3.0/ ls
$mysql 8.3.0/ cat README
```
Installation des dépendance nécessaire  
openssl version   
cmake  
```bash
mysql 8.3.0/mkdir build
$mysql 8.3.0/cd build
$mysql 8.3.0/build/sudo cmake ..
```
ERROR:manque de dépendance  

flex bison zlib  
installation de ces dépendance  
```bash
mysql 8.3.0/build/sudo cmake ..
sans erreur
mysql 8.3.0/build/ make
mysql 8.3.0/build/make install
cd ~
echo ‘export PATH=$PATH /usr /local/bin’ >>.bashrc
```
<img src="https://github.com/M-Mampionontsoa/INSTALLATION-PAQUETS/blob/main/mysql.png">




















##ETAPE D’INSATALLATION APACHE  
#Etape 1:Télechargement du source sur github  

httpd-2-4-59.tar.gz  

#Etape 2:Décompression et désarchivage du fichier source  
```bash
tar -zxvf httpd-2-4-59.tar.gz
```
#Etape 3:Installation
```bash
cd  httpd-2-4-59
httpd-2-4-59/./configure
ERROR;no such files or directory
httpd-2-4-59/ls
httpd-2-4-59/cat README 
httpd-2-4-59/./buildconf
ERROR:APR not found
```
Installation des dépendances 
apr version
apr-util version
```bash
httpd-2-4-59/./configure
ERROR:APR could not found
httpd-2-4-59/ ./configure  --with-apr=/usr/local/apr/bin
httpd-2-4-59/ sudo make 
httpd-2-4-59/sudo make install
httpd-2-4-59/ echo ‘export PATH=$PATH /usr /local/bin’ >>.bashrc
```
<img src="https://github.com/M-Mampionontsoa/INSTALLATION-PAQUETS/blob/main/apache2.png">

##ETAPE D’INSTALLATION DE PHP  
#Etape 1:Télechargement du source sur github  
php-8.2.18.tar.gz  
#Etape 2:Décompression et désarchivage du fichier source  
```bash
tar -zxvf php-8.2.18.tar.gz
```
#Etape 3:Installation  
```bash
cd   php-8.2.18
  php-8.2.18/./configure
ERROR;no such files or directory
php-8.2.18/ls
php-8.2.18/cat README .md
php-8.2.18/cat INSTALL
```
installation des dépendances :
```bash
httpd-2-4-59/sudo apt install -y pkg -config build -essential autoconf bison re2c
php-8.2.18/./buildconf
 php-8.2.18/./configure  
php-8.2.18// sudo make 
php-8.2.18/sudo make install
echo ‘export PATH=$PATH /usr /local/bin’ >>.bashrc
```
<img src="">
