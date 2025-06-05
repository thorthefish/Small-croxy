## High Speed Prototyping Printer
Author: ryan d

Description: A high speed, small form factor, crossed gantry 3d printer on a mostly printed frame

Created: 6-2-2025


# 6-2-2025

## 3 hours

I spent today just scetching my idea and getting the main concept down, and getting a rough idea of what materials i could use. I decided on going with rails over rods on the gantry because that has a super high potential for getting way out of alignment and also they are much easier to mount.

Overall today was just a bunch of planning, and figuring out what parts would be suitable.

I decided to go with:
- V6 hotend (trianglelab)
- BMG extruder (clone)
- mgn9 200mm rails (robotdigg)
-linear bearings (igus)
-steppers from voron trident BOM (never picked these before, and vorons work sooo)
-  120mm buildplate (voron 0?)
- BTT spyder
- a laptop (klipper)

(sorry no pics this was all mental)

# 6-3-2025

## 9 hours

A full day of CAD. I started with getting the outer gantry assembled, with the motor mounts comming first, and once i gad those down I added the linear rail supporting pieces, to help them maintain their rigidity. Then I Mirrored everything to the bottom to get the lower structural members done.

![image](https://github.com/user-attachments/assets/203d743c-13d3-41c3-b996-72c5f6bda4da)

The Main side braces are a little small, but they should be plenty, especialy on a bit higher infill, maybe even as high as 50%. Other than that the design is sparse but should be able to handle realitively high speeds, especialy because the plastic structural will have little to no ringing so input shaping may not even be nessisary. Also the design is conviniently modular(besides for the bed) so I can continue development later on if this is sucessful.


![image](https://github.com/user-attachments/assets/da6b65d9-d54c-45c3-8b65-7fba59d6c7fd)

The budget for this will be a bit tight, but with liberal applications of printed parts it will be managable, so the BOM doesnt need a ton of work after this. The parts are just about as cheap as I could get them, and I think the overall cost is reasonable(esspecialy for cross gantry). I will have to find some filament somewhere else for all of this, and borrow a soldering iron and other such supplies.

I also pitched the project in slack (later found out this was not nessisary but was nonetheless helpful) and I got some great advice on improving the design.
![image](https://github.com/user-attachments/assets/67dd3ba9-9855-4d6f-ade2-015616e98534)

# 6-4-2025

## 5 hours

Polished CAD, got some final parts modeled such as the bowden extruder mount. I just put it at the top on one of the corner motor mounts for simplicities sake because it was as close to the printhead as I could get and realisticaly wont add much weight. It was super important to get it as close to the printhead as possible for the extrusion quality, and also to be as rigid as possible to act as an umbilical cord for all of the other wires that need to run allong to the printhead such as heaters and cooling.

![image](https://github.com/user-attachments/assets/aa0fe17c-8c74-4ef2-a69f-ea092fa92ac2)


I also decided to Add on some 2020 200mm extrusion after a helpful conversation on slack to help with the riggidity of the printer and to make assembly that much easier. I went with some cheap stuff off amazon as thet was the best price I could find, and precision id not super important here, just making sure that the printer doesnt wobble to much.

![image](https://github.com/user-attachments/assets/fb4199af-f659-4dd8-b85c-d7c5d2c61b8c)

Worked on Github page. README is looking good and all requirements are met.

Submitted, and waiting.

# 6-5-2025
## 3 Hours

Just spent today working of the journal, getting more pictures in and all that.

I also spent some time thickening the cross supports, so that there would be less flex in the system. These parts just attach with bolts, but should be plenty rigid on account of three surfaces of contact, they should stay in place plenty well.

![image](https://github.com/user-attachments/assets/779097a2-3534-4c88-8cb4-39093a02735e)

All of the parts will be printed in pla which is kinda trash for this but its the only thing im confident in printing on my old ender 3, so its what ill have to work with untill I get an enclosed printer, but all said, it should work well enough for a low temp and small printer such as this one.

Also after putting some thought into how to mount the electonics... im gonna worry bout that later cause this cold has killed my abbility to cad pretty much.

