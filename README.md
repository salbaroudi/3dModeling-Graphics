## Introduction:

Simple folder that contains my progression with Blender Modelling and Animations. I focus first on realistic modelling, moving to Animations for the second stage.


## Modelling Shortcut Keys:

- Translate Object: G + [xyz]
- Scale Object: S + [xyz]
- Rotate Object: R + [xyz]
- Pan View: Shift + MW
- Zoom in on Object: LC + Number Pad "."
- Orthogonal and Oblique Views: Number Pad 0-9
- Rotate Scene: MW
- Duplicate: LC + SHIFT + d
- Apply Scale: LC + CTRL + A -> Set Scale
- Object Properties: LC + N
- Shade Smooth: RC Object, Select Shade Smooth
- Switch between Edit and Object Mode: TAB
- Toggle Proportional Editing: o
- Select Connected Nodes/lines: CTRL + L
- Extrude: LC Object + E
- Toggle X-Ray: ALT + Z
- Select Edge Loops: ALT + LC

### Modifiers:
- Added with the Wrench Button.
- They are added in chains - ordering in which they apply can be manipulated.
- To finalize modifiers, you apply them. You cannot undo this.


### Meshes:
- Once a mesh is generated, a properties box appears. You must finalize properties before clicking out.
- If you click out...you can't go back to the init properties. 
- To add more points after the fact - applly a subsurf modifier and increase the middle points.

### Geometry and Shading Nodes:
- Are applied Left to Right.
- Boxes represent complex functions with many inputs outputs.
- To use a scene mesh/object, drag from the RHS menu into the Node area. A Properties box will auto-appear.

##Quirks with Linux:
- When selecting mesh points, or applying texture paint, linux has a habit of getting mixed up with surface normals.
- The result of this is that points at the front and back get selected.
- If you want this to happen, switch to X-Ray mode, and use an orthographic view to grab all points.
- If you don't want this to happen, go to mesh/surface properties, and "recalculate normals".
   - This can be done by selecting the mesh, and pressing ALT + N.

:
