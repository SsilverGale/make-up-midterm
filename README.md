# Shader 1: Reflection

<img width="1227" height="597" alt="image" src="https://github.com/user-attachments/assets/41d8ac99-7241-49c2-b420-296f05aee535" />
This was my last shader so it was very rushed. Pretty much copying course content

# Shader 2: Texture and tiling

<img width="1181" height="552" alt="image" src="https://github.com/user-attachments/assets/9dfa1188-4e18-40e7-bd45-b32b036eadf7" />

This was the lava of my project. I set up a tiling and offset node into my shader graph and also added a texture. For a little bonus I made it scroll with time

# Shader 3: Multiple UVS

<img width="1056" height="531" alt="image" src="https://github.com/user-attachments/assets/ab0d8844-fe36-47a1-8fcb-bd87844a664f" />

For this I made a shader that's supposed to make the toad look like he's blicking by swapping back and forth
between two different UVs. One where his eye texture is while and another where it's his skin tone of yellow

# Shader 4: General Purpose

<img width="1331" height="767" alt="image" src="https://github.com/user-attachments/assets/752fb179-5b9e-4351-ad5e-0ce9a893d8f0" />

While trying to think of something that is general purpose, I though about substance painter and how it exports maps together as 1 condensed map
so I made a lit shader that takes the inputs the substance painter outputs as well as adding a noram map into the mix. On top of all that I made it 
tilable and all 3 maps using the same UVs

# Shader 5: Lighting toggle

<img width="1790" height="887" alt="image" src="https://github.com/user-attachments/assets/9e25a184-ba46-45f4-a124-a025af2e2cd6" />

Here's my lighting. The specular is straight from the slides but the diffuse uses the light direction node istead of and HLSL.
The Ambient was based off a graph I found while studing where you learp beatween different ambient node outputs depending on the normal vector
sadly I did not getting it working properly this time. The toggles use branch nodes to either add 0 or add the lighting data dpending on a boonlean

# Shader 6: Bonus Shader of your choice

<img width="1452" height="411" alt="image" src="https://github.com/user-attachments/assets/52cd829f-37fc-4b75-8055-87c4a4749f7e" />

I've done quite a few sine time vertex shaders now so I chose to stick in my comfort zone. The brdge moves back and forth on the y-axis(which since it's a blender 
model means depth) using sine time. With variables for the speed and distance.





