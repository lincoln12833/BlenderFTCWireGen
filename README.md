# BlenderFTCWireGen
A blender geometry node group to make modeling wires a whole lot easier

## Setup
### step 1:
Open up wireGen.blend and there will be a couple objects; a Bezier curve, a camera, and a connector basic. The connector is attached to the end of your wire and then duplicated for the number of wires. You can attach the wire generator to any bezier curve. You will want to do this now to get aquainted with the process.

1a: Create a new bezier curve, then go into modifiers and click add modifier. Next you will click geometry nodes and then create new (this file already has the required geometry nodes, so if  you want to just mess around with it for a while you could, but I highly recommend setting it up at least once before going into a real project). Next you will need to open up a geometry nodes window (I like to change the timeline into mine). With this new window, you will need to add in a group called wireGenWorkingWithScale (I know there are a lot of groups, im sorry I can't find a way to remove them ).  
1b. Next you need to attach the group into the middle of your output and input. Attach the amount sockets together, then the wire number sockets. Open up the modifiers panel and click output attributes. You then need to write in the input box wireNumber (I know it looks a little redundant, but it is neccasary).

### step 2: 
