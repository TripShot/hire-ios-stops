## Welcome

This is intended to be a simple project to help us get to know your experience with iOS development. The goal is to create a simple one screen iOS application that can satisfy the following use cases:

1. Display a list of transit stops, sorted by proximity to the user's current location, closest stop first.
2. If the user's current location cannot be obtained, display the stops alphabetized by stop name.
3. For each list item, render what you think is important data from the file. Be prepared to make your case for what should be shown, put yourself in the shoes of a transit user.
4. Ensure that VoiceOver announces the stop name using the tts_stop_name column.
5. Support a refresh button. This button should reload the stops and use the user's _latest_ location (if available).
6. Show an error if the stops cannot be loaded.

The transit stops are defined in the included stops.txt file. The structure of this file is defined here: https://developers.google.com/transit/gtfs/reference#stopstxt.

The hope is that this takes you a few hours, feel free to take your time and spread the work over a few days. This repository contains an app skeleton that may help you get started. It uses Cocoapods for dependencies (the expectation for this exercise is that you will use one or more dependencies). If you have an app skeleton you prefer to use, prefer to start from scratch, or prefer to use a different system for managing dependencies, feel free to do so. The only file that is essential is stops.txt.

## Other Requirements

1. Must be written in Objective-C or Swift.
2. Must use programmatic layout (no Storyboards or xib files).
3. Does not need authentication, localization, unit tests, or UI tests.
4. The stops file must be loaded asynchronously. Be prepared to show or discuss how you would load the same file (or some other representation of the contents of that file) over a network.
