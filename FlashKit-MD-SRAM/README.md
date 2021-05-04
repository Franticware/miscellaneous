[FlashKit-MD clone from AliExpress](https://www.aliexpress.com/item/1005001515149225.html)  can be modded to include battery backed SRAM.

It was tested with Wolfenstein 3d (homebrew) and Sonic 3.

Please be aware that it will probably restrict ROM size to just 2 MB (instead of full 4 MB) - Pocahontas did not work after this mod. So it might be better to just go with the ready made 2MB Cart with the save function that is offered at the same link.

I am currently not sure if it is possible to change this mod so that it would support both options (4 MB without save, 2 MB with save) at the same time, be it automatically or with some kind of a switch.

Parts for the save function:
----------------------------

R1  100K (replace 0R)  
R2  100K  
R3  100K  
R4  100K  
R5  4K7  
R6  22K  

C1  100n  
C4  100n  
C5  100n  
C6  100n  

U1  74HC139D  
U2  IS62LV1024LL-55H  

Q2  BAT54C  
Q3  MMBT2222A  

BAT1 CR1220 Holder  

Board before and after the mod:
-------------------------------

![FlashKit-MD](FlashKit-MD-SRAM.jpg)
