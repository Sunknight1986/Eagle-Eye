# Eagle Eye
![icon-eagle-eye](https://user-images.githubusercontent.com/88772212/130043618-0f3d9ee4-57ff-43b3-9ee6-c0e91202c806.png)
## Overview 
Eagle Eye is a mapping tool to let users identify the distribution of 1) **Tall buildings** (you could choose to filter by height or level)and 2) **Infrastructures**(Only Hospital and Pharmacy currently) in a particular area, based on the metadata from OpenStreetMap.
## Features 
- Fast cuculating speed
- Could be used in many areas in the world(only limited by the data from OpenStreetMap)
- Visually display the information you need
- Frequent update
## Installation
For now the Eagle Eye is still A GH definition, you don't have to install but just run it through Grasshopper.
## Overview of the Definition
![Overview of the definition](https://user-images.githubusercontent.com/88772212/130322835-88167083-091c-4917-8caf-e9b41a941667.png)
*light green groups: parameter parts that can be adjusted by the user; gray lilac groups: please do not change it; blue group: an optional part for users to adjust.*
## Usage
*Before the text usage instruction, here is the video tutorial link https://www.notion.so/Video-Tutorial-of-Eagle-Eye-389c9f69a0924bb1a3167b97ea745505*

**1**, Set your API map file from OpenStreetMap here:
![set the map file](https://user-images.githubusercontent.com/88772212/130316109-0482bb8c-5273-4f17-84a3-9e74f48e8576.png)
Now it should show the lines connection of high-rise buildings but no geometries for hospitals and pharmacies. Don't worry, we have another move to show this part:

**2**, Set a rectangle in this component to cover the region you want to see the distribution of these two facilities:
![set the boundary](https://user-images.githubusercontent.com/88772212/130316429-cbba50ee-8416-4fe3-abc4-26971d833792.png)
**Caution: this step will cost a relatively long time, depending on your map scale and computer.**

**3**, Now we have almost done, the rest is to adjust the parameters to make the output to your satisfication.
## Examples of output
![Gaza City](https://user-images.githubusercontent.com/88772212/130319089-3acf6249-dbb8-48d0-b305-e00a4f6b6a7d.png)
- *Pharmacies and hospitals in Gaza city, with tall buildings higher than 10m.*



![Manila](https://user-images.githubusercontent.com/88772212/130318835-6afb4683-319c-4f27-9c4e-e3462bc8b699.png)
- *Pharmacies and hospitals in Manila, with tall buildings higher than 20m.*

## Feedback and Support
It is really welcomed to [leave your feedback and comments](https://github.com/Sunknight1986/Eagle-Eye/discussions) after using Eagle Eye, I appreciate and look forward to your advice!



**[Eagle Eye](https://github.com/Sunknight1986/Eagle-Eye) is maintained by [Sunknight1986.](https://github.com/Sunknight1986)**
