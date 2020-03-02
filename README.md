# Our Virtual Machine

A Vagrant powered Ubuntu VM with Android Studio and Flutter for mobile development.

This is our `Vagrantfile` based on [felipecassiors/ubuntu1804-4dev](https://app.vagrantup.com/felipecassiors/boxes/ubuntu1804-4dev) base box.

## Quick start

1. Install **Chocolatey** (the Windows Package Manager): <https://chocolatey.org/install>  
   It will be better if you follow the instructions in the link to install Chocolatey because the command can change in the future, however, currently it is:
   > Open **PowerShell as Administrator**

   ```powershell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
   ```

2. Install **Git for Windows**, **VirtualBox** and **Vagrant**
   > Open **PowerShell as Administrator**

   ```powershell
   choco install git
   choco install virtualbox
   choco install vagrant
   ```

3. Clone this repository and run `vagrant up`
   > Open **Git Bash**

   ```bash
   mkdir ~/Repos
   cd ~/Repos
   git clone https://github.com/price-search/our-vm
   cd our-vm
   vagrant up
   ```
