Consuela
========
*A task delegation application*

Development
============

1. Ensure you have Vagrant (> 1.1), Virtualbox & composer installed on your host machine.
2. I recommend installing the host updater and guest additions plugin:
```
$ vagrant plugin install vagrant-hostsupdater
$ vagrant plugin install vagrant-vbguest
```
2. Clone the repository and cd into the project folder.
3. Run `$ composer install` inside the repo.
4. Copy homestead file `$ cp homestead.example.yaml homestead.yaml`, configure it to your local environment.
5. Copy env file `$ cp .env.example .env`, configue database details to local enviornment.
6. Run `$ vagrant up`.
7. SSH into the vagrant box `$ vagrant ssh`.
8. Generate an Application Key `$ php artisan key:generate`
8. Navigate to `http://consuela.app` in your browser to access the application.




