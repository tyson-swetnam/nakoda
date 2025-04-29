# Batteries

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

Drones utilize Lithium Polymer (LiPo) batteries primarily for their excellent energy density-to-weight ratio, enabling longer flight times. Proper care and handling are essential for safety and maximizing battery lifespan.

LiPo battery technology continues to evolve, offering improved performance and safety features.

## Inventory

Nakoda Drone utilizes:

* 4 x [Tattu Plus 16,000 mAh 12S](https://genstattu.com/ta-plus1-0-15c-16000-12s1p-c-xt90.html){target=_blank} batteries (Standard LiPo). (Connector: AS150U-F)
    

Mini-me Drone utilizes:

* 3 x [Floureon 5500 mAh 3S](https://www.ebay.com/b/Floureon-LiPo-RC-Batteries/40700/bn_88402995){target=_blank} batteries. (Connector: XT60)

## Battery Specifications

| Battery           | Nominal Voltage | Fully Charged Voltage | Capacity   | Configuration | Connector Type | Approx. Weight | Recommended Charge Rate (1C) | Storage Voltage (~3.85V/cell) |
| :---------------- | :-------------- | :-------------------- | :--------- | :------------ | :------------- | :------------- | :--------------------------- | :---------------------------- |
| Tattu 16000mAh    | 44.4V           | 50.4V                 | 16,000 mAh | 12S1P         | AS150U-F       | ~4.25 kg\* | 16.0 A                       | ~46.2 V                       |
| Floureon 5500mAh  | 11.1V           | 12.6V                 | 5,500 mAh  | 3S1P          | XT60           |  | 5.5 A                        | ~11.55 V                      |

*\*Please verify actual weight of Tattu batteries.*

## Charger Setup

We utilize an [EV Peak A9 battery charger](https://www.ev-peak.com/product/a9/){target=_blank} powered by a [MaxAmps 24 Volt DC Power Supply (1500W)](https://maxamps.com/products/24v-maxamps-power-supply-62a-1500w-single-output){target=_blank}. The A9 is a multi-channel charger capable of handling both battery types simultaneously, provided the power supply can deliver sufficient wattage.

**Power Calculation Estimate:**

* Charging one Tattu @ 1C: ~50.4V * 16A = ~807 Watts

* Charging one Floureon @ 1C: ~12.6V * 5.5A = ~70 Watts

* The 1500W power supply can comfortably charge one Tattu and multiple Floureon batteries, or potentially two Tattus simultaneously at slightly reduced rates if needed, depending on the charger's internal power distribution limits per channel.

## Safety First: Pre-Operation Checks

**Before every charge, discharge, or storage cycle:**

1.  **Inspect the Battery:**

    * Check for any puffiness, swelling, or deformation. **DO NOT USE OR CHARGE PUFFED BATTERIES.** Isolate them immediately in a fireproof container away from flammable materials.

    * Examine the outer wrapping for tears, punctures, or damage.

    * Inspect wires for cuts, abrasions, or exposed conductors.

    * Check connectors (main power and balance) for damage, dirt, or corrosion. Ensure a snug fit.

2.  **Inspect the Charger & Leads:** Ensure charger ports and connection leads are clean and undamaged.

3.  **Prepare Charging Area:**

    * Always charge in a well-ventilated area on a fire-resistant surface (e.g., concrete floor, ceramic tile, dedicated charging bunker).

    * Keep flammable materials far away from the charging area.

    * Have a suitable fire extinguisher (Class ABC minimum, Class D preferred for metal fires) or a bucket of dry sand readily accessible.

    * Using a LiPo-safe charging bag or container for each battery during charging is highly recommended.

## Charging Procedure (Balance Charge)

Balance charging is the recommended method as it ensures all cells within the pack reach the same voltage, maximizing performance and lifespan while minimizing risk.

1.  **Connect Power:** Connect the MaxAmps Power Supply to mains power and then to the EV Peak A9 charger's input. Power on the charger.

2.  **Connect Battery:**

    * Connect the battery's **main power lead** (AS150U for Tattu, XT60 for Floureon) to a corresponding output port on the charger. Ensure correct polarity.

    * Connect the battery's **balance lead** (the smaller multi-wire connector) to the corresponding balance port on the charger. The connector is usually keyed to prevent incorrect insertion.

3.  **Configure Charger Settings (Per Channel):**

    * Navigate the EV Peak A9 menu.

    * Select **Battery Type:** Select **"LiPo"** for BOTH Tattu and Floureon batteries.

    * Select **Mode:** Choose **"Balance Charge"**.

    * Set **Cell Count (Voltage):** The charger should auto-detect the cell count (12S for Tattu, 3S for Floureon) via the balance plug. **Always verify** that the detected cell count and corresponding voltage matches the battery specification (e.g., shows 12S and targets 50.4V for Tattu, shows 3S and targets 12.6V for Floureon when fully charged).

    * Set **Charge Current (Amps):**
        * For Tattu: Set to **16.0 Amps** (for a 1C rate). You can select a lower rate (e.g., 8.0A / 0.5C) for gentler charging if time permits.
        * For Floureon: Set to **5.5 Amps** (for a 1C rate). Lower rates (e.g., 2.7A / 0.5C) are acceptable.

    * Review all settings on the charger screen one last time before starting.

4.  **Start Charging:** Confirm the settings and initiate the charging process on the EV Peak A9.

5.  **Monitor:**

    * **NEVER leave charging batteries unattended.** Stay within sight and hearing distance.

    * Periodically check the battery's temperature by carefully touching the sides. It may get slightly warm, but should never become uncomfortably hot.

    * Monitor the cell voltages via the charger's display if possible, ensuring they are rising evenly and none are lagging or rising significantly faster than others.

    * Stop the charge immediately if you notice any abnormal behavior: excessive heat, swelling/puffing, smoke, unusual noises from the battery or charger, or error messages on the charger. If safe to do so, disconnect the battery (main power lead first) and move it to a safe, isolated location (like outdoors on concrete).

6.  **Completion:** The charger will indicate completion, typically with audible beeps and a screen notification ("FULL").

7.  **Disconnect:** Promptly disconnect the battery (main lead first, then balance lead) from the charger once charging is complete. Leaving it connected could lead to a slight discharge or potential issues if the charger malfunctions.

8.  **Cool Down:** Allow the battery to rest and cool down to ambient temperature (approx. 15-30 minutes) before use or storage.

**Estimated Charge Time:** Charging a fully discharged battery at 1C typically takes around 60-90 minutes. The 120-180 minutes mentioned previously might apply if charging at lower rates (e.g., 0.5C) or if the batteries are only partially discharged.

| Battery           | Charger Type Setting | Charger Cell Setting (Verify Auto-Detect) | Charge Mode    | Recommended Charge Current (1C) | Fully Charged Voltage (Target) |
| :---------------- | :------------------- | :---------------------------------------- | :------------- | :------------------------------ | :----------------------------- |
| Tattu 16000mAh    | **LiPo** | 12S (50.4V)                               | Balance Charge | 16.0 A                          | 50.4V                          |
| Floureon 5500mAh  | **LiPo** | 3S (12.6V)                                | Balance Charge | 5.5 A                           | 12.6V                          |

## Storage Charge Procedure

LiPo batteries degrade faster when stored fully charged or fully discharged. For storage longer than a few days (especially for the planned 1-3 months), they **must** be put into a storage charge state.

1.  **Connect Battery:** Connect the main power lead and balance lead to the charger as described in the charging procedure.

2.  **Configure Charger Settings:**

    * Select **Battery Type:** **"LiPo"** for both battery types.

    * Select **Mode:** Choose **"Storage"**.

    * Verify **Cell Count (Voltage):** Ensure the charger correctly detects/is set for 12S (Tattu) or 3S (Floureon). The target storage voltage per cell is typically 3.80V to 3.85V.

    * Set **Current:** Select an appropriate current for the storage process. The charger will automatically charge *or* discharge the battery to reach the target voltage. A rate of 0.5C to 1C is generally suitable (e.g., 8.0A-16.0A for Tattu, 2.7A-5.5A for Floureon). Check the EV Peak A9 manual for its maximum *discharge* current in storage mode, as this may be lower than the charge current.

3.  **Start Storage Cycle:** Confirm settings and start the process.

4.  **Monitor:** Monitor the process periodically, similar to charging, especially if the battery is discharging (as this generates more heat).

5.  **Completion:** The charger will signal when the battery has reached the target storage voltage (~3.85V per cell).

6.  **Disconnect:** Disconnect the battery promptly. It is now ready for safe storage.

| Battery           | Charger Type Setting | Charger Cell Setting (Verify Auto-Detect) | Mode    | Target Voltage/Cell | Target Pack Voltage (Approx) | Recommended Current |
| :---------------- | :------------------- | :---------------------------------------- | :------ | :------------------ | :--------------------------- | :------------------ |
| Tattu 16000mAh    | **LiPo** | 12S                                       | Storage | ~3.85V              | ~46.2V                       | 8.0A - 16.0A        |
| Floureon 5500mAh  | **LiPo** | 3S                                        | Storage | ~3.85V              | ~11.55V                      | 2.7A - 5.5A         |

## Discharging Procedure

* **For Storage:** If a battery is fully charged but will not be used within 2-3 days, use the **"Storage"** function on the charger (as described above) to automatically discharge it down to the safe storage voltage level. This is the most common "discharging" need for routine maintenance.

* **For Disposal (Use Caution):** Deep discharging for disposal requires care. The EV Peak A9 likely has a "Discharge" mode.
    1.  Connect battery and balance lead.
    2.  Select "LiPo Discharge" mode.
    3.  Set Cell Count (12S/3S) and desired **End Voltage**. *Consult safe disposal guidelines; discharging below 3.0V/cell can be risky without proper equipment. A target of 3.0V/cell is often used before final disposal steps.*
    4.  Set **Discharge Current**. Chargers typically have a much lower maximum discharge current than charge current due to heat dissipation limits (check the A9 manual - likely 1A-5A range). This can take a very long time for large batteries like the Tattu 16Ah pack.
    5.  Start and **monitor closely**, preferably outdoors or in a bunker, as deep discharging generates significant heat. Ensure adequate ventilation for the charger as well.

| Battery           | Purpose          | Mode                | Target Voltage/Cell       | Target Pack Voltage (Approx) | Notes                                                                            |
| :---------------- | :--------------- | :------------------ | :------------------------ | :--------------------------- | :------------------------------------------------------------------------------- |
| Tattu / Floureon  | **After Use** | **Storage** | **~3.85V** | **~46.2V / ~11.55V** | **Use this mode if not flying again within 2-3 days.** |
| Tattu / Floureon  | **For Disposal** | Discharge (Use Care) | Variable (e.g., 3.0V)     | Variable (e.g., 36V / 9V)    | Follow safe disposal protocols. Check charger's max discharge rate. Very long process. |

## Post-Flight Handling

1.  **Cool Down:** Always allow batteries to cool down to ambient temperature (typically 30-60 minutes, potentially longer for the large Tattus after heavy use) after flight **before** charging. Charging a hot battery is dangerous and degrades it quickly. Feel the pack; it should not feel noticeably warm.

2.  **Inspect:** Check for any physical damage incurred during flight (dents, scrapes, connector issues).

3.  **Charge/Store:**

    * If flying again soon (within ~24-48 hours), recharge the battery using the Balance Charge procedure once it has fully cooled.

    * If the battery will not be used for more than 2-3 days, put it into **Storage Charge** using the charger once it has cooled. **Do not leave batteries fully charged or depleted for extended periods.**

## Battery Storage (Physical Location & State)

Proper storage is critical for preventing fires and maintaining battery health.

* **Charge State:** Store batteries ONLY at their storage charge level (~3.85V per cell / ~46.2V for Tattu / ~11.55V for Floureon). **Never store fully charged or fully depleted.**

* **Container:** Store batteries inside LiPo-safe bags or fire-resistant containers (e.g., metal ammo cans with rubber seals removed and small vent holes drilled, or dedicated battery bunkers).

* **Location:** Store containers in a cool, dry, temperature-stable location away from flammable materials (paper, wood, chemicals, etc.), direct sunlight, and sources of heat or sparks. Avoid locations with extreme temperature swings (like non-insulated sheds or garages, especially here in Tucson during summer/winter). A climate-controlled room is best.

* **Separation:** Ensure battery terminals cannot accidentally short-circuit against each other or conductive surfaces (like the metal walls of an ammo can if not using bags). Store them so connectors are protected, perhaps using connector caps if available.

* **Monitoring:** Periodically (e.g., monthly) visually inspect stored batteries for any signs of puffing. If storing for very long terms (>3 months), it's good practice to check the voltage using a cell checker or the charger and briefly run the Storage function again if the voltage has drifted significantly (unlikely unless there's an issue).

## Battery Disposal

LiPo batteries contain materials that should not enter the landfill and pose a fire risk if damaged in trash collection/processing.

* **Discharge:** Safely discharge the battery as low as possible using the charger's "Discharge" function or a dedicated discharger (e.g., light bulbs, resistor bank). Aim for 0V per cell if possible *and safe according to your equipment and local regulations*. Handle potentially hazardous low voltages with care.

* **Recycle:** Take depleted LiPo batteries to a designated battery recycling center or hazardous waste disposal facility.
    * In Tucson/Pima County, check the City of Tucson recycling directory or Pima County hazardous waste program for drop-off locations (e.g., Los Reales Landfill Household Hazardous Waste site).
    * Retailers like Home Depot or Lowe's sometimes have battery recycling bins (Call2Recycle), but verify they accept LiPo specifically.
    * **Never** dispose of LiPo batteries in regular household trash or curbside recycling bins.

---
