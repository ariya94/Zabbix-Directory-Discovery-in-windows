# Zabbix-Directory-Discovery-in-windows
Discovery all of directories in specific path from windows os and check if is changed

There is one macros that is called {$DIR}. you shoud introduce your path to this macros like C:\inetpub\wwwroot

The first item check changes the {$DIR} direcory 

the discovery item find all of directories in {$DIR}, then check changes in each directory and sub directory

I use system.run command to get data. you must enable the AllowKey=system.run[\*] in your zabbix agent configuration file

you can import The template in your zabbix server
