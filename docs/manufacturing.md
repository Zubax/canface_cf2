# Babel-Babel manufacturing

## PCB specification for all PCB
### Main PCB
* Quantity per product/order: 1
* Layers: 4 (layer stack in manufacturing package)
* Thickness: 1.0mm
* PCB color: Red
* Silkscreen: White
* Surface Finish: LeadFree HASL-RoHS
* Outer Copper Weight: 1 oz or 1.4 Mils
* Inner Copper Weight: 0.5 oz or 0.7 mils
* Material Type: FR4-Standard Tg 130-140C
* Flying Prob Test: Fully Test
* Castellated Holes: No

### Enclosure PCB

### Part B1
   * Quantity per product/order: 1
   * Thickness: 0.8mm
   * Surface Finish: LeadFree HASL-RoHS
   * Color: Red
   * Silkscreen: White
   * Material: Textolite
   * No Copper

### Part A
   * Quantity per product/order: 2
   * Thickness: 1.6mm
   * Surface Finish: LeadFree HASL-RoHS
   * Color: Red
   * Silkscreen: None
   * Material: Textolite
   * No Copper

### Part C
   * Quantity per product/order: 1
   * Thickness: 1.2mm
   * Surface Finish: LeadFree HASL-RoHS
   * Color: Red
   * Silkscreen: None
   * Material: Textolite
   * No Copper

### Part D
   * Quantity per product/order: 1
   * Thickness: 0.8mm
   * Surface Finish: LeadFree HASL-RoHS
   * Color: Red
   * Silkscreen: None
   * Material: Textolite
   * No Copper



The following operations must be performed for Babel-Babel manufacturing:

1) SMT mounting of the main PCB.

2) Flashing both Babels and [Dronecode probe](https://github.com/Zubax/dronecode_probe) on the PCB.
This operation should be performed without installing any connectors on the PCB,
a 4-pin pogo pin connector should be used instead.
Connectors' pinouts used for flashing can be found in the picture below.(Flashing process will be covered in a deperate doc)

![](figures/flashing_interface.svg)

3) After flashing is done, all the PCBs should be stacked, aligned,
and secured together using x5 2 mm diameter pins.
"Part A" PCBs should be split in two parts beforehand,
and the excessive material that interferes with USB A connector placement should be removed.
The pins can be manufactured by cutting widely available round wooden dowels 
with 2 mm diameter to appropriate length (7.7 mm).
The dowels can be purchased in general hardware stores 
or on [Amazon](https://www.amazon.co.uk/Wooden-Sticks-Round-Dowels-Natural/dp/B07T4ZFFHQ)
and other online shops.

![](figures/blow_scheme.svg)

## BOM for final assembly of Babel-Babel

| Name          | Quantity |
| ------------- | -------- |
| Main PCB         | 1 |
| Wood dowel       | 5 |
| Part A           | 2 |
| Part B1          | 1 |
| Part C           | 1 |
| Part D           | 1 |
