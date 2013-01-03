------------------
Layout Folder:
------------------

The Layout folder contains all the scss for the layouts. 
It is crucial to keep this folder lean and clean.
These are the base layouts of the website and should not 
control the layout of blocks or regions. 

The purpose of the layout folder to define the common elements
of a layout and how they transition through different device 
sizes. 

The files are named for those device sizes. Layout.scss 
is the containing file of the different layout sizes. 

------------------
Mobile First
------------------

The mobile layout file should be near empty and contain very
few overwrites for the mobile screen size, unless if it is mobile
landscape. The reasoning behind this is that this theme is Mobile First
and all design, layouts, and processing, should be done through
the mindset that the mobile device is the primary device. 