

<!--- Name:PROBE01A: --->
# TFPROBE01A

<!--- LongName --->
Omnipolar magnetic and reflective optical probe. 
<!--- ELongName ---> 

<!--- Lead --->

<!--- ELead ---> 

The sensor is designed for RPM measurement in combination with [TFRPM01 sensor board](https://github.com/ThunderFly-aerospace/TFRPM01). The probe consists dual sensing technique - optical or magnetic. Therefore the user should select the one most suitable for the application. 

![Top view on TFPROBE01A](/doc/img/TFPROBE01A_top_big.png)

![Bottom view on TFPROBE01A](/doc/img/TFPROBE01A_bot_big.png)

### Magnetic Sensing

The magnetic Hall-effect sensor mounted on the probe board is able to sense both directions of magnetic field. The strenght of the magnetic field is decisive parameter for probe correct function. The magnetic flux is expected perpendicular to the sensor PCB surface. The detailed requirements of magnetic flux density are distribed in [AH3572 datasheet page 4](/doc/datasheets/AH3572-1483253.pdf).

In the case of use magnetic sensing it is recommended to cover the probe in black shrinking tube.  The covering blocks function of reflective sensor.

### Optical Sensing

Optical sensor is sensitive for infrared reflectance of material (usually a rotating disc with marks). 
