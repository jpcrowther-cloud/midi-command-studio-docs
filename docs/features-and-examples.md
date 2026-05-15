# Features And Examples

This page gives a quick overview of MIDI Command Studio features, with examples of how each one might be used.

For setup instructions, see [Getting Started](getting-started.md).

## Quick Links

- [README](../README.md)
- [Getting Started](getting-started.md)
- [Supported Use Cases](use-cases.md)
- [Troubleshooting](troubleshooting.md)

## Shortcut Control

Feature: assign MIDI controls to Windows shortcuts or application shortcuts.

Examples:

- Use a pad to trigger play/pause, mute, or record.
- Use a button to run a common app shortcut.
- Use an encoder or jogwheel for repeated left/right, zoom, scroll, or navigation shortcuts.
- Use a fader or knob where a continuous MIDI control makes sense for the target action.

Related tools: dedicated learn buttons, Shortcut Palette, keyboard shortcut capture, global or app-focused targeting.

## App-Focused Control

Feature: make a mapping target a specific application instead of always sending commands globally.

Examples:

- Send shortcuts only when a selected app is already in the foreground.
- Bring a selected app forward before sending the shortcut.
- Use one controller for different programs without changing your keyboard shortcuts.
- Build app-specific layouts for media players, video editors, photo editors, browsers, chat apps, audio tools, or other shortcut-driven software.

## Volume Control

Feature: use MIDI faders, knobs, encoders, or jogwheels to control Windows audio levels.

Examples:

- Control the main system output volume.
- Control the volume of an individual app.
- Control browser, media player, voice chat, or recording software volume.
- Control microphone or recording-device input volume where the app follows Windows input controls.
- Add mute controls where supported.

## Multi-Step Macros

Feature: trigger a sequence of actions from one MIDI control.

Examples:

- Send several shortcuts in order.
- Launch a program or open a file.
- Type text.
- Click, move, or scroll the mouse.
- Add waits or delays between steps.

## Soundboard And Sample Playback

Feature: use MIDI pads or buttons as a simple soundboard or sample player.

Examples:

- Trigger a short audio sample.
- Stop playback quickly.
- Control sample playback level from a fader, knob, or encoder.

Note: simple audio sample playback is a full-version feature.

## Preset-Based Layouts

Feature: keep different layouts for different tasks, devices, or work modes.

Examples:

- Use one preset for general Windows shortcuts.
- Use another preset for editing controls.
- Use another preset for audio controls.
- Switch layouts from the MIDI controller itself.
- Cycle through a smaller set of presets from one control.

Presets are device-specific and autosaved as you edit mappings and macros.

## Mapping Review

Feature: inspect a controller layout without triggering mapped actions.

Examples:

- Check what a pad or button is assigned to.
- Review a controller layout before using it live.
- Confirm mappings after editing a preset.

Assignment Check Mode temporarily pauses normal mapped actions while you check assignments.

## MIDI Thru

Feature: pass unmapped MIDI messages to another MIDI destination.

Examples:

- Use part of a MIDI keyboard for shortcuts while the rest still plays a virtual instrument.
- Keep unmapped controls available to another MIDI application.
- Route unmapped MIDI through a virtual MIDI port.

Requirement: MIDI Thru requires a virtual MIDI port.

## Hardware Feedback

Feature: send visual or motorized feedback to supported MIDI hardware.

Examples:

- LED feedback for mapped buttons.
- LCD feedback on supported devices.
- Motorized fader feedback on supported Mackie / MCU or native-device workflows.

Exact behavior depends on the device model, hardware mode, MIDI Command Studio version, and feedback configuration.
