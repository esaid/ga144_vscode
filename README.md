# Examples

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
