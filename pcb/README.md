The PCB is supposed to be bended to accomodate for the 3 different tenting angles. It has a cutting pattern on the middle to facilitate this, and should be manufactured with 0.6mm thickness.

# PCB characteristics:

- Kailh sockets for hot swaping
- Header pins to connect a Nice!nano or compatible microcontroller board.
- 

# Grid

To optimize the number of required pins, the PCB is wired in a virtual row/column matrix with 7 columns and 10 rows. The columns are wired in pairs, meaning each virtual column spans across two physical key columns. The left side of the PCB is exclusively wired to the odd-numbered rows, while the right side is wired exclusively to the even-numbered rows.


## Warning

Still under development, use at your own risk. I just ordered this version from JLCPCB and if it works I'll be glad to remove this warning ;)

## What's up with all those screws?

There are three constraints:

- Make it bend
- Make it sturdy enough for hotswap to work
- Make it practical, using common materials and manufacturing practices (so one can use services like PCBWay or JLCPCB...)

<img width="400" alt="venn" src="https://github.com/user-attachments/assets/2d2861b0-56b2-43f6-b3f8-4a43b080d99d">

> "I don't know... Have you tried a thin PCB with, like, lots of screws?".
>> Brain cell on the back, hand raised, a little bit ashamed of the suggestion.
