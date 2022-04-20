# leg7's build of dmenu

This is my build of suckless dmenu, dmenu is a menu for X available at https://tools.suckless.org/dmenu/

With dmenu you can start programs or the user to select an item from a list.
It sounds simple but it is very powerful.

## Features

### Here is a quick list of features/patches I've added to my build of dmenu:

* Emoji support (you need to use a patched version of libXft with bgra support)
* Dmenu numbers: show the total ammount of items in the list and the ammount you have selected
* Fuzzy match
* Fuzzy highlight
* Ordered patches for automatic patching with portage (gentoo)
* Nord theme

## Install guide

```
git clone https://git.leonardgomez.xyz/leg7/dmenu
cd dmenu
make install
```

For more info look at dmenus documentation
