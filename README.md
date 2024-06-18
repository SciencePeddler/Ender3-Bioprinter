# Ender3-Bioprinter
Conversion of the Large Volume Extruder paper to ender 3

Firstly, this project would not have been possible without the paper
**READ THIS PAPER FIRST**
_[Large volume syringe pump extruder for desktop 3D printers_ published by KiraPuschaThomas J.HintonbAdam W.Feinbergab](https://www.sciencedirect.com/science/article/pii/S2468067217300822)

Some equipment you'll need or need to work around listed in the order of most expensive

1. **15ml or 50ml centrifuge ** 
Needed to spin down gelatin support bath into a hydrogel, remove undisolved gelatin. These can sting you for quite a bit unless you kind find a cheap one on eBay

2. **3D printer**
The "filament" in this case is a mixture of sodium alginate pumped by a 3d printed syringe pump, this pump is entirely 3d printed, minus the nuts, bolts and extruder motor.

3. **Mason jar blender**
You'll need to be blending down set gelatin into tiny particles, smaller the better, without overheating the gelatin causing it to redisolve. I used a stick blender but it can make a mess if you're using it in a tiny space.

Bill of materials from the paper

Designator	Component	Number of Units	Cost per unit [USD]	Total Cost [USD]	Source of Materials	Material Type
Double Shielded Ball Bearings	608-ZZ	2	0.70	1.40	Amazon	Steel
M8 × 2.4 mm Steel Hex Nuts	90592A022	4	0.05	0.19	McMaster-Carr	Steel
M8 Brass Hex Nuts	MN2580000BR0000	2	0.50	1.00	Fastenal	Brass
M8 – 1.25 × 1 m, Threaded Rod, Stainless Steel, 304	21YP40	1	10.00	10.00	Grainger	Steel
M3 × 10 mm Socket Head Screws (i.e. Hex Bolts)	91290A115	10	0.07	0.70	McMaster-Carr	Steel
M3 × 16 mm Socket Head Screws (i.e. Hex Bolts)	91290A120	4	0.08	0.32	McMaster-Carr	Steel
M3 × 8 mm Socket Head Screws (i.e. Hex Bolts)	91290A113	2	0.07	0.14	McMaster-Carr	Steel
M3 × 45 mm Partially-Threaded Socket Head Screws (i.e. Hex Bolts)	91290A079	2	0.14	0.28	McMaster-Carr	Steel
M3 Hex Nuts	90592A085	16	0.01	0.14	McMaster-Carr	Steel
60 mL Luer-Lock BD Syringe	TM82175	1	0.77	0.77	Amazon	Polypropylene
Standard Polyurethane Tubing, 1/8″ OD, 1/16″ ID	4HL93	1	16.00	16.00	Grainger	Polyurethane
18-Gauge, 4″ long blunt-tip needle with Female Luer Lock Connection	6710A44	1	4.01	4.01	McMaster-Carr	Stainless Steel
Male Luer to 1/16″ Tubing Barb	EW-45,518-00	1	0.48	0.48	Cole-Parmer	Polypropylene
Epoxy	554,869,652	1	6.95	6.95	Walmart	Steel Reinforced Epoxy
17-Gauge Luer-Lock Needle	JG17-1.0X	1	0.18	0.18	Jensen Global	Stainless Steel
26-Gauge Luer-Lock Needle	75165A555	1	0.24	0.24	McMaster-Carr	Stainless Steel
Loctite 0.2 fl. oz. Threadlocker Blue 242	209728	1	6.47	6.47	Home Depot	Glue/Epoxy

Reagents (chemicals) you will need

1. Gelatin ( I purchased some from the baking isle in our local super market. I used powdered because it's easy to weight out and disolves quickly)
2. Calcium Chloride (also sold as Damp Rid. A white powdery, flakey, chemical that absorbs water. May also be sold in pool shops to increase the hardness of pool water)
3. Sodium Alginate (probably best served to search the net for this one. I purchased mine from a biotech company but you'll need a business address if you do the same)

**Other Useful Links**
Video guides detailing assembly of 3D-printed syringe pump and Slic3r software setup 

https://www.youtube.com/channel/UCEwYrE9pROR0kinbDDSCFWg/videos 

Article detailing 3D bioprinter hardware/software conversion processes and algae bioink preparation 

https://www.hackster.io/dynamic-ink/open-affordable-3d-bioprinting-14d68b

Pronterface program for controlling bioprinter directly from computer while connected via USB https://www.pronterface.com/ Index of G-code commands https://marlinfw.org/meta/gcode/

Slic3r program for slicing STL files 

https://slic3r.org/ 

Video guide detailing setup of Slic3r program for printing with sodium alginate 

https://www.youtube.com/watch?v=ASdhIE9vMF8
