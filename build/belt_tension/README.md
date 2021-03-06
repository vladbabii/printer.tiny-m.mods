Wrench is a cut up version of https://github.com/gsl12/Tiny-M/blob/master/usermods/Xile_Mods/Tensioning_Wrench/Knob_Wrench.stl since the full sized one can't be used when the top panel between motors is already screwed in place. All credit for the wrench goes to that mod author.


According to http://benchtopmachineshop.blogspot.com/2019/04/printer-belt-tension.html
the correct tension in hertz is 28531 / mm

If we pluck the belts in the back of the printer, the tension should be 28531 / 283 = 100.8 hertz

Steps
1. unscrew motor screws so it can slide
2. slide motor all the way to the outside of the frame
3. open spectroid app
4. pluck the belt
5. tighten the tensioner with the tool
6. repeat 4 and 5 untill 100.8 hz is reliably detected by the app

It's more important to have the same hz on the two belts than to have it equal to 100.8. For example it's better to have both at 100.7 than one at 100.7 and one at 100.8


for top belt just touch the belt a little and move from right to left

![pluck top belt](https://raw.githubusercontent.com/vladbabii/printer.tiny-m.mods/main/build/belt_tension/pluck_1.png)

for bottom belt insert the wrench so not to touch the top one right to left

![pluck bottom belt](https://raw.githubusercontent.com/vladbabii/printer.tiny-m.mods/main/build/belt_tension/pluck_2.png)

to tighten/loosen the belts just rotate the know with the wrench

![set tension](https://raw.githubusercontent.com/vladbabii/printer.tiny-m.mods/main/build/belt_tension/tension.png)
