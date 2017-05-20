# nginx-virthosts
This repository provides a configuration for the nginx webserver that can handle multiple PHP versions and multiple userspace mass dynamic virtual hosts. It can give a base to build an advanced development machine with multiple projects on it.

This examples have been created for nginx on an Ubuntu system with multiple PHP versions installed via the PPA: https://launchpad.net/~ondrej/+archive/ubuntu/php
In Ubuntu you can install the PHP versions and their FPM modules via the following commands:
```
sudo apt install php5.6 php7.0 php7.1 php5.6-fpm php7.0-fpm php7.1-fpm
```

If nginx is installed, you can place the .conf files in `/etc/nginx/sites-available` and symlink them into `/etc/nginx/sites-enabled`. Reload the nginx configuration or restart the webserver to have the configuration take effect.
