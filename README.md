# DuckDuckGo Search for Gnome Shell #

## Settings ##

To use it please go to:

    https://duckduckgo.com/params.html

Chose your settings and fork and update template attribute for Url tag.

## Installation ##

After this put file into:

    /usr/share/gnome-shell/search_providers/

For Gnome Shell 3.4

    /usr/share/gnome-shell/open-search-providers/

## Debian and Debian Derivatives ##

### Gnome Shell < 3.4 ###

    sudo dpkg-divert --divert /tmp/google.xml --rename /usr/share/gnome-shell/search_providers/google.xml
    sudo dpkg-divert --divert /tmp/wikipedia.xml --rename /usr/share/gnome-shell/search_providers/wikipedia.xml

### Gnome Shell 3.4 ###

    sudo dpkg-divert --divert /tmp/google.xml --rename /usr/share/gnome-shell/open-search-providers/google.xml
    sudo dpkg-divert --divert /tmp/wikipedia.xml --rename /usr/share/gnome-shell/open-search-providers/wikipedia.xml

## Activation ##

Restart Gnome Shell

    Alt+F2
    r
    Enter

Enjoy
