Are you developing on Windows platform using cygwin? Is the windows native python that you use rather than the cygwin one?

This fork could be your choice if you want to use virtualenvwrapper.

To get it work you need virtualenv >= 1.7.1 (http://www.virtualenv.org/en/latest/news.html#id4) 

In your .bashrc or .zshrc, specify (all in unix style file path):

export VIRTUALENVWRAPPER_PYTHON="/cygdrive/c/Python27/python.exe"
export VIRTUALENVWRAPPER_VIRTUALENV="/cygdrive/c/Python27/Scripts/virtualenv.exe"
source "$HOME/dev/virtualenvwrapper/virtualenvwrapper.sh"

I've submitted a pull request to the main repo, so hopefully before long this feature will be available in main stream virtualenvwrapper.

Cliff
