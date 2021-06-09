# jeti8s-vsens
A cheap LiXX voltage sensor for Jeti-RC Telemetry using pre built parts with simple modifications <br>

BOM: <br>
--> BX100 LiXX-Checker (up to 8 Cells) <br>
--> Arduino Nano or equivalent <br>
--> Some wires <br>
--> Solder equipment <br>

Pre-Work done: <br>
--> Find datasheet of 3-Digit 7-Segment Display: http://www.xlitx.com/datasheet/3631BS.pdf <br>
--> Analyze Display Behaviour: -1- --> <Cell 1 Voltage> --> -2- <Cell 2 Voltage> --> ... <Total Pack Voltage> --> -1- --> (Repeat again and again)
<br><br>
ToDo (Next steps): <br>
a)Write code to decode the 3-Digit 7-Segment Display on a Cheap ready-made LiPo Checker (known as BX-100) <br>
b)Write/fork code to convert the enlighted LEDs of the 7-Segment Display to characters <br>
c)Merge with already done code from https://github.com/Sepp62 for Jeti Telemetry support <br>
d)(optional) provide Interface for other telemetry systems as well <br>

I'm doing this non-profit as a hobby project, so progress will not be very fast. Please understand. <br>
