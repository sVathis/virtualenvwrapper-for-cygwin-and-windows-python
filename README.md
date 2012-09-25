*Github mirror of Mercurial repo on [bitbucket](https://bitbucket.org/cliffxuan/virtualenvwrapper-for-cygwin-windows-python)*

1) Are you developing on Windows platform using cygwin? 

2) Is the windows native python that you use rather than the cygwin one?

3) Do you want to use [**virtualenvwrapper**](http://www.doughellmann.com/projects/virtualenvwrapper/) by *Doug Hellmann*.

This fork is for you.

Requirement
--
[**virtualenv >= 1.7.1**](http://www.virtualenv.org/en/latest/news.html#id4) 

In your *.bashrc* or *.zshrc*, specify (all in unix style file path):

    export VIRTUALENVWRAPPER_PYTHON="/cygdrive/c/Python2(x)/python.exe"

    export VIRTUALENVWRAPPER_VIRTUALENV="/cygdrive/c/Python2(x)/Scripts/virtualenv.exe"

    source "PATH_TO_SCRIPT/virtualenvwrapper.sh"


I've submitted a pull request to the main repo, so hopefully before long this feature will be available in mainstream virtualenvwrapper.
