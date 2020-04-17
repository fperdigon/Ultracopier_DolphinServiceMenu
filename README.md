# Ultracopier Dolphin Service Menu
This is a Ultracopier (copy handler) Dolphin Service Menu that aims to integrate the Ultracopier to Dolphin KDE File Manager.

There are two variants:   

Variant A: Using a Submenu.

![Variant A](media/ultracopier_variant_A.png "Variant A")

Variant B: Directly on the Right Click Menu without a submenu.

![Variant B](media/ultracopier_variant_B.png "Variant B")

Currently the destiny folder has to be selected using a KDialog. 

![KDialog dest](media/KDialog_dest.png "KDialog dest")

#### Future improvements
* Add a Paste entry to avoid the ise of the KDialog destiny selection
* Add Keyboard shortcut (like Ctrl+C, Ctrl+V, Ctrl+X) not directly allowed on Dolphin Service Menu (https://bugs.kde.org/show_bug.cgi?id=260266). Posible workarround by using xdotool (https://askubuntu.com/questions/958180/assigning-keyboard-shortcuts-to-kde-dolphin-service-menus)

#### License

MIT License

Copyright (c) 2020 Francisco Perdigón Romero

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
