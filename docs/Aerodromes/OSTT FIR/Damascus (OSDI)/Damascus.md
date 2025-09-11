---
  title: Damascus (OSDI)
---

## Positions

| Name			   	|       Callsign	    |  Frequency    |   Login ID    | Remarks |
| ---------------	| ---------------------	| -------------	| ------------| ------- |
| **Damascus ADC** | **Damascus Tower** | **118.500** | **OSDI_TWR** | |
| **Damascus SMC** | **Damascus Ground** | **121.900** | **OSDI_GND**	| |
| **Damascus ATIS** | | **128.225** | **OSDI_ATIS**	| |


## Airspace - Class B

OSDI_TWR is responsible for the entire Damascus CTR airspace from `SFC` to `A037`.

## VFR Operations

### Circuits
VFR Circuits are permitted on all runways (23L/05R and 23R/05L)

All VFR aircraft wishing to do remain in the circuit at Damascus shall be issued `A020` and the following circuit directions:

| Runway | Direction |
| ------ | --------- |
|  23L   |   Left    |
|  23R   |   Right   |
|  05L   |   Left    |
|  05R   |   Right   |

!!! phraseology
    **FDY**: Damascus Tower, FDY holding short runway 23L.  
    **DI ADC**: FDY, Dmascus Tower, cleared to operate in the circuit area not above altitude 2000ft, left hand circuits report on the downwind, surface winds 120 degrees 3 knots, cleared for take-off runway 23L.  
    **FDY**: Cleared to operate in the circuit area not above altitude 2000ft, will report on the left downwind, cleared for take-off runway 23L, FDY.

VFR Circuits shall **not** be permitted at the aerodrome during times of increased IFR departure or arrival activity.

### Leaving the CTR
Once VFR aircraft are ready for departure, they shall be cleared for take-off in sequence. As they begin their crosswind turn they shall be instructed to report leaving the CTR. VFR procedures inside the Damascus CTR must be conducted at or below `A037`.

!!! phraseology
    **FYI**: Damascus Tower, FYI holding short J holding point, runway 23L.  
    **DI ADC**: FYI, Damascus Tower, surface winds 320 degrees 5 knots, cleared for take-off runway 23L.  
    **FYI**: Roger, cleared for take-off runway 23L.  
    **AIRCRAFT ON THE CROSSWIND TURN**  
    **DI ADC**: FYI, report leaving the Damascus CTR, maintain at or below altitude 3700ft.  
    **FYI**: At or below 3700ft, wilco, FYI.

Aircraft requesting to exit the Damascus CTR shall be assigned a clearance limit followed by a valid VFR cruising altitude (+500ft).

!!! phraseology
    **YYC**: Aleppo Tower, YYC is requesting to exit the Aleppo CTR via direct Qamishli, altitude 7500ft.  
    **ALP ADC**: YYC, Aleppo Tower, cleared to leave the Aleppo CTR direct Qamishli, maintain altitude 7500ft, squawk 7403, QNH 998 hectopascals.  
    **YYC**: Cleared to leave the Aleppo CTR direct Qamishli, maintain altitude 7500ft, QNH 998, and squawk 7403, YYC.

### Entering the CTR
Inbound VFR aircraft shall be sent to **ADC** with enough time such that two-way
radio communications have been established before aircraft receive clearance to enter the CTR.

On initial contact, Aleppo **ADC** will pass the instructions for joining the circuit, as well as any other pertinent information such as traﬃc information with the sector.

!!! phraseology
    **YYC**: Aleppo Tower, YYC is requesting to enter the Aleppo CTR from the southwest for circuits.     
    **ALP ADC**: YYC, Aleppo Tower, information A, cleared to enter the Aleppo CTR, maintain at or below altitude 5000ft, report left downwind runway 27L with intentions, squawk 7403.  
    **YYC**: We have A, cleared to enter the Aleppo CTR, at or below altitude 5000ft, will report left downwind runway 27L with intentions, squawk 7403, YYC.   
    **ALP ADC**: YYC, correct, QNH 998 hectopascals.    

During times of heavy IFR arrival activity, VFR arrivals may be denied entry into the CTR and instructed to hold outside of the CTR awaiting further instructions.

## IFR Operations
IFR clearances are issued by Aleppo **SMC**, ensuring appropriate routing. 

### Standard Instrument Departures (SIDs)
All aircraft shall be assigned a Standard Instrument Departure 

Controllers shall assign the proper SID exit waypoint based on the first enroute waypoint in their
flight plan, and the proper procedure identifier based on the selected runway for departure.
All SIDs with an identifier of 1R/2R are valid for runway 27L. SIDs with an identifier of 1J/2J are valid for runway 09R. SIDs with an identifier of 1E/1W are valid for both runway 27L and 09R.
Listed below are the SIDs:

|   SID   | 27L | 09R |
| ------- | -- | -- |
|  DELTA  | **2R** (:material-information-outline: 1R) | **2J** (:material-information-outline: 1J) |   
|  GOLF   | **2R** (:material-information-outline: 1R) | **2J** (:material-information-outline: 1J) | 
|  KILO   | **2R** (:material-information-outline: 1R) | **2J** (:material-information-outline: 1J) |  
|  LIMA   | **2R** (:material-information-outline: 1R) | **2J** (:material-information-outline: 1J) |
|  TANGO  | **2R** (:material-information-outline: 1R) | **2J** (:material-information-outline: 1J) |

!!! abstract "SIDs in Aleppo"  
    :material-information-outline: Like most aerodromes in Syria, for each departure procedure there are 2 options "*Departures applicable under military restrictions*" **2R/2J** identifiers, and "*Non-military restriction departures*" **1R/1J** identifiers. For purpose of simulation, controllers are to issue the **2R/2J** "*Applicable under military restriction*" departures, this departure involves a higher climb gradient and altitude restrictions of `+F160` at `D20.0 ALE` and `+F240` at `D40.0 ALE`, aswell +`A100` at waypoint GOLF. 

Departures should primarily adhere to the Standard Instrument Departure (SID) routes, avoiding
radar vectors whenever feasible. If radar vectors are to be assigned, a specific reason must be
provided. 

!!! phraseology
    **SYR123**: Aleppo Ground, SYR123, request clearance to Damascus,  with information Alpha.  
    **ALP SMC**: SYR123, Aleppo Ground, Cleared to Damascus, KILO2R departure, flight planned route, initial climb 8000ft, squawk 4301.  

### Omni-directional Departures
Aircraft may be assigned an omni-directional departure if they are unable to fly a SID (for examble not RNAV capable). **SMC** must adjust their phraseology accordingly. 

!!! phraseology
    **SYR123**: Aleppo Ground, SYR123, request clearance to Damascus, unable SID, with information Alpha.  
    **ALP SMC**: SYR123, Aleppo Ground, Cleared to Damascus, expect omni-directional departure, flight planned route, squawk 4301.  

### Arrivals
At Aleppo, **OSAP_TWR** is responsible for the entirety of the CTR, and is required to provide top-down service if the underlying **SMC** controller is offline.

!!! phraseology
    **SYR123**: Aleppo Tower, SYR123, final runway 27L.
    **ALP ADC**: SYR123, Aleppo Tower, salam, winds 260 degrees at 8 knots, runway 27L cleared to land.  


## Standard Taxi Routes
All departing aircraft shall be assigned the most appropriate taxiway, onto taxiway A. Aleppo **SMC** must exercise extreme caution on taxiway A, as conflicts can easily occur between arriving and departing traffic.

## Runway Modes
### Preferred Runway Modes
Winds must always be considered for Runway modes (Crosswind <20kts, Tailwind <5kts), however the order of preference is as follows:

| Priority - Mode | Arrivals | Departures | Remarks |
| --------------- | -------- | ---------- | ------- |
| 1 - MODE A | 27L | 27L | |
| 2 - MODE B | 09R | 09R | |

!!! note  
    The preferential runway is runway 27L. 

## Coordination

### Departure Procedures
Due to the airspace structure in Aleppo, all departures shall be coordinated with the relevant **TMA** controller before release.

'Next' coordination is **not** required to Aleppo **TMA** for aircraft that are:

- Departing from a runway nominated on the ATIS; and
- Assigned the Standard assignable level; and
- Assigned a **Procedural SID**; or
- Assigned a **Standard Assignable Heading**

'Next' coordination is additionally required for:

- Visual depatures (eg. VFR aircraft)
- All departures not on a Standard Assignable Heading
- After a go around, the next departure from that runway

The Standard Assignable level from Aleppo **ADC** to **TMA** is:

| Aircraft | Level |
| -------- | ----- |
| IFR | `A080` |
| VFR | `A050` |

### Standard Assignable Departure Headings
If a departing aircraft is receiving an omni-directional departure, they must recieve an assigned heading with their line up or take-off clearance. 'Next' coordination is not required to the relevant Aleppo **TMA** controller when the departing aircraft has been assigned the standard assignable level and assigned one of the headings listed below:

| Runway | Heading |
| ------ | ------- |
| 27L | `H274` |
| 09R | `H094` |


!!! tip
    If strong winds are present at altitude, **ADC/TMA** should discuss slight changes to these headings (+/- 5 degrees) to compensate for large crosswind components.

!!! phraseology
    **SYR23**: SYR23 ready for departure.  
    **ALP ADC**: SYR23, after departure climb to altitude 8000ft, fly runway heading, surface winds variable at 3 knots, runway 27L cleared for take-off.

