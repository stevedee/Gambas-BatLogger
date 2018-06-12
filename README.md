# Gambas-BatLogger

This program automatically records full-spectrum ultrasonic bat calls from a system comprising; Raspberry Pi, Wolfson audio card, & bat detector.

Recording can be triggered using either:-
 - a frequency division output from the detector connected to a Pi GPIO input
 - SoX Volume parameter taken from the full-spectrum recording

The frequency division method counts +/- transitions and seems to be better, and less influenced by noise than simply using SoX Volume.
