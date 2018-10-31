The [suckless terminal (st)](https://st.suckless.org/) with some additional features:

+ Adjustable transparency/alpha
+ Compatibility with `Xresources` and `pywal` for dynamic colors
+ Copy is alt-c, paste is alt-v or alt-p pastes from primary selection
+ Default font is system "mono" at 14pt, meaning the font will match your system font.
+ Hold alt and press either ↑/↓ or the vim keys k/j to move up/down in the terminal.
+ Shift+Mouse wheel will as well.
+ Alt-u and Alt-d scroll back/forward in history a page at a time.
+ Alt-PageUp and Alt-PageDown will do the same.
+ Zoom in/out with Alt+Shift+k/j or u/d for larger intervals.
+ Vertcenter
+ Default solarized colors without `pywal`
+ updated to latest version 0.8.1

The following additional bindings were added before I forked this:

+ Scroll through history -- Shift+PageUp/PageDown or Shift+Mouse wheel
+ Increase/decrease font size -- Shift+Alt+PageUp/PageDown
+ Return to default font size -- Shift+Alt+Home
+ Paste -- Shift+Insert

If Transparency is not working try removing the 'vsync' line in
~/.config/compton.conf and run 'compton -b' to start compton in the background.

## Installation for newbs

```
make
sudo make install
```
