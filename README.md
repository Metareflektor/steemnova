# SteemNova - 2Moons engine-based browsergame for Steemians by steemnova

*This fork just removes new implementation of fighting system for a webspace, where no php-extension could be installed.*

Fork of [github.com/steemnova/steemnova](https://github.com/steemnova/steemnova) repository which is a fork of [jkroepke/2Moons](https://github.com/jkroepke/2Moons) for Steem community purposes. 

## Local installation

- Clone the repo: `git clone https://github.com/Metareflektor/steemnova`
- Install components: `apt-get install apache2 php7.0 php7.0-gd php7.0-fpm php7.0-mysql php7.0-curl libapache2-mod mysql-server`
- Setup mysql: `create user USER identified by PASSWORD; create database DB; grant all privileges on DB.* to USER;`
- Set write privileges to dirs: `cache/`, `includes/`
- Run wizard: `127.0.0.1/install/install.php`

## Copyright and license

SteemNova is a fork of Open Source Browsergame Framework [jkroepke/2Moons](https://github.com/jkroepke/2Moons) engine.

Code copyright 2009-2016 Jan-Otto Kröpke released under the MIT License. 

Code copyright 2018 @steemnova released under the MIT License.
