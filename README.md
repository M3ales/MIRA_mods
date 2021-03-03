# ACE Vehicle Medical
## Features
- Dynamically adds itself to anything inheriting from: `Car, Tank, Helicopter, Ship, Plane`, using `ace_interact_menu_newControllableObject` for performance.
- Provides a main interact while inside vehicle, which splits into two subcategories.
   - Stable
   - Unstable
- Filters by severity, with rapidly degrading status effects being listed in Unstable, and more minor afflictions placing the unit under Stable.
- Tracks deceased members inside a vehicle to easily see if you're working on someone who has passed on.
- Icons to more easily identify a situation and triage patients quickly - get to those who need it most.
- Easily access the Ace Medical Menu by selecting either the patient's name, or one of their afflictions.

Effective CASEVAC Management Example:

![Icon Updates](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/dynamic_icon_updates.gif)

### Stable
This category is for most non varying conditions such as:
- ![Bandage Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/bandage.png) Bandaging required on a tourinquetted limb
- ![Stitch Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/stitch.png) Stitching of bandaged wounds
- ![Low Blood Pressure Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/low_blood_pressure.png) Low Blood Pressure (Although not yet in cardiac arrest)
- ![Low Heart Rate Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/low_heart_rate.png) Low Heart Rate (Although not yet in cardiac arrest)
- ![Fracture Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/fracture.png) Arm Fractures
- ![Splinted Fracture Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/splint.png) Splinted Fractures

### Unstable
This is for conditions which may quickly lead to the patient dying, or significantly reduce their effectiveness
- ![Dead Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/dead.png) Deceased
- ![Cardiac Arrest Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/cardiac_arrest.png) Cardiac Arrest
- ![Unconscious Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/unconscious.png) Unconscious
- ![Bleeding Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/bleeding.png) Bleeding
- ![Fracture Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/fracture.png) Leg Fractures
- ![Splint Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/splint.png) Splinted Leg Fractures
- ![SpO2 Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/kat_spo2.png) SpO2 [With [KAM](https://github.com/Tomcat-SG/KAM)]
- ![Pneumothorax Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/kat_pneumothroax.png) Pneumothorax [With [KAM](https://github.com/Tomcat-SG/KAM)]
- ![Airway Blocked Icon](https://raw.githubusercontent.com/M3ales/MIRA_Vehicle_Medical/dev/Source/pr/kat_blocked_airways.png) Airway Blocked [With [KAM](https://github.com/Tomcat-SG/KAM)]

### Configurability
CBA Settings are provided and can be accessed under Configure Addons -> ACE Vehicle Medical
- Enable/Disable tracking of most states
- Apply your own thresholds for 'low' heartrate/blood pressure. (Medics only)
- Enable/Disable dead people being listed as unstable
- Enable/Disable warning popups for viewing dead members

## Translations
- English | [m3ales](https://github.com/M3ales)

I am accepting translation PRs.
