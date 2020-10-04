 # Auto Game Updater

This is a simple WPF Windows application made to update games without steam [I originally wanted to make simple game launcher, don't get confused by the name :)].

## How to use it

To apply this code to the game of your choice you need only 1 thing: A server. On the server you need to host a .zip file of the game files and a "Version.txt" file, make sure the version.txt file contains "0.0.0" - meaning the first version. I have marked all parts that you need to change in the code with "//change stuff here!", simply fill in what it says. Also open the "Images" folder and change the images according to your game.

## How to update the game

To update the game, simply change the "Version.txt" on your server to "0.0.1" and upload the zip file with the new game files (Make sure **All** Directories and file names stay the same so the software can use the same things you declared in the code.). The launcher will compare the local "Version.txt" to the on your server on every launch, so as soon as you have updated it, the launcher will download the new game files. Simply keep going like this and your users will get constant updates :). 

## Example

The first example of this is my "Among Us Auto Updater" you can find a download for the program here: https://amongus.crackhub.tk

## License

This program is Licensed under the [MIT License](https://tldrlegal.com/license/mit-license) Meaning you can modify, distribute and sell this as much as you want. 

> The work is provided "as is". You may not hold the author liable.

Meaning I won't be held liable for anything done with this source code.
