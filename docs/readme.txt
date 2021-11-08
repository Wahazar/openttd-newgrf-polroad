Polroad newgrf
-------------------
This version: polroad v7682M (19652225c080)

Contents:

1 About
2 Compatibility
3 Features
4 Development
5 License
6 Credits



-------
1 About
-------

Polroad newgrf allow to use most popular Polish road vehicles.

Name of this Repo:  polroad v7682M (19652225c080)
Repository version: 7682
GRF_ID: 
MD5 sum:            {{GRF_MD5}}


---------------
2 Compatibility
---------------

Polroad is compatible with temperate, subarctic and subtropical climate.
All known cargo classes are supported.

----------------------
3 Features
----------------------

This set provide buses, trucks, small commercial vehicles, cars, horse carriages and tractors, beginning from 1700 year.
Small trucks capacity is calculated using vehicle max load and cargo unit weight to account.
Semi-trailer trucks and farm tractors can be refitted to single power units (using passengers refit).
Running costs depend on truck and trailer weight (are decreased without trailer).

Refitting to diferrent truck body or diferrent trailer is expensive, hovewer in case of semitrailer interchange, only small fee is apllied (difference between trailer purchase and sell price).
Refitting without body/trailer change is free of charge.

3.1 Parameters
--------------

* Purchase cost modifier:
    Half, normal and double purchase costs.
* Running cost modifier:
    Half, normal and double running costs.
* Capacity multiplier modifier:
    Normal, double or triple max load, use wih caution if road slope is high.
* Keep old vehicles in purchase menu:
    Allows to disable expiration or extend model life of old vehicles. This option applies only to this set. To disable expiration of all another vehicles, use option "Vehicles never expire" in game settings.
* It is possible to switch off some groups of vehicles.
* Custom Road Types are implemented and if enabled, highway access for slow vehicles will be prohibited.

----------------------
4 Development
----------------------

Requirements for building this NewGRF successfully:
	NML (0.3 or nightly)
	gcc
	awk
	grep
	md5sum (or md5 on Mac)
	make
    mercurial (recommended)
    python (recommended)
If you want to bundle the grf, you'll need additionally
	tar
	zip
	bzip2
	unix2dos (optional)


---------
5 License
---------

This NewGRF was written by the authors as listed in the credits section
and is free to use for anyone under the terms of the GNU Pulic License
version 2 or higher. See license.txt.



---------
6 Credits
---------

Authors: nml code: McZapkie
         makefile: planetmaker         

Graphics:
Graphics:
	trucks, tractors: Sojita, McZapkie 
	horse carriages: McZapkie 
	buses: Sojita, McZapkie, Collosal 
	roads: Andrew350, GarryG, McZapkie
	depots: GarryG

