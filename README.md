# FlyinDiamonds

## General rules

For objects that you want to plan transitions, you need to ensure the exact number of vertices, such as drones
Be careful, the vertices must not overlap

Minimum distance for transition must not be greater than 70% of the smallest distance between two vertices in mesh.
For example - if I want to keep a drone distance of 2 m for a transition, I have to keep the vertexes at least 2.9 m apart.


## Frames

### Frame duration
- calculates given number of frames starting with your current frame

![Frame duration](gifs/frame_duration.gif)

### Frame range
- calculates frames in selected range

![Frame range](gifs/frame_range.gif)

### Frame step
- number of frames to step over during calculation
- can be used to control intensity of blinking with selecting random drones or for better performance with selecting by mesh

![Frame step](gifs/frame_step.gif)

## Colors

### Color pallete
- color pallete for quick access to often used colors

![Color pallete](gifs/color_pallete.gif)

### Color picker
- color picker for ather colors

![Color picker](gifs/color_picker.gif)

### Color transition
- two pickers to calculate color transition on

![Color transition](gifs/color_transition.gif)

### Override background
- if checked colors on drones which are not selected are overriden with selected color

![Override background checked](gifs/override_background_checked.gif)
- if unchecked colors on drones which are not selected will stay as they are

![Override background unchecked](gifs/override_background_unchecked.gif)

## Select

### Select mouse
- drones selected in viewport are used

![Select mouse](gifs/select_mouse.gif)

### Select by mesh
- drones which are in picked mesh are used

![Select by mesh](gifs/select_by_mesh.gif)

### Select random
- select random drones on each step

![Select random](gifs/select_random.gif)

### Invert selection
- drones which are not selected are used

![Select invert](gifs/select_invert.gif)
