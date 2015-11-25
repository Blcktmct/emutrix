# Goals for versions #
Crossed-out entries are implemented features. Probably subject to a lot of change, but most features are feasible up to version 1.0. Comment below or post an issue if you want a particular feature implemented.
## Pre-release ##
  * ~~GUI~~
  * ~~Basic routing~~
  * ~~Master level~~
  * ~~Basic panic button~~
  * ~~Output attenuation PADs~~
## v0.1 ##
  * ~~Sane/safe initial settings~~
  * ~~Card selection~~
  * ~~Read initial ALSA element values~~
  * ~~Callbacks to react to outside changes~~ ~~(pads don't work yet, alsa lib or driver bug?)~~
Works now, was a driver bug, now fixed. Implemented a workaround in the meanwhile.
## v0.2 <font color='red'>current</font> ##
  * ~~Fix input Pads~~
  * ~~"Link" feature (L and R channels go together)~~
  * ~~Move ALSA code to its own class~~
  * ~~View settings (hiding unavailable channels)~~
  * ~~Change names of 1010 devices to 1010/Dock if available~~
## v0.3 <font color='green'>in svn</font> ##
  * Support for full hardware resolution fader.
  * Make mute toggle (clicking it again reverts to original setting)
  * Useful panic feature (temporarily mute all channels)
  * 0404 PCI support
## v0.4 ##
  * Session management (storage of element values) using LASH(?)
  * Tray icon
## v0.5 ##
  * User manual
  * Stabilizing
  * Testing with different cards
## v0.6 ##
  * Display channels available to jack (as alias?), depending on used device
  * Display Jack port names in emutrix (?)
  * Automatize changing card clock rate settings according to jack setup
## v0.7 ##
  * External clock rate
## v0.8 ##
  * Nicer icons (that make sense)
  * Make matrix look nicer, easier to navigate (e.g highlight channel names on hover)
## v0.9 ##
  * Fancier GUI stuff (Tooltips, dB displays, etc.)
  * Level monitoring
## v1.0 ##
  * User manual
  * Stabilizing
  * Testing with different cards
## v1.1+ ##
Very speculative, may involve driver modification.
  * Multichannel routing with levels ("sends")
  * Effects
  * Hardware level monitoring
  * Autodetect card model
  * Control dock LEDs ("lock")
  * S/MUX for higher clock rates (88.2, 96 kHz)
  * S/MUX for highest clock rates (176.4, 192 kHz)
  * MIDI control