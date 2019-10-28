# docker-symfony 
## Docker for symfony projects

# 1. Run project
- create symfony folder inside project
- create symfony project -> https://symfony.com/doc/current/setup.html
- run docker-compose build
- run docker-compose up -d 
- ! Important sometimes mysql image brokes up than run previous command one more time ! 
- fill .env file in symfony project with proper data f.e DATABASE_URL=mysql://root:root@db:3306/symfony
- add symfony.localhost to your host file
- run browser with app under symfony.localhost
