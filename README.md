# Sensoswap
Working under Professor Matthew Campisi's SIIL(Student Impact Innovation Lab) and New York University's Tandon School of Engineering to create health sensors for a platform developed by Professor Campisi. Currently working on an EKG/Heart Rate monitoring sensor and an SPO2 sensor. Creaded PCB schematics based on reference boards to fit the sensoswap platform. 
<p align="center">
    <img src="https://github.com/dareminion/Sensoswap/assets/128090000/dce9c3f6-d67d-47f2-b9a1-0311dba2ce27">
</p>
<p align="center">The schematic above shows the different connections and traces needed in order to connect and power each sensor properly.</p>
<p align="center">
    <img src="https://github.com/dareminion/Sensoswap/assets/128090000/7e5f6b28-7d2d-4f88-b66c-77a50a136778">
</p>
<p align="center">Traces to connect power to the right components. Three pins on the main module connect with the bottom three holes. (Above)</p>

The team I am on works more on the EKG/Heart Rate monitoring portion of the sensor. We have tested two methods of getting an input from a user through electrical wires that connect straigh to the reference board and also turning the wires into electode pads to increase the surface area for the user to have contact with.
<p align="center"><img src="https://github.com/dareminion/Sensoswap/assets/128090000/001bbff7-3947-4074-a33a-71d948f20f5a"></p>
<p align="center">Graph using wire contact points (Above)</p>
<p align="center"><img src="https://github.com/dareminion/Sensoswap/assets/128090000/97918713-9958-481c-b95a-e58e059f0bdb"></p>
<p align="center">Graph using electode pads (Above)</p>
After analyzing both graphs above and running multiple trials, we concluded that having the electrode pads resulted in more consistent and more accurate results to what an EKG graph should look like. We also need to modify the code to filter out more noise, our original code produced too mmuch noise in the data which resulted in inconsistent and inaccurate results.

<p align="left"> </p>

Next Steps:
  - Translate code for nRF Microcontroller
  - Derive Heart Rate from the graphs
  - Being able to detect signs of  cardiac ilnesses and provide feedback to users
  - Create the capability to swap between SPO2 sensor and EKG
  - Improve metal pads design by increasing size and shorting two pads together (single-lead)

