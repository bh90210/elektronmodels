<img src="https://i.imgur.com/omIKbjp.jpg" alt="drawing" width="350"/> <img src="https://i.imgur.com/pJbgSUh.png" alt="drawing" width="350"/>

[![DeepSource](https://deepsource.io/gh/bh90210/elektronmodels.svg/?label=active+issues&show_trend=true)](https://deepsource.io/gh/bh90210/elektronmodels/?ref=repository-badge)

# elektron:models

A Go package for programmatically interaction with [elektron](https://www.elektron.se/)'s **model:cycles** & **model:samples** via midi.

_WARNING: still in active development, things might not work, things might change._

## Prerequisites

### Go

Install Go https://golang.org/doc/install

### RtMidi

For Ubuntu 20.04+ run `apt install librtmidi4 librtmidi-dev`. For older versions take a look [here](https://launchpad.net/ubuntu/+source/rtmidi).

Instructions for other operating systems coming soon.

## Usage

_complete examples can be found under [examples](https://github.com/bh90210/elektronmodels/tree/master/examples/) folder_

If you haven't already, download cycles/samples manuals from elektron's website.
The relevant part for this library is the `APPENDIX A: MIDI SPECIFICATIONS`.

<img src="https://i.imgur.com/Yrs6YS3.png" alt="drawing" width="350"/> <img src="https://i.imgur.com/cmil9NG.png" alt="drawing" width="350"/>
