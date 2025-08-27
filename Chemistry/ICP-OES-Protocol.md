---
tags:
  - protocol
  - chemistry
  - analysis
  - metals
category: chemistry
---
# ICP-OES Protocol

**Last Updated**: 2025-03-24
**Author**: Max
**Instrument Responsible**: [Vitalli Shtender](https://www.katalog.uu.se/profile/?id=N18-2154)

## Introduction
ICP-OES is a great technique to determine the concentrations of Metal ions in solution. It takes about *45 min to set up the device*, and measuring a sample takes about 5 min. Therefore, only sign in when you have at least 4 samples!

## Material and Equipment
- ICP grade HNO3 (69%)
- MilliQ Water
- Sample
- Syringe Filters
- 15 mL Falcon Tubes
- 50 ml Falcon Tube
- Tissues


## Procedure
**Instrument Booking**: [LIMS](http://lims.eqp.angstrom.uu.se/)
### Sample Preparation 
*20 min*
1. Dissolve accordingly in "2%" HNO3.
	- "2%" here means: Two parts of 69% HNO3 in 98 parts MilliQ Water.
	- For good results try to aim for 50 mg/L (ppb or ng/mL) of approx metal conc.
	- For Fe and Mn 100 ppb is too high! For Ni its fine.
2. Filter with 0.45µm syringe filter.

### Starting the Program and Device
*Total 25 min*
1. Turn on Argon gas by 
	1. opening the upper valve, at the wall behind the device, marked Argon. 
	2. opening the valve at the right side of the device marked Nitrogen.
2. Open the Computer Program: Syngistic (Purpel)
3. Check the right panel if everything is ok. This might take some time until everything is displayed.
4. If not already open, open the windows *Plasma Camera* and *Plasma control*.
5. Check the plasma torch for dirt, by opening the plasma chamber. If dirty, tell Vitalli.
6. Clip tubes into position. Make sure that they will suck up from the right end.
	- When transferring tubes, make sure to wipe them with a tissue before.
7. Start with tube in the air, by pushing the grey button on the *Plasma Control* Centre window.
8. When right panel says "Ideal" and the pressure stabilizes on the *Plasma Control* panel, put tube in the blank ("2%" HNO3)
9. Let it run for 10 min to heat up and wash the tubing.
	- The flow should be continuous through the inward tube. Ex-ward tube is not so important that it its constant speed.
	- While you wait this 10 min, you can prepare the standard solutions.
10. System is ready!
### Creating a new Method
This is important if you need to measure anything else that was not set up in your introduction with Vitalli. Here I am a little bit foggy with the details.
1. Open: Analysis and press New Method.
2. Select your Method Library, that was created probably by Vitalli
3. Change delay tome to 30 sec. (it takes the sample approx. 25 sec to reach the flame)
4. Change replicates to 3.
5. In Spectrum Tab: Set wavelengths and metals you want to analyse.
6. In second Tab you can choose to do Axial or Radial measurements. (See Notes.)
7. In calibration Tab put in the Calibrations you are planning to do.
8. In the last two Tabs there is nothing to do.
9. Save as... press two times "ok".
10. Done!
### Setting up Sample Information
*5 min*
Here I am also foggy, it was so fast!
1. Go to analysis and change Data Sheet. Save.
	- Its **important** to check the panel on the right side of the screen if all the information there was updated to your information, otherwise you will overwrite the data of other users!
### Starting a Measurement
*10 min + 5 min/per Sample*
1. Spectrometer Control Panel: If the system did not do it by itself now, start *Initialisation*. (see notes for detail)
2. All measurements are controlled in the XXX window.
	- Wash between every sample 1 min with the blank.
	1. Measure Blank.
	2. Measure your calibration points. Start with the lowest concentration and go higher from there. After measuring the high concentration calibration point, wash for >3 min!
		- The R2 should be >0.999 to be acceptable. And >0.9999 to be good.
		- Calibration curve should have (at least) 3 points. Eg. 1, 10 and 100, or 0.01, 0.1 and 1
	3. Measure your samples. Select the right sample for the sample name that you defined earlier in the Sample Information. (If you have more samples that you previously set up, the program will just give it random names.)
### Turning the Device off
*5-10 min*
1. Turn of plasma by pushing the green button.
2. Close all windows. Except the Plasma control and Plasma camera.
3. Clean and wash the system, but pumping the blank.
4. Dry the system by pumping air, until now bubbles are left in the outgoing tube.
5. Close the Program. Okay. No.
6. Close the valves. First on the device, then on the wall.
7. Release tubes from pump.
8. Not yourself in the log book.
9. Done! Good job!

## Notes
- Possible Errors:
	- Z-Error: Unknown reason. Just try again what you just did, often happens upon starting the device
	- Warmth Error: Currently the ventilation is not strong enough, therefore the device might heat up to much. If this happens, turn of the plasma and wait 20 min. Then turn i on again and continue where you left of, you can keep the pump pumping.
- Standards you take from the fridge in the lab of the ICP. After taking them out you can use them up to 2 weeks. If stored in the fridge, but after that they are not good enough anymore, because of *Evaporation*.
- When referring to a 2% HNO3, they mean 2 to 100 dilution of the 69% ICP grade HNO3 in MilliQ water.
- Initialisation is done (dafoq did I mean by that?? 🤨)

![[1-1.png]]taken from [here](https://cais.uga.edu/facilities/plasma-chemistry-laboratory/guide-selecting-the-most-suitable-technique/) 