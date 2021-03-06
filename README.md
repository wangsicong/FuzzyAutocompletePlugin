# FuzzyAutocomplete Plugin

![Demo](http://f.cl.ly/items/3B0X2j1e213a0u1b2x2f/fuzzyautocomplete.gif)

This is a Xcode 5 plugin that patches the autocomplete filter to work the same way the `Open Quickly` works.

It performs very well, and the fuzzy matching actually uses Xcode's own `IDEOpenQuicklyPattern`, however for performance reasons, the first letter of the fuzzy match must start with the same letter of the completion you want.

Like nifty tools like this plugin? Check out [Shortcat](https://shortcatapp.com/), an app that lets you control your Mac more effectively with your keyboard!

## Features

* Gives Xcode's autocompletion to be able to filter like `Open Quickly` does
* Performs well
* Productivity++

## Installation

* [Download](https://github.com/chendo/FuzzyAutocompletePlugin/releases/download/v1.0/FuzzyAutocomplete.xcplugin.zip) and extract into `~/Library/Application Support/Developer/Shared/Xcode/Plug-ins`, or clone and build the project.
* Restart Xcode and enjoy!

## Notes

* Only tested with Xcode 5 on 10.9
* Hasn't been tested with other plugins yet

## Changelog

#### 1.1 - 2013/10/21

* Implement partial completion support via `Tab`

#### 1.0 - 2013/10/20

* Initial release

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/2803367345737409176241eb9cc3f903 "githalytics.com")](http://githalytics.com/chendo/fuzzyautocompleteplugin)
