---
tags:
  - protocol
category: biophysics
---
# EPR
**Last Updated**: 2024-10-11
**Authors**: Max
==Probably incomplete== 
# CryoEPR set up

### Part 1: Disassembly of the Current Setup

1. **Remove the iris (old long thing)**
    - Carefully take off the old iris from the EPR setup. This is the long component.
2. **Remove the cable in the front going to the capillary**
    - Disconnect the cable that is connected to the capillary at the front.
3. **Remove the nitrogen tube on the back**
    - Detach the nitrogen tube located at the back of the setup.
4. **Remove the support**
    - Unscrew and remove the support piece, which is likely attached to the side or base.
5. **Remove the long gray thing going to the bridge (start with the lower part, then the top part)**
    - Detach the long gray component, starting from the bottom, followed by the top.
6. **Move it away and store it in a box**
    - Once removed, carefully store all these components in a designated box.

---

### Part 2: Preparing the Cryogenic Module

1. **Get the cryogenic module from the other side of the room**
    - Retrieve the cryogenic module that is stored elsewhere.
2. **Set it up vertically**
    - Position the module vertically.
3. **Remove the small black part from the capillary (cryogenic part) by pulling**
    - Gently pull to remove the small black piece attached to the capillary.
4. **Remove the upper part by gently twisting**
    - Twist the upper part of the cryogenic setup to remove it, taking care not to apply too much force.
5. **Remove the lower part by pulling (be careful of the O-ring and quartz)**
    - Pull off the lower part, making sure not to lose the O-ring or damage the quartz components.
6. **Take away the golden cover gently (careful with quartz), store it in the cabinet**
    - Carefully remove the golden cover, handling the quartz with care, and store the cover in a cabinet.
7. **Untwist the lower silver part so it loosens and can rotate later**
    - Loosen the lower silver component by untwisting it so that it can rotate freely.
8. **Reattach the capillary part (in place of the golden cover), avoid twisting it horizontally**
    - Attach the capillary part in the same place where the golden cover was removed, ensuring you don’t twist it horizontally.
9. **First, twist left to align with the threads**
    - Turn the component to the left to ensure the threads align.
10. **Then screw it to the right, leaving some movement**
    - After the left alignment, screw it to the right, but do not over-tighten to allow some flexibility for movement.
11. **Reattach the black parts to the quartz part**
    - Reconnect the black parts that were removed earlier, securing them to the quartz part.

---

### Part 3: Reassembling the Setup in the EPR

12. **Put the cryogenic module back into the EPR**
    - Slide the cryogenic module back into the EPR machine.
13. **Slide into the guide rail (align the pins to the pin holes)**
    - Ensure the pins at the end of the component align with the holes on the guide rail as you slide it in.
14. **Screw in the golden screws (stored in the Tupperware)**
    - Secure the setup with the golden screws from the Tupperware container.
15. **Connect the components to the bridge (adjust with silver ring if necessary)**
    - Attach all the necessary components to the bridge. If needed, use the silver ring at the bottom to adjust alignment.
16. **Attach the support (black parts on the side, screw them in)**
    - Reattach the black support parts by screwing them in place.
17. **Turn on N2 (check for good flow, a slight breeze, no whistling sound)**
    - Start the nitrogen flow and ensure that it is slightly more than a breeze but not causing a whistling noise.
18. **Attach the front cable**
    - Reconnect the front cable.
19. **Attach the vacuum pump**
    1. Remove the parafilm from the pump.
    2. Remove the metal piece from the capillary.
    3. Ensure everything is secure and functional.

---

### Part 4: Cooling Procedure

21. **Begin cooling procedure**
    
22. **First, flush the capillary with helium (He)**
    
    1. Lift the small black part on top of the quartz to allow helium to escape.
    2. Turn on the helium flow, making sure it's similar to the nitrogen flow, maybe a little less.
    3. Attach the helium source to the capillary front.
1.  Flush the Apperature that will introduce the lq He with He as well
	1. o
	2. make sure to not loose the teflon piece
	3. Leave both for 30 min to flush
3. Mount CryoNeedle
	1. Disconnect He flush
	2. Slowly mount to tank

# How to Perform an EPR Measurement

### 1. Initial Setup

1. **Turn on water cooling for the magnets.**
    
    - Ensure that the water cooling system for the magnets is running smoothly before proceeding.
2. **Turn on the electronic hub.**
    
    - Power on the hub that controls the electronics for the EPR setup.
3. **Check the bridge.**
    
    - Verify if the bridge has turned on. If not, manually switch it on.

---

### 2. Flushing with Helium (He)

1. **Flush all tubes with helium.**
    
    - This includes the long, skinny component.
    - **Important**: Ensure that the Teflon ring is not lost during this process.
    - **Wear gloves** to prevent grease or oils from contaminating the setup.
2. **Adjust the valve for helium flushing:**
    
    - Open the valve completely, then close it slightly by rotating two full rounds.
    - This step controls the helium flow effectively.
3. **Nitrogen (N2):**
    
    - Ensure the nitrogen supply is running smoothly, but specific adjustments are not needed at this stage unless specified by your setup.

---

### 3. Start the Cooling Process

1. **Turn on the vacuum pump.**
    
    - Begin pumping to prepare for cryogenic cooling.
2. **Insert the long component into the helium tank.**
    
    - Place the long component (cryogenic probe or sample holder) into the helium tank.
3. **Insert it into the cryo module.**
    
    - Once cooled by the helium, transfer it to the cryogenic module.
4. **Adjust the valve:**
    
    - Close the valve fully, then open it by half a turn to maintain optimal cooling conditions.

---

### 4. Sample Insertion

1. **Insert the sample into the EPR.**
    
    - Ensure that the sample is properly secured and aligned.
2. **Open the software program.**
    
    - Start the EPR software on the computer.
3. **Create a new experiment.**
    
    - Select "Continuous Wave EPR" as the experiment type.
4. **Send parameters to the hardware.**
    
    - Input the necessary parameters for the measurement and send them to the EPR machine.
5. **Adjust the gain.**
    
    - If necessary, reduce the gain to decrease sensitivity, depending on your sample.

---

### 5. Tuning the Instrument

1. **Tune the system.**
    
    - Follow the specific tuning procedure for your machine. You can refer to the provided tuning sheet for guidance.
2. **Modulation amplitude:**
    
    - Ensure that the modulation amplitude is smaller than the line width of the signal you are measuring.
    
    **Tip:** If available, you can import parameters from previous experiments for reference.
    

---

### 6. Check for Power Saturation

1. **Measure at different power levels.**
    
    - Perform measurements at multiple power settings (e.g., increasing by multiples) to observe how the signal behaves.
2. **Evaluate signal response:**
    
    - If the signal increases in proportion to the power, it indicates no saturation.
    - **Note:** If you saturate quickly, reduce the power to avoid signal distortion.
3. **Check line width stability:**
    
    - If the line width increases with increasing power, this indicates saturation. Adjust accordingly by lowering the power.

---
