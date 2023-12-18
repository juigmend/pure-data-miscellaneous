Audio-Video Player v0.1

Tested on:
- Puredata Extended 0.43.4
- Macintosh OS 10.11

March 7th., 2016

===================================================================

Audio-Video Player plays synchronised audio and video files allowing detailed control and retrieval of position in frames and time.

Dependencies: Puredata and codecs (audio and video, installed in the operation system).

Audio-Video Player is copyrighted, free to use and free to distribute under
the GNU General Purpose License version 2.

-------------------------------------------------------------------
Instructions:

Click the “settings” button to open an audio and video file that will play synchronised.

You might have to change audio settings in Pd’s menu “Media, Audio Settings” as follows:
	- Sample rate: Adjust this to the sample rate of the audio file to be played 
	- Delay (msec): Increase this as “Block size” is increased
	- Block size: Increase this if you are experiencing audio drops at playback
Changes in audio settings done after any audio file is opened will crash Puredata. Thus, changes in audio settings should be done before any audio file is opened. For example, when you notice drops in audio you should close the patch, open the patch again, adjust the audio settings and only then play back audio and video together.
To minimise the delay in audio playback it is convenient to have the video and audio files in separate drives.

The rest is quite intuitive.
-------------------------------------------------------------------
===================================================================
Version log
-----------

0.1
hello world
Tested formats: 
	Audio: 16bit-WAV
	Video: Cinepak-MOV

-------------------------------------------------------------------
Copyright 2016 Juan Ignacio Mendoza 
