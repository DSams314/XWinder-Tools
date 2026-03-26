X-Winder Visualizer: 
  - Useful for taking .X4G or .X4G files converted to .TXT files to verify wind GCODE integrity
  - Not perfect yet but appears to be useful in analyzing helical winds
  - Hoop winds are still broken visually but work conceptually

GCODE Web Converter:
  - Has not been tested yet, but likely due to a Windows Update breaking USB timing or Software/Firmware Update messing with things, XWinder can fail to register mandrel position after reaching the end of the end of the mandrel.
  - To solve this, this tool changes the programming archicture from one that reads the position of the mandrel and adjusts, to one that instaed waits a set amount of time.

Example Files:
  - Example files are present to use as reference when using the visualizer or gcode web converter.
