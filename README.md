Vagrant & Docker php development environment
============================================

First approach to docker web development environment based on this great post from 
["osteel's blog"](http://tech.osteel.me/posts/2015/12/18/from-vagrant-to-docker-how-to-use-docker-for-local-web-development.html).

## Requirements:

* [vagrant](https://www.vagrantup.com/docs/installation/)

## Stack:

* nginx
* php 7
* mysql
* PhpMyAdmin

## Installation:

Move to your workspace and clone repository.

    git clone git@github.com:kpicaza/php7-docker.git ./projectName

## Usage

Start container and open a browser at [http://localhost/info.php](http://localhost/info.php), served files are 
allocated inside `app/` folder.
    
### Start:

    cd projectName
    vagrant up dev

### Stop:
    
    vagrant halt dev
    
### Console access

    vagrant ssh dev
