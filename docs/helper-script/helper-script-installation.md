Helper Script allows to install latest official builds and many useful features.

It's completely automated, necessary changes are made automatically when installing a feature and restored after uninstallation.

When the script is updated, installed files are automatically updated as well.

!!! Warning
    **FOR <u>K1 SERIES</u>: ONLY USE THIS SCRIPT WITH FIRMWARE 1.3.3.5 AND ABOVE!<br />
    FOR <u>KE SERIES</u>: ONLY USE THIS SCRIPT WITH FIRMWARE 1.1.0.12 AND ABOVE!<br />
    FOR <u>ENDER-3 V3 SERIES</u>: ONLY USE THIS SCRIPT WITH FIRMWARE 1.2.1.3 AND ABOVE!**

!!! Note
    **Please restore firmware to factory settings before using script to avoid issue.**<br />
    See: <a href="../../firmwares/reset-factory-settings">Reset Factory Settings</a> section.

## Installation
<hr>

If you have already installed Moonraker, Fluidd or Mainsail provided by Creality, please uninstall them first using `[Remove] Menu`.

- Connect to SSH (Guide is available <a href="../../firmwares/ssh-connection">here</a>).

- Enter the following command to install script in `usr/data` folder:

    ```
    git clone https://github.com/Guilouz/Creality-Helper-Script.git /usr/data/helper-script
    ```

- And enter this command to run the script:

    ```
    sh /usr/data/helper-script/helper.sh
    ```

<br />

- If you encounter an issue to clone Helper Script repository, enter this command before cloning:

    ```
    git config --global http.sslVerify false
    ```

- Also, make sure your system date and time are correct. See [Change Date & Time](../../firmwares/change-date-and-time) section.

!!! Note
    Some features are not available for KE Series.


## Update
<hr>

Creality Helper Script can be updated in two ways:

- Directly from the script at startup:

    <img src="../../assets/img/Creality-Helper-Script/Update_Screen.png">

- In Update Manager from the Web interface:

      | From **Fluidd** in `Settings` tab → `Software Updates` |
      | :---------: |
      | <img width="800" src="../../assets/img/Creality-Helper-Script/Update_Fluidd.png"> |

      | From **Mainsail** in `MACHINE` tab |
      | :---------: |
      | <img width="800" src="../../assets/img/Creality-Helper-Script/Update_Mainsail.png"> |


## Main Menu
<hr>

This is the main menu:

<img src="../../assets/img/Creality-Helper-Script/Main_Menu.png">


## Install Menu
<hr>

This menu allows you to install various useful features:

<img src="../../assets/img/Creality-Helper-Script/Install_Menu.png">


## Remove Menu
<hr>

This menu allows you to remove installed features:

<img src="../../assets/img/Creality-Helper-Script/Remove_Menu.png">


## Customize Menu
<hr>

This menu allows you to customize your printer:

<img src="../../assets/img/Creality-Helper-Script/Customize_Menu.png">


## Backup & Restore Menu
<hr>

This menu allows you to backup and restore your configuration files:

<img src="../../assets/img/Creality-Helper-Script/Backup_Restore_Menu.png">


## Tools Menu
<hr>

This menu allows you to perform different actions:

<img src="../../assets/img/Creality-Helper-Script/Tools_Menu.png">


## Information Menu
<hr>

This menu allows you to know what is installed or not on the printer:

<img src="../../assets/img/Creality-Helper-Script/Information_Menu.png">


## System Menu
<hr>

This menu allows you to have different information about the printer:

<img src="../../assets/img/Creality-Helper-Script/System_Menu.png">


<br />

**If you like my work, don't hesitate to support me by paying me a 🍺 or a ☕. Thank you 🙂**

<a href="https://ko-fi.com/guilouz" target="_blank"><img width="350" src="../../assets/img/home/Ko-fi.png"></a>
