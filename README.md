** NOTE: THIS REPO IS UNMAINTAINED, THIS FLOWER HAS BEEN PORTED TO NEW INFRASTRUCTURE, PLEASE USE <https://github.com/kivy-garden/modernmenu> **


<img src="https://github.com/kivy-garden/garden.modernmenu/blob/master/screenshot.png" align="right" width="256" />



Kivy ModernMenu
===============

This set of widgets allows you to build a flexible set of modern looking
menus. 3 widgets are provided, conceived in a way to allow both tweaking
and subclassing for maximum flexibility in representation.

The MenuSpawner is a very simple widget allowing you to create a widget
for a long touch (arbitrary time) staying in a short distance of its
origin point, i.e: "long press" actions.

The ModernMenu widget is a configurable menu based on a circle with the
various options appearing around. It animates the transitions to
submenus and provides a nice "back/close" button in the center.

The ModernMenuLabel is the default class used to display the elements of
the menu.

A simple mecanism allow passing options from each widget to the one it
builds, making customization for each instance of the menu easy if
needed.

An example of usage is provided in the module (run the module as a
python program), you can see a result of this example
[here](http://youtu.be/zzMTpcUGG0Q).
