xmonad-config
=============

Configuration files for getting XMonad working with different desktop environments.

Choose right file for your desktop environment.

These files have been tested with following distros:

* Linux Mint 13.
* Fedora 15.

Don't forget to copy **xmonad.hs** file to your **~/.xmonad/** directory.

Each time you change **xmonad.hs** file, you should run following command:

    $ xmonad --recompile

In order to use **XMonad** with *MATE** you need to execute following commmand:

    $ mateconftool-2 -s /desktop/mate/session/required_components/windowmanager xmonad --type string

[Cheatsheet](http://www.haskell.org/haskellwiki/Image:Xmbindings.png)
