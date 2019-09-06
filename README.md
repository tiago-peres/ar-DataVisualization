# AR Data Visualization

![Result](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/end.png)

In this project work, I will:

+ Create a 3D data visualization model

+ Create a simple AR app that will show a 3D data visualization model through your smartphone camera when you point it at a special "target" that you'll print out.

For this project, we will need an Android device running 4.4 or above, or an iOS device running 9 or above.

I've gone through similar procedure as in [AR Robot](https://github.com/tiago-peres/ar-robot) except in this case I had to create a 3D model.

The model started with the following sketch using pencil and paper

![Sketch Data visualization model](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/sketch.jpg)

Then using Adobe Ilutrator I've done the following 2D

![2D Data visualization model](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/2D.png)

And using Cinema4D the following 3D model was created to use in the project

![3D Data visualization model](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/model.png)

Then I had to extract as .fbx and then import [graph.fbx model](https://github.com/tiago-peres/ar-DataVisualization/blob/master/model/graph.fbx) in Unity 

When i imported into Unity using drag and drop, I got the following result

![3D DataVis model](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/1.png)

As we can see from looking at the Inspector (image above) the material is grey and can't be edited. The materials of the default assets cannot directly be edited but there's a way to go around it.

I've created a new material (right click in assets > Create > Material)

![New Unity material](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/2.png)

Gave it a new name (green) and changed Albedo to green.

![New Unity material albedo](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/3.png)

And dragged the material to the cube

![Cubes's color](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/4.png)

The end result now looks like expected

![End result](https://github.com/tiago-peres/ar-DataVisualization/blob/master/imgs/5.png)
