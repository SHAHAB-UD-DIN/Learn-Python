
# Environment Setup
We'll start with downloading and setup the necessary software and tools.

Follow the step to download your envirnment.

- Visual Studio Code
- Docker Desktop





## 1. Visual Studio Code

Visual Studio Code (VSCode) is a free, open-source text editor that allows you to write code, edit code, and debug code. It is used for development, debugging, and version control. It is free to download and install.

[Download VSCode](https://code.visualstudio.com/download)

## 2. Docker Desktop

Docker Desktop is a software application that allows to build, share, and run containerized applications and microservices on local machine. It provides a user-friendly interface for managing containers, images, and Docker Compose files. Essentially, it's a tool that makes working with Docker easier and more accessible for developers.

Docker Desktop is free for education and learning purpose. However, commercial use of Docker Desktop at a company of more than 250 employees OR more than $10 million in annual revenue requires a paid subscription (Pro, Team, or Business)

Download & install [Docker Desktop](https://www.docker.com/products/docker-desktop/)

## 2.1 Docker Desktop for Windows
#### Pre-requisites:
- Windows 10 or later (64-bit)
- Enable Hardware Virtualization from BIOS Settings
- Windows Subsystem for Linux (WSL) - required to run linux containers
  #### Enable WSL:
  i. Open Start menu and search for "Turn Windows Features on or off". A new window will open.
  
  ii. Enable "Windows Subsystem for Linux (WSL)" and "Virtual Machine Platform".
  
  iii. Save it and restart the system

  iv. To check the installed version of WSL, run `wsl -l -v` in the command prompt.

  v. If you see version '1', we've to update to version '2'. In command prompt, run `wsl --update`. After update, run this command `wsl --set-default-version 2`.

Read more about [How to install WSL](https://learn.microsoft.com/en-us/windows/wsl/install)

## 2.4 Run your first container
After successful installation, run docker desktop. Open CLI tool and run this command `docker --version`. this will show the version of docker installed.

In CLI, run `docker run hello-world` command. Read the output.
