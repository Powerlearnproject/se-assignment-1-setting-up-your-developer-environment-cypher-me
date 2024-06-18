Author: Emmanuel Ngugi<br>
Assignment: PLP Academy<br>
Title: Environment setup<br>
Email: emmanuelngugi8@outlook.com<br>

## Operating System Setup
I chose to use Fedora linus due to its ease of use and its minimal use of system resources such as RAM and CPU cycles. <br>
[Fedora Linux Download Page](https://fedoraproject.org/workstation/download/)


## Installation Of IDE

Visit the Visual Studio Code download site and download the `.rpm` installer that is compatible with my system.
![VS Code download Page](./imgs/Screenshot%20from%202024-06-18%2011-07-03.png)

## Set Up Version Control System
Install git through the terminal with the command `sudo dnf install git`<br>

Initial git config commands to set the username, user email and default branch name.
```
    # set username
    git config --global user.name "cypher-me"
    # set useremail
    git config --global user.email "cyphermanu8@outlook.com"
    # set default branch name
    git config --global init.defaultBranch master
```

## Install Necessary Programming Languages and Runtimes
Install Python in fedora linux using this command `sudo dnf install python3` though it may be available on your system.<br>
To confirrm installation run the command `python` in the terminal
![Python install confimation](./imgs/Screenshot%20from%202024-06-18%2011-21-18.png)

## Install Package Managers

To install pip in linux i used the command `sudo dnf install python3-pip`
<br>
To confirrm installation run the command `python` in the terminal
![PIP confirmation](./imgs/Screenshot%20from%202024-06-18%2011-23-03.png)

## Dart Installation 

![Dart archive](./imgs/Screenshot%20from%202024-06-18%2010-43-37.png)
Download the dart archive file compatible with your system.<br>
- Unzip the file using the command `unzip dartsdk-linux-x64-release.zip` <br>

- copy the extracted folder to an instalation folder
- copy the path to the bin folder in the dart-sdk directory and add it to the $PATH variable in the ~/.barhrc file to make it persistent across boots. 

![Dart unzip and PATH editing](./imgs/Screenshot%20from%202024-06-18%2011-58-17.png)

![Dart PATH editing](./imgs/Screenshot%20from%202024-06-18%2012-00-04.png)

## Configure a Database (MySQL): Download and install MySQL database.

To install mySQL i run the command `sudo dnf install community-mysql-server` in my terminal

![MySQL Instalation](./imgs/Screenshot%20from%202024-06-18%2011-27-34.png)

To confirm the installation i run the command `mysql`

## Set Up Development Environments and Virtualization (Optional): Consider using virtualization tools like Docker or virtual machines
To install virtualbox you download the `.rpm`file from https://www.virtualbox.org/wiki/Linux_Downloads<br>

To install in the machine run the command `sudo dn install VirtualBox-7.0-7.0.18_162988_fedora40-1.x86_64.rpm`

![VirtualBox Download](./imgs/Screenshot%20from%202024-06-18%2011-36-27.png)

To install docker you first have to enable its repositories by running the command `sudo dnf config-manager --add-repo https://download.docker.com/linux/fedora/docker-ce.repo
`<br>

To install docker run `sudo dnf install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin`

![Docker Install](./imgs/Screenshot%20from%202024-06-18%2011-38-56.png)


## Explore Extensions and Plugins

The reqired extensions for Dart development, container Integration, MySQL development, git source contrall and python development are: `autopep8, Dart, Docker, Dev Containers, Flutter, MySQL Shell for VS Code, Pylance, Python, `

