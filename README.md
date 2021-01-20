# Micromanager_Scripts
/Author: Théo ASPERT - theo.aspert@gmail.com
This script is attached to the MDA and performs autofocus on the first position of the position list, then apply the z-offset to the rest of the positions.
Applies at each time point before the first channel.
It is an efficient method if your loss of focus is homogeneous (example: thermal drift of the stage) to save time in your MDA routine.

CHange the parameters of the .attachRunnable(frame,position,channel,slide) to adapt it to your need.
