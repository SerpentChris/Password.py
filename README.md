# Password.py
A CLI password manager written in Python 3.6. Platforms this should work on are macOS, Linux, FreeBSD, Windows, and Cygwin, though it has only been tested on macOS.

## Dependencies
* Python 3.6. To install on macOS with Homebrew, run `brew install python3`. On Windows just download the installer from python.org. On Linuxes, you shhould probably compile it from source and install using `make altinstall`.
* keyring library. To install, run `pip3.6 install keyring`.
* xclip in Linux and Freebsd. To install in Ubuntu, run `sudo apt install xclip`.

On macOS this uses pbcopy to do keyboard copying, on Windows the clip command, on Cygwin /dev/clipboard.

To see usage information, run it with no arguments.
