# dmark

Simple bookmark script written in POSIX SHell and uses [dmenu](https://tools.suckless.org/dmenu/) as a menu picker
and X11 as the windows system (to type the bookmarked URL) to keep all of your
bookmarks in one single **bookmarks.md** file adhering to the UNIX philosophy;
simple, modular & does one thing & does it right.
**dmark** works by writing a link in your clipboard to a file **bookmarks.md**
(change the $file variable to whatever file you want) under a catagory you choose
from the list presented to you by dmenu. 

### Usage
- Add catagory names to a file like `### News`.
- Make sure theres a blank line between every catagory.
- Bind `./damark` to a key-binding to show bookmarks and type where ever you want.
- Bind `./damark -a` to a keybinding to add a bookmark to you bookmark file.

Change $file variable to your bookmark file path.
