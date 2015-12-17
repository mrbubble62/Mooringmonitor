# Mooring Monitor
Monitor your vessel when away from the boat
Low cost, low power sensors for battery operated telemetry
web services alert you to situations looming on your boat
Status monitoring dashboard for peace of mind.

Primary functions
Pressure sensor monitors bilge water depth. 
Accelerometer monitors wave action and impacts.
Gyro attitude sensing for rolling and listing?
Compass tracks anchor swing
Temperature
Battery Voltage
Wi-Fi or Cell data to send telemetry

Status and alarms
Boat is sinking
The boat is listing
Freeze warning
Can we infer Mooring line length? Are we banging into the dock?
Mooring conditions wave action
Correlation to local weather and tide conditions
*Battery Voltage

Requirements
Water depth sensing:  0.0mm until the whole thing starts to float.
Acceleration: TBD
Relative rotation: TBD
Update rate: TBD

Wi-Fi / Cell for telemetry upload to cloud service
Bluetooth for configuration, debug.
USB for firmware update

Hardware
IoT device 
9 DOF sensor
Barometric pressure sensor
Alarm sounder

Power
House power will allow GPS and geofencing (power calcs req)
Lithium primary batteries for extended low temperature  operation

Inverted chamber containing sensors is placed directly into the bilge.
Rising water is sensed by the pressure sensor, values are filtered, multiplexed with other telemetry and relayed for remote analysis.

