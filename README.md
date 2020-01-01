# Software-Configurations

## Purpose

All configuration files used for some software software. Use at your own risk.  
This is the list of all settings files available :

- Visual Studio Code.

## About VSCode

### Add settings

You have 2 ways to install the settings :

- Open the settings in `File > Preference > Settings` and click on *Open settings (JSON)*  on the top bar to show the settings.json file
- Type <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>P</kbd> and type `Open Settings (JSON)`.
Then, you just *copy / paste* the settings into the opened file.

:warning: Dont' forget to install the font [Cascada Code](https://github.com/microsoft/cascadia-code) to get the ligature font.

### Install extensions

You just execute the following command `> .\vscode\extensions.sh` on the root of the project to install the extensions I use.

### Add custom snippets

You have 3 ways to add customs snippets :

- Go to `File > Preference > User Snippets` then click on `New Global Snippet file ...`, type the name of the snippet file and *copy / paste* the snippet into the opened file.
- Type <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>P</kbd>, type `snippet` on search bar and click on `Preferences: Configure Users Snippets` then `New Global Snippet file ...` and *copy / paste* the snippet into the opened file.
- In *Microsoft Windows*, open an explorer window and go to here `C:\Users\user_name}\AppData\Roaming\Code\User\snippets` and *copy / paste* directly the file get from the repository.
