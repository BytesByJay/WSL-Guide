# Windows Subsystem for Linux (WSL) Installation and Configuration Guide
This guide provides step-by-step instructions for installing and configuring Ubuntu within the Windows Subsystem for Linux (WSL). WSL allows you to run a Linux distribution directly on Windows, enabling you to use Linux tools and workflows without the need for dual-booting or virtual machines.

## Installing WSL (Windows Subsystem for Linux)

1. **Open PowerShell as Administrator**: Right-click the Start menu, then select "Windows PowerShell (Admin)".

2. **Install WSL**: Run the following command in PowerShell:
   ```sh
   wsl --install
   ```
   This command will enable the WSL feature on your system.

## Switching to WSL 2

3. **Set Default WSL Version to 2**: After installing WSL, switch to WSL 2 by running:
   ```sh
   wsl --set-default-version 2
   ```
   This ensures that any new Linux distributions installed will use WSL 2.

## Managing Linux Distributions

4. **List Available Linux Distributions**: To see all available Linux distributions in the Microsoft Store, use:
   ```sh
   wsl --list --online
   ```
   This command will display a list of Linux distributions that you can install.

5. **Install Ubuntu**: If you choose Ubuntu, you can install it directly using:
   ```sh
   wsl --install -d Ubuntu
   ```
   This command will download and set up Ubuntu on your system.

6. **Check Installed Distributions**: To see which Linux distributions are installed and their versions, run:
   ```sh
   wsl -l -v
   ```
   This will list all installed distributions along with their respective versions.

## Configuring Ubuntu

7. **Set Default Distribution**: If Ubuntu is not your default distribution, you can set it using:
   ```sh
   wsl --setdefault Ubuntu
   ```
   This will make Ubuntu the default distribution to launch when using WSL.

8. **Configure Ubuntu**: After setting Ubuntu as default, update its package lists by running:
   ```sh
   sudo apt update
   ```
   This ensures that you have the latest package information.
   
```vb
This Markdown document provides a step-by-step guide for installing, managing, and configuring WSL with Ubuntu on your Windows system.
```
