---
tags:
  - protocol
  - protein
category: protein
---
# CODH Expression

**Last Updated**: 2025-08-12
**Authors**: Max, but inspiration taken from [here](https://pubs.acs.org/doi/full/10.1021/acsami.2c09547) and other sources

## Introduction

Here I summarised the general protocol for the expression of CODH in *E. coli*. There are different protocols out there how to do it! This one gave us the best yields so far. Equipment and Chemicals are noted for 1 L of Culture, adjust as necessary.

## Material and Equipment
- a 3 L Erlenmeyer Flask
- a 1 L Erlenmeyer flask with ground joint 
- septum
- syring needels
- some LB
- 1 L of LB-phosphate (900 ml LB + 100 mL 10x TB Salts) (sterile)
- 40 % glucerol (sterile)
- Ammonium iron citrate (0.5g)
- L-cystein (0.6g)
- 0.5 M Nickel chloride solution (2 mL)
- 1 M Isopropyl β-D-1-thiogalactopyranoside (IPTG) stock (200 µL)
- Ampicillin
- Chloramphenicol
- Centrifugation bottels
- Falcon tubes


## Procedure
### Day 0
1. Prepare an overnight culture by inoculating 20 mL of LB + appropriate antibiotics.
2. Incubate it over night at 37 C while shaking.
- Check if you have everything for the next day(s)! Prepare if necessary!
###  Day 1
1. Pre heat the big shaker to 37 C.
2. Prepare the growth medium in 3 L Erlenmeyer flask: 1 L of LB-phosphate containing 0.5% (w/v) glucose, 1 mM NiCl2, 2 mM ammonium iron citrate (0.5 g/L), 5 mM L-cysteine (0.6 g/L), 100 mg/L Ampicillin and/or 35 mg/L Chloramphenicol and/or 50 mg/L Kanamycin sulphate.
	*I make the "Salt Mix" seprate from the rest of the medium, and dissolve it and then add it (i.e. for 2 L I weigh in 1 g Iron citrate, 1.2 g L-cys, 4 mL of 0.5 M NiCl2, and sometime sugger, if i dont have 40% solution at hand. Then I dissolve it in 40 mL dH2O and add 20 mL to 1 L of medium*
1. Take blank sample for OD measurement!  
1. Inoculate with 10 mL of overnight culture.
2. Grow to an OD(600nm) of 0.3 to 0.6 at 37 C while shaking (150 rpm). *This usually takes 2.5 h but will vary if you use different antibiotic or nickel concentration*
3. Transfer to 1 L Erlenmeyer flask. Add a stirring bar. Take OD and collect a sample for later SDS page analysis (before induction).
4. Add 50 µL of a 1/10 dilution of AntiFoam C. 
5. Seal with septum and bubbel for 30 min with N2. 
	*From now on the cells should not see any more oxygen!*
7. Then add IPTG to gain a final concentration of 200µM under bubbling.
8. Addition of 10 ml 0.5 M fumarate stock under bubbling.
9. Let them grow for 20 h at 30 C/ 20 C while shaking (160 rpm).
### Day 2
1. Ideally harvest is done anaerobically. For this poke a needle in the septum and transfer it to the glovebox.
3. Harvest cells by transfering them to centrifugation bottles and spin them down.
	*General 5000g for 5 min is plenty for pelleting E. coli, however, our centrifuge in the glovebox does not go so high. So put maximal speed for 20 min.*
4. Since storage of an anaerobe cell pellet is not trivial it is recommended to continue directly with the purification.  --> [[CODH purification]]

## Notes
- 10x TB Salts: 23.135 g of KH2PO4 (Molecular Weight: 136.09) and 125.41 g of K2HPO4 (Molecular Weight: 174.18) in water to a final volume of 1L, sterilely filtered.
- Alternateively the harvest can be done aerobically. We can assume that the oxygen concentration says low in the cells, if handled quickly.
- CbCODH likes TB medium, and glycerol instead of glucose.
- ChCODH-I, ChCODH-II, RfCODH, CBC1CODH like LB more, as written above.
- LB-phosphate = 20 g LB mix in 900 mL water --> autoclave, then add 100 mL 10x TB salts.