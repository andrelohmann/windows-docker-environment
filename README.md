# windows-docker-environment
The perfect windows setup for developing with containers

## Install WSL2

https://docs.microsoft.com/en-us/windows/wsl/install

  * Press Win Key + X and select "Windows PowerShell (Admin)"
  * Run the WSL2 installer
  
```
wsl --install -d Ubuntu-20.04
```

  * set your wsl username and password properly
  * verify, you are working on WSL version 2

```
wsl -l -v
```

### How to enable Ctrl+C and Ctrl+V in WSL?

  * Open your WSL Terminal Window.
  * Right Click on the title bar.
  * Click on Properties menu.
  * Under Options, Tick the Use Ctrl+Shift+C/V as Copy/Paste.

## Install chocolatey

  * https://chocolatey.org/install

## Install Chromium

  * choco install chromium

## Vagrant + Virtualbox?
DO NOT INSTALL YET

  * https://www.vagrantup.com/docs/other/wsl
  * https://thedatabaseme.de/2022/02/20/vagrant-up-running-vagrant-under-wsl2/

## Docker Desktop

  * choco install docker-desktop
  * Start docker Desktop
  * Settings - General - use wsl2

## Visual Studio Code

  * choco install VisualStudioCode
  * install remote extensionpack
  * https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

### Some helpful VSCode tutorials

  * https://docs.microsoft.com/de-de/windows/wsl/tutorials/wsl-vscode
  * https://docs.microsoft.com/de-de/windows/wsl/tutorials/wsl-git

## GIT UI

Not solved yet
