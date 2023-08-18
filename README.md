# 3DPF
3D Printing Filter, initially designed for PFA Micron+

![3DPF](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/3DPF.png)

## Thank you
Equal amounts of credit should go to @staticanime for initial testing / feedback and ideas with this project. Thank you.

Also thanks to: 
- @Kyleisah for answering my 1000x CAD questions
- @.Corvid for the advice on the airflow adjustments from Test V3 to Test V4
- and obviously @HartK & the team for Micron+

## 3DPF
During my assembly of the Micron+ I noticed there wasn't a "made to fit" filter.

There are several very good options around:
- [The original Nevermore](https://github.com/nevermore3d/Nevermore_Micro) (Lots of good info on carbon filters on this page)
- [The ZeroFilter by @zruncho](https://github.com/zruncho3d/zerofilter)
- [The MF Nano by Maple Leaf Makers](https://github.com/MapleLeafMakers/MFNano)

These are all awesome, but are designed for other printers, so in comes the "3DPF" (3D Printing Filter):

(Name comes from me being a mechanic by trade, diesel cars have DPFs, 3D for obvious reasons, and it's pretty much a mixture of the 3x filters above)

This is my first proper CAD project, and so far it seems to be going well. It's nothing in comparison to some of the CAD geniuses in the community, but not a bad first attempt.

Current details as of Beta 1:

- 84mm (W) x 120mm (D) x 18.5mm (H)
- Uses a 5015 blower fan
- 6x3 magnets to attach the 2 bodies together
- Exhaust grill points upwards rather than to the door, with a taper to assist the air on the way out.

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/Sidesshot.png)

- Current iteration has a grill with angled towers in an attempt to direct the air from the fan into the left of the cartridge.
- Wago mount / simple brackets that allow it to be slid into the extrusions from the front.
- Designed to fit under the Micron+ bed, much like the Nevermore does on a Voron V2

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/UnderBed.png)

- 2x Cartridge options, one with a handle and one without.
- Handle variant includes built in, snap off supports

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/Support.png)

## BOM
Qty |Part|Notes
---|----|---
8x|6x3 Magnets
8x|Voron Spec Brass Heatset Inserts|M3x5Dx4.5W
2x|M3x6 FHCS|M3x8 / M3x10 FHCS will also work
4x|M3x6 BHCS|M3x8 / M3x10 BHCS will also work for the cartridge and plenum lids
2x|M3x6 BHCS|To mount the brackets to the plenum
2x|M3x8 BHCS|To moount the brackets to the extrusions
1x|5015 Blower Fan
2x|Wago Connectors|221-412, Optional


## Printed Parts BOM
Qty|STL
---|---
1x|Plenum
1x|Cartridge [*]
1x|Cartridge_Handle [*]
1x|Plenum Lid
1x|Cartridge Lid
1x|Wago Mount [*]
2x|Compact Mounts (Left & Right) [*]

[*] Choose either/or


## Assembly

- Insert 4x heatsets into the Cartridge and Plenum for the lid securing screws.

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/3DPF_nolid.png)

- Insert 2x heatset inserts into the bottom of the screw tabs on the 5015 fan.

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/Fan_Inserts.png)

- You may need to recess them 1-2 mm to allow the screws to sit correctly on the underside of the plenum.

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/Fan_INsert_Recess.png)

- Insert 2x heatsets into the 2x outside tapered edges of the plenum, where the mounting brackets will attatch. 

![](https://github.com/Jadecky/3DPF/blob/main/Beta%201/Images/Mount.png)

- Insert the fan into the plenum body routing the wire up the cable guide and out towards the back, and secure the fan with the 2x M3 FHCS from underneath the plenum.

- Attatch either the wago mount or 2x compact mounts to the plenum with M3x6 BHCS.

- Insert the 8x 6x3 Magnets into the provided holes on the mating faces of the cartridge & plenum.

- Fill cartridge with Carbon Pellets of your choosing.

- Slide the cartridge & plenum lids into place and secure with M3 BHCS.



## This filter is still in testing so any feedback/advice is much appreciated, please direct this to the [kyle_gb channel](https://discord.com/channels/825469421346226226/1132795892810907748) on the Doomcube discord.
