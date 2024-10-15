---
tag: protocol, protein
category: protein
---
# CODH Purification Protocol

**Last Updated**: 2024-09-22  
**Authors**: Max

## Introduction

This is the general purification protocol for CODHs. It took 2.5 years to optimize in our lab. It is very important to be paranoid about O2 exposure.

> "Just because you're paranoid, doesn't mean they are not after you."  
> — Joseph Heller, _Catch-22_, 1961

It is **highly recommended** to complete this protocol in one day. There is no real chance to stop at any point. Break times are marked.

## Materials and Equipment

- Cell pellets
- Lysis Buffer (50 mM Tris-HCl, pH 8, 20 mM NaCl, 5% Glycerol)
- Desoxycholate (DCA) (see Notes)
- Saccharose
- Lysozyme
- DNAse
- RNAse
- Dithiothreitol (DTT) (see Notes)
- Tris-HCl Buffer (50 mM, pH 8, 20 mM NaCl, 5% Glycerol)
- Ultracentrifugation (UC) tubes
- StrepTrap XT prepacked chromatography column
- Elution Buffer (Tris Buffer with 50 mM Biotin, see Notes)
- Spin columns for concentrating
- Cryo vials
- Sonicator

## 7 to 3 Days Before Purification

Bring all plasticware that will contact protein or cell pellets into the glovebox ideally _a week before purification_ to remove any residual adsorbed oxygen.

- Harvest Bottles (4 in Maggie)
- 50 mL Falcon Tubes (at least 2 in Maggie and 2 in Scarlett)
- UC Tubes (at least 2 in Maggie)
- Pipet tips
- Syringe + Syringe filter (0.2/0.45 µm)
- 15 mL Falcon tubes (2 in Scarlett)
- Protein Concentration filters
- Cryo tubes
- PCR tubes + hypovials for storage
- **Buffers**

## Purification Day

### Cell Lysis

1. To the cell pellet from a 2 L culture, add 20 mL of Lysis Buffer (10 mL for 2g wet biomass) containing:
    - 10% Saccharose
    - 0.5% DCA
    - 40 mg Lysozyme
    - 2 mg DNAse
    - 2 mg RNAse
    - Protease Inhibitor
    - 12 mg DTT (~2 mM)
2. Incubate for 30 min to 1 h at room temperature. The longer, the better. [**Good Break Time!**]
3. Sonicate (not optimized): 3*(5*(5 sec pulses, 10 sec break), 2 min break)
4. Take a sample for SDS PAGE.
5. Transfer cell lysate to UC tubes.
6. Centrifuge for 40 min at 55k rcf, 4°C. [**Good Break Time!**]

### Preparation of StrepTrap Column

1. Turn on the lamp of the FPLC system. Check if the flow works.
    - _Wash pumps with a syringe before starting the flow of new buffer/water/EtOH_
2. Add fresh DTT to all buffers.
    - _DTT is an oxygen scavenger. If the buffer stands around in the glovebox too long, it might dissolve trace amounts of O2 again if DTT is consumed._
3. Take the column from the fridge and connect it to the FPLC system.
4. Wash the column with dH2O for 5 CVs, then with Tris Buffer for 5 CVs.
    - _Check for leaks!_
5. The column is now ready for your protein!

### Purification

1. Take the cell lysate back into the glovebox and separate the supernatant from the cell lysis. Filter with a 0.2 µm filter (0.45 µm is also acceptable).
2. Take a sample for SDS PAGE.
3. Load the column with protein at a maximum rate of 1 mL/min. [**Good Break Time!** if you have a lot of protein to load.]
4. Collect some of the flow-through for SDS PAGE.
5. Wash until no absorbance is detected in the chromatogram.
6. Collect some of the wash for SDS PAGE.
7. Elute protein with filtered (inside the glovebox) Elution Buffer.
8. Collect in a 15 mL Falcon tube.
9. Concentrate protein with spin columns.
10. _Optional_: Wash protein 2-3x with Buffer in spin columns to dilute/remove Biotin.
11. Aliquot into cryo vials. Take samples for SDS PAGE, Bradford Assay, Iron Assay (10 µL total), and ICP-OES (50 µL).

### Reconstitute Column

1. Wash the column with dH2O for 5 CVs.
2. Wash with 50 mM NaOH for 5 CVs.
3. Wash with dH2O for 5 CVs.
4. Wash with 20% EtOH for 2 CVs for storage.
5. Disconnect from the system, close it, and store in the fridge.

**Done! Good Job!**

## Notes

- **Elution Buffer**: Prepare outside the glovebox. Biotin is not soluble in Tris Buffer at pH 8 and will acidify the solution upon addition. Add NaOH dropwise until all biotin is dissolved. Avoid adding too much base, as biotin will precipitate again. Ensure no O2 is present in the buffer before use. A must is adding a reductant to quench remaining O2! Adding a cryoprotectant like 5% glycerol is recommended if samples will be frozen. Due to the high concentration of Biotion (50 mM), needed to elute form the column, make sure that the overall salt concentration is below a certain value, otherwise your protein will precipitate. What this value is is dependent on the protein, so far what worked for most of my CODHs is a Buffer with 50 mM Biotin, 20 mM Tris-HCl, 20 mM NaCl,  5% Glycerol, pH 8, 2 mM DTT.
- **CbCODH and RfCODH**: Prefer 25 mM Tris, 10 mM NaCl.
- Lysis Buffer: 
- **DCA**: Protect from long exposure to light after dissolving. Dissolves poorly; shaking for 30 min to 1 h at 37°C helps. Cool before adding to cell paste.
- **DTT**: An oxygen scavenger. Reacts with oxygen and other oxidizing substances. Add freshly to the buffer. Buffers with DTT should not stand around for too long. Use your judgment to decide if a buffer is "too old." Consider adding Resazurin for certainty.