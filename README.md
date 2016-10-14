# alexfeeder
This page describes a simple fully 3D printable semi-automatic SMT part feeder for custom Pick and Place machines.

## How it works?

![alt text](https://raw.githubusercontent.com/alexavr2/alexfeeder/master/feeder.jpg "alexfeeder")

The best way to see now it works is to see a video: https://youtu.be/IDiFrP3rNAg

## Features

1)Width=tape width+2mm (actually this is 1mm more than tape reel and gives ~100% space usage efficiency).
2)Fully 3D printable(or milled). Needs a few M2 screws and two springs to assemble.
3)Feeders are easy to stack into any configuration and are easily adaptable to different width.
4)SMT tape thickness up to 5mm, no need to tune.
5)Precision and repeatability does not depend on precision of actuator (head) move. The tape is always moved to one fixed position.
6)Costs about 1-2$ if you have a 3D printer.

## Cons

1)The design is machine dependeble. You may need to adjust it for your machine sizes, mount, etc.
2)It is not really convinient and fast to change a tape in the feeder and the feeder itself is fixed to machine.
3)Does not support tapes thicker than 4-5mm in current version.
4)Need to be adapted for tapes wider than 16mm.

## Flat spring

Flat spring dimension is 51x(tape width - 3)mm. It is 51x5mm for 8mm tape. Actually the length is not really critical and may vary by few mm. 

One of the most common spring metal source is paper binder clip. These are made from very elastic steel and one of the standard size is 51mm wide which is perfectly fit for the feeder. They also can be bought absolutely everywhere for very little money.

## Pull pin

Printing pull pin on the 3D printer is a bit difficult, so the tip is printed with extra ammount of plastic. It is very easy to cut it by knife after printing to get the right shape. See photos.

Original prinnted part:
![alt text](https://raw.githubusercontent.com/alexavr2/alexfeeder/master/pull1.jpg "Pull pin")

After first cut:
![alt text](https://raw.githubusercontent.com/alexavr2/alexfeeder/master/pull2.jpg "Pull pin")

After second cut:
![alt text](https://raw.githubusercontent.com/alexavr2/alexfeeder/master/pull3.jpg "Pull pin")


