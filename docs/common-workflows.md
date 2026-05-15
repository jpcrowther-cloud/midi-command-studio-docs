# Common Workflows

This page shows practical ways to use MIDI Command Studio after your device is connected and your first preset is ready.

For the first setup path, see [Getting Started](getting-started.md).

## Quick Links

- [README](../README.md)
- [Getting Started](getting-started.md)
- [Supported Use Cases](use-cases.md)
- [Troubleshooting](troubleshooting.md)

## Map A Button Or Pad To A Shortcut

Use this when you want a MIDI pad, key, transport button, or other button-style control to trigger a Windows shortcut.

Basic flow:

1. Select the device and preset you want to edit.
2. Click the button/pad learn button in the `Mappings` panel.
3. Press the control on your MIDI device.
4. In the editor, choose a shortcut from the Shortcut Palette or capture your own keyboard shortcut.
5. Save the mapping and test it in the target app.

Good uses include media controls, window management shortcuts, app commands, editing shortcuts, and utility actions.

## Control Windows Volume From A Fader, Knob, Or Encoder

Use this when you want physical control over Windows audio levels.

Basic flow:

1. Click `Learn Fader/Knob` or `Learn Encoder/Jogwheel`.
2. Move the control you want to use.
3. In the editor, choose a volume mapping type.
4. Choose `System` for master output volume, `App Target` for one application's audio session, or `Input` for the Windows default recording input.
5. Save and test the control.

For `App Target` volume, the target app must be running and producing audio so Windows creates an audio session. For input volume, some ASIO, exclusive-mode, or vendor-specific audio paths can bypass Windows input volume and mute controls.

## Target A Specific Application

Use app targeting when a mapping should behave differently depending on the app you are controlling.

Modes:

- `Global`: send the shortcut to whatever app is active.
- `Only when app has focus`: send the shortcut only when the selected app is already in the foreground.
- `Force focus`: bring the selected app to the foreground before sending the shortcut.

Example target applications can include media players, video editors, photo editors, browsers, chat tools, audio tools, and other shortcut-driven software.

## Build A Multi-Step Macro

Use a macro when one shortcut is not enough.

Common macro step types include:

- Keyboard shortcut
- Run program or open file
- Mouse click, move, or scroll
- Text input
- Wait or delay between steps

Basic flow:

1. Learn a button, pad, or key.
2. Open the macro editor for that mapping.
3. Add the steps you want to run.
4. Save the macro.
5. Test it in the target workflow.

Macro steps run in order when the mapped control is triggered.

## Use A MIDI Device As A Simple Soundboard

Use this when you want MIDI pads or buttons to trigger audio samples.

The full version supports simple audio sample playback. Audio mappings can trigger samples, stop playback quickly, and control the overall sample playback level from a MIDI control.

Common controls:

- A pad or button to trigger a sample
- A stop button to stop playback quickly
- A fader, knob, or encoder to control sample playback level

## Switch Layouts From The Controller

Use preset switching when the same MIDI device needs different layouts for different work modes.

Examples:

- General Windows shortcuts
- Editing controls
- Audio controls
- Streaming or recording controls
- App-specific shortcut layouts

Presets are device-specific and autosaved as you edit mappings and macros. Switching presets changes which controls are active, which apps shortcuts target, which macros run, and how faders or encoders behave.

## Check What A Control Is Assigned To

Use Assignment Check Mode when you have already built a preset and want to confirm what a control does without triggering its mapped action.

While checking assignments, normal MIDI actions are paused for the selected device and preset. Pressing a mapped control shows the assigned mapping instead of sending the shortcut, macro, or volume action.

## Keep Unmapped MIDI Passing Through

Use MIDI Thru when part of a MIDI keyboard or controller should still feed another MIDI application while mapped controls trigger MIDI Command Studio actions.

MIDI Thru requires a virtual MIDI port. When it is enabled, mapped controls still trigger their assigned actions, and unmapped MIDI messages are sent to the virtual MIDI Thru port.

## Use Hardware Feedback Where Supported

Use MIDI feedback when supported hardware should show mapping or preset state on the controller itself.

Examples include LED feedback for mapped buttons and LCD or fader feedback on supported Mackie / MCU or native-device workflows. Document exact device behavior only after testing a specific model and version.
