# Troubleshooting

This page covers common setup checks for MIDI controller shortcuts, macros, volume control, and app-focused mappings on Windows.

## Quick Links

- [README](../README.md)
- [Getting Started](getting-started.md)
- [Controller Compatibility](controller-compatibility.md)
- [Support](../SUPPORT.md)

## MIDI Device Is Not Detected

- Confirm the controller is connected and powered
- Confirm Windows can see the device
- Close other MIDI or DAW applications that may have opened the same device
- Start MIDI Command Studio before DAWs or other MIDI-heavy applications if a device is being grabbed by another program
- Reconnect the device and restart MIDI Command Studio
- Check whether the controller exposes separate input and output ports

## MIDI Learn Does Not Detect A Control

- Verify the correct MIDI input is selected
- Try a different pad, key, knob, fader, or button
- Check whether the controller requires a specific preset, mode, or MIDI channel
- Confirm the device is sending standard MIDI messages

## Shortcut Or Macro Does Not Trigger

- Test with a simple shortcut first
- Confirm the target application has focus if the mapping is app-focused
- For app targeting, confirm the target application is running and has an open window
- Check whether the shortcut is already captured by another application
- Verify the active preset is the one you expect

## Volume Control Does Not Affect The Expected Target

- Confirm the target application is running and producing audio
- Check whether the app appears in the Windows volume mixer
- Verify the mapping targets the intended app
- Test system volume separately to isolate app-specific behavior
- For microphone or recording-device input volume, confirm the intended input device is selected and visible in Windows sound settings
- Some ASIO, exclusive-mode, or vendor-specific audio paths can bypass Windows input volume and mute controls

## Force Focus Does Not Bring The App Forward

- Windows can sometimes block background apps from taking focus
- Force focus works best when the target app has been used recently
- Keep the target app open and not minimized for the most predictable behavior
- App-target volume mappings do not need focus when using normal app-volume targeting

## MIDI Thru Port Is Missing

- Create a virtual MIDI port before using MIDI Thru
- The expected port name is `MCS MIDI Thru`
- Keep the virtual MIDI tool running in the background
- If the port was created after MIDI Command Studio opened, use `Rescan` in the Devices menu or restart the app

## MIDI Feedback Or X-Touch Feedback Does Not Update

- Confirm the MIDI output port is selected where required
- Verify the device and current app version support the expected feedback behavior
- Check whether the active preset includes feedback mappings
- Test with a minimal feedback mapping before troubleshooting a full preset

## Preset Switching Does Not Behave As Expected

- Confirm the preset switch action is assigned to the expected MIDI message
- Check whether another mapping uses the same control
- Verify the target preset exists and is saved
- Test switching between two simple presets before using a larger setup

## When Reporting A Problem

Include:

- MIDI Command Studio version
- Windows version and build
- MIDI controller model
- Whether the issue affects input, output, feedback, volume, macros, shortcuts, or presets
- Steps to reproduce
- Screenshot, GIF, or short screen recording if helpful
