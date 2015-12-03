Board Description
-----------------

board designation           : uMyriadRF6002
board version		    : v2	
board type                  : Lead Free
board size                  : 49.3 mm x 36.6 mm
board thickness             : 
board material              : IT-180A
number of layers            : 8
 

Top layer copper foil thickness: 17.5 um
Dielectric thickness between Top layer and 2nd: 173 um (6.8 mils)
Dielectric between Top layer and 2nd relative permittivity (Er): 4.2


minimum finished hole size  :  200 um
minimum spacing             :  100 um
minimum track width         :  100 um

drill diameters             : finished hole

plating finish (both sides) : immersion gold
                              0.05-0.10 um of gold over
                              2.50-5.00 um of nickel

Important Notes
---------------

DRCs must be run on Gerber files before building boards.

All through hole vias may be plated shut.

Solder mask : black, both sides.

Silkscreen : white epoxy ink, both sides.

Electrical test : 100 % netlist.

Boards are to be individually bagged.

Design software used:  KiCad


Controlled Impedance
--------------------
  * 50 ohm microstrip line (Top layer) track width 0.33 mm


Board Stackup
----------------

 Solder Paste Front		: Stream-F_Paste.gtp
 Silk Screen Front		: Stream-F_SilkS.gto
 SolderMask Front		: Stream-F_Mask.gts

1. Front Layer			: Stream-F_Cu.gtl
2. Inner 6		        : Stream-Inner6_Cu.gbr
3. Inner 5	                : Stream-Inner5_Cu.gbr
4. Inner 4                      : Stream-Inner4_Cu.gbr
5. Inner 3                      : Stream-Inner3_Cu.gbr
6. Inner 2                      : Stream-Inner2_Cu.gbr
7. Inner 1                      : Stream-Inner1_Cu.gbr																
8. Back Layer			: Stream-B_Cu.gbl

 SolderMask Back		: Stream-B_Mask.gbs
 Silk Screen Back		: Stream-B_SilkS.gbo
 Solder Paste Back      	: Stream-B_Paste.gbp

--------------------------------------------------
 PCB edges           	: Stream-Edge_Cuts.gbr

 Drill map            	: Stream-drl_map.pho
         	 	: Stream-NPTH-drl_map.pho






