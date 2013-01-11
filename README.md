## Overview

Slideshow will display the last _x_ pictures in any subdirectory, and loop based on a custom duration. As you add new pictures, the older ones play faster and drop off sooner, and the newer ones stay up longer.

The purpose was to display incoming pictures from an Eye-Fi card during an event (wedding, birthday, funeral, what-have-you).  As the current Mac OSX Screensavers do not rescan the directory while they are running, this was made specifically for that purpose.

## Features

I had a number of features in mind when making this.

 * Rotates the last _x_ number of pictures in a directory.
 * Newer pictures stay up longer than older pictures.
 * Custom duration of entire slideshow.
 * Optionally displays image name on the picture.

## Installation

You cannot figure out what this is or how to use it?  It is an OSX Screensaver!  Put it in ```~/Library/Screen Savers/```.

## Known Issues

 1. It requires a minimum number of two (2) pictures in the directory. The way I check and set the "Scan Signal", if you have less than two (2) pictures in the directory, it never properly toggles.
 2. The last _x_ pictures are counted by NAME. This is made for cameras dumping images in the directory, therefore, it is expecting new files to be added to the end of the sequence (e.g. ```IMG_0001.jpg``` is added then ```IMG_0002.jpg```, etc). If you add new files out of sequence, (e.g. then adding in ```IMG_0000.jpg```), the count is incorrect.

## Contributing

Go ahead and give me a pull-request!

## License

Creative Commons - Attribution-NonCommercial-ShareAlike 3.0 Unported, [CC BY-NC-SA 3.0](http://creativecommons.org/licenses/by-nc-sa/3.0/)


