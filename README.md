# zip2Animation
Utility to assist in creating flipper zero animations.

# PREREQUISITES
```
Python3
Zip file with your png frames
```

# USAGE
```
options:
  -h, --help           show this help
                       message and exit
  -z ZIP, --zip ZIP    specify zip file
  -o OUTPUT, --output OUTPUT
                       specify output file
  -w WIDTH, --width WIDTH
                       specify width of
                       animation
  -ht HEIGHT, --height HEIGHT
                       specify height of
                       animation
```

# Default Example (128x64)
```
python3 png2Animation.py -z Mario.zip -o Mario
```
* This will rename the frames as frames_0.. etc. and create a basic meta.txt file
  that will play the animation (as normal).

• Key note
 - the width default is 128, and the height default is 64. 
 - Specify the width and height of your animation otherwise. 

# Custom Width Height Example
```
python3 png2Animation.py -z Mario.zip -o Mario -w 97 -ht 61
```
* This will automatically change the width and height in the meta file. 
