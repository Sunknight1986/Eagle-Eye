# Eagle Eye
![icon-eagle-eye](https://user-images.githubusercontent.com/88772212/130043618-0f3d9ee4-57ff-43b3-9ee6-c0e91202c806.png)
## Overview 
Eagle Eye is a mapping tool to let users identify the distribution of buildings with various height: Low-rise, High-rise, and Skyscrapers in a particualr city, and how they change overtime.
## Installation
For now the Eagle Eye is still A GH definition, you don't have to install but just run it through Grasshopper.
**NOTICE:** Eagle Eye v0.2 is based on the latest plugin *Caribou*. If you are using older version, please update it otherwise Eagle Eye may not work.
## Overview of the Definition
![image](https://user-images.githubusercontent.com/88772212/134807127-92d6797b-71ca-4613-8e1b-0db7ec8c8de8.png)

*lilac groups: parameter parts that can be adjusted by the user; gray groups: please do not change it in most cases*
## Usage
*Before the text usage instruction, here is the video tutorial link Youtube https://www.youtube.com/watch?v=HQJEJkIh9ek; BiliBili https://www.bilibili.com/video/BV1G44y1872N/*

**1**, Set your API map file from OpenStreetMap here:
![image](https://user-images.githubusercontent.com/88772212/134807231-cae270ae-4287-44a9-a980-300280e2d387.png)

**Note:** in some cases, the *Extract Buildings* will remain orange after you input your map. If that happens, please reconnect the *file path* and *Extract Buildings*.

**2**, Set a rectangle for your legend bar:
![image](https://user-images.githubusercontent.com/88772212/134807410-8745fc31-a2ed-4f9e-b762-8968cfac18c1.png)
**Caution: this step will cost a relatively long time, depending on your map scale and computer.**

**3**, this part is to show the bubbles/contour/boundareis of the three kinds of buildings, recommend to use these in Top View.
![image](https://user-images.githubusercontent.com/88772212/134807487-b25feb42-9abf-41c1-b2d4-811cf12ef569.png)

**Note:** the number of Low-rise buildings is the largest in many cities, so the caulculation about this part always takes a long time. I choose to leave it unconnect, and you can reconnect it if you need. Otherwise the open time of my tool will be too long!
![image](https://user-images.githubusercontent.com/88772212/134807584-70437c98-4821-42bf-afdf-871a59256bbe.png)

## Examples of output
![Gaza City](https://user-images.githubusercontent.com/88772212/130319089-3acf6249-dbb8-48d0-b305-e00a4f6b6a7d.png)
- *Pharmacies and hospitals in Gaza city, with tall buildings higher than 10m.*



![Manila](https://user-images.githubusercontent.com/88772212/130318835-6afb4683-319c-4f27-9c4e-e3462bc8b699.png)
- *Pharmacies and hospitals in Manila, with tall buildings higher than 20m.*

## Feedback and Support
It is really welcomed to [leave your feedback and comments](https://github.com/Sunknight1986/Eagle-Eye/discussions) after using Eagle Eye, I appreciate and look forward to your advice!



**[Eagle Eye](https://github.com/Sunknight1986/Eagle-Eye) is maintained by [Sunknight1986.](https://github.com/Sunknight1986)**
