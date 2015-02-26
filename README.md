Description
-----------

This package provides support for Multiple Major Mode (MuMaMo) in the
[Emacs IPython Notebook](https://github.com/millejoh/emacs-ipython-notebook)
project.

MuMaMo is part of the [nxhtml][nxhtml] project, which hasn't seen any updates in
a long time. Unfortunately I cannot guarantee this code will continue to work
in later version of Emacs, but at the moment it seems to work fine with Emacs 24.3
with this [fix](http://millejoh.github.io/emacs-ipython-notebook/#id17)

More documentation on this feature can be found in the
[documentation](http://millejoh.github.io/emacs-ipython-notebook/) for ein.

Installing
----------

With ein-mumamo depends on parts of nxhtml, so I have tried to include all the
nxhtml dependencies in one place since [nxhtml][nxhtml] is not currently
availabe in MELPA and can be difficult to install.

Both ein and ein-mumamo are available in MELPA, and this is the preferred way to
install these pacakges. Otherwise you will need to download both from Github
([ein][ein github] and [ein-mumamo][ein-mumamo github]).

Make sure both ein and ein-mumamo are in your load path, then add

    (require 'ein-mumamo)

to your emacs init file. Note that there are many other customizations you can
make to ein, see the full
[documentation](http://millejoh.github.io/emacs-ipython-notebook/) for details.


[nxhtml]: http://ourcomments.org/Emacs/nXhtml/doc/nxhtml.html
[ein github]: https://github.com/millejoh/emacs-ipython-notebook
[ein-mumamo github]: https://github.com/millejoh/ein-mumamo
