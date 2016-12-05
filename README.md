# Computer Graphics Final Project
## Michelle Ma

My goal for the final project is to extend the medh editor to include some of my favorite tools in Maya. These tools include:

**Additional Selection Modes**
1. Multiple vertex, edge, and face selection (holding shift and selecting multiple components)
2. Selection along a loop (mostly for quad meshes, select a vertex/edge/face and then shift double click an adjacent vertex/edge/face to get the whole loop)
3. Expand/reduce selection to surrounding faces (select a face and then hold '<' or '>' to increase or decrease the range of selection.
4. (Bonus) Soft selection (selecting a vertex/edge/face and then using a radius and dropoff parameter to extend the selection influence to the surrounding attributes)

**Additional Atomic Editing Operations**
1. Insert edge loop (mostly for quad meshes, select a point along an edge to insert an edgeloop)
2. Extrude multiple faces
3. Fill hole (select a faceless edgeloop and insert a face)

**Other Features that I love but am less sure about how to implement**
1. Mirror Geometry - Duplicate the geometry accross a certain axis and merge vertices that overlap

I hope to implement these features in this order so that I can model a character, delete half of the mesh, and then mirror the remaining half to get a full symmetrical model.
