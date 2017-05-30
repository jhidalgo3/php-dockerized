# PHP Dockerized

> Dockerized PHP development stack: Nginx, MySQL, PHP-FPM, HHVM, SOAP

PHP Dockerized gives you everything you need for developing PHP applications locally. The idea came from the need of having an OS-agnostic and virtualized alternative to the great [MNPP](https://github.com/jyr/MNPP) stack as regular LAMP stacks quite simply can't keep up with the Nginx + PHP-FPM/HHVM combo in terms of performance. I hope you'll find it as useful an addition to your dev-arsenal as I've found it!

[Original code from @kasperisager](https://github.com/kasperisager/php-dockerized)

## What's inside

* [Nginx](http://nginx.org/)
* [MySQL](http://www.mysql.com/)
* SOAP Client PHP

## Requirements

* [Docker Engine](https://docs.docker.com/installation/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Machine](https://docs.docker.com/machine/) (Mac and Windows only)

## Running

Set up a Docker Machine and then run:

```sh
$ docker-compose up
```

That's it! You can now access your configured sites via the IP address of the Docker Machine or locally if you're running a Linux flavour and using Docker natively.

## License

Copyright &copy; 2017 [Jose Maria Hidalgo Garcia](http://github.com/jhidalgo3). Licensed under the terms of the [MIT license](LICENSE.md).
