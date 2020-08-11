# Avalonia Rounded Border Window
This is an attempt to implement an Avalonia Window with rounded borders.

## Problems
* The window can not be dragged.
* The resizing handles do not align correctly on the edges.
* The window shadow is lost.
* Resizing is unreliable. May sometimes also result in `System.AccessViolationException: 'Attempted to read or write protected memory. This is often an indication that other memory is corrupt.'` (might have to do with tooltips)
* When maximized, there is an offset between window and screen.

## Screenshots
#### Windows
![Windows Screenshot](https://raw.githubusercontent.com/FrankenApps/Avalonia-Rounded-Window/master/Screenshots/Screenshot.png "Windows Screenshot")
