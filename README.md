# Cuoco Starter Kit

This is a sample configuration respository to kickstart your server configuration.

## Usage

    git clone git://github.com/leonid-shevtsov/cuoco_starter_kit.git my_configuration
    cd my_configuration
    rm -rf .git
    bundle install
    vagrant up
    vagrant ssh-config >>~/.ssh/config
    cap cuoco:update_configuration

And you've already deployed a 'Hello, world' configuration to your virtual machine.

## Contents

* [Capistrano](https://github.com/capistrano/capistrano)
* [Vagrant](http://vagrantup.com)
* [Cuoco](https://github.com/leonid-shevtsov/cuoco)
* A `Vagrantfile` that will start up an Ubuntu 12.04 virtual machine
* A `Capfile` with multistage that uses the virtual machine by default.
* A Chef cookbook that includes one recipe that runs `apt-get update`

## Further instructions?

If you'd like to receive further instructions on using Cuoco, Capistrano and Chef, please [submit an issue](https://github.com/leonid-shevtsov/cuoco_starter_kit/issues) and I'll do my best to provide them.

* * *

[Leonid Shevtsov](http://leonid.shevtsov.me)