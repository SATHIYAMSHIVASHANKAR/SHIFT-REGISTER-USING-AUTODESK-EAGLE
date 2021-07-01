# SHIFT-REGISTER-USING-AUTODESK-EAGLE
DEVELOPING SHIFT REGISTER USING IC 74595 IN AUTODESK EAGLE
***
step 1: In Autodesk Eagle, create a new project under the project sector. Name the file as Shift Register. Now under Shift Register create a Schematic file.
***
step 2: Allocate nessasary grid lines value in the grid section such that the editor page comes with the sutable grid lines
***
step 3: Using Add components tool, take the required parts and place it in the schematic with refernce to the circuit diagram. 
***
step 4: In order to reduce the complexcity in wire connection, introduce bus connection using Bus tool.
***
step 5: In Bus connection, it is mandatory to give Alias name and the Specification. Through this we can connet the Net (wire) conection at ease.
***
step 6: Now connect the components in the schematic using Net tool. 
***
step 7: Refer the data sheet to allocate the values to the components by using Value tool.
***
step 8 Its is mandatory to create a Net class for the ciruit made in Schematic. Create a net class, name it as Power and add the nessasary values to the Member section. Enter the respective terms to Default and Power sections.
***
step 9: To frame the entire circuit, select a Frame of your choice in Add components tool, place it around the circuit in schematic.
***
step 10: Now create a board, such that the diamentions of the board must be 80*60 mm
***
step 11: Move the components into the board and route the components using Air Routeing tool.
***
step 12: Select Polygon tool and extend its strech to the entire board. Name it as Ground. Now by appling Ratsnest tool, the polygon (ground) gets activated.
***
step 13: To give the name to board use Name tool. Enter the appropriate name and place it on the board with the Name Layer activated.
***
step 14: Drill four holes in each corner using Hole tool. By accessing Manufacturing tool we will get to know about the completed PCB board.
***
