# Project 1 README

Student: ZongYuan Wei (919597167)

## Project Status

Compare complete:
I divided the comparison into 3 layers 
first layer (X2 and Y2) - if they are the same then we go to the next layer, else we check whether X is < or > Y and output the results
second layer (X1 and Y1) - if they are the same then we go to the next layer, else we check whether X is < or > Y and output the results
third layer (X0 and Y0) - if they are the same then we go to the next layer, else we check whether X is < or > Y and output the results

Gray done:
Create the SOP using k-mapping. See the pdf I attached

FiveSeven done:
Create the logic gates of each digit and connect them to the tunnel. Then connect tunnels with the seven segment display

## Known Issues
N/A

## References
* [Introduction of K-Map (Karnaugh Map)](https://www.geeksforgeeks.org/introduction-of-k-map-karnaugh-map/)

## Generative AI Use
I used ChatGPT for Prompt 1

### Prompt 1
Write me the standard mapping from digit to output for the seven segment display

### Response 1
Digit 0: V=0, W=0, X=0, Y=0, Z=0 → A, B, C, D, E, F = 1, G = 0
Digit 1: V=1, W=0, X=0, Y=0, Z=0 → B, C = 1, A, D, E, F, G = 0
Digit 2: V=2, W=0, X=0, Y=0, Z=0 → A, B, G, E, D = 1, C, F = 0
Digit 3: V=3, W=0, X=0, Y=0, Z=0 → A, B, G, C, D = 1, E, F = 0
Digit 4: V=4, W=0, X=0, Y=0, Z=0 → F, G, B, C = 1, A, D, E = 0
Digit 5: V=0, W=1, X=0, Y=1, Z=0 → A, F, G, C, D = 1, B, E = 0
Digit 6: V=1, W=1, X=0, Y=1, Z=0 → A, F, G, E, D, C = 1, B = 0
Digit 7: V=2, W=1, X=0, Y=1, Z=0 → A, B, C = 1, D, E, F, G = 0
Digit 8: V=3, W=1, X=0, Y=1, Z=0 → A, B, C, D, E, F, G = 1
Digit 9: V=4, W=1, X=0, Y=1, Z=0 → A, B, C, D, F, G = 1, E = 0

### Changes 1
I use this mapping to see the relations between tunnels (L0-L9) and the Seven segment display  
