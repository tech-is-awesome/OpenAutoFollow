# Open Auto Follow (OAF)

OAF is a project to allow cameras on tripods to Identify Subjects and Follow them, or create panning shots, and more.

> :warning: **This Project Is in the Early Stages Of Develepment** It is currently not recommended to use it in a production environment

## Installation

run the command
`git clone https://github.com/tech-is-awesome/OpenAutoFollow && cd OpenAutoFollow` then to start the program run `./oaf.py -m normal` (if that doesnt work see the [Troublesooting Section](https://www.github.com/OpenAutoFollow/wiki/Troubleshooting) of the wiki)

## How to use

if you just run `./oaf.py` it will say `Open Auto Follow Version [xx.xx.xx]` to propenlystart the OAF program you need to provide arguments these arguments are
`oaf.py [mode] [modeargs]`

### Modes Table

| Mode | Description | Min/Max Version | args |
|:----:|:-----------:|:---------------:|:----:|
| default | Track the first face it can find same as subject1 | 0/latest | None |
| pan | Pans the attatched camera to the degrees entered into the cli | Not In program | **INT** Degrees |
| obj-pan | pans past the most prominent frame, after a calibration sequence | Not In Program | none |
