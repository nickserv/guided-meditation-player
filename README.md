# [Guided Meditation Player](https://meditationplayer.surge.sh/)

A minimal guided meditation player, built with Polymer.

## Goal
Play a series of meditation audio segments with arbitrarily long pauses in between segments. Audio must automatically pause between segments, pressing a play button to continue.

## Status
In development, currently as a prototype for the UI.

## Supported Browsers
- Chrome
- Edge
- Firefox
- Safari

## Requirements

### Non Functional
- Implemented as a responsive client-side web app
- Minimal UI
- Support for modern (including mobile) browsers

### Functional

#### Input
- Series of audio files
- Can be specified in the URL, or entered through a GUI
- Audio files can be of different lengths, and each one plays until completion and then pauses, unless if it is paused prematurely

#### Playback
- Full-screen toggling pause/play button
- Audio starts paused
- When played, a segment will play until its completion (unless it is prematurely paused by the user) and wait until the play button is pressed to play the next segment

## Development

### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```
$ polymer serve
```

### Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
