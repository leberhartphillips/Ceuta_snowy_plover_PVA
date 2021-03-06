# Overview
## The plight of a plover: viability of an important Snowy Plover population with flexible brood care in Mexico
#### Luke J. Eberhart-Phillips, Medardo Cruz-López, Guillermo Fernández, Rene Beamonte-Barrientos, Tamás Székely, Martín Alejandro Serrano-Meneses, and Clemens Küpper

In this repository you can find all the necessary files needed to reproduce the analyses presented in our paper.

* **Rcode_Ceuta_PVA.pdf** contains the documented code for all analyses, which can be implemented after downloading the datasets provided in the **`Data_files`** folder.
* **`Data_files`**

    + **nest_fate.txt**: each row is a single nest. Definitions of variables:  
*FirstFound* -- Day of the season when nest was found  
*LastPresent* -- Last day of the season the nest was seen alive  
*LastChecked* -- Last day of the season the nest was checked  
*Fate* -- 1 = was seen alive after the 25th day of incubation, 0 = failed
before 25th day of incubation  
*Freq* -- Frequency of nests with these data  
*NestAge* -- Age of a nest on the first occasion  
*Year* -- Year that nest was monitored (between 2006 and 2012)  
*std_time* -- Standardized laying date (early nests are
negative, late nests are positive). Note: maximum duration of
breeding season is 85 days.  

    + **chick_data.txt**: each row is a single individual. Definitions of
variables:  
*ch* -- capture history of a given chick over the brooding period. 1 = seen, 
0 = not seen, . = no survey effort given on that day (i.e. no data)  
*Year* -- Year the chick was monitored (between 2006 and 2012)  
*Day_of_Season* -- Day of season the chick hatched  

    + **fledgling_adult_data.txt**: each row is a single individual. Definitions of
variables:  
*ch* -- capture history of a given individual each year between 2006 and 2012.
1 = seen, 0 = not seen  
*age* -- Adult (A) or fledgling (J). Note: this describes the stage that the individual
was initially ringed.  

    + **fecundity_data.txt**: each row is a single male. Definitions of variables:  
*Year* -- Year of data collection (between 2006 and 2012)  
*Bird_ID* -- Unique number assigned to each male individual  
*Eggs* -- number of eggs tended by a given male in a given year  
