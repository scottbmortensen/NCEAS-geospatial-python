AK network: AWC (Anadromous Waters Catalog)

BC distributions: http://www.env.gov.bc.ca/esd/distdata/ecosystems/bc50kfiss/hist_fish_dist/

Yukon: http://cmnmaps.ca/fiss_yukon/

(1)	Create species specific layers (networks) using BC data and species specific layers using AK data In anticipation of merging AK, YT, and BC networks together

Individual layers were created for 
- Coho
- Chinook
- Chum
- Pink
- Sockeye		

(2)	No digital layers for Yukon data exist. There is just an interactive map showing the distributions and no way to download….so we attributed our SASAP rivers network with Yukon fish distribution information to create species specific layers:
http://cmnmaps.ca/FISS_Yukon/

(3)	Merged AK, BC, YT distributions for each individual species

(4)	Each layer has 
Species attribute =
 ‘CO’ = Coho
‘CH’ = Chinook
‘CM’ = Chum
‘PK’ = Pink
‘SK’ = Sockeye
And 
State_Prov attribute = ‘AK’, ‘YT’ and ‘BC’

I also created a numerical attribute: Chinook, Coho, Pink, Sockeye, and/or Chum attribute which is coded 1=present 0=absent. This attribute was intended for an ‘All salmon’ network since a single stream reach can provide habitat for more than one species, but I didn’t get around to creating it…..
