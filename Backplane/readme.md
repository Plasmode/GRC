# GRC Backplane
GRC is a modular computer system consists of an expandable backplane, 100mm X 100mm, with six female 2×25 connectors and a dedicated slot for disk-on-module. Each board is 100mm X 40mm with a corresponding 2×25 male connector that plugs into the backplane. Table below shows the signal assignments of the backplane connectors.

### Generic Retro Computer Bus Definition
The expansion connector for GRC modules is a 2×25, 2.54mm spacing female header on the backplane and a corresponding right-angle male connector on each module. The following is the pin assignment of the GRC expansion connector.

|Pin Number	|Signal Name	|Description|
|---|---|---|
|1	|GND	|Ground|
|2	|VCC	|+5V|
|3	|nCS5	|Chip select #5, active low|
|4	|D7	|Data bus 7, bidirection|
|5	|nCS4	|Chip select #4, active low|
|6	|D6|	Data bus 6, bidirection|
|7	|nCS3	|Chip select #3, active low|
|8	|D5	|Data bus 5, bidirection|
|9	|nCS2	|Chip select #2, active low|
|10	|D4	|Data bus 4, bidirection|
|11	|nCS1	|Chip select #1, active low|
|12	|D3	|Data bus 3, bidirection|
|13	|nWRCF	|Compact flash write strobe, active low|
|14	|D2	|Data bus 2, bidirection|
|15	|nRDCF	|Compact flash read strobe, active low|
|16	|D1	|Data bus 1, bidirection|
|17	|nCSCF	|Compact flash chip select, active low|
|18	|D0	|Data bus 0, bidirection|
|19	|nCSRAM	|RAM chip select|
|20	|CPU |Ctrl4	CPU-specific control line|
|21	|nNMI	|Non-maskable interrupt|
|22	|CPU Ctrl3	|CPU-specific control line|
|23	|nWAIT	|CPU wait, active low|
|24	|nWR	|Write, active low|
|25	|Bank3	|Memory bank select, MSB|
|26	|CPU |Ctrl2	CPU-specific control line|
|27	|Bank2	|Memory bank select|
|28	|CPU Ctrl1	|CPU-specific control line|
|29	|Bank1	|Memory bank select|
30	nIRQ	Interrupt
31	Bank0	Memory bank select, LSB
32	nRESET	System reset, active low
33	A15	Address line, MSB
34	CLK	System clock
35	A14	Address line
36	A0	Address line, LSB
37	A13	Address line
38	A1	Address line
39	A12	Address line
40	A2	Address line
41	A11	Address line
42	A3	Address line
43	A10	Address line
44	A4	Address line
45	A9	Address line
46	A5	Address line
47	A8	Address line
48	A6	Address line
49	GND	Ground
50	A7	Address line

