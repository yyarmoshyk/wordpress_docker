This repo is designed to run separate containers required for WordPress CMS.
This includes
* php
* nginx
* mysql

In order to start everything run the following command:
```bash
docker-compose up -d
```

The mysqli exension will be installed to php_fpm container.
The folder `files/vhosts` will be created automatically.

When everything is up and running you can download and unzip the wordpress into the `files/vhosts/example.com` and proceed with the installation.
