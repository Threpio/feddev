# feddev
## Used by Threpio as a Fedora Developement machine setup script that is automated through Ansible. 

This script has a variables file that is defined by what is needed by my current work environment.

This code is proven to work on Fedora 30. This code requries the sudo passworkd twice towards the beginning and takes about 20 minutes to complete it's work.

It ensures (As a base) that the following programs are installed:

- git
- vim
- htop
- exa
- deluge

Adds the Dash-To-Dock Gnome interface extension and customises parts of it.

Also ensures the install and configuration of the following:

- Brave internet browser
- Fish Shell
- Postman
- Visual Studio Code
- NodeJs
- Jetbrains Toolbox

Also adds the following keyboard extensions:
- **Super+T** from Nautilus to open terminal from the current location in the file explorer
- **CTRL+Shift+Esc** opens the Sytem Monitor
- **CTRL+Alt+T** opens the terminal
- **Super+D** hides all windows

### Run the provision.sh file!


A copy of https://github.com/alexandrunastase/fedora-dev-machine - Adapted to my needs
