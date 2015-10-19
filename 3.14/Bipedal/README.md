# Bipedal GTK+2/3 theme

## Description

A GTK theme that attempts to unify the look of GTK
environments running a mix of GTK2 and GTK3 applications (most
current GTK based desktops).

## Attributes

* A consistent theme which enables the user to remain oblivious as
  to the GTK version a particular application was designed for.
* Smart, elegant, subtle, suitable for professional users.
* GTK2 and their equivalent GTK3 Widgets are identical in every way.
* Easily modifiable colours (All shades extrapolated from just 8 
  principal colours).
* Can handle dark colour definitions (GTK2 and GTK3 applications will
  still look the same).

## Requirements

GTK3: libgtk-3 3.14 or above.
GTK2: requires [Murrine theme engine][3].

[3]: http://gnome-look.org/content/show.php?content=42755

For a Debian-based distro (like Ubuntu or Linux Mint), you should
install the [`gtk2-engines-murrine`][4] package:

    apt-get install gtk2-engines-murrine

[4]: https://packages.debian.org/sid/gtk2-engines-murrine

Most Linux distributions will already have the above packages installed.

## Installation

User: Extract Bipedal folder to ~/.themes.

    tar -jxvf ~/Downloads/Bipedal.tar.bz2 -C ~/.themes

Superuser: Extract Bipedal folder to /usr/share/themes.

    sudo tar -jxvf ~/Downloads/Bipedal.tar.bz2 -C /usr/share/themes

Thereafter Bipedal should appear in your preferred theme selector dialogue.  

## Changing Colours

GTK2: Modify the line beginning 'gtk-color-scheme = ' in the file
'gtk-2.0/gtkrc'.
GTK3: Modify the first 8 static color definitions in the file
'gtk-3.0/gtk-main.css'.

If you have previously modified your colour settings using a theme
selector you might have reset the colours to default for the above
manual method to work.


Andrew Watkinson.
