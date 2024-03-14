# ESP-EZ-Debug Library

This is a quick library I threw together to make adding this to Kicad projects as easy as possible. 

Simply download the repo, and [follow these instructions from Kicad to install them](https://docs.kicad.org/7.0/en/getting_started_in_kicad/getting_started_in_kicad.html#library_and_library_table_basics)

### Example Usage
![Example wiring for each connector](../files/SymbolConnectionExamples.png)



#### A note on SOICbite
I have also included the [SOICBite](https://github.com/SimonMerrett/SOICbite) kicad footprint in this repo for ease of use.

The awesome SOICbite footprint was created by [Simon Merrett](https://github.com/SimonMerrett) and is licensed under BSD-2. A copy of the BSD 2-Clause license can be found in `footprints/` next to the SOICbite footprint, `SOIC_clipProgSmall.kicad_mod`. The original SOICbite footprint can be found directly [here](https://github.com/SimonMerrett/SOICbite/blob/master/SOIC_clipProgSmall.kicad_mod), and you should go give that repo a like; this one wouldn't have been possible without it. 

Simon's repo also includes [instructions on modifying your SOIC clip connector](https://github.com/SimonMerrett/SOICbite/blob/master/HOWTO_mod_clip.md), which is needed before you can use it as a programming connector. 


#### Tag-Connect Symbols and Footprints
* The TC2050 footprint should already be in Kicad's `Connector` footprint library by default. If not, download and install nawotech's [kicad-tag-connect](https://github.com/nawotech/kicad-tag-connect) library.
