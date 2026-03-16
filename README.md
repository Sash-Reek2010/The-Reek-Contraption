# The-Reek-Contraption
It is an RC Circuit where an LED changes the time it takes to regain its brightness based on the time a switch is open.
<img width="375" height="325" alt="Screenshot 2026-03-16 191505" src="https://github.com/user-attachments/assets/caf4d6e1-cb93-4c73-a1fd-5d1902d2dc83" />

<img width="372" height="317" alt="Screenshot 2026-03-16 191513" src="https://github.com/user-attachments/assets/77fe5e6b-27ff-4cdb-974c-7fc5d368bb43" />

## Components
This circuit consists of 3 resistors, 2 capacitors, a power supply and 3 switches. I will refer to the main resistor as R1 and the two resistors in the circuit as R'1 and R'2. For the capacitors, C1, C2, C'1 and C'2. Then for the switches, the main switch is S1 and the two other ones are S'1 and S'2.
## What happens in the circuit
The S1 controls the power supply to the circuit. We will focus on one subsection of the circuit since both are copies of each other but with the capacitances swapped.\
When all switches are closed the LED slowly brightens and reaches a level of brightness, say L1. Opening S'1 results in the LED getting brighter than L1. Then when you close S'1 again, the LED dims a bit and slowly regains its brightness back to L1. The dip in brightness depends on how long the ciruit is open for.\
<img width="256" height="141" alt="Screenshot 2026-03-16 185215" src="https://github.com/user-attachments/assets/4a9d6d9c-da34-4e0c-b507-0e8e4a29c1cf" />

## Interesting observations
The first main thing I observed was that R1 HAD to be of lower resistance than R'1 and R'2 or the circuit wouln't function properly as expected. \
The reason I reason i chose to have two different subsections was to experiment with the values of the capacitance of the two pairs capacitors by swapping them.\
Swapping the capacitors made the "open" time different for a full dim of the LED. C1's capacitance is less than that of C2 so the time I had to keep the circuit is very little. Meanwhile C'1's capacitance is greater than C'2's, so the time I open the circuit is pretty high. Keeping the circuit open for a really long time just delays the initial brightening of the LED but the time it takes to fully brighten depends on the capacitances.\
I haven't experimented with my circuit enough to record all the observations but I hope to in the future.
## Use case
It still needs developement until it can be a useful circuit by itself but as of now it can be used as a part of a bigger one./
### Thanks for reading! Hope you like my design! - Sashreek :3
