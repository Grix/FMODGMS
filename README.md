# FMODGMS

<p align="center">
    <img src="https://github.com/mstop4/FMODGMS/blob/master/img/fmodgms2.PNG" width=75%>
    <img src="https://github.com/mstop4/FMODGMS/blob/master/img/fmodgms%20ubuntu.png" width=75%>
</p>

A ***GameMaker: Studio* and *GameMaker Studio 2* extension** that provides **GML bindings to the [FMOD](http://www.fmod.org) Studio low-level API.** Compatible with **Windows**, and **Linux** games.

---

## **Status**

### **Stable/Latest - [0.9.0](https://github.com/mstop4/FMODGMS/releases/tag/v0.9.0)**  

* *Platforms:* Windows, Ubuntu
* *FMOD Studio API:* 1.10.00
* *GMS 2 Runtime:* v.2.1.1.158
* *GM:S Runtime:* v.1.4.1773


Features
--------

- Load and play a wide variety of audio formats not natively supported by *GameMaker:Studio* (e.g. MP3, MIDI, MOD, S3M, XM, IT, etc.).
- Play MIDI files using DLS1 sound banks.
- Add custom loop points to sounds. This allows, for example, a music track to have an intro section that can seamlessly transition into an infinitely looping main section without having to break them up into two separate files.
- Dynamically change to volume, playback frequency and relative pitch of a sound.
- Analyze an audio stream using Fast Fourier Transform (FFT) and obtain its spectrum data.
- Support for DSP effects such as flange, reverb and filters.
- Extract tag information from audio files (e.g. ID3 tags from MP3s and Vorbis tags from OGGs).
- Supports various audio output modes (e.g. ASIO, WASAPI, ALSA).

What's inside
-------------

- **FMODGMS.gmez** - FMODGMS GameMaker: Studio extension
- **FMODGMS_Demo_win.zip** - FMODGMS player demo for Windows
- **FMODGMS_Demo_linux.tar.gz** - FMODGMS player demo for Linux
- **src** - library and player demo source code
 - *gms/FMODGMS Test.gmx* - GameMaker: Studio project for player demo
 - *gms2/FMODGMS Test* - GameMaker Studio 2 project for player demo
 - *linux* - FMODGMS source for Linux
 - *vc/FMODGMS* - FMODGMS source for Windows as a Visual Studio project

Possible Features in the Future
--------

- Mac support.
- More options for FFT and spectrum data functionality.
- Android support.

For a list of changes and development history, [click here](../../wiki/Changelog).
