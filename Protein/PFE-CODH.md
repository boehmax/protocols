---
tags:
  - protocol
category: protein
---
# PFE - CODH

**Last Updated**: 2025-09-09
**Authors**: Max, Tipps from Patricia

## Introduction
[[Protein Film Electrochemistry]] PFE is a very powerful tool to probe protein activity. Its advantage is low material requirement and testing of different conditions/potentials on one film. 


## Material and Equipment
- Buffer (100 mM MES-NaOH, pH 7)
- CODH (nice and active)
- Sandpaper (FEPA #1200 5 or 15 µm)
- PG Electrode

## Procedure
- Polish electrode with Sandpaper for 1 min dry (rougher sandpaper will give higher current)
- Rinse with dH2O
- Put electrode in beaker with dH2O and sonicate for 1 min
- Rinse again with with dH2O
- Bring inside glove box
- Fill cell with Buffer
- Remove adsorbed O2 by reductive cycling (**between +0.2 V and −0.8 V vs Ag/AgCl** at **50–200 mV·s⁻¹** for **10–50 cycles** until no change in CV is seen)
- Let dry
- Drop cast 5 µL of Protein (5 µM) on the electrode and let sit for 5 min (see notes)
- Add back to cell, add substrate, and pray to the Echem gods that the film is stable (see notes)

#### Running CV
Potentials are against Ag/AgCl
##### For CO2 Reduction only
- Start: -0.7 V
- VT 1: -0.9 V
- VT 2: -0.6 V
Substrate: 0.84 mg/ml NaHCO3 (cell volume is 100 mL, so 80 mg aliquots are conveniently added directly to the cell shortly before e-chem.)

## Notes

I tried now different adhesion protocols for ChCODH-II
- Polishing out side, bring inside, add 16mg/ml 2uL enzyme
- Polish inside, add 16mg/ml 2uL enzyme
- Polish inside add 3 times more concentrated polymyxin 3uL, with 2uL of 16mg/ml enzyme
- Polishing out side, with water, bring inside, 5µL Polymyxin (0.2mg/ml) 10 min,  add 5µM 5µL enzyme, 5 min 
- Positively charged electrode no Polymyxin (see charge graph of ChCODH-II, so maybe negatively charged surface would have worked...)
- Pre reduced Enzyme
Those all didn't worked.
From Patricia I got the tip that the buffer makes a huge difference here, before I always used HEPES, but she recommended MES. I know that pH 7 is not in the buffering range any longer, but that is also used by others.[1] 

The protocol above does not produce a stable film. After 6 cycle current was still decreasing, I hadn't had time to optimise it yet :(

The substrate of the CODH is CO2 *not* HCO3-, so with higher pH you will run into the problem to not probe CO2 reduction but CO2 to HCO3- equilibrium. 
Using CO as a substrate will most likely be easier to initially see a current. However, the max conc. that you can get at ambient pressure for CO in water is approx. 1 mM. 

[1] V. C.-C. Wang, S. W. Ragsdale, F. A. Armstrong, “Investigations of Two Bidirectional Carbon Monoxide Dehydrogenases from Carboxydothermus hydrogenoformans by Protein Film Electrochemistry” _ChemBioChem_ **2013**, _14_, 1845–1851.

![[ChCODH_2.svg]]

vs

![[ChCODH-II_surfaceexposedaa.svg]]