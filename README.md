# Magento 2 Boilerplate

A boilerplate for working with Magento 2.

## Starting your project
1. Run `git clone https://github.com/HoustonMagentoMeetup/magento2-boilerplate.git project_name`
2. Run `script/bootstrap`
3. Run `script/setup`
4. Run `script/server`

## Environment Variable Settings
**Docs coming soon**

## Scripts to rule them all!
The boilerplate is using a script pattern that @github uses, [scripts to rule them all](https://github.com/github/scripts-to-rule-them-all). 

### Bootstrap
Command: `script/bootstrap`

Bootstraping sets up your docker environment which includes:

1. Nginx
2. Percona
3. PHP7 FPM
4. Magento 2

### Setup
Command: `script/setup`

Setup takes your Magento 2 project and brings it into your bootstrapped environment.

### Server
Command: `script/server`
Command: `script/server stop`

The server sript lets you start and stop your environment so you can switch between multiple projects if needed.

### Destroy
Command: `script/destroy`

The destroy script will completely wipe your docker environment.

### Magento Command Line
Command: `script/magento`

Allows you to run the Magento command line from your project root without having to ssh into the container.

### SSH
Command: `script/ssh`

Allows you to SSH into the container.
