# ExpertTyCE Box

## Tutorial

Esta caja de vagrant está preconfigurada para que unos miutos tengas listo un ambiente de desarrollo completo para iniciar directamente a codificar sin preocuparte por la instalacion y configuracion de Linux.



## ExpertTyCE Box v0.0.1

#### Caracteristicas:

- Ubuntu 16.04 LTS 64bits

  - Usuario: root
    - Contraseña: toor
  - Usuario: vagrant
    - Contraseña: vagrant

- PHP 7

- NGINX 

- PHP-FPM

- PostgreSQL 9.5

  - Usuario: postgres
  - Contraseña: postgres

- PHPMailer

- SMTP Mailhog y MhSendmail

  - http://192.168.33.10:8025

- Beanstalkd

  - http://192.168.33.10/console/public/

- Carpetas compartidas para tus proyectos de backend o frontend

  - Incluir en su archivo local "host"
    - 192.168.33.100	backend.localdomain.lan	frontend.localdomain.lan
  - URL
    - http://backend.localdomain.lan
    - http://frontend.localdomain.lan

- Email worker

  - Script en PHP enlaza Beanstalkd con PHPMailer

- JasperServer

  - URL

    - http://192.168.33.10:8080/jasperserver/login.html

  - Usuario: jasperadmin

  - Contraseña: jasperadmin

    ​

## Instalación

El proceso de instalación es muy sencilla, solo se requiere como tener instalado [Vagrant](https://www.vagrantup.com/downloads.html) y [Virtualbox](https://www.virtualbox.org/wiki/Downloads) y obviamente Git

```basic
$ git clone https://github.com/corozcop/vagrantbox
```

y luego

```basic
$ vagrant up
```

![beanstalk](C:\Users\carlos\Pictures\github\images\beanstalk.PNG)

![mailhog](C:\Users\carlos\Pictures\github\images\mailhog.PNG)

![jasperserver](C:\Users\carlos\Pictures\github\images\jasperserver.PNG)



# 

# Licencia MIT

```
Copyright (c) 2017 Carlos Orozco

Por este medio se concede permiso a cualquier persona que obtenga una copia de este software y archivos de documentación asociados (el "Software"), para tratar el Software sin restricciones, incluyendo sin limitación, los derechos de uso, copia, modificación, fusión, publicación, distribuir, sublicenciar y / o vender copias del Software, y permitir que las personas a las que se suministre el Software, con sujeción a las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso incluidos en todas las copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O IMPLÍCITA, INCLUYENDO PERO SIN LIMITARSE A LAS GARANTÍAS DE COMERCIALIZACIÓN, ADECUACIÓN PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO SERÁN LOS AUTORES O LOS TITULARES DE DERECHOS DE AUTOR RESPONSABLE DE CUALQUIER RECLAMACIÓN, DAÑO O OTRA RESPONSABILIDAD, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE OTRA MANERA, QUE SURJAN DE, EN FORMA O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTROS NEGOCIOS EN EL SOFTWARE.
```

