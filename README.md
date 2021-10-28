Fork of the Teensy Audio Library for use in M8 - https://github.com/PaulStoffregen/Audio

Removed unused classes for clearity with only a few left:
* AudioControlSGTL5000 - Modifed. Removed unnecessary power-up/init delays
* AudioFilterBiquad (16bit) - Used for hp/lp filter on the delay effect since it's 16bit
* AudioMixer4 (16bit) - Used for mixing the feedback input of the delay effect
