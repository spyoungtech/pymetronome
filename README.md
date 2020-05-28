# PyMetronome

A simple metronome utility.

## Installation 

```
pip install pymetronome
```

## Usage

After installing the `met` command is available

```
usage: met [-h] [--bpm BPM] [--meter METER]

optional arguments:
  -h, --help     show this help message and exit
  --bpm BPM      Beats per minute
  --meter METER  The time signature to use (e.g. "4/4")
```

Alternatively, you can also use `python -m met`

## Notes

Currently, this is only supported on Windows (because it relies on the standard library `winsound` module)