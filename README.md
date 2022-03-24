# ESP32-workshop-files
Kicad files from my two-day workshop at [Bitraf](https://github.com/bitraf) on creating an ESP32 based IoT device from scratch. In the Workshop, attendees will be making an IoT device from scratch using the Open Source EDA software Kicad. [Slides from the workshop](https://www.slideshare.net/jensa/two-day-electronics-workshop-with-kicad-training) can be found at my Slideshare account.

## Reference designs
In the workshop, we'll create our own boards from scratch, but we found that it's convenient to have a project to compare and check things against. In the workshop, the attendees can choose to use either the ESP32 S2/S3 Mini or the ESP32 Wroom 32E modules. The latter requires the use of a serial chip such as the CP2102/04 and this tested design has the required auto-program circuitry.

## Alternate parts
Having a devboard is fun, but having some builtin input and output is even better, so for the attendees that don't have a plan, I've suggested to add an APA102 Dotstar pixel as well as a simple NTC-based temperature sensor. The circuit for these two are in the files for the S2/S3 Mini.