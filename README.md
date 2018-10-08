homebrew-sync
=========

***Oct 2018: OBSOLETE/DEPRECATED/DO NOT USE***
***`homebrew-bundle` and a global ~/.Brewfile are better***
***just keep your ~/.Brewfile in Dropbox, perhaps using [mackup](https://github.com/lra/mackup)***

Sync homebrew packages (including taps and casks) between computers using Dropbox

Based on code by @witt3rd - https://gist.github.com/witt3rd/894c9e0b9ca4e24e5574

Outstanding issues:

* Hard-coded paths, most notably the location of your Dropbox folder
* Package re-installation is imperfect
* No error handling either
* Does not *remove* packages, only installs them


Usage
-----

```
git clone https://github.com/jamiew/homebrew-sync
cd homebrew-sync
```

Read the `sync-brews` file and make sure the hard-coded paths align with your interests (e.g. `~/Dropbox (Personal)/Apps/Homebrew` for stashing your list of taps, packages and casks)

Then

```
./sync-brews
```

Re-run regularly-ish


License
--------

All source code released under an [MIT license]()

Copyright &copy; 2017 Jamie Wilkinson



