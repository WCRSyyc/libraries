# libraries

This repository is a wrapper to hold all of the Arduino libraries used by the maintained
sketch repositories as submodules.  All maintained and used libraries can be obtained by
cloning this single repository.  This was originally created just to include as an
empty submodule in the [sketchbook](https://github.com/WCRSyyc/sketchbook) repository, so that
it could be directly used with the standard Arduino IDE.  Without this, the IDE creates
a libraries folder, which makes updating the sketches to the latest in the associated
repositories more difficult.

The licensing can vary between libraries.  Where needed, and allowed, 3rd party
libraries will be forked and included here.  They will have whatever the authors
have chosen for licensing requirements.  Libraries that a maintained directly at
WCRsyyc, **probably** use the MIT license.

To clone this repository, including the submodules, use

git clone --recursive https://github.com/WCRSyyc/sketchbook.git

from the command line.

The issue tracker for this repository should be for other sketches that should be added to the repository, or things that do not belong. Comments and issues with individual sketches should go in the issue tracker for that sketch. Where the issue affects multiple sketches, or the interaction between, that can go here, if there is no other repository that already groups the related sketches together.
wrapper to hold arduino library files to be used with the maintained sketches

For information on installing libraries, see: http://arduino.cc/en/Guide/Libraries
