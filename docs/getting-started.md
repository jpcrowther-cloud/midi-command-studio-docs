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

1. In the `Devices` panel, add or select your device and confirm its status is green.
2. If this is your first setup, keep the default preset selected or click `New` to create a fresh preset.
3. In the `Mappings` panel, click the `Learn` button that matches the control you want to map.
4. Use button learn for pads, keys, transport buttons, or other on/off controls.
5. Use fader/knob learn for sliders or absolute knobs.
6. Use encoder learn for endless rotary controls.
7. Press or move the control on your MIDI device. The editor opens automatically after the control is detected.
8. In the editor, click a shortcut field such as `On`.
9. Pick a shortcut from the Shortcut Palette, or use `Capture from keyboard` to record your own shortcut.
10. Optional: configure app targeting.
11. Use `Global` to send the shortcut to whatever app is active.
12. Use `Only when app has focus` to send the shortcut only when the selected app is already in the foreground.
13. Use `Force focus then send` to bring the selected app to the foreground before sending the shortcut. This is useful when one MIDI control should target a specific app while you are working across multiple applications.
14. Click `Save`.
15. Test the control in the app you want to control.

## Quick Tips

- If learn does not detect your control, make sure the device row is selected and connected.
- If the wrong learn mode was used, delete that mapping and learn it again with the correct control type.
- If the target app is missing from the app list, open that app first so MIDI Command Studio can see it.
- Use the `Log` window if you are unsure whether a control is sending button, CC, or encoder-style data.

## Next Steps

- Build a volume workflow: [Common Workflows](common-workflows.md)
- Confirm controller message behavior: [Controllers and MIDI Messages](controllers-and-midi-messages.md)
- Solve setup issues: [Troubleshooting](troubleshooting.md)
