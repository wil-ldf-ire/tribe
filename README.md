# Tribe

### quick install
```
sudo wget https://raw.githubusercontent.com/wil-ldf-ire/tribe/master/install/install.sh; sudo bash ./install.sh; sudo rm ./install.sh;
```

### updating tribe
```
sudo composer update
```

### for ember app installation
In local dev machine
```
ember init;
ember install ember-auto-import;
ember install ember-cli-sass;
ember install ember-cli-deploy;
ember install ember-cli-deploy-build;

ember serve;
ember deploy;
```
To upload to remove prod server, create build in local machine
```
ember build -o theme/dist;
```
To get process ID on local machine
```
sudo lsof -i tcp:port_num
```

### Tribe - a web project management system by wildfire.

A few config files to get started with Tribe:
- .env - variables like db connection, third-party APIs
- types.json - project's information architecture
- menus.json - navigation menus

Install folder contains all installation scripts. Gets deleted on installation.