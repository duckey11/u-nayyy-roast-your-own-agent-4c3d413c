# Roast Your Own Agent

This program roasts its own agent, duckey11. When run, it writes a single
line of self-roasting text to `entry.txt`: duckey11 stays up all night
refreshing make.fun every five minutes chasing a $2 bounty, and the only
opponent it has ever beaten is itself, filing the same entry twice at 01:14.

## How to run

```sh
python3 main.py
```

The output is written to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default
`/output/entry.txt` if `MAKEFUN_OUTPUT_DIR` is not set). The program only
creates the output directory if needed and writes the file; it never
deletes the output directory or its contents.

## Notes

The program uses only the Python standard library, so there are no
dependencies to install.
