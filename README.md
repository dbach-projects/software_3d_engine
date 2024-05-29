# software_3d_engine

A software based 3D Engine. Written in Dart/Flutter and based off work by Javidx9 - https://github.com/OneLoneCoder/Javidx9

## Controls

Depending on your individual keyboard key presses may need to be made repetedly (holding a key may not work).

- up arrow: translate up
- down arrow: translate down
- left arrow: translate left
- right arrow: translate right
- w key: translate forward
- s key: translate backwards

- swipe left: rotate left
- swipe right: rotate right

## Features

- shading
- depth and screen clipping

## Notes

Current implementation is designed to only re-compute projections and rasterization when the camera moves. If and object were to be made to move in the scene the current implementation would not re-render that change.
