# GA144 README
this extension lets you highlight text in your editor for GA144 code.

Alternative tools for the GA144 multi-computer chip using Python3 :
https://github.com/mschuldt/ga-tools

here a documentation about GA144 :
https://www.elektormagazine.com/labs/ga144-forth-144-processeurs-programmable-en-langage-forth

Chips and evaluation boards GreenArrays Products :
https://www.greenarraychips.com/home/products/index.php


ArrayForth tutorial :
http://esaid.free.fr/tutoriel_arrayforth/tutoriel_arrayforth.html

homemade your board :
http://esaid.free.fr/tutoriel_arrayforth/Ga144_pcb/Ga144_kit.html


## Features
![Screenshoot](https://github.com/esaid/ga144_vscode/raw/main/images/example.png)

## Requirements
installation in vscode CTRL + Shift + P  
install from vsix
select the ga144.vsix file.

![Screenshoot](https://github.com/esaid/ga144_vscode/raw/main/images/installation_ga144vsix.webm)

## Extension Settings

Extension GA144 select the theme 

## Known Issues



## Release Notes


### 1.0.0

Initial release of 1.0.0


## Working with Markdown



## For more information


**Enjoy!**




# Examples from https://github.com/mschuldt/ga-tools


## fibonacci.ga

Prints the first 15 numbers of the Fibonacci sequence

## port-execution.ga
Simple example of using port execution to
utilize an adjacent node as a random access 64 word array.

## 3-node-ram.ga, 3-node-ram-ASM.ga
3 node ram cluster.
192 addressable words, word and byte addressable.

3-node-ram-ASM.ga is the same thing with ASM syntax

## square_waves.ga
Various ways of toggling a pin, with timing info.

## sram-demo.ga
example reading and writing SRAM

## variables.ga
Simple example showing one way of implementing variables

## counter.ga
Uses a crystal to maintain time.
Prints counter and debug values over serial.

## fast-ram-node.ga
60 word RAM node with small client code (2 words)

## racecar.ga
An example using all the nodes. Used to measure the time to
send a number around the chip in a loop.

# library examples

## 708serial.ga
serial communciation from node 708

## 708serial-ASM.ga
ASM syntax version of 708serial.ga

## 600serial.ga
Like 708serial.ga, but for node 600

## 715crystal.ga
Drives a 32.768 khz watch crystal from pin 715.17

see `counter.ga` for a running example that uses the same
technique.

## sram.ga, sram-minimal-master.ga

`sram.ga` main sram control.

`sram-minimal-master.ga` minimal capability SRAM master.

See `sram-demo.ga` for example usage of these files.
