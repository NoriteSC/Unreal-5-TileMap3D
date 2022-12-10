# Unreal-5-TileMap3D
plugin for unreal 5 

* how to use it
	* Editor Panel and editor mode
		- there are 3 layers if u wont to onverlap tiles use layer 1 (base) and layer 2 (overlap) layer 3 (overlap)
		- on bottom there is button for adding tile slots
		- grid up and down buttons are for moving drawing plane up and down
		- grid size and rotacion increments, For now is set on ![image](https://user-images.githubusercontent.com/53096989/206863306-9be3e805-c6dd-456a-aa0e-e54364eb4d78.png)
		- placing tile select tile from grid and u should see green box following the cursor
		- remove tool press on tile and on empty space in selecion (this will change) u should see red box following the cursor
		- key Binds
      - Q rotate left by rotacion increments
      - E rotate right by rotacion increments
			- R drawing plane Up
			- F drawing plane down
	* Auto tile
		- Make new data asset look for Tile
		- Default Mesh Will show up if all tiles rules are invalid i recommend leaving it empty
		- **setting up rules**
			- there are 3 rules 
				 - extend dont (X icon)
				 - extend      (Arrow Icion)
				 - dont care   (Empty)
			- press on sqere to change state or rule
		- 3 floats fields is for tile it will be rotated by amount when places
	* StaticTile
 		- just drag end drop Static Mesh in to tile slot
 	* Stacked Auto tile
		- Make new data asset look for StackedTile
		- Stacked Tile is used to make tiles with are changing with height example: terrain , walls , rooms
		- Needs 3 tile data Assets
		- top ,bottom , middle of Stacked Tile need to have the same tile rules list in tile Data Asset, change only mesh

fair warning, plugin is not tested !!
and can change a lot
