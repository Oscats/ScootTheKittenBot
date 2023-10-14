

# Scoot: The Kitten Bot

===============================================

<iframe width="560" height="315" src="https://www.youtube.com/embed/bEF0AGFgYwE?si=UNsT_K8FBAAk4sSv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Why did we make Scoot?

Inspired by many mini bots that the team and it's mentors have interacted with over the years, Scoot was developed for team 6762 as a minimal entry point to explore the feasibility of a swerve drive for a robotics in-season bot.

## What is Scoot?

Scoot is a robot with a 3d printed chassis that uses 2 of Rev's swerve modules and a full FRC control system. This way, the team can experiment with many season-legal swerve libraries, or roll their own (we are definitely not ready for this). This also allows a team to purchase only two modules versus the 4 a typical swerve bot has.

## Why only 2?

Swerve is expensive. Four Rev Swerve modules costs ~2282.50. That is a large investment for a design that may not be a good fit for a team. This solution allows a team to dip their toes in the waters of swerve relatively inexpensively.

## How much will this cost?

We do not have a full BOM yet, but the general estimate is below.

### The price of each swerve module, motors and controllers...

Number | Item             | Price | Desciption 
-------|------------------|-------|------------
1      |Rev Swerve Module |305.00 |this comes with the Rev Through Bore Encoder We purchased the plastic ones for testing, and the aluminum for competition. There is a known issue with the v1 plastic wheels. 
1 |Neo (no pinion) |52.00|	
1 |Neo 550 (no pinion) |29.50|	
2 |Spark Max| 92.00|	
  |Total   | 570.50

  
### Total General Cost


Number| Item| approximate cost of the number listed
-------|------------------|-------
1| 1Full FRC Control System: Radio, PDP/PDH, POE for Radio, Rio 1 or 2, RSL, | ~950
1| Optional: We substituted the [Rev POE cable](https://www.revrobotics.com/rev-11-1210/) for the Rev Power Module. This is not tournament legal, but is working for us.|11.99
1| Optional: Small PDP. We used [this one from Amazon](https://www.amazon.com/gp/product/B0B5TTTPM2/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)| 19.99
1| Optional: 12Ohm terminating resistor. If you substitute the PDP, you need a terminating resistor for the Can Bus.| .15 at Digikey, 5.00/3 at Amazon
 |18 Gauge cable for the RSL| 11.99
 |12 Guage cable for all motor and power connections| 12.98
 |22 Guage cable for the rio and CAN | 10.48
 |cable connectors We used Anderson for the battery and Wago for all other power connectors molex/ dupont for CAN | 35.00 for 50; more than you need for this project
2 |swerve modules | 1141
  |Ring or hook Connectors for our PDP| 14.99 
~801.81 g |3d Fillament| 11.99
   |Fasteners for control system (we used velcro)| 7-20 depending on the brand and length
 4 |#10 bolts for the swerve modules and securing the base| 5.00
 1 |2 inch Swivel Caster; We used [this one](https://www.homedepot.com/p/Everbilt-2-in-Gray-Rubber-Like-TPR-and-Steel-Swivel-Plate-Caster-with-Locking-Brake-and-90-lb-Load-Rating-4035245EB/203672390) because we had it in our shop, but one [without a brake](https://www.homedepot.com/p/WEN-2-in-110-lbs-Capacity-Rubber-Single-Bearing-Swivel-Plate-Caster-4-Pack-CA2112W/314272694) would be even better | 7.50
1 |Limelight or other targeting camera, Optional| 200 - 400
1 |battery; We use one of the [Studica batteries](https://www.studica.com/studica-robotics/12v-3000-mah-nimh-battery-pack-pp45)|44.99
  | Total| ~2303.05

That sounds like a lot, however, other than the swerve drives themselves, we were able to source all of the materials from team stock. So, for us, it cost us clocer to $650.00. Many of the materials are also reuseable. Another aspect of the design is that you could use scoot as the control board for a full-size bot with four swerve modules.
## CADD
![ScootCaddImage](https://github.com/Oscats/ScootTheKittenBot/assets/25676667/99e06826-f81f-4707-afcc-7719149f3de2) (https://cad.onshape.com/documents/dc911cfa8b3dccdac654b76b/w/eddf5a90f3b74427297dde25/e/3c74e6053ab6216a8b7a64ff)


[View our Cadd on onshape](https://cad.onshape.com/documents/dc911cfa8b3dccdac654b76b/w/eddf5a90f3b74427297dde25/e/3c74e6053ab6216a8b7a64ff)

### Changes that have not made it into our CADD designs

- We are using the Amazon PDP and terminating resistor because it is smaller
- We put the PDP under the chassis to allow more flexibility on top

# Some images of our current bot

![PXL_20231006_200813674](https://github.com/Oscats/ScootTheKittenBot/assets/25676667/65e40264-05c8-49a1-a590-c94464d73de7)
![PXL_20231006_200752239](https://github.com/Oscats/ScootTheKittenBot/assets/25676667/2938ea18-248b-4b28-8c16-43b676c40482)


