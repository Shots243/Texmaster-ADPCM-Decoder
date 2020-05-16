# Texmaster-ADPCM-Decode
 Decoder for the custom ADPCM format used in Texmaster2009.
 Some code taken from the source files for the external player.

## Build
`!! TODO !!`

## Usage
`TXM-ADPCM-DECODER [ADPCM File; required] [Loop Point Sample Number; optional]`

## Notes
* It is recommended that the ADPCM file is in the same directory as the program.
    * For the best experience, call this program from the terminal with the parameters you want.
* Loop point sample number needs to be > 0. See special_loop.txt in the game files for info.
* This program can only output 44100 Hz, Stereo, 32-bit Signed Integer PCM RIFF WAVE files.
* Use a program like LoopAuditioneer to hear the loop points.
* I'm not sure how memory-safe this program is.

