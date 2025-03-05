TFPROBE01 is an IR reflective and hall probe designed for RPM measurement in combination with [TFRPM01](https://docs.thunderfly.cz/avionics/TFRPM01/) ([Tindie](https://www.tindie.com/products/27741/)) sensor board. TFPROBE01 contains two sensors supporting two sensing methods - optical or magnetic. Therefore the best one should selected for the application.

The probe is connected to the TFRPM01 sensor using a 3-pin cable with DuPont connectors. A 20 cm cable is included. The package also contains two 3-pin headers - one straight and one angled, one of which needs to be soldered to the probe, in accordance with the customer's needs.

### Magnetic Sensing

The hall sensor mounted on the probe board is sensitive to both directions of the magnetic field. The strength of the magnetic field is a decisive parameter for the probe's correct function. The magnetic flux is expected perpendicular to the sensor's PCB surface. 

In the case of using magnetic sensing, it is recommended to cover the probe in a black shrinking tube. The covering blocks the function of the reflective sensor.

### Optical Sensing

The optical sensor is sensitive to infrared reflective material (usually a rotating disc with marks). The sensing distance of the sensor is between 0.5 and 2 mm above the sensor edge. Recommended mounting and properties of the sensor can be found in the datasheet of the [vcnt2020](https://github.com/ThunderFly-aerospace/TFPROBE01/blob/TFPROBE01A/doc/datasheets/vcnt2020.pdf) sensor. More details can be found in the [application notes](https://www.vishay.com/docs/84395/designingvcnt2020.pdf).
