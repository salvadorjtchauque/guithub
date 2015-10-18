# GuitHub
A guitar scale helper website as my final project for CS50 through EdX. It's a work in progress, and a bit messy at the moment.

### How does it work?
You pick a root note and a tonality, and it draws the scale on the fretboard.

It uses the colors of the rainbow (ROYGBIV) to indicate scale tones, so if you know your colors then you know which fret is which degree of a given scale.

### Can I use it right now?
I currently have not hosted this anywhere, but if you clone the repo and open index.html with your favorite browser you can see the current state of the project.

### TODO
- [x] Fix output
  - [x] Encapsulate each note in a text object
  - [x] Clear all note graphics on submit
- [ ] Better clarity
  - [ ] Colorblind friendly display options
  - [ ] Improve text rendering
  - [ ] Better support for high PPI displays
  - [x] Thicker line to differentiate the nut
  - [x] Note names as markers
- [x] Position markers for easy glances
- [ ] Chord tone highlighting
  - [x] Base layer of markers to show where notes outside chord are
  - [ ] Toggle highlighting with number keys (1-7 for chords, 0 for full)
