# tasmota-rules

StartupBrightness.txt <br>
start tasmota lightbulb with specific brightness depending on time of day <br>
Tasmota Lampe abhängig von der Tageszeit mit bestimmter Helligkeit einschalten <br>

MasterSlave.txt<br>
I use two plugs in master/slave. An amp and a subwoofer are connected.<br>
When the amp is switched on/off, the sub also is switched on/off.<br>
First i had a flood of mqtt messages because on EVERY power change<br>
there was a message! rule1 5 changed that to one message per on/off change.
