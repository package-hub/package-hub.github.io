---
title: audio_to_midi_melodia
categories: ['python']
---
## [audio_to_midi_melodia](https://github.com/justinsalamon/audio_to_midi_melodia)

### Extract the melody from an audio file and export to MIDI

Extract the melody notes from an audio file and export them to MIDI and (optionally) JAMS files.

The script extracts the melody from an audio file using the [Melodia](http://mtg.upf.edu/technologies/melodia) algorithm, and then segments the continuous pitch sequence into a series of quantized notes, and exports to MIDI using the provided BPM. If the `--jams` option is specified the script will also save the output as a JAMS file. Note that the JAMS file uses the original note onset/offset times estimated by the algorithm and ignores the provided BPM value.

Note: extracting a MIDI melody from a polyphonic audio file involves two main steps: 
1. melody extraction 
2. note segmentation. 

**Melody extraction** is the task of estimating the continuous fundamental frequency (f0) of the melody from a polyphonic audio recording. This is achieved using the Melodia melody extraction algorithm, which is the result of [several years of research](http://www.justinsalamon.com/phd-thesis.html). 

**Note segmentation** is the task of converting the continuous f0 curve estimated by Melodia (which can contain e.g. glissando and vibrato) into a sequence of quantized notes each with a start time, end time, and fixed pitch value. **Unlike Melodia, the note segmentation code used here was written during a single-day hackathon** and designed to be as simple as possible. Peformance will vary depending on musical content, and it will most likely not provide results that are as good as those provided by state-of-the-art note segmentation/quantization algorithms.
