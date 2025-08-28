---
tags:
  - protocol
category: protein
---
# Size Exclusion Chromatography

**Last Updated**: 2023-06-14
**Authors**: Max

## Introduction
Under CONSTURCTION


## Material and Equipment


## Procedure

### Calibration
To use an analytic SEC to estimate the size of your protein, a calibration needs to be performed. This is done by running proteins with known MW on the colomen and generating a kalibration kurve of Eltuion time vs MW. We use the commercial kit from Citiva (LMW or HMW) but a self mixed calibration is as good! Most of the information was taken from the Citiva *Gel Filtration Calibration kit - Instructions for Use*
1. Equilibration of column. A buffer with a ionic strenght of >= 0.15 is suggested. 
1. Choice of calibration proteins.
2. ![[Pasted image 20230614090122.png]]
3. Prepare protein stocks for calibration of 20mg/mL in a buffer between pH 6 and 8 with an ionic strenght of 0.15 or greater (e.g. 50 mM phosphate, 0.15 M NaCl, pH 7.2.)
4. For use in a glovebox, prepare them in one, aliquot them in apropriate sizes and freez them in cryo tubes.
5. Mix protein in appropriate concentrations, to get peaks of similar hight. 
6. ![[Pasted image 20230614084357.png]]
7. Apply the mix on the column. The sample olume should not exceed 2% of the geometric column Volume (Vc)! (e.g. for our 24mL only have a sample volume of 480 µL or less!)
8. Determine the elution volume (Ve)
![[Pasted image 20230614084634.png]]
7. Determine the void volume (Vo). This is done by running a **fresh** solution of Blue Dextran 2000 in the sample buffer, with a concentration of 1.0mg/mL and a sample size of 0.5% of Vc. Run it by its own! It gets a very broad peak.
8. Calculate Kav for all the proteins like so:
$$
K_{av}=\frac{V_e-V_o}{V_c-V_o}
$$
9. Prepare calibration kurve as Kav vs log molecular weight.

### Molecular weight determination
1. Apply unknown sample (volume 0.1% to 2% of Vc)
2. Determine elution volume.
3. Calculate Kav and use the kalibration kurve to determin the molecular weight.
4. Note: For lipo or gluco proteins the Stoke's Radius might be a better parameter, sinze their elution is not only related to their weight. for this create a $\sqrt{(-logK_{av})}$ vs $R_{St}$ 

## Notes

[Does a different Buffer make a different elution profile?](https://www.cytivalifesciences.com/en/us/solutions/protein-research/knowledge-center/protein-purification-methods/how-buffer-ph-and-nacl-affect-size-exclusion-chromatography)

![[Pasted image 20230614085849.png]]
![[Pasted image 20230614085837.png]]