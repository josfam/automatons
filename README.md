# automatons
A growing (🤞) collection of short (🤞) scripts that help me automate the boring stuff.

## Scripts summary

### _cutecoverage 
Automates the creation and viewing of the html file created by [coverage](https://coverage.readthedocs.io/) after running:
\
`coverage run -m pytest ...`
\
`coverage report`
\
`coverage html`

---

### _zshthemeswap
Switch between any number of specified zshell themes.
\
\
I usually use a visually-heavy terminal theme (with lots of handy information) for everyday
\
terminal sessions, and a (relatively) more minimal theme for recording demos of programs
\
(visual overload is not ideal for the viewer of said recording).
\
\
This script allows me to very quickly toggle between the two themes depending on the
\
context, without having to:
1. Go into my `.zshrc` file
2. Change the `ZSH_THEME` line to the theme I desire
3. Source the `.zshrc` file
4. Repeat steps 1-3 to change to the first theme
