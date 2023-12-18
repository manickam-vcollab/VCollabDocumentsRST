Mouse Operations
==================

This section lists and explains the functions performed by the mouse.

**Motion Model**

The basic functions for any 3D model viewer are Pan, Rotate and Zoom.

This motion model functions are achieved in two ways,

1. Interactive method

2. Passive Transformation method.

**Interactive Method**

1. **Pan**
   This is achieved by dragging the **right** button or third
   button inside the viewer.

   1. Press down the mouse **right** button and hold inside the viewer.

   2. Drag the mouse as the model is panned proportionally.

   3. Release the mouse button to stop panning.

   4. Model panning and mouse dragging will be in the same direction.

2. **Rotate**
   This is achieved by dragging the mouse **left** button or
   mouse first button inside the viewer.

   1. Press down the mouse **left** button and hold inside the viewer.

   2. Drag the mouse as the model is panned proportionally.

   3. Release the mouse button to stop rotation.

   4. The axis of rotation will be perpendicular to the mouse direction.

   5. Direction of rotation and mouse dragging direction are the same.

   6. Default rotation center is the center of the model.

   7. User can change and set any point on the model as rotation center
      using Display \| Set Rotation Center.

3. **Zoom** 
   Zoom is achieved further in two ways

   1. Mouse dragging

      -  Press down the mouse middle button and hold inside the viewer.

      -  Drag the mouse as the model is panned proportionally.

      -  Release the mouse button to stop zoom.

      -  If the mouse dragging direction is vertically downwards, then
         the model will be zoomed in.

      -  if it is vertically upwards, then the model will be zoomed out.

      -  Here the window scene center is zoomed in or out.

4. **Mouse Scroll**

      -  The advantage in mouse scroll zoom is, here zoom is *mouse pointer position based*.

      -  Move the mouse to the position on the model to be zoomed in or out.

      -  Scroll forward to zoom in.

      -  Scroll backward to zoom out.

**Passive Transformation method**

In general, it is very hard to go back to the previous transform, after
some model transformations. It is almost impossible in case of
interactive rotations. Because the mouse dragging curve is not linear.
Passive transformation methods overcome this disadvantage significantly.
Passive transformations are linear and uniformly incremental /
decremental. VCollab provides a user friendly interface, Navigator
inside the viewer.

Click **Tools \| Navigator** to know more.

Note: The default mouse buttons for motion model can be customized using
Edit \| Mouse Mode.
