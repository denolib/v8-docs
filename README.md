[Go to v8 docs for Deno](http://denolib.github.io/v8-docs/)
===============

About
-----

This project is intended to be an up-to-date reference for developers using the [Google v8](http://code.google.com/p/v8/)
api. The reference is automatically created by [doxygen](http://www.stack.nl/~dimitri/doxygen/).

Current v8 version of this doc is 7.2.502.16

**This is not the official v8 repository. The v8 is not ours, it's an open-source project developed by Google.**

Contribute
----------

**Please**: If you find this reference out-dated don't hesitate to create a pull-request:

1. Fork the project
2. `git clone https://github.com/<your username>/v8-docs.git`

Then:

```shell
git checkout gh-pages
git submodule init
git submodule foreach git pull
doxygen
```

[doxygen](http://www.stack.nl/~dimitri/doxygen/) automatically pulls the `Doxyfile` and generates the docs. If
you don't have [doxygen](http://www.stack.nl/~dimitri/doxygen/): There are ready-to-use binaries for
[every major platform](http://www.stack.nl/~dimitri/doxygen/download.html).
