###Changelog for PyBBIO  
http://github.com/alexanderhiam/PyBBIO   


#### version 0.8
 * Added tools/ directory for install helpers
 * Support for Kernel >= 3.8:
   * GPIO
   * Serial
   * ADC
   * Added tool to generate and compile DT overlays
 * misc. fixes


#### version 0.6
 * Moved to multi-file package structure
 * New structure and install method can now easily support platforms besides 
   the Beaglbone
 * Swithed to setuptools instead of distutils for setup.py
 * All memory access moved to C extension to increase speed
 * Created this changelog!
