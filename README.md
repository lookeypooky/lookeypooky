
    cd Minecraft
    python main.py

On Mac OS X, you may have an issue with running Pyglet in 64-bit mode. Try running Python in 32-bit mode first.
### Mac

On Mac OS X, you may have an issue with running Pyglet in 64-bit mode. Try running Python in 32-bit mode first:

    arch -i386 python main.py

Or, try Pyglet 1.2 which supports 64-bit mode.
If that doesn't work, set Python to run in 32-bit mode by default:

    defaults write com.apple.versioner.python Prefer-32-Bit -bool yes 

This assumes you are using the OS X default Python.  Works on Lion 10.7 with the default Python 2.7, and may work on other versions too.  Please raise an issue if not.

Or try Pyglet 1.2 alpha, which supports 64-bit mode:  

    pip install https://pyglet.googlecode.com/files/pyglet-1.2alpha1.tar.gz 

### If you don't have pip or git

For pip:

- Mac or Linux: install with `sudo easy_install pip` (Mac or Linux) - or find a package called something like 'python-pip' in Linux and install in your package manager.
- Windows: [http://stackoverflow.com/a/12476379/992887](install Distribute then Pip) using the linked .MSI installers.

For git:

- Mac: install [Homebrew](http://mxcl.github.com/homebrew/) first, then `brew install git`.
- Windows or Linux: see [Installing Git](http://git-scm.com/book/en/Getting-Started-Installing-Git) from the _Pro Git_ book.

See the [https://github.com/fogleman/Minecraft/wiki](wiki) for this project to install Python, and other tips.
