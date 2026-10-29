---
title: Software Proposal
---

## Introduction

The layout of our boards is closest to one main hub board and 3 separate individual boards. The order of processing is that the photo resistor board checks light levels and if sufficiently dark enough informs the hub board to start monitoring head motion using a gyroscope. If it detects head movement in line with nodding off it alerts the two action boards one with a speaker and one with a vibration motor to start.

## Connections

* Photo Resistor Board: One output connection to the gyroscope board that sends light level data to it.
* Gyroscope Board: One input connection from the photo resistor board and two output connections to the buzzer and vibration motor boards for High-Low signals
* Buzzer Board: One input connection from the Gyroscope board
* Vibration Motor Board: One input connection from the Gyroscope board

## Goals

1. Detect low light levels
2. In the event of low light levels check for head motion associated with sleepy behavior
3. In the event of that behavior send buzzer and haptic alerts to wake up driver
4. If head position persists in that state change feedback strength or pattern in a greater attempt to wake up drvier
5. If head orientation changes then stop buzzer and haptics and continue monitoring like normal

## Results

The results we are looking to achieve using this configuration is as follows

1. Accurately detect correct lighting and head positions with low error rates
2. Achieve fast reaction time to confirmed drowsy indicators
3. Effectively keep drivers alert through feedback systems

## Conclusion

The overall goal is to create a device that accurately and effectively detects and prevents drivers from falling asleep at the wheel. One serious potential problem that may arise due to coding is our software being too "good" in that it detects any type of head movement or low light level regardless of how brief as a indicator for drowsiness. It is important that we strike a balance between our product not being annoying to use if it goes off at the slightest motion or shadow while also maintaining fast and accurate readings in order to react quickly enough to a driver losing awareness. 
