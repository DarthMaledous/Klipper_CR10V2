This macro adds a handy tool for printing a test part and using it to calibrate your printer. Currently, it includes the following components:

- one-wall vase mode heat tower for print temperature calibration.
- one-walled rounded cube for flow calibration.
- tuning tower for pressure advance calibration.
- one-layer height validation pattern for bed leveling. Note: This one is designed for the print bed of my Anycubic Predator (round, diameter: 370mm).
- For flow and pressure advance calibration, there is a built-in calculator labeled as "CALC."

The STL files are included so that you can reslice and modify the G-code for your printer. To add the macro, simply place the "Calibration_Prints" folder in the same location as your printer.cfg. Then, inside the printer.cfg file, add the following line: [include Calibration_Prints/*.cfg]

If you type "help" into the TOOL parameter of the macro, you will receive further information."