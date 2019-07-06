# th.midiglide

**Please consider to download and donate via http://gumroad.com/tmhglnd**

A Max Abstraction that keeps track of currently held midi-notes and glide the midi-pitch back to previous note on release of latest pressed midi-note.

## About

Input a polyphonic kslider or keyboard. The object stores the previous played notes and glides towards the new played note when playing legato. When releasing a note it slides back to the previous held note and also changes previous played velocity. The output is the velocity on the left outlet, and the sliding pitch (as midi-floats) on the right. The grainsize of the slide is 5 milliseconds. Interpolation time between two pitch values can be set on the right inlet or as an argument in the object.

## Install

```
1. download zip 
2. unzip in Max searchpath (eg. on MacOS ~/Documents/Max 8/Library)
3. restart Max8
```

```
1. open terminal
2. navigate to Max searchpath (eg. on MacOS cd ~/Documents/Max\ 8/Library)
3. $ git clone https://github.com/tmhglnd/th.midiglide.git
```
