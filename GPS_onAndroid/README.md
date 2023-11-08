HI, welcome to the selfmade README

This package is for you if you want to make locationbased Augmented Reality experiences in your neighbourhood.
In the ExampleScene you find the necessary Setup. 

Please note that for it to work you need to manually change three things:

1) Import a map of the area you want to walk around in. You can do this using Open Street Maps, export an area and 
	convert your .osm file into a .obj. Then import it to your unity projecct. Follow the instructions here: https://osm2world.org/

2) You need to manually set the GPS coodinates of your chosen Point of Reference in the PhoneManager.cs

3) It's crucial that you align the map in the editor, so the Point of Reference GameObject points to the above chosen 
	Point of Reference in the real world AND in the unity map. NOTE: The PointofReference Object needs to be at 0,0,0. To align
	move the map instead.


This package is one of three packages. Import the package "AR-GPS-Switch" if you want to move your audience using GPS and then
switch to a more detailed view in AR using ARFoundation. The third package is "Networked locationbased AR" and will be released 
in the beginning of 2024. 

This publication is made possible by the Rechercheförderung of Fonds Darstellende Künste under the name of "Vernetzte Fiktionen" 
Gefördert vom Fonds Darstellende Künste aus Mitteln der Beauftragten der Bundesregierung für Kultur und Medien.

I want to thank Friedrich Kirschner, with whom I developed all of the code during the course of the last years. <3
