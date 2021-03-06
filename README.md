# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.

## Patches applied

I'm trying to keep the list of patches I applied up to date in
the patches folder.

This may be harder if I ever start to write my own patches, but
this is frankly unexpected for now.

### Current patches

- lineheight (-h flag to set a minimum height in pixels)
- fuzzymatch (uses fuzzy matching by default, use -F to deactivate)

## Requirements

In order to build dmenu you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

```
    make clean install
```

## Running dmenu

See the man page for details.
