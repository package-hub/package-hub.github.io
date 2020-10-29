---
title: moonlight
categories: ['python']
---
## [moonlight](https://github.com/tensorflow/moonlight)

### Optical music recognition in TensorFlow


An experimental [optical music
recognition](https://en.wikipedia.org/wiki/Optical_music_recognition) engine.

Moonlight reads PNG image(s) containing sheet music and outputs
[MusicXML](https://www.musicxml.com/) or a
[NoteSequence message](https://github.com/tensorflow/magenta/blob/master/magenta/protobuf/music.proto).
MusicXML is a standard sheet music interchange format, and `NoteSequence` is
used by [Magenta](http://magenta.tensorflow.org) for training generative music
models.

Moonlight is not an officially supported Google product.
