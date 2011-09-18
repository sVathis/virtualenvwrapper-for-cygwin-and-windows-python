Are you developing on Windows platform using cygwin? Is the windows native python that you use rather than the cygwin one?

This fork could be your choice if you want to use virtualenvwrapper.

Extra requirements:
1. environment variable CYGWIN_HOME for where cygwin is on your file system.
2. this patch on your virtualenv: https://github.com/pypa/virtualenv/pull/107/files the patch is addressing a bug in virtualenv, where its logic to determin whether the platform is cygwin does not work.

Why not submitting a pull request to mainline virtualenvwrapper?
Mainly because the bug fix in pull request https://github.com/pypa/virtualenv/pull/107 has not yet been accepted by mainline virtualenv.

Cliff
