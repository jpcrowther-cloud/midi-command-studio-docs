# Getting Started

MIDI Command Studio is a Windows utility for mapping MIDI input to shortcuts, macros, output and input volume controls, soundboard actions, and app-focused workflows.

## Quick Links

- [README](../README.md)
- [Common Workflows](common-workflows.md)
- [Troubleshooting](troubleshooting.md)
- [FAQ](faq.md)
- [Download](https://crowtherian.gumroad.com/l/ddscqt)
- [Website](https://midicommandstudio.com)

## Requirements

- Windows PC
- MIDI controller, keyboard, pad controller, fader bank, knob controller, encoder device, or supported control surface
- MIDI Command Studio installed from the official download page

## From Install To Your First Mapping

1. In the `Devices` panel, add or select your device.
2. Keep the default preset selected or click `New` to create a fresh preset.
3. In the `Mappings` panel, click the `Learn` button that matches the control you want to map.
4. Press or move the control on your MIDI device. The editor opens automatically after the control is detected.
5. In the editor, click a shortcut field such as `On`.
6. Pick a shortcut from the Shortcut Palette, or use `Capture from keyboard` to record your own shortcut.
7. Optional: configure app targeting.
8. Use `Global` to send the shortcut to whatever app is active.
9. Use `Only when app has focus` to send the shortcut only when the selected app is already in the foreground.
10. Use `Force focus` to bring the selected app to the foreground before sending the shortcut. This is useful when working across multiple applications.
11. Click `Save`.

## How To Control Windows Volume With A MIDI Controller

Use a MIDI knob or fader for system volume and app-specific volume targets.

Learn a knob or fader, set it to a volume action, choose either system volume or an app target volume, then save.

1. Add your MIDI device.
2. Click `Learn Fader/Knob` and move the control you want to use.
3. In the editor, choose a volume mapping type.
4. Choose `System` for master volume, or choose `App Target` for a specific application.
5. Save and test by moving the control.

For `App Target` volume, the target app must be running and producing audio so Windows creates an audio session.

## Quick Tips

- If learn does not detect your control, make sure the device row is selected and connected.
- If the wrong learn mode was used, delete that mapping and learn it again with the correct control type.
- If the target app is missing from the app list, open that app first so MIDI Command Studio can see it.
- Use the `Log` window if you are unsure whether a control is sending button, CC, or encoder-style data.

## Next Steps

- Build a volume workflow: [Common Workflows](common-workflows.md)
- Confirm controller message behavior: [Controllers and MIDI Messages](controllers-and-midi-messages.md)
- Solve setup issues: [Troubleshooting](troubleshooting.md)
