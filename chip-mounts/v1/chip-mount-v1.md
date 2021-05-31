# chip mount v1: a low-upward-expansion TEC vacuum chuck for small to medium die

This design is a vacuum chip mount with thermal control through a TEC.
It is designed to minimize thermal expansion-induced vertical displacement in chip position -- critical for stable fiber-die position during thermal sweeps.
The expansion is minimized in two ways: the chuck on which the die sits is supported by a top-mounted flange, such that the expansion happens _downward_, and the flange itself is made from low-thermal-expansion steel.
In order to support vacuum lines/the bulky NPT-threaded hose nipple, the chuck is somewhat thick.
For this reason, I have them machined from high thermal conductivity copper.
Wiring from the thermistor and TEC to your TEC driver are left up to you.

The provided flange design is set up to mount to a Newport Ultralign 561D-YZ stage, but it mounts to anything with 1" separated #8 screws.

A glaring omission from the BOM below is a heatsink to mount on the TEC's hot side.
I haven't been able to find a good quality copper/aluminum heatsink in the correct form factor -- for my probe stations, I'm using a large skived copper heatsink (scrounged from the lab) which I cut to the correct size using a bandsaw (the rough edges can be cleaned up with a dremel).

Another heatsink option would be water cooling, if your lab has extra chillers around.
A block for liquid cooling the TEC would be pretty easy to design.
I have avoided it so far due to concerns about vibration of the heatsink, but I have never quantitatively tested these concerns.


## Bill of Materials

| Description  | Vendor/Manufacturer | Part Number | Quantity | Comments |
| ------------- | ------------- | ------------- | ------------- | ---- |
| Chip mount 	|	Custom	|	 mount-chuck-v1		| 	1	| 	Copper 	|
| Mounting flange	|	Custom 	| 	mount-flange-v1	|	1	|	Stainless steel |
| Vacuum hose fitting | McMaster | 5463K54		|	1	|	|
| Vacuum hose 	 | McMaster | 5233K52		|	1	| 	|
| Brass screws 	 | McMaster | 5233K52		|	1	| Attach chuck to flange |
| TEC module 	|	Digikey	|	1681-1190-ND |	1	|	|
| Thermistor (10k) |	Digikey |	235-1423-ND | 1 |	|
