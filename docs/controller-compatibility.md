# Controller Compatibility

MIDI Command Studio is intended to work with MIDI devices that send standard MIDI note, button, fader, knob, or encoder data.

Controller support is broad, but exact behavior depends on the hardware, MIDI mode, driver, and the type of controls you want to map. The safest way to check a device is to test it with the free version.

## What Usually Works

- MIDI keyboards
- Pad controllers
- Fader controllers
- Knob controllers
- Endless encoders and jogwheels
- Hybrid MIDI controllers with buttons, pads, faders, knobs, or encoders
- Mackie / MCU-style devices where the device and workflow match the supported feedback mode

## What To Test

When checking a controller, test the controls you actually plan to use:

- Buttons, pads, and keys
- Faders and absolute knobs
- Endless encoders or jogwheels
- Transport controls
- LED feedback, if needed
- LCD or motorized fader feedback, if using Mackie / MCU or native-device feedback
- MIDI Thru, if you want unmapped MIDI to continue to another app

## Learn Modes Matter

Use the learn button that matches the physical control:

- Button learn for pads, keys, transport buttons, and other on/off controls
- Fader/knob learn for sliders and absolute knobs
- Encoder/jogwheel learn for endless rotary controls
- Touch fader learn only when the device sends separate touch data

If a mapping behaves oddly, delete it and learn it again with the correct control type. The `Log` window can help confirm what data the device is sending.

## Feedback And Control Surfaces

Basic input mapping is separate from hardware feedback. A device can send usable MIDI input even if LED, LCD, or motorized feedback is not available.

MIDI Command Studio includes support for MIDI feedback on supported devices and Mackie / MCU-style workflows where configured. Feedback behavior should be tested per device model.

HUI is not currently supported. MMC transport data is only minimally supported; simple commands such as play/stop, and sometimes record, may be usable depending on how the device is configured.

## Behringer X-Touch Notes

Behringer X-Touch One has a native profile in MIDI Command Studio.

- For Native protocol, set the X-Touch One hardware to `MIDI` mode.
- For MCU protocol, set the X-Touch One hardware to `MC Std`.
- In X-Touch One MCU mode, the CH1-CH8 channel buttons switch which channel strip the fader, pan encoder, Mute, Solo, and Rec controls belong to.
- This lets one physical fader, one pan encoder, and the Mute/Solo/Rec buttons work across up to 8 channel-specific mappings in the same preset.
- In `Single fader` MCU layout, the CH1-CH8 channel buttons are reserved for channel selection and cannot be mapped as normal controls.

For Behringer X-Touch and other 8/9-fader MCU-style surfaces, use MCU mode for LCD and motorized fader feedback, then choose the `Multi fader` MCU layout in device feedback settings.

## MIDI Thru

MIDI Thru requires a virtual MIDI port. When enabled, mapped controls trigger MIDI Command Studio actions and unmapped MIDI messages are sent to the virtual MIDI Thru port.
