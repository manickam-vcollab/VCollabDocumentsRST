Options
========

This interface helps user to modify the following attributes,         
                                                                          
-  Line Size for line set geometry.                                   
-  Point Size for point set geometry.                                 
-  A flag for updating normals during CAE Animation.                  
                                                                          
**Interface**
                                                 
|image1|                                                           
                                                                          
**Panel**                                                   
                                                                          
|image2|                                                           
                                                                          
                                                                          
============================================ ===============================================================

**Use Shader**                                Allows user to control rendering in shader or non-shader. User can change this option only before loading any model and it requires restarting application.

**Inverse Flat Normal**                       User can use this flag when model becomes dark due to negative scale or huge deformation.

**Line Size**                                 User can change in the range of [1, 5].

**Point Size**                                User can change in the range of [1, 5].

**Transparency**                              Applies 93% opacity by default for display mode transparency. 

**Update Normals on CAE Animation**           Enables or Disables the option of updating normals.

**Set Working Directory**                     The directory from which the cax file was loaded is the default working directory. The working directory can be  
                                              edited and set by the user. All file dialogs will pop with the setworking directory.

**Apply**                                     Applies the modifications.

**Close**                                     Closes the dialog without applying the modifications.

============================================ ===============================================================

.. |image1| image:: images/Options_Context.png
.. |image2| image:: images/Options_Panel.png
