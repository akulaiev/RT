# RT
Take on the previous RTv1 project with lots of added, more advanced features. Because RT is a group project, below are listed only the bonuses, implemented by me.

# Project features
• Ambiance light

• Reflection

• Transparency

• Advansed figures : cube, elliptic paraboloid, hyperbolic paraboloid, ellipsoid, toroid

• Skybox

• Screenshots


<p align="center">
<img src="https://github.com/akulaiev/RT/blob/master/demo.png" width="350">
</p>

# Running
To compile the executable, use Make. Then run it with one of the test files with .scene extension in the "scenes" directory, located in "src".
```
Usage: ./RT src/scenes/scene_name skybox_number
```
If the number of skybox is not selected, the default one will be shown. To elimit skybox, use '0' as a skybox number parameter.

# Controls
- Use arrows, to move the rendered objects;

- Use '+' and '-' to change the size of the objects;

- Use 'w', 's', 'a' and 'd' keys to rotate the camera;

- Use 'Q' to create a screenshot, which will be located in the "screenshots" directory.

