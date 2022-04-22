# cli-stryket

CLI for the popular Swedish betting game [Stryktipset](https://spela.svenskaspel.se/stryktipset)

Enter your system and work your way to 13 correct and the millions using the cli-stryket. Your friends will probably think you are the coolest person alive, or the geekiest person alive.

cli-stryket fetches live data and correct your system in real-time.

The CLI is built using the curses python library which supplies a terminal-independent screen-painting and keyboard-handling facility for text-based terminals.

![cli-stryket](assets/cli-stryket.png)

## Requirements
- Python3

## Installation

```bash
python3 -m venv venv
source venv/bin/activate

pip3 install -r requirements.txt

```
## How to run

```
cd cli-stryket
python3 cli-stryket.py --input-file system.txt
```

`system.txt` is the file containing your system. 

Example `system.txt` : 

```
1x
1x2
12
x
1
2
12
1x2
1x
x2
x
2
x2
```
## Contribute?

Questions, Issues, or PRs are more than welcome! Happy Hacking.
