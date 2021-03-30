A script for playing "The Poems of Wind" according to the midi file. Driven by python.

## The operating environment

```
Windows
python 3.x
pywin32 （Used to simulate keyboard input ）
```

When the python environment is configured, install the module using the `pip install pywin32` numpy command.

## Instructions

1. Put the midi file directly on top of the file to start.

2. Put the score into a folder named `songs`, and make sure that the notes in the midi file are in the center C and two octaves of white keys up and down.

3. Run command `python piano.py` in `PowerShell` with administrator privileges

4. Follow the prompts to enter the midi file name (not including the suffix, that is, `.mid`) and the sleeping time (ie, wait a few seconds to start playing).

5. Be sure to switch back to the in-game page before starting to play, and stay in the game during the performance.
