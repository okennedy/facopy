# facopy
A simple lookup widget for fontawesome 4 icons

## Installation

```
chmod +x facopy
mv facopy /usr/local/bin # or your favorite bin directory
```

If you want fuzzy matching, make sure `agrep` is installed.  `sudo apt install glimpse` on debian/ubuntu-based distributions.

## Usage

```
okennedy@thor:~$ facopy chevron-circle-
Didn't find 'chevron-circle-'.  Similar icons include:
  chevron-circle-down
  chevron-circle-left
  chevron-circle-right
  chevron-circle-up
okennedy@thor:~$ facopy chevron-circle-down
copied chevron-circle-down: 
```
