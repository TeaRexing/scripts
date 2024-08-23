# My personal scripts

> I use these on a daily basis to reduce my time on the commandline and the exhausting task to remember all these commands.

## barrierKeymap.sh

When I work on a Windows desktop machine, I have my linux laptop by my side and like to switch seamlessly between the two systems with the same mouse and keyboard. 
[Barrier](https://github.com/tpoechtrager/barrier) allows me to do this but sometimes the keymap on my linux machine gets mangled up...
As you can see I am using a german keyboard layout - so you might change the layout for your needs.
This small script fixes this issue for me.

## heicToPng.sh

If you have an iPhone, iPad or whatever out of the [Apple](https://www.apple.com/) universe, you might have noticed that they save camera images in the very inconvienient *heic*-format. 
This small script iterates through all your photos in the given destination and converts them to *png*. 
I fixed the quality of the images to 75% of the original in the conversion process which results in images at ~10MB. 
If you need smaller file sizes you might want to change the quality parameter. 
In the future I might add a parameter for the script to set the conversion quality.
