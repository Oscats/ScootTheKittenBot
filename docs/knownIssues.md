# Known Issues

This is ultimately a test for us. Thus far, we are pleased, but there are still some things we are working through.

-The Chassis: We are not experienced in printing multi-piece items. So, when we designed the tongue and groove construction for the chassis we left a bit of space (way too much) for PLA expansion. This was a mistake. This issue was easily overcome by putting a few bolts in specific places.
- The code. We are using a modified version of Rev's code. This is working generally, but there are a few inconsistencies with field relative driving and trajectory path following. However, this is why we built this robot: to work through some of these challenges.
- Current: To build such a small robot, we needed to use a smnall battery. The Studica battery we are using is a 12 volt, 3 Ah battery as opposed to the 12 volt, 18 Ah battery. In theory, this is fine because the robot is so light, it does not need the full power of these motors, but without current- limiting (or some very cautious driving), the motors will still take way more juice than this battery can handle. With current-limiting, it is fine.
- Rev calibration jigs: The calibration jigs only mostly fit on one of the sides without removing the module from the robot. For us, the mostly fit seems fine thus far. Also, we did not know that the jig is made to turn one wheel 45 degrees from the other. Once we figured that out, it worked quite well.

