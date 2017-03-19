# Code-Foo Lincoln Logs

## Problem: 
Figure out how many Lincoln Logs it would take to build a replica of the Empire State Building. Describe each step in your thought process.

## Facts
* Width = 187ft at base
* Length = 424ft at base
* Height = 1250ft (roof)
* Height = 1454ft (tip)
* Windows = 6500
* Floors = 102

## Assumptions
* Only outside structure needs to be made with inside completely empty
* We will be using Loblolly Pine wood which when mature grows to an average of 100ft with a 2ft diameter.  (Log max length 100ft with 2 ft diameter)
* Logs can be cut to any length under 100ft
* When stacked on top of each other no gap between logs
* 1 Extender log required if not long enough
* Windows are evenly spread across the floors and approximately 6 ft tall.  So every floor has approximately 64 windows.  (6500 windows / 102 floors)
* Assume that front and back have 20 windows each and left and right have 12 windows each
* Each side of window requires 2 end logs.
* Average floor height is 12 ft (1250ft to roof / 102 floors)
* Building narrower at the top than at the bottom.  Every 25 floors the outside of building will taper in 20 ft on each side of building (40 ft reduction in both length and width)
* Floor 101 and 102 same length and width as floors below
* Antenna height does not need to be account for using lincoln logs


## Solution:

### Rows with windows
Since the number of windows on each side of the building is constant and the length of the logs will never exceed 100ft the number of logs used for rows with windows will always be the same.

(Single Row)
Front: 2 end logs + 19 logs between windows + 40 window end logs = 61 logs<br />
Back: 2 end logs + 19 logs between windows + 40 window end logs = 61 logs<br />
Left: 2 end logs + 11 logs between windows + 24 window end logs = 37 logs<br />
Right: 2 end logs + 11 logs between windows + 24 window end logs = 37 logs<br />
Logs required (single row): 61 + 61 + 37 + 37 = 196 logs<br />

Window Height 6ft per floor x 102 floors = 612ft<br />
Rows required: 612 ft / 2 ft = 306

Total logs required (row with windows): 196 logs per row * 306 rows = 59976

### Section 1 (Floor 1 - Floor 25)
#### Length: 424ft,  Width: 187ft, Height: 12ft per floor x 25 floors = 300 ft
(section 1 no windows)<br />
Height (no window) = 150ft<br />
Rows required (no windows): 150 ft / 2 ft = 75<br />

Front: 4 100 ft logs + 1 24 ft logs + 4 extender logs = 9 logs<br />
Back: requires same as front<br />
Left: 1 100 ft log + 1 87 ft log + 1 extender logs = 3 logs<br />
Right: requires same as left<br />

Logs required (single row): 9 + 9 + 3 + 3 = 24 logs<br />
Total needed: 24 x 75 = 1800 logs<br />

### Section 2 (Floor 25 - Floor 50)
#### Length: 384ft, Width: 147ft, Height 12 ft per floor x 25 floors = 300 ft
(section 2 no windows)<br />
Height (no windows) = 150 ft<br />
Rows required: 150 ft / 2 ft = 75<br />

Front: 3 100ft logs + 1 84 ft log + 3 extender logs = 7 logs<br />
Back: same as front<br />
Left: 1 100 ft log + 1 47 ft log 1 + extender log = 3 logs<br />
Right: same as left<br />

Logs required (single row): 7 + 7 + 3 + 3 = 20 logs<br />
Total needed: 20 x 75 = 1500 logs<br />

### Section 3 (Floor 51 - Floor 75)
#### Length: 344ft, Width: 107ft Height 12 ft per floor x 25 floors = 300 ft
(Height 3 no windows) = 150 ft<br />
Rows required: 150 ft / 2ft = 75<br />

Front: 3 100ft logs + 1 44 ft log + 3 extender logs = 7 logs<br />
Back: same as front<br />
Left: 1 100 ft log + 1 7 ft log 1 + extender log = 3 logs<br />
Right: same as left<br />

Logs required (single row): 7 + 7 + 3 + 3 = 20 logs<br />
Total needed: 20 x 75 = 1500 logs<br />

### Section 4 (Floor 76 - 102)
#### Length: 304ft, Width: 67ft Height 12 ft per floor x 27 floors = 324 ft
(Height 3 no windows) = 162 ft<br />
Rows required: 162 ft / 2ft = 81<br />

Front: 3 100ft logs + 1 4 ft log + 3 extender logs = 7 logs<br />
Back: same as front<br />
Left: 1 67 ft log = 1 log<br />
Right: same as left<br />

Logs required (single row): 7 + 7 + 1 + 1 = 16 logs<br />
Total needed: 16 x 81 = 1296 logs<br />

### Total logs required
Rows (window): 59976<br />
Section 1 (no window): 1800<br />
Section 2 (no window): 1500<br />
Section 3 (no window): 1500<br />
Section 4 (no window): 1296<br />

59976 + 1800 + 1500 + 1500 + 1298 = 66072 logs total need to build replica