<img width="256" height="256" alt="AudioInceptionIcon" src="https://github.com/user-attachments/assets/dd364db0-cfdc-4e1b-9d15-b11d088693c5" />

# Audio Inception

**Direct mono or stereo audio input from a secondary Core Audio device into your macOS DAW.**

Audio Inception is a macOS AUv2 and VST3 plug-in that allows you to bring audio directly from a selected Core Audio input device into a DAW, independently of the DAW's normal audio-input device.

It is designed for situations where you want to use inputs from a device that is **not your DAW's main audio interface**, without creating an Aggregate Device or changing the DAW's audio device.

## What it does

Audio Inception opens a selected Core Audio input device directly and sends audio from **one or two selected hardware input channels** to the DAW through the Audio Inception plug-in instance.

It supports:

- mono input
- stereo input
- mono-to-stereo duplication
- stereo-to-mono using Left, Right, or Sum

This makes workflows possible such as:

- bringing a microphone or instrument into a DAW from a secondary audio interface
- receiving audio from an iPhone or iPad over IDAM while continuing to use another device as the DAW's main audio interface
- accessing inputs from a second Core Audio device without creating an Aggregate Device
- working around DAW limitations that make using inputs from multiple audio devices inconvenient or impossible

For example, your DAW can continue using your normal audio interface for its main input and output while an Audio Inception instance independently receives audio from another connected Core Audio device.

Audio Inception does **not** host other plug-ins, create a virtual audio device, modify system audio drivers, or provide arbitrary multichannel routing.

## Plug-in formats

Audio Inception 1.0.0 includes:

- Audio Unit (AUv2)
- VST3

The macOS installer allows either format, or both, to be installed.

## Requirements

- macOS
- A Core Audio-compatible input device
- An AUv2- or VST3-compatible DAW or plug-in host

## Installation

Download the Audio Inception installer from the latest GitHub Release and run it.

Both plug-in formats are selected by default. You can choose to install either format individually if preferred.

The installer is signed with a Developer ID certificate, notarized by Apple, and stapled for Gatekeeper verification.

## Version

Current release: **1.0.0**

## Developer

Audio Inception is developed by **Vaultnaemsae**.

Copyright © 2026 Vaultnaemsae. All rights reserved.
