# Computer Graphics Final Project
## Michelle Ma

My goal for the final project is to extend the medh editor to include some of my favorite tools in Maya. These tools include:

**Additional Selection Modes**

1. Multiple vertex, edge, and face selection (holding shift and selecting multiple components)
![Multiple Selection](https://github.com/michell3/graphics-final/blob/master/Screen%20Shot%202016-12-05%20at%201.54.09%20PM.png?raw=true)

2. Selection along a loop (mostly for quad meshes, select a vertex/edge/face and then shift double click an adjacent vertex/edge/face to get the whole loop)
![Loop Selection](https://github.com/michell3/graphics-final/blob/master/Screen%20Shot%202016-12-05%20at%201.54.28%20PM.png?raw=true)

3. Expand/reduce selection to surrounding faces (select a face and then hold '<' or '>' to increase or decrease the range of selection.

4. (Bonus) Soft selection (selecting a vertex/edge/face and then using a radius and dropoff parameter to extend the selection influence to the surrounding attributes)
![Solft Selection](https://github.com/michell3/graphics-final/blob/master/Screen%20Shot%202016-12-05%20at%201.55.55%20PM.png?raw=true)

**Additional Atomic Editing Operations**

1. Insert edge loop (mostly for quad meshes, select a point along an edge to insert an edgeloop)

2. Extrude multiple faces
![Extrude Faces](https://github.com/michell3/graphics-final/blob/master/Screen%20Shot%202016-12-05%20at%201.54.53%20PM.png?raw=true)

3. Fill hole (select a faceless edgeloop and insert a face)

**Other Features that I love but am less sure about how to implement**

1. Mirror Geometry - Duplicate the geometry accross a certain axis and merge vertices that overlap
![Mirror Geometry](https://github.com/michell3/graphics-final/blob/master/Screen%20Shot%202016-12-05%20at%201.57.11%20PM.png?raw=true)

I hope to implement these features in this order so that I can model a character, delete half of the mesh, and then mirror the remaining half to get a full symmetrical model.
