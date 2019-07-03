# Development Environment Script

### Supported Systems
* [Linux Mint - 19.1](https://linuxmint.com/)
  * Cinnamon - 4.0

### Supported Architectures
* Fully Supported
  * amd64 (64-bit)
* Partially Supported
  * i386 (32-bit)

### Install Applications
* Base Applications - Latest
  * Snap
  * Flatpak
  * Curl
  * Wget
  * Git
  * Unzip
  * Tar
  * Jq
  * Neofetch
  * Htop
* OpenJDK - 8
* Maven - Latest
* [Node - 10 (Snap)](https://snapcraft.io/node)
* [Docker - Latest (Script)](https://www.docker.com/)
* Docker Compose - Latest
* MySQL Workbench - Latest
* [Postman - Latest (Snap)](https://snapcraft.io/postman)
* [Google Chrome - Latest (Dpkg)](https://www.google.com/chrome/)
* [Visual Studio Code - Latest (Snap)](https://snapcraft.io/code)
* Visual Studio Code Extensions - Latest
  * Material Icon Theme
  * Bracket Pair Colorizer
  * Beautify
  * Version Lens
  * GitLens — Git supercharged
  * Java Extension Pack
  * Spring Boot Tools
  * Lombok Annotations Support for VS Code
  * Vetur
  * vuetify-vscode
  * language-stylus
  * Docker
  * Debugger for Chrome
  * Live Server

### Change Configurations
* OpenJDK
  * Environment Variables
    * $JAVA_HOME
* Visual Studio Code
  * Json
    * ~/.config/Code/User/settings.json

<br/>

# Execution Example

```shell
curl -H 'Cache-Control: no-cache' -sSL https://raw.githubusercontent.com/daniloancilotto/development-environment-script/master/install.sh | bash
```
