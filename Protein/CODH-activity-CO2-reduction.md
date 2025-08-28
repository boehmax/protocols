---
tags:
  - protocol
  - protein
category: protein
---
# CODH activity - CO2 Reduction Assay

**Last Updated**: 2025-03-13
**Authors**: Max

## Introduction
The reduction of CO2 is a characteristic properties of CODHs. Here you find the procedure to determine the CO2 reduction of a CODH with CO-Hemoglobin as reporter.

## Material and Equipment

- Buffer (0.1 M Tris-HCl, pH 8, 150 mM NaCl)
- Methyl Viologen (MV) (25 mM, 6.43 mg/mL in Buffer) 🥼🥽🧤❗
- Sodium dithionite (NaDT) (100 mM, 17.4 mg/mL in Buffer) 🥽
- Sodiumbicarbonate (NaHCO3) (100 mM, 8.40 mg/mL in Buffer, pKa 6.34)
	- alternatively: Na2CO3 (100 mM, 10.6 mg/mL in Buffer, pKa 10.33) will have bigger impact on pH of solution, only use if no NaHCO3 available
- [[Hemoglobin]] (Hb) (31.25 µM, 2.0 mg/mL in Buffer) 🧤
- Enzyme (0.25 mg/ml, for a "normal" CODH of ~68kDa, that is 3.68 µM)
- Kuvetts/Plates

## Procedure

### Before you start
Is the glovebox (Maggie) free and tidy? Have you been trained?
Make a list of what you need and bring it inside.
Check for buffer, ideally the day before.
Work in triplicates. One result is no result.

### CO2 Reduction assay
1. Prepare MV, NaDT, Hb, NaHCO3 and Enzyme inside the glovebox.
	- for dissolving NaHCO3: The equilibrium between NaHCO3 and CO2 is reached slowly. Give it at least 20 min at rt. Hold vile closed.
2. Mix the following in a cuvette: 820 µL Buffer, 10 µL MV, 20 µL NaDT, 50 µL Hb and 100 µL NaHCO3.
	- This Yields a final concentration of: 250 µM MV, 2 mM NaDT, 0.1mg/mL Hb and 10 mM NaHCO3.
3. Measure with Method:                        . This will measure the absorbance at 429nm and 413nm.
4. If solution stable, add 10 µL of Enzyme (2.5 µg). Mix with pipetting with 1000p up and down. (Two pipettes in your hands. Takes some practice.)
		- To check if the solution is 'stable', do a blank measurement without adding enzyme. A slope below 10^{-5} to 10^{-6} OD/sec can be considered background.
1. Press okay, and let instrument measure. After the measurement it will aske you to insert the next cuvette. Do so if you want to continue with another measurement and press ok. If not press cancel. (Your progress will be saved.)
2. Note the slope of OD(429nm)/sec.

### Adaptation for 96-Well Plate
*For quantification you need to determine the K Factor for the assay solution.*
3. Prepare MV, NaDT, Hb and NaHCO3 as above.
4. Mix in a falcon tube the following:  15 mL Buffer, 223 µL MV, 445 µL NaDT, 2.23 mL Hb and 2.23 mL NaHCO3. Keep flacon tube closed, until shortly before measurement. Yields Volume for 1 Plate (á 200 µL) so 20 mL (with extra)
	- Concentrations are adapted to yield the following concentrations in a well, **after** the 20 µL Enzyme was added. 250 µM MV, 2 mM NaDT, 0.2mg/mL Hb and 10 mM NaHCO3
	- The Hb concentration was doubled! Since the pathlength is much shorter in the 96 Well plate.
5. Add 20 µL of appropriate diluted Enzyme to well plate. (around 0.5 µg (20 µL of 0.36 µM))
6. Start Method XXX: *180 µL = 2x 90µL*
	1. Add 180 µL assay solution to rows 1 to 3 
	2. give prompt, 
	3. then add 180 µL assay solution to rows 4 to 6, 
	4. give prompt
	6. Done!
7. Remove plate and continue next plate if necessary.
8. Collect Plates with MV outside of glovebox and label accordingly, wait untli dried out, then discard in toxic waste.

### Calculate activity
One unit of activity in CODH community is defined as: 1 mmol CO production per min. Extinction coefficients for Hb at 433nm was determined by us as: 350.1031 1/cm/mM in Buffer listed above. (corrected)
Literature Value for recombinant Ch-CODH-2 is 16.9 U/mg at 25 C.
For a more precise calculation use... 

<img src="C:\Users\maxbo565\Documents\Obsidian\UU Vault\01 Figures\Pasted image 20221118141845.png" alt="Caculation of Hb and CO-Hb" width="450"/> 

<img src="C:\Users\maxbo565\Documents\Obsidian\UU Vault\01 Figures\Pasted image 20221118141938.png" alt="exticntion of Hb" width="450"/> 

taken from: https://doi.org/10.1021/acscatal.2c02221
ACS Catal. 2022, 12, 13131−13142
**Note**: one equivalent of CO-Hb equals 4 CO moleculs!

### Calculating CO2 concentration 
Refer to the supplemenatry infromation of https://doi.org/10.1021/acscatal.2c02221 ACS Catal. 2022, 12, 13131−13142 for details, if needed. In general we use a high excess.
## Notes
- To determine the K factor, measure your assay mixture in 1 cm cuvette in the region of 900nm to 1000nm. The maximum should be around 974nm (pre-set in method) The A974nm - A900nm is you K factor for a pathlength of 1 cm. You then can calculate your activity by adjusting the pathlength with this K factor as such:
- ![[Pasted image 20230908134047.png]]
- taken from: Microplate Based Pathlength Correction Method for Photometric DNA Quantiﬁcation Assay - Thermo Scientific
- MV waste needs to be collected and thrown away in special containers
- Mixing Buffer with Carbonates will influence their pH
	- Example for 50 mM Tris Buffer pH8
		- NaHCO3, 10 mM will yield approx pH 7.85
		- Na2CO3, 10 mM will yield approx pH 8.2