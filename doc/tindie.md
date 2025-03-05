TFPROBE01 is an IR reflective and hall probe designed for RPM measurement in combination with [TFRPM01](https://www.tindie.com/products/thunderfly/tfrpm01-drone-rpm-tachometer-sensor/) ([github](https://github.com/ThunderFly-aerospace/TFRPM01)) sensor board. TFPROBE01 contains two sensors supporting two sensing methods - optical or magnetic. Therefore the user should select the one most suitable for his application.

The probe is connected to the TFRPM01 sensor using a 3 pin cable with duPont connectors. A 20 cm cable is included. Package also contains two 3-pin headers - one straight and one angled, one of which needs to be soldered to the probe, in accordance with customer's needs.

### Magnetic Sensing

The hall sensor mounted on the probe board is sensitive to both directions of the magnetic field. The strength of the magnetic field is a decisive parameter for the probe's correct function. The magnetic flux is expected perpendicular to the sensor's PCB surface. The detailed requirements of magnetic flux density are described in [AH3572 datasheet page 4](https://github.com/ThunderFly-aerospace/TFPROBE01/blob/TFPROBE01A/doc/datasheets/AH3572-1483253.pdf).

In case of using the magnetic sensing it is recommended to cover the probe in black shrinking tube. The covering blocks the function of the reflective sensor.

### Optical Sensing

Optical sensor is sensitive to infrared reflective material (usually a rotating disc with marks). Sensing distance of the sensor is between 0.5 and 2 mm above the sensor edge. Recommended mounting and properties of the sensor can be found in the data sheet of the [vcnt2020](https://github.com/ThunderFly-aerospace/TFPROBE01/blob/TFPROBE01A/doc/datasheets/vcnt2020.pdf) sensor. More details can be found in the [application notes](https://www.vishay.com/docs/84395/designingvcnt2020.pdf).
