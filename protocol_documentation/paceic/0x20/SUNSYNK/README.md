Thank you kitor for sharing these!  They don't contain any info on commands 42h or 44h, the two main Read Analog/Status Information commands, but do contain documentation on multiple other CIDs. These additional CIDs seem to be used more from the perspective of an inverter querying the battery packs, and return redundant (from a status readouts perspective) information that's already included in commands 42h and 44h.  For that reason, they not been implemented by esphome-pace-bms.  This documentation would be invaluable for anyone writing a "BMS emulator" though!



From kitor: 



It has some typos/mistakes, two I found:



&nbsp;   in 61h field 2 (total current) example shows accuracy 3 but table lists 1

&nbsp;   in 64h (shutdown a specific battery pack) table lists CID2 as 9Bh instead of 64h



