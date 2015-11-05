Gello Build System
==================

Inline build environment for Gello

Documentation
-------------

Features
----------
- *-h*          = Show help message
- *-v*          = Verbose mode, show more details
- *--fast*      = Skip sync and runhooks, useful for testing changes
- *--clean*     = Remove the whole Gello build system
- *--depot*     = Install Depot Tool
- *--mp*        = Once everything else is done, install the given apk on a connected device
- *--no-sync*   = Skip sync
- *--verbose*   = As "-v", show more details

Setup
----------
Read [chromium documentation](https://chromium.googlesource.com/chromium/src/+/master/docs/linux_build_instructions_prerequisites.md) for needed packages to build Gello. To get sources you need Depot tools that can be easily installed using _gello_build.sh --depot_
