Description
=======================
The zip file contains "soil line" information between corresponding bands of Terra/MODIS and EO-1/Hyperion, and between different bands of EO-1/Hyperion at a calibration site (RailRoadValley Playa: RRVP). These were used for model-based spectral band adjustment between them over the site. Please be careful about the uncertainty and limitations when using the data for a calibration purpose, and appropriately cite the reference below.

### Revision History:
First release on 2021/07/01

### References:
1. Mizuochi, H., Tsuchida, S., Obata, K., Yamamoto, H., Yamamoto, S. (2020): Combination of cross- and inter-band radiometric calibrations for a hyperspectral sensor using model-based spectral band adjustment. Remote Sensing, 12(12), 2011.

Data
=======================
### soilline_xxx_to_yyy.csv
this was used to translate surface reflectance of the Hyperion xxx band to that of yyy band, during 2001 to 2008 over the RRVP.
	- column 1: slope of the soil line
	- column 2: offset of the soil line
	- column 3: coefficient of determination

### soilline_Bx.csv
this was used to translate surface reflectance of MODIS band x to the corresponding Hyperion band.
	- column 1: slope of the soil line
	- column 2: offset of the soil line
	- column 3: coefficient of determination
