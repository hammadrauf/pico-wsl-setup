# pico-wsl-setup
Bash script derived from official Raspberry Pi Pico script, to setup Pico development environment on WSL2 in Windows 10 or Up.

## WSL2 Reference

https://docs.microsoft.com/en-us/windows/wsl/about

https://docs.microsoft.com/en-us/windows/wsl/install


## Test Environment Setup
WSL2 on Windows 10 or 11, Visual Studio Code (VSCode).

Following link is a Beautiful Article by 'Paul Bupe, Jr',  describing WSL2 based C/C++ setup for Windows 10 and Up:
https://paulbupejr.com/raspberry-pi-pico-windows-development/

You may want to use following script to setup configure WSL2 as the Script in above article skips some official Repositories for Pico:
https://github.com/hammadrauf/pico-wsl-setup/blob/main/pico_setup.sh

To download this script in your home folder in WSL2 and run the following on the WSL2 prompts:
```
cd ~
sudo apt install -y git
git clone https://github.com/hammadrauf/pico-wsl-setup.git
cd pico-wsl-setup
/bin/bash ./pico_setup.sh
```

Configuring of Visual Studio Code is explained very nicely in the the article by Paul in section "Configure and Build with Visual Studio Code" in [the article link given above.](https://paulbupejr.com/raspberry-pi-pico-windows-development/ "Link to article")
