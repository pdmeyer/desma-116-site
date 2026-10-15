# Field Recorder Settings

## All Recorders

- Format your card before your record
- Check your batteries
- Make sure your recorder is set up to use:
  - File format: `WAV`
  - Sample rate: `48kHz`
  - Bit depth: `24 bit`
- Make a test recording

WHEN RECORDING: Blinking red light means ARMED (listening). SOLID red light means recording.

## Tascam DR40

Manual: <https://www.tascam.eu/en/docs/DR-40_RM_vC.pdf>

### Basics

Input gain control: `Input level` buttons on the side

### Hardware switches

`Ext In`: `MIC`
`Hold`: `OFF` (to the right)

### Menus

#### REC MODE (button on front)

`REC MODE`:`STEREO`
`SOURCE`:

- `INT MIC ST` if using integrated mics on top of device.
- `EXT IN 1/2` if using separate mics plugged into XLR ports on bottom
`MS DECODE`: `OFF` / `--`

#### Recording Settings

Menu > `REC SETTING`

- `FORMAT`: `WAV 24bit`
- `SAMPLE`: `48k` (or `96k` if you want, but this creates a bigger file size)
- `LOW CUT`: `OFF`

All other settings off.

### Formatting Cards

`Menu > OTHER > SYSTEM > QUICK FORMAT > Exec`

### Notes

- Supports external mics (including contact mics)
- If using external mic that requires phantom power, use the `EXT IN` switch on the side to select `MIC + PHANTOM`
- Mics on top can be swiveled to a narrow narrow (XY) or wide (A/B) configuration. Use narrow for focused object recordings, use wide for environments.

## Zoom H2

Manual: <https://www.manualslib.com/manual/458720/Zoom-Handy-Recorder-H2.html>

### Basics

Input gain control: Use the left and right buttons labeled `Rec Level`

### Recording Settings

MENU button

- `LO CUT`: `OFF`
- `REC MODE`: `48/24`
- `AGC/COMP`: `OFF`

### Notes

This recorder has multiple internal mics: 2 front-facing, and 2 back-facing. The small `>` and `<`  buttons let you select which microphones to use.

- `FRONT 90`: Microphones with a narrower listening area on the front of the recorder
- `REAR 120`: Microphones with a wider listening area on the back of the recorder
- `SURROUND 2CH`: Both front and back at the same time. The result is a 2-channel audio file.
- `SURROUND 4CH`: Both front and back at the same time. The result is a 4-channel audio file.

You can also use and external microphone with a 3.5mm (headphone-style) plug. It is on the right side of the device. Use this for contact microphones or electromagnetic pickups. If you plug something into this port, the settings described above (`FRONT 90` etc) don't matter.

## Zoom H2n

Manual: <https://www.manualslib.com/manual/2182539/Zoom-H2n.html>

## Zoom H5

Manual: <https://zoomcorp.com/media/documents/E_H5_v2.pdf>

## Notes

- Will record multiple files, separating the internal microphones and the XLR inputs
