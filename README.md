# libraries

This repository is a wrapper to hold all of the Arduino libraries used by the maintained
sketch repositories as submodules.  All maintained and used libraries can be obtained by
cloning this single repository.  This was originally created just to include as an
empty submodule in the [sketchbook](https://github.com/WCRSyyc/sketchbook) repository, so that
it could be directly used with the standard Arduino IDE.  Without this, the IDE creates
a libraries folder, which makes updating the sketches to the latest version in the associated
repositories more difficult.

The licensing can vary between libraries.  Where needed, and allowed, 3rd party libraries
will be forked and included here, or simply referenced as a submodule.  They will have
whatever the authors have chosen for licensing requirements.  Libraries that are maintained
directly at WCRsyyc, **probably** use the MIT license.

To clone this repository from the command line, including the submodules, use:
```sh
git clone --recursive https://github.com/WCRSyyc/libraries.git
```

The issue tracker for this repository should be about other libraries that should be added to the repository, things that do not belong, or out of date libraries. Comments and issues with individual libaries should go in the issue tracker for that library.  Which could be totally outside of the WCRSyyc github repositories. Where the issue affects multiple libaries, or the interaction between, that can go here, if there is no other repository that already groups the related libaries together.

For information on installing libraries, see: http://arduino.cc/en/Guide/Libraries
