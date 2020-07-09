![Logo](admin/smartcontrol.png)
# ioBroker.smartcontrol

[![NPM version](http://img.shields.io/npm/v/iobroker.smartcontrol.svg)](https://www.npmjs.com/package/iobroker.smartcontrol)
[![Downloads](https://img.shields.io/npm/dm/iobroker.smartcontrol.svg)](https://www.npmjs.com/package/iobroker.smartcontrol)
![Number of Installations (latest)](http://iobroker.live/badges/smartcontrol-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/smartcontrol-stable.svg)
[![Dependency Status](https://img.shields.io/david/Mic-M/iobroker.smartcontrol.svg)](https://david-dm.org/Mic-M/iobroker.smartcontrol)
[![Known Vulnerabilities](https://snyk.io/test/github/Mic-M/ioBroker.smartcontrol/badge.svg)](https://snyk.io/test/github/Mic-M/ioBroker.smartcontrol)

[![NPM](https://nodei.co/npm/iobroker.smartcontrol.png?downloads=true)](https://nodei.co/npm/iobroker.smartcontrol/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/Mic-M/ioBroker.smartcontrol/master.svg)](https://travis-ci.org/Mic-M/ioBroker.smartcontrol)

## smartcontrol adapter for ioBroker

Control devices smarter: by grouping, including triggers like motion, opening window, etc. and set target devices accordingly.

Icon made by [freepik](https://www.flaticon.com/authors/freepik) from [flaticon.com](https://www.flaticon.com/).

## WARNING

**Please do not yet use this adapter in a productive environment** — It is in an early development stage and just published for testing purposes.

## Installation
The adapter is not yet in the "latest repository". So please [Install adapter from own URL](https://github.com/ioBroker/ioBroker.docs/blob/master/docs/en/admin/adapter.md). Then add an adapter instance.


## Instructions

We are having a nice term [Medienbruch](https://de.wikipedia.org/wiki/Medienbruch) in the German language, which is an unnecessary requirement to 'break' the current medium and switch to a different medium (like different website, program, etc.) to execute/complete a task. 
Since this is cumbersome, I am not providing any adapter instructions here, but intuitively right within the adapter configuration.

Therefore, all instructions have been included in the admin settings of this adapter. Click on the according header, and you will get the instructions as needed:

![SmartControl Options](admin/img/smartControl_options1.gif)


## To Do (to be considered for further development and future releases
* (frostnatt) - 2020-07-05 - Es wäre ein gewisses "misbehaviour-handling" wünschenswert, wenn zum Beispiel der Occupancy-Datenpunkt nicht auf False gesetzt wird. Hier könnte man zwischen "nichts tun" und "in z Minuten ausschalten" wählen. [ioBroker Forum Link](https://forum.iobroker.net/post/458399)
* (OstfrieseUnterwegs) - 2020-07-03 - Add option to disregard additional schedule table if a time specific trigger is activated - [ioBroker Forum Link](https://forum.iobroker.net/post/457849)
* ~~(OstfrieseUnterwegs) - 2020-07-03 - Think about a better name for "Room/Area", which is actually like a complex 'scene'. Maybe "zone"? - [ioBroker Forum Link](https://forum.iobroker.net/post/457849)~~ -> renamed to "Zones"
* (OstfrieseUnterwegs) - 2020-07-03 - Cron Wizard - [ioBroker Forum Link](https://forum.iobroker.net/post/457861)
* (looxer01) - 2020-06-22 - IFTTT etc. - [ioBroker Forum Link](https://forum.iobroker.net/post/453321)
* (EdgarM) - 2020-06-18 - Several ideas - [ioBroker Forum Link](https://forum.iobroker.net/post/451578)
* (siggi85) - 2020-05-24 - time depending light control features - [ioBroker Forum Link](https://forum.iobroker.net/post/437887)
* (klassisch) - 2020-05-24 - several suggestions - [ioBroker Forum Link](https://forum.iobroker.net/post/437877)
* (Mic-M) - 2020-05-23 - die Möglichkeit, nach x Minuten ausschalten zu lassen (z.B. nach 2 Stunden) falls kein Trigger wie BWM mehr was auslöst, um Fälle abzudecken wie "der User ist eingeschlafen" [ioBroker Forum Link](https://forum.iobroker.net/post/437806)
* (MartyBr) & (crunship)  - 2020-05-17 - Manuelles schalten soll Bewegungsmelder außer Kraft setzen. [ioBroker Forum Link](https://forum.iobroker.net/post/433871) | [ioBroker Forum Link 2](https://forum.iobroker.net/post/437803) | [Script](https://forum.iobroker.net/topic/21226/vorlage-automatisches-licht)


## Changelog

### 0.1.0-alpha.2
* (Mic-M) multiple changes, improvements and enhancements

### 0.1.0-alpha.1
* (Mic-M) multiple changes, improvements and enhancements

### 0.0.3
* (Mic-M) release for very early testers

## License
MIT License

Copyright (c) 2020 Mic-M <iob.micm@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.