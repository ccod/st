# st - simple terminal
st is a simple terminal emulator for X which sucks less.
This is my fork of the project. customizations are on ccod_patches branch

# Requirements
* In order to build st you need the Xlib header files.
* Fira Code font.

# Patches included
* ligatures
* keyboard select
* scrollback

You can find the patches included here: [here](https://st.suckless.org/patches/)

# Theme

Based on [vim-colors-pencil](https://github.com/reedes/vim-colors-pencil)
* light variant

# Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).<br/>

Afterwards enter the following command to build and install st (if
necessary as root):
<br/>

```bash
  make clean install
```

# Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

