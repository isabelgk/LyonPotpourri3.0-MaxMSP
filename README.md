# LyonPotpourri

LyonPotpourri is a collection of externals developed for the creation and performance of computer music. The externals were originally developed for Max/MSP, and then extended into hybrid code that could compile for both Max/MSP and Pd. As of version 3.0, LyonPotpourri has diverged into separate Pd and Max/MSP versions. The Pd version is available [here](https://github.com/ericlyon/pd-lyonpotpourri).

LyonPotpourri is Copyright Eric Lyon, 1999-2023, and is covered under the MIT license. Please see the accompanying License file for details.

## Object Listing

- adsr~ a simple ADSR envelope that can be click triggered
- arrayfilt~ fft-based filtering by drawing into an array
- bashfest~ a click driven buffer player with randomized DSP
- buffet~ provides operations on a stored buffer
- buffi~ interpolates between the contents of two buffers
- bvplay~ selective playback from a stored buffer with enveloping and increment control
- cartopol~ convert a spectral frame from cartesian to polar form
- chameleon~ an oracular sound processor
- channel~ access to a precise address in the signal vector
- chopper~ munging loop playback from a buffer
- clean_selector~ like selector~ but crossfades when switching channels
- click~ converts a bang to a click
- click2bang~ converts a signal click to a bang message
- click2float~ translates a signal click to a float message
- clickhold~ sample and hold a click
- convolver~ non-real-time convolution with impulses of arbitrary size
- distortion~ lookup function distortion
- dmach~ pattern based sample accurate drum machine prototype
- epluribus~ combine several signal inputs to a single output based on min or max sample value
- expflam~ converts a click to an exponential flam click pattern
- flanjah~ simple flanger
- function~ write various functions into an array
- granola~ granular pitch scaling
- granule~ granular synthesis module reading from a stored waveform in a buffer
- granulesf~ granular synthesis module reading from a soundfile in a buffer
- kbuffer~ low sampling rate buffer to capture gestures
- killdc~ DC block filter
- latch~ sustain an incoming click with sample-accurate timing
- magfreq_analysis~ transforms a time domain signal to a magnitude/frequency spectrum
- markov~ implements a first order Markov chain
- mask~ a click driven pattern sequencer
- npan~ power-panning to an arbitrary number of output channels
- oscil~ oscillator with flexible waveform specification
- phasemod~ phase modulated waveform
- player~ click driven buffer player that can sustain multiple iterations
- poltocar~ convert spectral frame from polar to complex representation
- pulser~ pulse wave generated by additive synthesis
- quadpan~ pan an incoming sound within a quadraphonic plane
- rotapan~ rotate an array of input channels to the same number of output channels
- rtrig~ generates random click triggers
- samm~ sample accurate multiple metronomes, with click signal articulation
- sarec~ sample accurate recording
- sel~ sample-accurate implementation of the sel algorithm
- shoehorn~ collapse from a larger number to a smaller number of audio channels
- sigseq~ signal level numerical sequencer
- splitbank~ - split an incoming sound into complementary, independently tunable spectra
- splitspec~ split an incoming sound into complementary spectra
- squash~ implementation of a compression algorithm by Christopher Penrose
- stutter~ stuttering playback from a buffer
- vdb~ a delay line using an array for storage (no vector limit on feedback delaytime)
- vdp~ a simple, self-contained delay unit
- vecdex~ outputs the sample index within the current signal vector
- waveshape~ a Chebychev function lookup waveshaper
- windowvec~ apply a Hann window to the input signal vector

I hope you have as much fun using these externals as I did creating and using them in my own compositions.

Eric Lyon<br>
ericlyon@vt.edu<br>
School of Performing Arts | Music<br>
Institute for Creativity, Arts, and Technology<br>
Virginia Tech. 

January 9, 2023
