---
tags:
  - protocol
  - protein
  - expression
  - comparison
category: protein
---
## Are BL21 deltaISCR or BL21 with pISC plasmid better for my protein?

**Last Updated**: 2023-10-30
**Authors**: Maximilian Böhm

## Introduction
This is an experimental design (probably nested), to check the effect of IPTG, Iron source and strain on the effect of the expression of CODH-II. 

## Material and Equipment
- 96 deep well plates (1 for ON, 2 for Irons Source x 2 for Strain) = **5**
- 96 well plates (4 for before induction, 4 for after induction, 4 for lysate, 4 for assay) = **16**
- Yellow tip boxes (1 box for seeding, 8 rows for cell stuff, 1 row for lysate buffer addition,  4 boxes for lysate and assay) = **5**
- Reservoirs (1 for LB, 1 for water, 1 for buffer, 1 for assay solution) = **4**
- White Tipps (1 Box)
- Falcon Tubes

## Procedure
### Day -1: Transformation of E coli
1. Transform E.coli BL21 with your Plasmid and the pISC plasmid. Transform also E.coli BL21 deltaISCR with you plasmid. You need 24 colinies for this set up.
### Day 0: Overnight Cultures
1. Take 96 deep well plate, fill half of it with LB Medium and with appropriate antibiotics. 
2. Take colonies, dip it on separate LB-Aga-Plate and in the LB Medium.
3. Cover with breathable film.
4. Grow at 37 C over night at xxx rpm on Plate Shaker

### Day 1: Culturing and Expression
1. Fill the 4 96 deep well plates with a total of 1.5 ml LB medium with specific iron source, glucose, ampicillin, L-cysteine.
	LB-1: FeCitrate
	LB-2: FeSO4
2. Now add Chloramphenicol and Kanamycin to each of 2 of the deep well plates. 
3. Add 15 uL Overnight culture. 
4. Cover with breathable film.
5. Let grow for Yh at 37 C XX rpm.
6. Check OD of one well, work clean and fill back again.
7. If OD 0.6 ish, transfer to glovebox.
8. Put in the small antechamber and cycle slowly.
9. Make a pleat read of the OD 600. Take 200 µL and fill in each well! Cover this plate and freeze at -20C
10. Add IPTG to each well (have fun, this is the most annoying part). New Volume is 1.3ml!!
	- 0 µM, 100 µM, 200 µM and 400 µM
11. Incubate over night at RT shaking inside glovebox.

### Day 2: Harvest and Lyse
1. Make a plate read of the OD 600. Take 200µL. Cover plate and freeze at -20C.
2. Centrifuge at max speed, and separate supernatant from pellet.
3. Add 300µL Lysis Buffer. 
	- 1% DCA, 10% Succrose, 0.1mg/mL DNAse, 0.1mg/ml RNAse, Protease inhibitor, 4mg/mL Lysozyme
4. Lyse while shaking at RT for 1 h. 
5. Centrifuge add full speed. Transfer at least 100µL of clear lysate to fresh 96 well plate. Cover and keep in fridge.

### Day 2: Activity
*see Activity Assay protocol*
1. Fill assay mix (235 µL) in plate.
	- Mix: 
2. Add 15 µL Lysate to well.
3. Measure. OD 433 and 413? (Half Plates!)
4. Save plates with lysate in the fridege in the Glovebox, until all measurments have seen to be good, afterwards get them out and freez and store.
5. Done!
6. MV plates, store in a Fume hood with a sign and later discharge as toxic waste.

### Day 3: Data and SDS PAGE analysis
1. Analyse data with appropriate statistical Model. 
2. Choose samples for SDS PAGE analysis where you see fit. All (almost 800), might be a bit if a over kill...

## Notes