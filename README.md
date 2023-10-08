# automatons
A growing (🤞) collection of short (🤞) scripts that help me automate the boring stuff.

## Scripts summary

### ,cutecoverage 
Automates the creation and viewing of the html file created by [coverage](https://coverage.readthedocs.io/) after running:
\
`coverage run -m pytest ...`
\
`coverage report`
\
`coverage html`

---

### ,zshthemeswap
Switch between any number of specified [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) [themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes).
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

---

### ,make
Mimics how using `make` to compile C works in Harvard's CS50's Visual Studio Code codespace.
\
That is to say, there is no need to specify the output file or link any libraries explicitly.
\
Instead, the user only needs to type `make <filename>`. 
\
The `filename` is just the name of the C file, without the `.c` extension.
\
\
This is especially useful for students who are not coding from within the codespace (but rather
\
their own local machines), but still want the convenience of making their files with minimal input.
\
\
The script assumes that `clang` is installed in the user's computer, as this is really
\
what is being used to compile the `C` file.

