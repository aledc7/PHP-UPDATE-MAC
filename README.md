# Actualizar a PHP 7 en MAC

[![aledc.com](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/aledc.com.svg)](https://aledc.com)
[![License](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/mit-license.svg)](https://aledc.com)
[![GitHub release](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/release.svg)](https://aledc.com)
[![Dependencies](https://github.com/aledc7/Scrum-Certification/blob/master/recursos/dependencias-none.svg)](https://aledc.com)


- [x] aledc.com



###### 1 - Abrir la terminal y actualizar brew


```php	
sudo brew update && brew upgrade
```


###### 2 - Instalar PHP7

```php	
brew install php@7.2
```




###### 3 - cerrar y volver a abrir la terminal


###### 4 - por ultimo comprobar la versión de PHP con el siguiente comando


```php
php -v
```



###### 5 - Si todo fue bien debería salir la leyenda

```php
HP 7.2.9 (cli) (built: Aug 22 2018 02:58:58) ( NTS )
Copyright (c) 1997-2018 The PHP Group
Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies
    with Zend OPcache v7.2.9, Copyright (c) 1999-2018, by Zend Technologies
```


###### En caso de que en la terminal se muestre una version diferente de PHP, correr los siguientes comandos

```php
echo 'export PATH="/usr/local/opt/php@7.2/bin:$PATH"' >> ~/.bash_profile
echo 'export PATH="/usr/local/opt/php@7.2/sbin:$PATH"' >> ~/.bash_profile
source ~/.bash_profile
````



###### Eso sería todo

###### SALUDOS !


- [X] ING. ALEJANDRO DE CASTRO
