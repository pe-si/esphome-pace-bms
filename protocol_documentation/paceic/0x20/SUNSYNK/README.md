Thank you kitor for sharing these!  

These PDFs don't contain any info on commands 42h or 44h, the two main Read Analog/Status Information commands, but do contain documentation on multiple other CIDs. These additional CIDs are not sent by PbmsTools but seem to be used more from the perspective of an inverter querying the battery packs for specific information.  They return redundant (from a status readouts perspective) information that's already included in commands 42h and 44h.  For that reason, they have not been implemented by esphome-pace-bms.  

But, this documentation would be invaluable for anyone writing a "BMS emulator", since these commands are sent by many inverters.



From kitor: 



It has some typos/mistakes, two I found:



&nbsp;   in 61h field 2 (total current) example shows accuracy 3 but table lists 1

&nbsp;   in 64h (shutdown a specific battery pack) table lists CID2 as 9Bh instead of 64h



