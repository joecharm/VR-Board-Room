# VR Board Room

## Features
* Ability to walk around the scene with the VR controllers
* Collision on objects
* Custom PBR Assets

I have designed the VR Board Room experience to be an open and bright environment, perfect for meeting others. The area has been split into two primary sections, with the first being a large open outdoor area and the second an open plan building featuring a bright room. I made the decision to not add a roof as this could make some users feel claustrophobic, this is important if users are meeting for a long period of time.

To enhance the aesthetics of the scene I have added custom created 3D assets. The cabin helps to create a pleasing back-drop to the scene, being surrounded by vegetation and fences this helps to create an outdoor atmosphere. The bench helps to separate the large outdoor area and the positioned benches act as an informal meeting place. 

![Image of Scene](https://raw.githubusercontent.com/joecharm/vr-assignment2/main/Images/Unity%20Scene%20Image%201.PNG)
![Image of Scene](https://raw.githubusercontent.com/joecharm/vr-assignment2/main/Images/Unity%20Scene%20Image%202.PNG)
![Image of Scene](https://raw.githubusercontent.com/joecharm/vr-assignment2/main/Images/Unity%20Scene%20Image%203.PNG)

## 3D Text

Despite the world being designed to lead the user to all areas, I added 3D text to implement further guidance. This feature is used to inform the user that the board room is at the top of the stairs, there is also a message that displays in the board room to add character to the room. This feature was added using the TextMeshPro tool.

To ensure accessibility with this feature I ensured the text was a contrasting colour to that of the surface it was on. This white on grey contract allows the text to be visible from far away and at lower resolution, which is important in Virtual Reality. I also ensured that the text font was large, if the text were too small this would make it difficult to read and detract from the overall Virtual Reality experience.

## Terrain Smoothing

![Terrain](https://raw.githubusercontent.com/joecharm/vr-assignment2/main/Images/Unity%20Scene%20Image%204%20-%20ground.PNG)

I used ProBuilder to create the terrain for the user to spawn on and explore. I used the toolset provided by ProBuilder to create a unique ground shape, as well as increasing the height of the perimeter to add immersion. For a realistic terrain effect, I used the edge and face select tools to manipulate the edges, faces and vertices creating a non-exaggerated ‘bumpy’ environment.

After creating this realistic terrain effect, I noticed that my manipulations created shading issues on some faces. The issue was being caused by the directional light bouncing off the surfaces at different angles. To counteract this, I used the smooth tool from ProBuilder. I first selected the faces displaying the shading issues and applied smooth shading.
After applying this to the environment it was pleasant to walk around and look ahead at eye level, I ensured there were no shading issues on the ground to avoid breaking the immersion. 


## Releases
<br>
Latest release V1.0.0
Tested on the following hardware: 

* Intel Core i7-7700 CPU @2.8GHz
* 16GB RAM
* GTX1070
* Acer Windows Mixed Reality VR Headset

<br>

[Download V1.0.0](https://github.com/joecharm/vr-assignment2/releases/tag/V1.0.0) 

[![DOI](https://zenodo.org/badge/302613857.svg)](https://zenodo.org/badge/latestdoi/302613857)
