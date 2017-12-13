ext
===

This directory holds git submodules that point to libraries needed by the WebM and WebP plug-ins.

You will need to manually add the following to this directory because the owners don't have a git repository I can embed:

* [Premiere CS5 SDK](http://www.adobe.com/devnet/premiere/sdk/cs5.html)
* [Photoshop CS5 SDK](http://www.adobe.com/devnet/photoshop/sdk.html)


If the submodule contents are missing, you should be able to get them by typing:

`git submodule init`
`git submodule update`

Both Mac and Windows require the "yasm" shell program be installed for libvpx to compile.  On Windows you get it via Cygwin.

