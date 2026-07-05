# Klipper Config  

Please note, this is only 1 option. There are many other macros that exist for this functionality, this is just what works for me. I load my filment with the hotend cold. If you chose to use this config, there are several parameters you will need to update:  

  + Switch pins
  + Secondary Extruder pins and config
  + Rotation_distance
  + Extrusion distances (speeds should be good/safe)
  + You will need to add this to your PRINT_START macro to reset the buffer before a print:

    SET_EXTRUDER_ROTATION_DISTANCE EXTRUDER=buffer DISTANCE=22.811

    
