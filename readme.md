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
2. Clone the repository.
3. Run `$ composer install` inside the repo.
5. Copy `homestead.example.yaml` to `homestead.yaml`, configure it to your local environment.
6. Run `$ vagrant up`.
7. You can now ssh in with `$ vagrant ssh` and should be able to access the application at `http://consuela.app` 




