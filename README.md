# Curtain-Opener-3D
This repo will contain all the CAD files for a case to hold a stepper motor a microcontroller and a custom PCB to control the opening of curtains

The PCB can be skipped and parts from it soldered with wires if needed.

PCB repo: [gwoolger/Curtain-Opener-PCB](Https://github.com/gwoolger/Curtain-Opener-PCB)

This is the style of curtain cord it will work with. Essentially a curtain where it can replace the curtain tensioner.

![Curtain cord image](images/Curtain_Cord.png)

---
This is the Stepper Motor that I am designing for. Decided to go for a Nema 17 pancake for its cheap price, and easyness to source. As well as being small but fairly powerful.

![photo of stepper used](images/stepper.png)


## The Design

![cad design - fusion 360 section analysis](<images/Screenshot 2026-10-14 204101.png>)
![cad design](<images/Screenshot 2026-10-14 205306.png>)

## Repo layout

in 3d_models\
 - Original Fusion 360 file
 - .step files for each printed part

## Parts
The CAD models are designed for M3 screws, with space for threaded inserts. Female ends currently sized for gluing inserts into jlc3dp resin prints as opposed to fdm.


## BOM
| Item | Qty | Supplier | Cost/item | Total Cost | link |
|---|---|---|---|---|---|
| 3D prints | 1 | JLC3DP | $23.11 | $23.11 | [JLC3DP](https://jlc3dp.com) |
| Misc hardware | 1 | Aliexpress | $4.79 | $4.79 | [Aliexpress](https://aliexpress.com) |
| Estimated total shipping | 1 |  |  | $0.00 |  |

Have included shipping in the vendor prices, as otherwise unclear to which vendor shipping is attributed to.

Aliexpress parts listed here with rough prices as they fluctuate a lot - and are generally cheaper with deals
- 608zz bearing $2
- 50pcs M3 threaded inserts kit $3

## BOM description
- bearings to provide shear support for the stepper - it's a pancake, so doesn't have the strongest shaft
- threaded inserts that I can glue in - as it'll be a resin print, so can't heat up. I think I've already got M3 screws.
