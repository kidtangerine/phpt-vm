# phpt-vm

## Setup

* Clone this repo
* `cd path/to/repo`
* `composer install`
* `./vendor/bin/homestead make`
* `vagrant up`
* `vagrant ssh`
* `git clone git@github.com:memphisphp/phptestfest-php-src.git`
* `cd phptestfest-php-src`

## Compile PHP

* `cd /home/vagrant/php/phptestfest-php-src`
* `./configure`
* `make -j5`
* `sapi/cli/php --version`
