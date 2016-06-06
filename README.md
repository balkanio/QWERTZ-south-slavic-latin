QWERTZ South Slavic Latin
=========================

The [QWERTZ South Slavic Latin][SSL] keyboard layout for OS X.
This keyboard layout was standardized in the 1980s in Yugoslavia
and is used in Windows PCs for Bosnian, Croatian, Serbian Latin
and Slovene. For people who are used to this layout, switching to
a Mac can be troublesome, so using this layout makes things like
finding `@` a bit easier.

To install:

    sudo cp -R "South Slavic Latin.bundle" "/Library/Keyboard Layouts/"

Then restart the computer and to add the layout, go to
System Preferences - Keyboard - Input Sources - `+` - start typing "south",
select "South Slavic Latin" - Add. Now you should be able to select this layout
from the keyboard menu bar icon (or it will be automatically selected if you
remove other layouts).

## Features

So far I got most of the keys to be in their right places including:

 - `@` can be found at `alt` + `v`
 - often used programming keys like `<`, `>`, `[`, `]`, `{` and `}`
 - state modifiers like `alt` + `<number>`, `a` for inputing other international
   characters such as ä, á or à
 - I don't need to mention where ć, č, ž, š and đ are, right?

## Hacking

The layout is created using [Ukelele](http://scripts.sil.org/ukelele),
the free Unicode Keyboard Layout Editor. You can get it using Homebrew Cask
to edit the layout:

    brew cask install ukelele

Icon generated using: <https://iconverticons.com/online/>

It's not a full clone yet. Feel free to improve it!

Živjeli!

[SSL]: https://en.wikipedia.org/wiki/QWERTZ#South_Slavic_Latin
