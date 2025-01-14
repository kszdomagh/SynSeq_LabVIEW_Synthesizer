work in progress

SynSeq - LabVIEW Synthesizer with built in 16-step Sequencer

//---------------------   SIMPLE OVERVIEW   -------------------------------------

SynSeq is a standalone LabVIEW based sequencer-synthesizer with built-in ADSR Envelope Generator, 16-step sequencer regulated with knobs that allow user to use microtonal music sequeces and fully explore his creative potential.

The design was heavily inspired by KORG SR-1, KORG Volca series, Arturia products, old-school Roland drum machines and the modular diy eurorack-compatible synthesizer scene.


//------------   CONTROLS AND INDICATORS LIST   ---------------------------------

The program uses 2 {UPDATE WHEN NECESSERY} custom SubVI's:
	- ADSR_Envelope_Generation_subVI;
	- FrequencyArrayToHz_SubVI;
	- Distortion_SubVI;
	- Filter_SubVIv;
	- Settings_SubVI;

Front panel is equipped with several Waveform graphs:
	- graph of ADSR Envelope;
	- current waveform graph;
	- Fast Fourier Transform graph of the currently played note.

Controls for the sequencer are as listed:
	- 16 knobs for all of the steps of the sequencer;
	- volume knob;
	- sequence legnth knob;
	- 4 sliders that control ADSR envelope generation;
	- lowpass filter slider;
	- lowpass filter enable switch;
	- distortion slider;
	- distortion  enable switch;


//---------------------   SIMPLE OVERVIEW   -------------------------------------

	INTRODUCTION:
Using of SynSeq is very simple. The user first enters the settings for his session in the "Settings" panel.
After confirming chosen settings the user is taken to the main Front panel where the parameters of the sequence can be chosen.

	SIMPLE SEQUENCE GENERATION:
All of 16 dials are programmed in such a way that the posoitions 0 to 12 represent all the notes of one octave.
Octave can be regulated by the "Octave Range" dial. Snapping is turned off which means that the user ia able to input microtonal note sequences.
Sequence length as the name suggests regulates the time of each sequence.
Waveform selects the waveform to be played

	ADSR ENVELOPE GENERATION MENU:
Attack, Decay, Sustain and Release control the envelope generation, which is displayed on the ADSR graph.
Attack, Decay and Release are time parameters, whereas Sustain is a level parameter.

	LOWPASS FILTER MENU:
tbd


	DISTORTION MENU:
tbd


	GRAPHS:
tbd







kszdom
