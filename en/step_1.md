## The Unity Terrain object

You can create a terrain in Unity to provide a more interesting environment than a flat plane.

- Right-click in the Hierarchy window, select **3D Object** and then **Terrain**.

![Terrain object selected from the 3D Object menu.](images/create-terrain.png)

- In the Inspector, select the paint brush tool and then **Raise or Lower Terrain** from the drop-down menu.

- You can raise the terrain by left-clicking, or lower it by holding down shift and clicking. Changing brushes will change how the terrain is drawn.

![The terrain object with different heights.](images/terrain.png)

- Clicking on the gear icon will allow you to add a material to your terrain.

![Grass material selected for the terrain.](images/terrain-material.png)

- Clicking on the tree icon will allow you to paint trees onto your terrain. Click on the **Edit Trees** button.

![Edit trees button highlighted in the Inspector.](images/edit-trees.png)

- Click on **Add Tree** and in the window that opens use the circle button to add a tree from your assets.

![Add tree button selected and a tree chosen.](images/add-tree.png)

- Use the brush to paint trees onto your terrain.

![Trees added to the terrain.](images/trees-terrain.png)

**Tip:** Adding a large terrain can slow down the processing speed of the game. To reduce the size of your terrain GameObject, naviagate to the 'Mesh Resolution' component and change the width, length, and height values. 

![The Mesh Resolution component with the Terrain Width, Terrain Length, and Terrain Height all set to '100'.](images/mesh-terrain.png)
