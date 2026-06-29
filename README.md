# CW312T_Template_Kicad_Dreg_Port

chipwhisper CW312T template for KiCad with Dreg port (and easyeda file to import)

![](photo.png)

------

## PCB specs

- Thickness: 1.6 mm (0.062"). Required by the CW312 card-edge connector (Samtec MECF), and it's the default thickness anyway, so no extra cost.
- Edge fingers: ENIG + "gold fingers" (solder mask removed over the pads) is enough for a target plugged in/out a few dozen times. Note JLCPCB only does "gold fingers" with ENIG selected, this is NOT real electroplated hard gold. Use real hard gold (e.g. PCBWay) only if you need hundreds/thousands of insertions.
- Bevel/chamfer (30°): JLCPCB won't bevel boards smaller than 50 x 50 mm, and can't bevel V-cut panelized fingers. Fine to skip on small targets, the MECF socket has its own lead-in.

-----

# kicad project 

[CW312T_Template_Kicad_Dreg_Port.zip](CW312T_Template_Kicad_Dreg_Port.zip)

------

# easyeda pro file to import

[ProPrj_CW312T_Template_Kicad_Dreg_Port_2026-06-29.epro2](ProPrj_CW312T_Template_Kicad_Dreg_Port_2026-06-29.epro2)
