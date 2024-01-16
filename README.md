# 16-Jan-2024
https://docs.unity3d.com/2023.2/Documentation/Manual/compound-colliders-introduction.html

# 14.1.2024
Search in Unity-Ctrl-K
https://discussions.unity.com/t/cant-find-unity-quick-search-anywhere/247036

Best advice to learn Unity
https://t.co/LARBpRrOFg

# 7.1.2024
Fixing the normals after the bridge edge loops. 

Mesh->Normals->Flip
The Book is finished based on the tutorial, but the import into Unity is failed.
I can't see the textures.

Looking at the next video while waiting for the answer:
The Basics of Designing 3D Art with Blender and Unity(O'Reilly) - this was very useful. I created a book model eventually.

A new shortcut: Shift-A to add a new object in the object mode.

# 6.1.2024
Building a book continued.
Select edges and hold the Shift button, press F to fill it up
Ctrl-R for a loop cut, in the Loop and cut menu set number of cuts to 5.
TO make the curvy side of the book, select the very middle edge and enable proportional editing by presssing O from the 
keyboard

Important: change Preferences/Navigation/Orbit & Pan/Orbit Mrethod -> Trackball
G = free Translate/Manipulate (X, Y and Z to lock axis) S = free Scale/Resize (X, Y and Z to lock axis) R = free Rotate (X, Y and Z to lock axis) 

## Selecting multiple edges:
 - Tab => Edit mode
 - Shift + Click  to select multiple edges
 - Ctrl-B to bevel the edges
 - select edges - bridge edge loops - to make faces 
 - select faces - Alt-E to bring the menu - extrude along normals
 - select faces - Shift-H to hide evrything except selected faces, bridge edge loops`
 - Select the loop - Mark seam

# 5.1.2024
https://www.youtube.com/watch?v=lZaIkmRK5Gc
How to create a book in Blender | Modeling tutorial in blender
Select a cube, S - X,Y,Z to resize in only 1 direction
Tab - to get into the edit mode
Ctr-R for loop cut

# 3.1.2024
Rigid Bodies • Physics • Unity Game Development for Beginners • Unity Fundamentals • (Pt. 194)
https://www.youtube.com/watch?v=r3fkreqqEMw&list=PLS9G7A6kaaHPC__uNE0GtJTxhGmn5PS0-&index=195
Physic Materials - Unity Official Tutorials
https://www.youtube.com/watch?v=SuUNnwswH94

Mesh Collider • Physics • Unity Game Development for Beginners • Unity Fundamentals • (Pt. 197)
https://www.youtube.com/watch?v=kjTGuCns2lg&list=PLS9G7A6kaaHPC__uNE0GtJTxhGmn5PS0-&index=197
Mesh collider - 2 mesh colliders will not collide unless "Convex" property is checked. Only 255 triangles can be used.

Creating Complex Colliders • Physics • Unity Game Dev Beginners • Unity Fundamentals • (Pt. 198)
https://www.youtube.com/watch?v=lr09elWiRqo&list=PLS9G7A6kaaHPC__uNE0GtJTxhGmn5PS0-&index=198


# 1.1.2024
the Goal - to learn how to create complex colliders in Unity

## Introduction • Physics • Unity Game Development for Beginners • Unity Fundamentals • (Pt. 193)
https://www.youtube.com/watch?v=ZgbnDIxtEpc&list=PLS9G7A6kaaHPC__uNE0GtJTxhGmn5PS0-&index=194

Unity is using NVIDA's Psysx

https://github.com/NVIDIAGameWorks/PhysX/

- Rigidbodies - Non-deforming object that responds to forces, collisions and joints
- Colliders - invisible surface used to calculate collisions
- Physic Materials - Definition of physical properties stored in a modular asset
- Joints(they are called Dynamic constraints in Maya) - constraints behaviour along some axis
- Forces - Energy applied to dynamic objects:
  * Linear
  * Angular (Torque)
- Cloth (special case) Deformable object that reacts to forces & collisions
  * Interactive
  * Skinned

Important: Physics ---> Performance
- Scale ==> 1 Unit = 1 Meter
    


