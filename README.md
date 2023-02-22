# VRSCustomMarkers
Custom SVG Aircraft Markers for Virtual Radar Server - forked from [shish0r/VRSCustomMarkers](https://github.com/shish0r/VRSCustomMarkers)

**Only** works on V3 VRS - which supports SVG aircraft markers.

## Installing

The following instructions are for a VRS installed on Linux - installing on windows should be very similar.

1) Ensure that the Custom Content Plugin is installed and enabled.
2) Download [MyMarkers1.html](https://raw.githubusercontent.com/rikgale/VRSCustomMarkers/main/MyMarkers1.html) (follow link then right-clink -> SAVE AS) into the CustomContent/CustomInjectedFiles folder of your VRS instalation.
3) In the Custom Content Plugin add an injection for the MyMarkers1.html

![image](https://user-images.githubusercontent.com/66202012/183701733-cab61151-b21b-46e9-bc87-8d401c662eb9.png)

4) Ensure that your VRS is set up to serve SVG images. If you do not have the SVG boxes checked then your VRS will serve .png files and this will have no effect.

![image](https://user-images.githubusercontent.com/66202012/183702047-d948cfbd-0a62-4d47-a3a1-fb5d3f328f4b.png)

5) Refresh your VRS web-page and it should be working.

## Colours

Note that the top section of the file assigns fill colours to the graphics based on various aircraft attributes.

Current Attributes are set for:

- MLAT + ICAO Type Code is SPIT|HURI|P51 = Dark Brown
- MLAT + Military = Kkahi Green
- MLAT = Light Grey
- Military = Green
- Operator = /Polizei|Police|Sheriff = Dark Blue
- Operator = /air med|airmed|med-trans|medevac|ambulance|adac/ = Light blue
- Operator = /Coastguard/ = dark red (Military Coastguard are still green e.g. U.S.C.G.)
- Operator = /fire/ or ICAO type code = CL2T|CL2P = burnt orange
- Aircraft undefinied registration = dark grey
- ICAO Type Code is SPIT|HURI|P51 = Brown
- (NEW!) Squawk(s) 7700, 7600, 7500 = Red/Lime Green/Cyan

## Aircraft Markers

Currently included SVG:

- Spitfire - currently set to "SPIT",  "HURI" and "P51" ICAO types (used to represent warbirds)
- F35 - set to "F35" and "VF35" ICAO types
- Eurofighter Typhoon - set to "EUFI" ICAO type
- Microlight/Ultralight - set to "ULAC" ICAO type
- CH47 - set to "H47" ICAO type
- Hawk - set to "HAWK" ICAO type
- A400M - set to "A400" ICAO type
- Global Express - set to "GLEX" and "GL5T" ICAO types (used to represent large business jets)
- C17 - set to "C17" ICAO type
- EH101 - set to "EH10", "A189" "S61" and "S92" ICAO types (used to represent larger helicopters)
- V22 - set to "V22" ICAO type
- Autogyro - set to "MT", "CDUS", "CLON" "MM16" "MM24" and "GYRO" ICAO types
- E3 - set to "E3CF" and "E3TF" ICAO types
- F16 - set to "F16" ICAO type
- T6 - set to "TEX2", "PC21", "PC12", "TBM7", "TBM8", "TBM9", "M600" and "P46T" ICAO types (used to represent single engine turboprops)
- Hunter - set to "HUNT" ICAO type
- AH64 - set to "H64" ICAO type
- MD11 - set to "MD11" and "DC10" ICAO type
- Lancaster - set to "LANC" ICAO type
- PBY-5A - set to "CAT" ICAO type
- BelugaXL - set to "A3ST" ICAO type
- B-52 - set to "B52" ICAO type
- DC-3 - set to "DC3T" and "DC3" ICAO type
- F-15 - set to "F15" ICAO type
- U2 - set to "U2" ICAO type
- B1 - set to "B1" ICAO type
- Tornado - set to "TOR" ICAO type
- IL-76 - set to "IL76" and "A124" ICAO type
- C5 - set to "C5" and "C5M" ICAO type
- AN-225 - set to "A225" ICAO type
- Saab-39 Grippen - set to SB39 ICAO Type
- Glider - set to "VENT" and "PK20" ICAO Type (more to be added to this)
- PC-24 - set to "PC24" ICAO Type
- JPRO - set to "JPRO" ICAO Type
- UAV - set to "UAV", "Q4" and "Q9" ICAO Type
- B707 - set to "K35R", "B703", "C135" and "K135"
- VEZE - set to "VEZE" and "VELO" + others TBA
- E135 - set to "E135", "E35L", "CRJ2" and "CRJ7"
- E145 - set to "E145", "E45X", "CRJ9" and "CRJX"
- SR20 - set to "SR20", "S22T" and "SR22"
- E4 - set to "E4B" (Custom ICAO for E-4B - see [VRSOperatorFlags](https://github.com/rikgale/VRSOperatorFlags) )
- IL62 - set to "IL62" ICAO Type
- P3 - set to "P3" ICAO Type
- GA - set to "ARC3" ICAO Type
- Boat/Ship - set to ZZZZ-BOAT

.... and many others.
