# XDJ-AZ Quick Mixing: Stems & Sampler MIDI Map for Serato DJ Pro

A custom Serato DJ Pro MIDI XML mapping for the **AlphaTheta XDJ-AZ** that gives you direct access to **Stems** and **Sampler** pad modes, with no **SHIFT** required. It brings the XDJ-AZ closer to the workflow of the XDJ-XZ, XDJ-RX3, DJM-S11 and similar gear.

## Features

- **No-shift access:** Jump straight into Stems and Sampler with a single button press.
- **Performance pad colors & lights :** The pad LEDs react instantly to what you do in Serato, so you always see the state of your pads at a glance, even in a dark booth.
- **Stock behavior preserved:** Hot Cue and Beat Loop stay exactly where they were.

## Why does this exist?

In a dark, fast-paced club set, finding and holding **SHIFT** just to reach Stems or Sampler slows you down. This map puts both modes on dedicated buttons so you can switch instantly, keep your eyes on the crowd, and build real muscle memory.

## What changes?

Only the Stems and Sampler pad modes are remapped. Hot Cue and Beat Loop stay exactly where they were.

| Pad Mode              | Original (stock)         | This map        |
| --------------------- | ------------------------ | --------------- |
| Hot Cue               | [HOT CUE]                | [HOT CUE]       |
| Beat Loop & Beat Jump | [BEAT LOOP]              | [BEAT LOOP]     |
| Serato Stems          | [SHIFT + BEAT LOOP]      | [SLIP LOOP]     |
| Sampler               | [SHIFT + BEAT JUMP]      | [BEAT JUMP]     |

## Requirements

- Pioneer DJ XDJ-AZ
- Serato DJ Pro (a version with Stems support)
- A track with stems loaded (Serato generates stems automatically on load)

## Installation

1. Download the MIDI map `.xml` file from this repository.
2. Close Serato DJ Pro if it's open.
3. Copy the file into your Serato MIDI XML folder:
   - **Windows:** `C:\Users\<your name>\Music\_Serato_\MIDI\Xml`
   - **macOS:** `~/Music/_Serato_/MIDI/Xml`
4. Connect your XDJ-AZ and open Serato DJ Pro.
5. Go to **Setup > MIDI**, select your XDJ-AZ, then choose this map from the **Preset** dropdown.
6. Load a track on deck 1 or 2 and press **SLIP LOOP** (Stems) and **BEAT JUMP** (Sampler) to confirm the pad modes switch and the pad lights update with the correct colors.

## Uninstall / Revert

Delete this map's file from the `Xml` folder (or pick the default preset in **Setup > MIDI**) and restart Serato DJ Pro. Your controller returns to stock behavior.

## Troubleshooting

- **Map doesn't appear in the preset list:** Check the file is in the correct `Xml` folder, then fully restart Serato.
- **Buttons still behave like stock:** Make sure this preset is selected for your XDJ-AZ in the MIDI settings.
- **Stems pads do nothing:** The loaded track needs stems available. Check that the Stems feature is enabled in your Serato version and plan.

## Contributing

Issues and pull requests are welcome. If you've tested this on a different Serato version or have ideas for more mappings, open an issue and share what you find.

## Disclaimer

This is an unofficial, community-made project and is not affiliated with or endorsed by AlphaTheta / Pioneer DJ or Serato. Use at your own risk.
