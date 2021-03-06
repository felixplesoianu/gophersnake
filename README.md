# Gophersnake

Gophersnake is a stand-alone Gopher client for modern desktops, written in Python and TkInter. As of November 2018, development has mostly stalled at an early stage, apart from contributed enhancements.

## Wait, what's Gopher?

To oversimplify, Gopher was a precursor of the Web, that fell by the wayside for various reasons. Nowadays considered obsolete, it's kept alive by a handful of fans, not just out of nostalgia but also its genuine qualities.

Gopher is much simpler than the Web. It uses less bandwidth, processing power and screen space. It's still largely text-based, so you won't have to deal with annoying ads (or any kind of script for that matter). Gopher is limited, but what it can do, it does quickly, cleanly and with no fuss. And Gophersnake can introduce you to this world.

## Why, man? Why?!

Because the Internet is turning into a web-based monoculture, and every monoculture is a disaster waiting to happen.

## Install and run

Just download `gophersnake.py`, it's a self-contained script. To run it, you need Python and Tkinter. Both should be installed by default on Linux and Mac; for Windows, just download an official installer from python.org.

Click on links to see where they lead; double-click to navigate. The up/down/enter keys work as well. In the text viewer, Ctrl-A selects the whole text, and Ctrl-C copies it to the clipboard.

Gophersnake is being developed on Python 3. For now it's still compatible with 2.7, but that could change at any time.

## Features

- Single-file app, just download and run.
- Modern, familiar GUI.
- Compact GUI: opens in 800x600 by default, and fits in 640x480.
- Useful home screen.
- Works on any port.
- Text and GIF files open in their own windows.
- Can save directories to a file and load them from disk again (useful for testing).
- "View source" function.
- Compatible with IPv6.

## Known bugs

- There's no way to interrupt downloads.
- ~~Directory entries with missing fields aren't rendered.~~
- GIF files may not show when running in older versions of Python 3.

## To do

- [ ] History
  - [X] Back button
- [ ] Bookmarks
- [X] Binary file downloads
- [X] GIF file display
- [X] Caching

## Similar software

- [Suck-O-Rama](https://github.com/avysk/suck-o-rama), a minimal client.
- [Burrow](https://github.com/sloumdrone/burrow): a more advanced client.
