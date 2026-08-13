<img width="256" height="256" alt="AudioInceptionIcon" src="https://github.com/user-attachments/assets/dd364db0-cfdc-4e1b-9d15-b11d088693c5" />

# Audio Inception

**Multichannel audio input for plug-ins in macOS DAWs.**

Audio Inception is a macOS AUv2 and VST3 plug-in that allows a DAW to access channels directly from a Core Audio input device, independently of the host's normal audio-input routing. No audio aggregation required.

It is designed for situations where a plug-in needs access to multichannel hardware inputs that the DAW cannot conveniently—or cannot at all—route to a single plug-in instance.

## What it does

Audio Inception can acquire audio directly from a selected Core Audio device and route selected hardware input channels into its plug-in instance.

This makes workflows possible involving:

- multichannel microphones and instrument sources
- iPhone IDAM audio injection
- bypass environment limitations in DAWs tat are not friendly to aggregate devices - I'm looking at you, Ableton Live!

Audio Inception does **not** create a virtual audio device or modify the system's audio drivers.

## Plug-in formats

Audio Inception 1.0.0 includes:

- Audio Unit (AUv2)
- VST3

The macOS installer allows either format, or both, to be installed.

## Requirements

- macOS
- Apple Silicon Mac
- A Core Audio-compatible input device
- Am AU/VST3 compatible DAW/plug-in host

## Installation

Download `Audio Inception.pkg` from the latest GitHub Release and run the installer.

Both plug-in formats are selected by default.

The installer is signed with a Developer ID certificate, notarized by Apple, and stapled for Gatekeeper verification.

## Version

Current release: **1.0.0**

## Developer

Audio Inception is developed by **Vaultnaemsae**.

Copyright © 2026 Vaultnaemsae. All rights reserved.


