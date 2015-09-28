# Si4703_Breakout_Modified
Modified Si4703_Breakout library for Arduino
Library supports SparkFun Si4703 FM Tuner Evaluation Board

Modification to SparkFun's Si4703_Breakout library:
- implemented new readRDS method from [Martin Marinov](https://github.com/martinmarinov/AATMEGA644PandSi4703.git) (in fm.c & fm.h)
- changed getChannel from private to public in header file
- added code to clear radiotext (RDS) buffer when seeking or setting the channel
