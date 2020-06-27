The [suckless terminal (st)](https://st.suckless.org/) with some official patches:

+ Adjustable transparency
+ Compatibility with `Xresources`
+ Copy is alt+c, paste is alt+v or alt+p pastes from primary selection
+ CTRL+Shift+c, CTRL+Shift+v and CTRL+Shift+p has the same function
+ Default font is system "mono" at 14pt, meaning the font will match your system font.
+ Hold alt and press either ↑/↓ or the vim keys k/j to move up/down in the terminal.
+ Alt+u and Alt+d scroll back/forward in history a page at a time.
+ Alt+PageUp and Alt+PageDown will do the same.
+ Zoom in/out with Alt+Shift+k/j or u/d for larger intervals.
+ Open a new terminal in the same directory with Alt+Shift+Return or Ctrl+Shift+Return
+ updated to latest version 0.8.4

Some additional bindings:

+ Scroll through history -- Shift+PageUp/PageDown
+ Return to default font size -- Shift+Alt+t
+ Paste -- Shift+Insert

Used patches can be found in '/patches/'. The utilized official patches (in '/patches/all-patches/') are combined into one file '/patches/st-all-patches.diff'. This can be applied
to the original st-0.8.4 folder from 'st.suckless.org' as describe din its header.


If Transparency is not working try removing the 'vsync' line in
~/.config/picom.conf and run 'picom -b' to start compton in the background.
