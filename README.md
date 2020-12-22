This project has a docker configuracion for Drupal 8. Update .env file if you need, this file contains the docker basic configurations. Docker configurations based on Wodby images, for more information go to: https://github.com/wodby/docker4drupal/

Then just run docker-compose up -d Go to pma and create both databases, for site 1 and for site 2. To run the drupal installations see the bellow links, make sure to use the correct db credentials. If everything went well you're done.

URLS:

  http://drupal1.docker.localhost:8000/ (Drupal site 1)
  http://drupal2.docker.localhost:8000/ (Drupal site 2)
  http://pma.drupal1.docker.localhost:8000/ (PHPMYADMIN site)
  http://portainer.drupal1.docker.localhost:8000/ (Portainer)
