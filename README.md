# outstandingKnife

## Overview

This is a simple little project which allows you to create github+pypi registered projects very very easily
It gives you a basic framework for setting out your code complete with argument parsing and setup.py working out of the box

## Installation

You should have a github account and an pypi account. Also you should install [hub](hub.github.com)

Then it should be as simple as:

    pip install outstandingKnife

## Example usage

To create a project called 'persistentIcyNeptune', go to where you usually like to develop your software and type:

    outstandingKnife persistentIcyNeptune -d persistentIcyNeptune

OK will print more instructions as it runs. Follow these to set up the repo on github and pypi.

To install your new project, cd into the persistentIcyNeptune directory and type:

    sudo python setup.py install --prefix=DIRNAME

You can omit the 'sudo' and the '--prefix=DIRNAME' if you want to install the project system-wide. Otherwise, provided that DIRNAME is in your $PATH, you should be good to go straight away.

## Help

If you experience any problems using outstandingKnife, open an [issue](https://github.com/minillinim/outstandingKnife/issues) on GitHub and tell us about it.

## Licence

Project home page, info on the source tree, documentation, issues and how to contribute, see http://github.com/minillinim/outstandingKnife

## Copyright

Copyright (c) 2013 Michael Imelfort. See LICENSE.txt for further details.
