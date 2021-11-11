# Advantest R4131D: conversion to color display
This repository contains the resources and description of how I succesfully converted a R4131D spectrum analyzer with a dead monochrome CRT to color salvaging a 6" Amstrad portable LCD TV.
The method used here is applicable to other pieces of equipment which use the same architecture for video generation (Raster + Composite video out) as well as to other types of LCD monitors.
A future modification will involve converting the video output from composite monochrome to color VGA.
## Advantest R4131D Brief Description
According to [user manual](manuals/pdf_mn_ER4131_OPERATING_MANUAL.pdf)
> The R4131 covers a band-width as wide as 10kHz to 3500 MHz and is controlled by a microcomputer. 
> This analyzer features easy confirmation of all measuring conditions, since 
> its frequency span is 4 GHz to 50 kHz, 
> resolution is 1 MHz to 1 kHz, 
> level data resolution by a marker is 0.05 dB, 
> tube surface dynamic range is 80dB, 
> and the setting conditions of its major functions are shown on its CRT display.

(typos have been corrected, grammar has been left to its original form).

According to documentation the "D" version sports
* 100kHz display frequency accuracy on frequancies ≤ 2.5 GHz
* POSI/NEG display
* Occupied Bandwidth measurement

The analyzer looks like the following picture (taken from the internet, I have the same but I did not think about taking a picture before removing the CRT)

![R4131D](thumbnails/R4131D.jpeg)

## How I Got the Analyzer and What Was Wrong
On March 2020 I was lucky enough to obtain from my friend **MrTimes** a R4131D with its tracking generator against the payment of a more than reasonable amount of cash. The instruments came fully aligned, however the analyzer presented a "narrow display" issue (the trace was compressed vertically) and so an external CRT monitor connected to the analyzer rear video output came along.
I started using it in this configuration until July 2021 when all of a sudden the external monitor stopped functioning.
I was able to verify that the problem was due to the external CRT being dead using a VGA→HDMI converter + external HDMI monitor, but this solution was not practical so I decided it was time to fix the issue once for all.

