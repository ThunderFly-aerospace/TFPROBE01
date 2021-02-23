# TFPROBE01A - Omnipolar magnetic and reflective optical sensor probe

![KiCad](https://github.com/ThunderFly-aerospace/TFPROBE01/workflows/KiCad/badge.svg)

The sensor is designed for RPM measurement in combination with [TFRPM01 sensor board](https://github.com/ThunderFly-aerospace/TFRPM01). The probe consists dual sensing technique - optical or magnetic. Therefore the user should select the one most suitable for the application.

<p float="left">
<img src="/doc/img/TFPROBE01A_connector.jpg" width="45%" />
<img src="/doc/img/TFPROBE01A_sensors.jpg" width="45%" />
</p>

> This module (TFGPS01A) was developed by [ThunderFly s.r.o.](https://www.thunderfly.cz) and is published as OpenSource hardware with a [GPLv3](LICENSE) license. It is possible to buy on request. For a quote contact us by email info@thunderfly.cz. Or together with a [TFRPM01](https://github.com/ThunderFly-aerospace/TFRPM01) sensor at [Tindie store](https://www.tindie.com/products/thunderfly/tfrpm01-drone-rpm-tachometer-sensor/).


### Magnetic Sensing

The magnetic Hall-effect sensor mounted on the probe board is able to sense both directions of magnetic field. The strength of the magnetic field is decisive parameter for probe correct function. The magnetic flux is expected perpendicular to the sensor PCB surface. The detailed requirements of magnetic flux density are described in [AH3572 datasheet page 4](/doc/datasheets/AH3572-1483253.pdf).

In the case of use magnetic sensing it is recommended to cover the probe in black shrinking tube.  The covering blocks function of reflective sensor.

### Optical Sensing

Optical sensor is sensitive for infrared reflectance of material (usually a rotating disc with marks).

## Hardware
TFPROBE01A is designed as Open-Hardware (GPL v3). All documentation is located in this repository.

The TFPROBE01 is sold and shipped without soldered header, because its orientation may depend on the customer's use. One straight and one right-angeled 3-pin header is included.

### PCB

<p float="left">
<img src="/doc/img/TFPROBE01A_top_big.png" width="45%" />
<img src="/doc/img/TFPROBE01A_bot_big.png" width="45%" />
</p>


### Eletronic schema

Full schema is avialible in [PDF](hw/cam/docs/TFPROBE01A_schematic.pdf)

![schema](hw/cam/docs/TFPROBE01A_schematic.svg)
