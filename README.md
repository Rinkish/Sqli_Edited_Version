# Sqli_Edited_Version
Edited SQLi Audi lab series so that it can work in kali linux with PhpVersion 7+

In latest version of kali we are having PHP version 7.xxx which does not support MySQL functions because it support MySQLi functions.

MySQLi Extension (or simply known as MySQL improved or MySQLi) is a relational database driver that is used mainly in the PHP programming language. 

So i made necessary changes in the original SQLi labs so that it can work in kali linux with PhpVersion 7+

Original SQLi version can be found at 

https://github.com/Audi-1/sqli-labs

How and what changes are made and how to setup this lab - You can read by blog for this

https://rinkishkhera.blogspot.in/2017/05/sqli-dhakkan-lab-setup-in-kali-linux.html


Before accessing lab from your browser make sure to run these three commands
in your kali machine

1 – service apache2 start
2 – service mysql stop
3 – mysqld_safe –skip-grant-tables

We are very thankful to Audi-1(aka Dhakkan) for creating such an interesting and awesome environment for us to understand and practice SQL injection.
