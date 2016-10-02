# Meditation Player
A minimal guided meditation player, built with Polymer.

## Goal
Play a series of meditation audio segments with arbitrarily long pauses in between segments. Audio must automatically pause between segments, pressing a play button to continue.

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
