# K_IO_Board
LA2NI's OpenHPSDR I/O Board (Kicad Version)

OpenHPSDR P.A. OpenHPSDR Input/Output board by LA2NI (Munin 400)


![La carte E/S](https://github.com/F6ITU/K_IO_Board/blob/main/IO_board.jpg)


This I/O board is part of a set consisting of a 400 W LDMos based RF power amplifier (Munin 400), 
a medium power (600 or 1500 W) Zolotarev low pass filter, an Automatic Antenna Tuner (ATU) nickname « Aries » 
and a 4 port antenna switch.

All these developments are the work and intellectual property of Kjell Karlsen LA2NI and Laurence Barker G8NJJ.

This original work can be downloaded from 

https://github.com/LA2NI/


https://github.com/laurencebarker

The I/O board ensures the physical link between the transceiver and the "Munin400/Aries" RF system

For more information, please refer to the Aries documentation (in the G8NJJ github repository)


This board was originally developed in September 2021 by Kjell LA2NI , with UltiBoard EDA. A very early release has been designed
using KiCAD EDA. After some test on a prototype setup, it has been decided to extend this board to offer both P1/output jack and
the full set of J1 signal output. A small extention has also been inclued to add a 12V switched power supply rail for Andromeda
 interface. 

This portage (convertion/translation) is placed under the CERN Open source/ Open hardware Licence.

Kicad is an Opensource EDA software maintained by the European Reseach Center CERN (Conseil européen pour la recherche nucléaire)

The original work is protected by the TAPR Open Hardware licence
![La carte E/S](https://github.com/F6ITU/K_IO_Board/blob/main/hecatonchire.png)

# Work in progress
do NOT use these files as long as this footnote hasn't been deleted

Caveat emptor : this design is concidered as buggy by design: the "Tune" rail comming or going to J1 P10 is probably an error

