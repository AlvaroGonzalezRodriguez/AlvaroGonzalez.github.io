---
title : Motores y sistemas de desarrollo para videojuegos' landscape
feed: show
date : 18/01/2023
---

# Landscape MSDV.
## Author: Álvaro González Rodríguez
alu0101202556

## About this project.
<p>This is a test to check the power and the limitations of Unreal Engine 5. I mainly use the landscape and foliage mode to create this level. There is also a litthe house just to check how the lights and reflections work in this engine.</p>

 * The player

![Alt Text](../assets/img/player.png)
<p>I reuse an asset that i used in the past. It is my interpretation of Megaman Exe! I created him in Blender with some basic animations. To make it move I use the third-person controller from Epic Games.</p>

 * The landscape
 
![Alt Text](../assets/img/landscape1.png)
<p>There are three sections. The first one is the section where the player spawns. In this section we can see a los of green vegetation, tall trees and a road. If the player follows the road he could see how the road divides in two. The second section is where the house is located. In this one there isn't a lot of foliage and is set in a more winter look. Then we have the third section, when the vegetation have a orange color and the trees aren't as tall.</p>
<p>With the landscape mode, using the sculpt tool, I put all of the mountains, ramps and the limitations of the map. With the paint tool I created 5 layers of materials, one for the grass, other for the road, the mountain, the snow and the forest floor.</p>

![Alt Text](../assets/img/landscape2.png)
<p>This is the initial section!</p>

![Alt Text](../assets/img/landscape3.png)
<p>This is the mountain section!</p>

![Alt Text](../assets/img/landscape4.png)
<p>This is the last section!</p>

 * The ambient

![Alt Text](../assets/img/ambient1.png)
<p>Using a directional light, exponential height fog, sky atmosphere, sky light and volumetrics cloud we can archieve a great level of realism. All of this elements need to be check as movable. I also use a plugin to make the coulds more realistic, it's name is "Volumetric". If you enable it, you can change the materials of the clouds to a more realistic one.</p>


 * The foliage
 
![Alt Text](../assets/img/foliage.png)
<p>I used a package from the Unreal Marketplace to add almost all of the vegetation. The foliage mode is very straightforward, I just needed to move the meshes that i want to add all over my landscape into the foliage section. This will create some assets prepared to be added to the terrain. I was very cautious about not putting too much to make my PC run smoother while making all of the vegetation look harmonious.</p>
 
 * The house

![Alt Text](../assets/img/house1.png)
<p>I used some assets from Bridge to make it more realistic. There is a door that opens when the player approach it, here is the blueprints node to accomplish that.</p>

![Alt Text](../assets/img/house2.png)

![Alt Text](../assets/img/house3.png)
<p>And this is how the inside looks like! It looks a bit abandoned, there is a table, some chairs, a light, some decorations, and... two strange items. The purpose of one of them is just to check the reflections of the room, while the other one will brighten when the player interacts with it and then the special item will show some hidden signs in the scene that will guide the player to the end </p>

![Alt Text](../assets/img/house4.png)

![Alt Text](../assets/img/house5.png)
<p>This is the blueprint who manages how the player can interact with the special objects</p>

![Alt Text](../assets/img/houseSpecial.gif)

![Alt Text](../assets/img/house6.png)
<p>That's the capsule who will end the game</p>
<p>And this is the presentation of the project. Take a look! </p> 

[Presentation Landscape Project](https://youtu.be/Chg_hnpTLpM)