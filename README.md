# GD-CodeEdit
Code Edit 4 Grim dawn
# Guide
Here is the DLL edit for grim dawn.
The target here is to build the MAX attribute value for every euqipments in Grim Dawn.
The equation is
item's attribute value := item's dbr[item's base attribute value] * (1+item's seed {operates with } item's dbr[item's jitter]).
for example:
A item has 5 base fire damage,its jitter is 25,then the attribute value is between 5*75%=3.75 and 5*125%=6.25.
The final attribute value is revalant to item's seed,the seed is a RNG that multiply with jitter(from -1 to 1).
We skip the item seed calculation to make the MAX varibles.
Special thanks to Cryptomancer,with his post about the execution to skip item seed. http://www.grimdawn.com/forums/showthread.php?t=60590.
# Screenshots

