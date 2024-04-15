# ETH2GC-Card-Slot-Adapter
ETH2GC Card Slot PCB, Case Files

Card Slot Adapter on the front of the Gamecube for the ETH2GC BBA Emulation Project made by Extrems & WebHDX collab using the ENC28J60 Module.

https://github.com/Extrems

https://github.com/webhdx

~~BBA Emulation is not currently supported on the front slots but other network features such as FSP and Disc/IPL Dumping and more are accessible see swiss-gc github for more details.~~

As of swiss_1644 build, BBA emulation has been added to Swiss Hypervisor and works on the front slots. See swiss build commit for more details.

https://github.com/emukidid/swiss-gc

PCB Fab:
When ordering for example from JLCPCB, Select 1.6mm PCB thickness with ENIG surface finish for long life wear and tear, I choose HASL for cheap 1 off tests.

On the bottom of the PCB is 2x5 female 2.54mm pin connector soldered to the PCB to mate with the ENC28J60 Module once assembled.

3D Printing: I printed in PLA+ with the model standing up, the Ethernet Jack facing down on the build plate with Tree supports set to auto on my FDM Bambu X1C printer.
for the cover I had it facing flat side down on the build plate.

Case modified from WebHDX's Thingiverse gecko case https://www.thingiverse.com/thing:4866325

Fastening: I used M2x4 pan head self tapping phillips screws from a generic amazon kit for the 4 screw posts.

![1-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/da43a7d5-8d73-4930-80f8-ae9f250b8f95)
![2-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/2f6dce42-54c0-4640-a93d-18020e30d780)
![3-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/496b2cd3-1d45-4c19-960c-9cd356757771)
![4-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/82ffe8b7-9a92-4e59-b1b3-29a537952539)
![5-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/e1258e42-5e0d-47b0-ac63-3ec1eeceb54b)
![6-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/45776fac-379c-4313-a98a-ead2cc1ee949)
![7-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/fa8afa1c-0855-41db-a756-10f6d660a5bf)
![8-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/817c9caf-1dca-4a3c-bd67-532c9073025b)

**SLIM VERSION**

Slim Version requires a bit more DIY, desoldering c1 capacitor and relocating it to top connecting pin 1 of the chip to capacitor the otherside of the capacitor to ground plane scrapped off on the board, desoldering Crystal and resoldering it sideways, and soldering the bottom of the ENC28J60 pins to the top of the adapter PCB as flush as possible then snipping off the top of the pins on the ENC28J60 module, currently awaiting test PCB for SLIM version to make it easier.

Case Already posted in Slim Cases, hopefully slim pcb can resolve the C1 cap relocation and only need the crystal to be desoldered and resoldered sideways.

TODO:
- Waiting to test Slim version PCB.


![20240415_181819-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/07b4830d-d836-427b-a1d1-bfe58c267253)
![20240415_181835-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/f7329a62-df68-4217-9b8a-c1cdca333fed)
![20240415_181759-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/87adecb4-1630-41af-bdeb-b205b778a754)
![20240415_181723-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/6680e628-4a3c-48c4-881c-ef7ee236fff2)
![20240415_181659-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/edd4b1e2-b846-4436-a6c3-0de56c3d7b7c)
![20240415_181625-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/c4409b02-9676-4aed-b126-3522c5e2a4b0)
![20240415_181548-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/aff32472-3ab6-4f24-bd73-15b229b8836f)
![20240415_181509-min](https://github.com/silverstee1/ETH2GC-Card-Slot-Adapter/assets/54997238/9ab630fc-de2b-482e-99ea-ab8309569932)
