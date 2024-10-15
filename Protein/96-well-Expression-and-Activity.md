---
tags:
  - protocol
category: protein
---
# 96-Well Protein Expression and Activity Assay Protocol

**Last Updated**: 2024-08-15  
**Author**: Max

## Introduction

This protocol outlines the steps for expressing CODHs in a 96-well plate format, which is ideal for large-scale screening. While it may not provide definitive activity measurements, it allows for rapid comparison of multiple samples or conditions. This protocol is a miniaturized version of standard expression protocols and activity assays.

## Materials and Equipment

### Expression and Lysis

- Deep-well 96-well plate
- Breathable membrane
- Plate shaker (inside and outside a glovebox)
- Multichannel pipette
- Pipette tips (abundant supply)
- Reservoirs
- Media
- Inducer (IPTG)
- V-shaped plate
- Flat-bottom plates
- Buffer
- Lysis components:
    - Lysozyme
    - RNase and DNase
    - Sucrose
    - Protease inhibitor tablet

### Activity Assays

#### CO Oxidation

- 0.05 M Tris-HCl, pH 8, 20 mM NaCl buffer
- Methyl viologen (MV) (25 mM, 6.43 mg/mL in buffer) 🥼🥽🧤❗
- Sodium dithionite (NaDT) (100 mM, 17.4 mg/mL in buffer) 🥽
- Flat-bottom plate for plate reader
- CO-saturated buffer ❗ (freshly prepared; same buffer as assay buffer)
- Reservoir
- Multichannel pipette
- Tips

#### CO2 Reduction

- 0.05 M Tris-HCl, pH 8, 20 mM NaCl buffer
- Methyl viologen (MV) (25 mM, 6.43 mg/mL in buffer) 🥼🥽🧤❗
- Sodium dithionite (NaDT) (100 mM, 17.4 mg/mL in buffer) 🥽
- Sodium bicarbonate (NaHCO₃) (100 mM, 8.40 mg/mL in buffer)
- Hemoglobin (Hb) (31.25 µM, 2.0 mg/mL in buffer) 🧤
- Flat-bottom plate for plate reader
- Reservoir
- Multichannel pipette
- Tips

## Procedure

### Day 0: Preparation of Overnight Culture

1. Inoculate 5 mL of LB media with the bacterial colony containing the CODH gene of interest.
2. Incubate the culture overnight at 37°C with shaking.

### Day 1: Expression

1. Prepare the media and distribute 1.5 mL into each well of a deep-well plate.
2. Reserve a small amount of media for OD blank measurement.
3. Inoculate each well to achieve a starting OD600 of 0.05:
    - Measure the OD600 of the overnight culture.
    - Calculate the volume needed to achieve a final OD600 of 0.05:
        - $V_{added} = \frac{0.05 \times 1.5}{OD_{ON measured}}$
4. Cover the plate with a breathable membrane, ensuring it is pressed down using a roll-on tool. **Do not touch the membrane with bare hands.**
5. Place the plate on a plate shaker set to 37°C at 700-900 rpm. **Ensure the shaker is balanced.**
6. Incubate until the OD600 reaches 0.4-0.7 (approximately 3 hours).
7. Transfer the plate into the glovebox:
    - Cycle the small antechamber to half vacuum _25 times_ (20 cycles were insufficient).
    - Perform each evacuation and filling step slowly (~30 seconds) to prevent boiling.
8. Bring a tube of IPTG into the glovebox.
9. Take a 200 µL sample from each well for OD measurement.
10. Add IPTG to induce protein expression.
11. Place the plate on a shaker and incubate overnight at room temperature or higher (cooling is not possible).

### Day 2: Harvesting and Lysis

1. After incubation, take another 200 µL sample from each well for OD measurement.
2. Centrifuge the plate at maximum speed for 15 minutes to pellet the cells.
3. Prepare the lysis buffer.
4. Remove the supernatant by inverting the plate into a waste container. **Exercise caution to avoid contamination.**
5. While the plate is still inverted, blot excess liquid from the rim using paper towels.
6. Add 200-300 µL of lysis buffer to each well. **Pipette precisely to ensure comparability across wells.**
7. Lyse the cells by shaking for 1 hour.
8. Add buffer to dilute the lysate for easier pipetting.
9. Centrifuge the plate again at maximum speed for 20 minutes.
10. Transfer the supernatant to a V-shaped plate.
11. Cover the plate with parafilm and store it in the fridge. **Avoid cross-contamination by not pushing down on the wells.**

### CO2 Reduction Assay

1. Prepare the assay mix:
    - 15 mL buffer
    - 223 µL MV
    - 445 µL NaDT
    - 2.23 mL Hb
    - 2.23 mL NaHCO₃
    - Total volume: 20 mL (sufficient for one plate)
2. Transfer 20 µL of lysate into each well of a flat-bottom plate.
3. Add 180 µL of the assay mix to each well when prompted.
4. Measure the K-factor with a 1 cm cuvette using the specified method.

### CO Oxidation Assay

1. Prepare the assay mix for each row:
    - 200 µL MV
    - 2 µL of 1/10 NaDT
    - 500 µL CO-saturated buffer
    - 1098 µL buffer (adjust as needed)
2. Transfer 20 µL of lysate into each well of a flat-bottom plate.
3. Add the CO-saturated buffer just before adding the mix to the row.
4. Add 180 µL of the assay mix to each well when prompted.
5. Measure the K-factor with a 1 cm cuvette using the specified method.

## Notes

- The CO oxidation assay has a prolonged lag phase. Optimization is needed to reduce MV waste—consider lowering the MV concentration, though this may affect the redox potential.
- Avoid touching the breathable membrane with your hands. Use a roll-on tool and carefully remove the membrane when accessing the wells.
- When using the plate rotor, it is very important that your plates are in the correct spot, use the grey underdish. If they are place incorrectly, they will break during centrifugation!
- Lysis buffer example: 
	- 50mM Tris-HCl, pH 8
	- 5 % Glycerol
	- 10 % Saccharose
	- 1 % DCA
	- 20 mg/mL Lysozyme
	- 0.1 mg/mL DNAse
	- 0.1 mg/mL RNAse
	- 1 tablet Protease Inhibitor