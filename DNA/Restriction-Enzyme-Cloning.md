---
tags:
  - protocol
  - dna
category: dna
---
# Restriction Enzyme Cloning

**Last Updated**: 2022-08-31
**Authors**: Max, Maria

## Introduction
This guide will carry you trough the whole journey of cloning via restricion enzymes. This can be used, to change vectors. Here we use two different restriction enzymes, with sticky ends. With comments from Maria from Germany.

## Material and Equipment
- Plasmid with insert
- Target vector
- Primer pair
- Thermo Cycler
- dNTPs
- 5x HF Buffer
- 2x Liagtion Buffer
- 10x Fast Digest Buffer
- Phusion Polymerase
- Quick Ligase
- Restriction Enzymes

## Procedure
### Primer design 
- Design a primer pair for your insert, with a overhang for the specific restriction enzymes of choice. 
- Use primers with overhangs of two different suitable restriction enzymes (2 different restriction enzymes to generate different sticky ends). The primers should also contain overhangs to enhance efficiency of restriction endonucleases according to attachment. These will be cleaved by the enzymes and won't appear in the final construct. Restriction enzymes don't cleave the amplificate without these overhangs! See [here](https://international.neb.com/tools-and-resources/usage-guidelines/cleavage-close-to-the-end-of-dna-fragments).
- Make sure that you gain **huge amounts** of gene amplificate and as pure as possible so that you can circumvent gel-purification which causes enormous losses of DNA.
### Amplification of insert
- Amplify your insert with your primer pair, in a typical PCR reaction. Use Polymerase, Buffer etc fitting to your Primers. (or the other way around) See [here](https://tmcalculator.neb.com/#!/main).
- A typical program can look like this:

| Sample             | Volume |
|--------------------|-------:|
| d H2O              |  36 µL |
| 5x HF Buffer       |  10 µL |
| fwd primer (100µM) | 0.5 µL |
| rev primer (100µM) | 0.5 µL |
| Template (10ng)    |   1 µL |
| dNTPs (10mM)       |   1 µL |
| Phusion Polymerase |   1 µL |

| Time (mm:ss) | Temperature | Cycles |
|--------------|------------:|-------:|
| 00:15        |         95C |      1 |
| 00:15        |         95C |     30 |
| 00:30        |         68C |        |
| 01:00        |         72C |        |
| 10:00        |         72C |      1 |
|              |          4C |        |

3. After the PCR reaction, do a Agarose Gel to see if it was sucessful.
4. Digest the template with DpN1. 1 µL of DpN1 enzyme for 2 h should be sufficient. 
5. Use a PCR purification Kit. Elute in 20 µL.
7. Nanodrop.
### Digestion
- Digesting your Amplicons and your (empty) Plasmid. By pipetting like this:

| Sample                | Plasmid | PCR product |
|-----------------------|--------:|------------:|
| dH2O                  |     _X_ µL|         _X_ µL|
| 10x FastDigest Buffer |       2 µL |           3 µL |
| DNA                   |    1 µg |      0.2 µg |
| Enzyme 1              |       1 µL |           1 µL|
| Enzyme 2              |       1 µL |           1 µL|
| **Total**             |  **20** µL|      **30** µL|

1. After adding the restriction enzymes, put your tubes in a Cycler, with time and temperature depending on the restriction enzymes used. Think about Star activity! Heat inactivate if available. 
2. Make sure that the plasmid is **digested entirely** (this is the most important!!!)
3. Afterwards, clean up with DNA clean and concentration kit. Elute with 20 µL!
4. For not empty plasmids, load everything you gained onto an agarose gel, and purify from gel band. Elute with 20 µL! 
5. Nanodrop
### Ligation
-  Combine insert and target plasmid togehter with buffer and [Quick Ligase](https://international.neb.com/protocols/0001/01/01/quick-ligation-protocol) as such:

|           |         A |         B |         C |
|-----------|----------:|----------:|----------:|
| Insert    |      4 µL |    3.5 µL |      3 µL |
| Vector    |    0.5 µL |    1.0 µL |    2.0 µL |
| Ligase    |    0.5 µL |    0.5 µL |    0.5 µL |
| 2 x Buffer    |      5 µL |      5 µL |      5 µL |
| **Total** | **10 µL** | **10 µL** | **10 µL** |

1. Do multiple ligations at once, with different ratios of Insert and Plasmid! Insert should be in high excess in any case!
2. Note that the **Liagtion Buffer** contains ATP and should be** thawed on ice**! If you open up a completly new Buffer, aliqot it into 50µL.
3. Do ligation over night at 14-16°C or use a gradient like this: 20°C 2h; 18°C 2h; 16°C…  
	- (I don't know how acurate this is. I have not tested this yet. The Protocol form the Manufactorer says 5 min at RT. -Max)
1. Do **not** heat inactivate  [Quick Ligase](https://international.neb.com/protocols/0001/01/01/quick-ligation-protocol)!
4. Transform the whole ligation (10µL) to 100 µL competent DH5a. Plate everything. If it's successful you get 10-50 colonies. If you get more, it's likely that the plasmid was not totally digested and you have empty plasmid.
5. Screen for sucessfull transformations (Antibiotik resistence, Blue/Whit screening, Colonie PCR)
6. If you don't get any colonies try different ligation ratio or try to produce higher concentrated digested gene-insert.

**Good Luck!**

## Notes
- The Ligase is expensive, only do 0.5 µL reactions!
- Try to avoid NdeI, rumor has it that the diguestion with it is not very clean
- ALWAYS check if you have all the diguestion enzymes you need, also look at the tubes to see if there is enough liquid in them!

