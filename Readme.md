# Simple PHP configuration with nginx

Php 7.4 with nginx 1.23.3 configuration in alpine 3.16 from docker-compose.

### Installation:

``git clone https://github.com/codesshaman/docker_nginx_php74_alpine.git``

``cd docker_nginx_php74_alpine``

## Build configuration (first launch)

For building configuration change composer commands in makefile and use

``make build``

In process of building running php-composer container and execute container commands (laravel creation for example).

laravel will be available in the next address:

``http://localhost/laravel/public/index.php``

If your not use laravel and composer, you can commit lines with this commands.

### Stop configuration

``make down``

### Restart

``make re``

### Start

``make``

## Usage:

Copy your php code to "app" folder or use symlink to this folder from your php project.