# Installation

`#` June 2018 ( Last update )

> **Requeriments**

* [Nodejs](https://nodejs.org/es/) (Required)

**`#` Linux Instalation**

```bash
sudo apt-get install npm
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
sudo ln -sf /usr/local/n/versions/node/<VERSION>/bin/node /usr/bin/nodejs
sudo n latest
```
* [Typescript](https://www.typescriptlang.org/) (Required)
* [Angular CLI](https://cli.angular.io/) (Required)

**`#` To update angular cli se debe correr los siguientes comandos:**

```bash
npm uninstall -g angular-cli @angular/cli
npm cache clean --force
npm install -g @angular/cli@latest 
```