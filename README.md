# Mooring Monitor
Monitor your vessel when away from the boat
Low cost, low power sensors for battery operated telemetry
web services alert you to situations looming on your boat
Status monitoring dashboard for peace of mind.

##Primary functions
0. Pressure sensor monitors bilge water depth. 
0. Accelerometer monitors wave action,, impacts and vibration
0. Gyro attitude sensing for rolling and listing?
0. Compass tracks anchor swing
0. Temperature
0. Battery Voltage


##Status and alarms
Boat is sinking

The boat is listing

Freeze warning

Can we infer Mooring line length? Are we banging into the dock?

Mooring conditions wave action

Correlation to local weather and tide conditions

Battery Voltage

##Requirements
###Accuracy
Water depth sensing:  0.0mm until the whole thing starts to float.

Acceleration: TBD

Relative rotation: TBD

Update rate: TBD

*Wi-Fi / Cell for telemetry upload to cloud service
*Bluetooth for configuration, debug.
*USB for firmware update

##Hardware
IoT device with Bluetooth Wi-Fi and optionally Cell Modem

*  9 DOF MEMS sensor
*  Barometric pressure sensor
*  Alarm sounder
*  PVC Pipe fittings
*  Nitrile membrane to keep water out
*  Battery holder and battery
*  Fuse
*  House battery wires and clips
*  Alarm Sounder

##Power
House power will allow GPS and geofencing (power calcs req)

Lithium thionyl chloride primary battery for extended low temperature  operation

##Design
Inverted chamber containing sensors is placed directly into the bilge.
Rising water is sensed by the pressure sensor, values are filtered, multiplexed with other telemetry and relayed for remote analysis.

Utilize the accelerometer as an input device
*  Invert device to change mode. 
*  Shake to input.
*  Switch Wi-Fi to AP mode and start web interface for initial configuration.
*  Detect horizonal and not moving "Shelf Mode" and got to deep power save.
  
  

