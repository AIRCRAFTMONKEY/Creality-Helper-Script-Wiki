---
hide:
  - toc
---
Entware is a software repository for devices which use the Linux kernel.

Installing Entware allows ton install packages to your printer to perform new tasks or provide other functionality than what it was marketed for, or simply to perform those functions better.

!!! Note
    **This procedure must be repeated after restoring the printer to factory settings or if you update the firmware.**


## Installation
<hr>

- Make sure you have followed this <a href="../../helper-script/helper-script-installation">Install Helper Script</a> section before.

- In the script, enter in `[Install] Menu` by typing ++"1"++ , validate with ++"Enter"++ and install `Entware`:

    <img width="900" src="../../assets/img/Creality-Helper-Script/Install_Menu.png">

- When it's done, log out of the current SSH session and log in again.

- The list of available packages can be found here: :material-web: [Entware Packages](https://bin.entware.net/mipselsf-k3.4/Packages.html).

- This is available commands (replacing `<packagename>` by the name of the package):

    
    To install a specified package:
    ```
    opkg install <packagename>
    ```
    
    To update available packages list:
    ```
    opkg update
    ```
    
    To update all installed packages:
    ```
    opkg upgrade
    ```
    
    To update a specified package:
    ```
    opkg upgrade <packagename>
    ```
    
    To display the list of all available packages:
    ```
    opkg list
    ```
    
    To display the list of all installed packages:
    ```
    opkg list-installed
    ```
    
    To display the list of packages that can be updated:
    ```
    opkg list-upgradable
    ```
    
    To remove package without its associated dependencies:
    ```
    opkg remove <packagename>
    ```

    To remove package and its associated dependencies:
    ```
    opkg --autoremove remove <packagename>
    ```
    
    To display detailed information about a specified package:
    ```
    opkg info <packagename>
    ```
    
    To display the list of files installed by a specified package:
    ```
    opkg files <packagename>
    ```

    !!! Example
        To install **Nano** (Nano is a small and simple text editor for use on the terminal):<br/>
        ```
        opkg install nano
        ```

<br />

**If you like my work, don't hesitate to support me by paying me a 🍺 or a ☕. Thank you 🙂**

<a href="https://ko-fi.com/guilouz" target="_blank"><img width="350" src="../../assets/img/home/Ko-fi.png"></a>
