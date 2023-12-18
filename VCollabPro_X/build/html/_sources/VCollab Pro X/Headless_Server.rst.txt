Linux - Configuration for Headless Server
===========================================

**Configuration for Headless Server**

VCollabPro uses OpenGL to render the images in the graphics hardware (or frame buffer) and export them into image files. This, in turn, requires an X Windows server running on the system. On headless systems with no X Windows server installed, the Xvfb in-memory display server is required to run *VCollabPro*.


**Prerequisites for Headless Server – SUSE Linux Enterprise Server**


The following package should be installed on a Headless server environment in order to make VCollabPro work.

    **xorg-x11-server**
    
The xorg-x11-server installs the following required packages. If there is an issue running VCollabPro on the Headless server even after installing the above package, make sure to check if the below packages are installed on the machine.
    #. Mesa-libGL1
    #. libGLU1
    #. Mesa-dri
    #. libglut3
    #. libXi6
    #. libXpm4
    #. libXrandr2
    #. libXrender1
    #. libfreetype6
    #. libfontconfig


**Prerequisites for Headless Server – Red Hat Enterprise Linux**

The following package should be installed on a Headless server environment in order to make VCollabPro work.

    **xorg-x11-server-Xvfb**
    
The xorg-x11-server-Xvfb package installs the other required packages. If there is an issue running VCollabPro on a Headless server even after installing the above package, make sure to check if the below packages are installed on the machine.
    #. mesa-libGL
    #. mesa-libGLU
    #. mesa-dri-drivers
    #. freeglut
    #. libXi
    #. libXpm
    #. libXrandr
    #. libXrender
    #. freetype
    #. fontconfig
    #. libdrm


**Usage syntax for Xvfb:**

>/usr/local/bin/vcollabpro   –xvfb   –b  <py_file> [cax_file]

**Xvfb Configuration**


How to check if Xvfb is installed:

rpm -qa | grep Xvfb

This above command lists the Xvfb version that is installed on the machine

How to check if Xvfb is running:

    ps -ef | grep Xvfb

    This above command lists the process details about Xvfb that is currently running on the machine

How to configure Xvfb for the Automatic startup:

   Edit the rc.local file to start the server automatically on boot, then start the server. After the package is installed, add the following line to the /etc/rc.local file to start the server on boot:

   Xvfb :1234 -screen 0 1280x1024x24  -nolisten inet6 &


   Either reboot the system to start the Xvfb server or manually run the following command to start the Xvfb server without rebooting the system:

   Xvfb :1234 -screen 0 1280x1024x24  -nolisten inet6 &


.. note::

   The xorg-x11-server-Xvfb version depends on the graphics driver version installed on the headless server. If VCollabPro still doesn't work after the installation of Xvfb, you may need to try installing the latest versions of Xvfb.




