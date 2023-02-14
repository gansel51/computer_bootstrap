# New Laptop Set Up

This repository is the host to my current computer's set up. It contains a bash script to install tools, packages, and applications I find useful to have on my personal machine.

## Compatibility

This script is only compatible with MacOS, as it leverages Homebrew, a platform specific tool. It installs and globalizes Python 3.7.8, though that is easily editable to your preferred version.

## How to Use This Script

To use this script, you're going to have to download the "computer_bootstrap" file. When you do, you'll have to change directory to the location to where you put the download, most likely by `cd Downloads`.

Once there, you may have to modify the script to be recognized as a script. If it appears as a TextEdit file, you will need to run a command to mark it as a script. However, depending on the permissions of your laptop, you may need to allow the shell edit access to the download. To do that, go into a Finder window, select the computer_bootstrap file, then right click (CMD + click) and select "Get Info". From there, under the heading "Sharing and Permissions" there will be a lock symbol on the bottom right. Unlock that (you may be prompted for your system password) then you can run `chmod 700 computer_bootstrap` to have your sysem recognize this script.

Finally, to run the script, use the command `./computer_bootstrap`. You will begin to see logs in the terminal window that share the status of the script.

You may need to add pieces of this script to your bashrc or zshrc as needed.
