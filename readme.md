# Wheels V2

Another go at creating a meditative web app that plays cyclical sine waves. Currently plays a major scale centered around a3 (220hz).

It uses [pythagorean tuning](https://en.wikipedia.org/wiki/Pythagorean_tuning) to create the scale.

##To Dos
* Add more scales, and a selection input to choose between them. The number of nodes will need to update
* Sort out the panning - at the moment it's just randomised for each node between -1 and 1. The nodes should really be panned according to their positions around the wheel.
* Performance (especially on mobile). This is using [tone.js](https://github.com/Tonejs/Tone.js), so performance is *a lot* better than using the p5 sound library, but it could be a lot better still. Reduce frame rate?