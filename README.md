# Stellar Astrophysics - Tools

This repository should serve as a general collection of useful tools
for various analysis purposes developed in house or externally.
Generally, there will be no direct development within this repository,
rather all tools will be added as a git submodule.

## List of tools available

### SMURFS
Smurfs is a command line tool, that allows for frequency analysis of
time series data. It will automatically determine all significant
frequencies above a given SNR. It also offers other features
such as spectral windows, spectrogram creation with overlaps, ...
For a better explanation see the github page.

## Do's and don'ts
If you want to add an internal tool to this repository, some things need
to be taken care of at first:

* **Documentation**: The code should be as documented as possible and
as necessary. Please write a short docstring for each function, method
and class and describe what they do.
* **Type annotations**: Python has the possibility to use type
annotations (see [here](https://docs.python.org/3/library/typing.html)
for documentation on it). Typing should **ALWAYS** be used throughout
the code, as it makes the code much more readable and understandable.
For other languages, please use equivalent functionality if they have
no strong typing.
* **Testing**: Generally, it is considered good practice to write tests
for your code. In the future, this repository will contain automated
tests, which will test your code using the tests you wrote. Preferably
use [pytest](https://docs.pytest.org/en/latest/). Please apply tests
to your code before adding it to the repository.
* **README.md**: Every submodule in this repository should contain at
least a small README.md that explains how to use the code, which
options are available, etc.
* **Keep your repo clean**: Only add files to your subrepo that are
necessary. Temporary files, images, Code Editor settings shouldn't be
checked in. For large files use git lfs.

