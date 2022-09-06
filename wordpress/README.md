# Docker compose for wordpress
This is a docker-compose file for running wordpress with mysql and phpmyadmin.

## Using your own files
To add your own files to the wordpress project, map them under the wordpress container in volumes.
For example, if you wish to use your own wp-content directory, your volumes would look as follows:
volumes:
- ${PWD}/wp-content:/var/www/html/wp-content